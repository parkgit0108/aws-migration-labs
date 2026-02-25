# Attach Volume to EC2 Instance

---

<aside>

**Purpose:** Attach an **EBS volume** to an EC2 instance so it can be used as additional storage.

</aside>

---

### Procedure

1. Sign in to the AWS Console using the provided credentials and URL.
2. Navigate to the **EC2 dashboard**.
3. In the left sidebar, go to **Elastic Block Store → Volumes**.
4. Select the volume you want to attach.
5. Go to **Actions → Attach volume**.
    
    <img width="1465" height="1123" alt="image" src="https://github.com/user-attachments/assets/84f667f5-261a-4125-b0a8-03abdee50a95" />
    
6. Fill out the required fields, then click **Attach volume**.
    
    <img width="1469" height="633" alt="image" src="https://github.com/user-attachments/assets/7f4f88cd-bfe6-4794-8f35-62b3751c713b" />
    
7. Confirm the volume is attached to the instance:
    1. Go to **Instances → Instances**.
    2. Select the instance.
    3. Go to the **Storage** section and confirm the **Volume ID** matches.
        
        <img width="1463" height="1067" alt="image" src="https://github.com/user-attachments/assets/6e946a67-220a-44da-8ad0-f00c130b73ce" />
        

### Quick check

- **Location:** EC2 → Elastic Block Store → Volumes
- **Expected result:** Volume shows **In-use** and appears in the instance’s **Storage** section
