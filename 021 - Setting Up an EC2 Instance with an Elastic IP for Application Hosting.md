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
        
        ![image.png](Setting%20Up%20an%20EC2%20Instance%20with%20an%20Elastic%20IP%20for%20/image.png)
        
        ![image.png](Setting%20Up%20an%20EC2%20Instance%20with%20an%20Elastic%20IP%20for%20/image%201.png)
        
4. Allocate an Elastic IP address:
    1. Click **Allocate Elastic IP address**.
    2. In the left sidebar, go to **Network & Security** → **Elastic IPs**.
    3. Leave all settings as default, then click **Allocate**.
        
        ![image.png](Setting%20Up%20an%20EC2%20Instance%20with%20an%20Elastic%20IP%20for%20/image%202.png)
        
5. Associate the Elastic IP address to the instance:
    1. Click **Actions** → **Associate Elastic IP address**.
        
        ![image.png](Setting%20Up%20an%20EC2%20Instance%20with%20an%20Elastic%20IP%20for%20/image%203.png)
        
    2. Add a name provided.
    3. Select the new Elastic IP.
    4. Select the instance you created, then click **Associate**.
        
        ![image.png](Setting%20Up%20an%20EC2%20Instance%20with%20an%20Elastic%20IP%20for%20/image%204.png)
        
6. Confirm the Elastic IP is associated:
    1. Select the instance.
    2. Open **Instances**.
    3. Confirm the **Elastic IP** shows as associated.
        
        ![image.png](Setting%20Up%20an%20EC2%20Instance%20with%20an%20Elastic%20IP%20for%20/image%205.png)
        

### Quick check

- **Location:** EC2 → Instances
- **Expected result:** Instance shows the assigned **Elastic IP address**