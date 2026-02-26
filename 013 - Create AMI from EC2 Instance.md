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
    
    ![image.png](Create%20AMI%20from%20EC2%20Instance/image.png)
    
6. Fill out the required fields, then click **Create image**.
    
    ![image.png](Create%20AMI%20from%20EC2%20Instance/image%201.png)
    
7. Confirm the AMI is created:
    1. Select your AMI.
    2. In the left sidebar, go to **Images → AMIs**.
    3. Wait until **Status** shows **Available**.
        
        ![image.png](Create%20AMI%20from%20EC2%20Instance/image%202.png)
        

### Quick check

- **Location:** EC2 → Images → AMIs
- **Expected result:** AMI shows **Available**