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
    
    ![image.png](Attach%20Volume%20to%20EC2%20Instance/image.png)
    
6. Fill out the required fields, then click **Attach volume**.
    
    ![image.png](Attach%20Volume%20to%20EC2%20Instance/image%201.png)
    
7. Confirm the volume is attached to the instance:
    1. Go to **Instances → Instances**.
    2. Select the instance.
    3. Go to the **Storage** section and confirm the **Volume ID** matches.
        
        ![image.png](Attach%20Volume%20to%20EC2%20Instance/image%202.png)
        

### Quick check

- **Location:** EC2 → Elastic Block Store → Volumes
- **Expected result:** Volume shows **In-use** and appears in the instance’s **Storage** section