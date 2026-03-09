# Configuring an EC2 Instance as a Web Server with Nginx

---

<aside>

**Purpose:** Launch an **EC2 instance** and configure it as a simple **web server (Nginx)** using **user data**, then verify the Nginx default page loads over **HTTP (port 80)**.

</aside>

---

### Procedure

1. Launch the EC2 instance:
    1. Open **EC2**:
        - AWS Console → **EC2** → **Launch instance**
    2. Configure the instance:
        - **Name:** lab provided
        - **AMI:** Ubuntu Server
        - **Instance type:** `t2.micro`
        - Continue **without** key pair
    3. Add user data script:
        - In **Advanced details** → **User data**, paste:

```bash
#!/bin/bash
sudo apt update -y
sudo apt install -y nginx
sudo systemctl start nginx
sudo systemctl enable nginx
```

1. Launch:
    - Click **Launch instance**
    - Wait until:
        - **State:** Running
        - **Status checks:** 2/2 passed
2. Allow HTTP access (port 80):
    1. Open the instance’s **Security group**
    2. Edit **Inbound rules** (for the existing attached security group)
    3. Add rule:
        - **Type:** HTTP
        - **Port:** 80
        - **Source:** `0.0.0.0/0`
            
            <img width="1472" height="837" alt="image" src="https://github.com/user-attachments/assets/68d151bc-fee2-48ec-b50c-7bc488f797b4" />
            
3. Verify Nginx is reachable:
    1. Copy the instance **Public IPv4 address**
    2. Open in a browser:
        - `http://<public-ip>`
    3. Confirm the **Nginx default page** loads
        
       <img width="1160" height="495" alt="image" src="https://github.com/user-attachments/assets/7c34fa8e-4e90-4d8b-9da6-f2788f7c4c3a" />
        

### Quick check

- **Location:** AWS Console (EC2)
- **Expected result:** Instance is **Running**, inbound rule allows **HTTP (80)**, and the **Nginx default page** loads via the instance public IP
