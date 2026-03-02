# Create IAM Role for EC2 with Policy Attachment

---

<aside>

**Purpose:** Create an **IAM role** for **EC2** and attach the required **IAM policy**.

</aside>

---

### Procedure

1. Sign in to the AWS Console using the provided credentials and URL.
2. Open **IAM**:
    1. In the AWS search bar, type **IAM**.
    2. Select **IAM** from the results.
3. In the left sidebar, go to **Roles**.
4. Click **Create role**.
    
    ![image.png](Create%20IAM%20Role%20for%20EC2%20with%20Policy%20Attachment/image.png)
    
5. Select the **trusted entity type** and **use case** as provided.
    
    ![image.png](Create%20IAM%20Role%20for%20EC2%20with%20Policy%20Attachment/image%201.png)
    
6. Search for the policy name provided, then select it to attach.
    
    ![image.png](Create%20IAM%20Role%20for%20EC2%20with%20Policy%20Attachment/image%202.png)
    
7. Set the **role name** as provided, review, then click **Create role**.
    
    ![image.png](Create%20IAM%20Role%20for%20EC2%20with%20Policy%20Attachment/image%203.png)
    
8. Confirm the role exists:
    1. Go back to **Roles**.
    2. Search for the role name.
    3. Confirm it appears in the list.
    
    ![image.png](Create%20IAM%20Role%20for%20EC2%20with%20Policy%20Attachment/image%204.png)
    

### Quick check

- **Location:** IAM → Roles
- **Expected result:** New role appears in the list and shows the intended policy under **Permissions policies**