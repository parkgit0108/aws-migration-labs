# Setting Up an EC2 Instance with an Elastic IP for Application Hosting

---

<aside>

**Purpose:** Launch an **EC2 instance** and associate an **Elastic IP address**.

</aside>

---

### Procedure

1. Sign in to the AWS Console using the provided credentials and URL.
2. Open **EC2**:
    1. In the AWS search bar, type **EC2**.
    2. Select **EC2** from the results.
3. Launch an instance:
    1. Click **Launch instance**.
    2. Set the instance **name** and select settings as per the provided information.
    3. For **Key pair**, select **Proceed without a key pair** (No key pair).
    4. Click **Launch instance**.
    
        
4. Allocate an Elastic IP address:
    1. In the left sidebar, go to **Network & Security** → **Elastic IPs**.
    2. Click **Allocate Elastic IP address**.
    3. Leave all settings as default, then click **Allocate**.
        
5. Associate the Elastic IP address to the instance:
    1. Click **Actions** → **Associate Elastic IP address**.
        
        <img width="1464" height="358" alt="image" src="https://github.com/user-attachments/assets/114c69ef-961d-43fb-815a-c7a0776def9c" />
        
    2. Add a name provided.
    3. Select the new Elastic IP.
    4. Select the instance you created, then click **Associate**.
        
        <img width="1468" height="615" alt="image" src="https://github.com/user-attachments/assets/8419de2e-1f7b-406f-9ebf-7ad31cdb5fce" />
        
6. Confirm the Elastic IP is associated:
    1. Select the instance.
    2. Open **Instances**.
    3. Confirm the **Elastic IP** shows as associated.
        
        <img width="1471" height="806" alt="image" src="https://github.com/user-attachments/assets/585c014a-a124-4fbf-b9c7-a2e97f140e54" />
        

### Quick check

- **Location:** EC2 → Instances
- **Expected result:** Instance shows the assigned **Elastic IP address**
