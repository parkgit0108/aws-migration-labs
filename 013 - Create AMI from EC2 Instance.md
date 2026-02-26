# Create AMI from EC2 Instance

---

<aside>

**Purpose:** Create an **Amazon Machine Image (AMI)** from an existing EC2 instance so it can be used as a backup or to launch new instances with the same configuration.

</aside>

---

### Procedure

1. Sign in to the AWS Console using the provided credentials and URL.
2. Navigate to the **EC2 dashboard**.
3. In the left sidebar, go to **Instances → Instances**.
4. Select the instance you want to create an AMI from.
5. Go to **Actions → Image and templates → Create image**.
    
    <img width="1462" height="786" alt="image" src="https://github.com/user-attachments/assets/eb5a72fc-1ea4-44df-bf4d-6bb39540302f" />
    
6. Fill out the required fields, then click **Create image**.
    
    <img width="1469" height="955" alt="image" src="https://github.com/user-attachments/assets/19775c61-b297-49b6-8937-3e1b8b4d3511" />
    
7. Confirm the AMI is created:
    1. Select your AMI.
    2. In the left sidebar, go to **Images → AMIs**.
    3. Wait until **Status** shows **Available**.
        
        <img width="1469" height="1062" alt="image" src="https://github.com/user-attachments/assets/c428ceea-7e8e-46fd-8937-c4f3061d95df" />
        

### Quick check

- **Location:** EC2 → Images → AMIs
- **Expected result:** AMI shows **Available**
