# Attach IAM Policy to IAM User

---

<aside>

**Purpose:** Attach an **IAM policy** to a specific **IAM user**.

</aside>

---

### Procedure

1. Sign in to the AWS Console using the provided credentials and URL.
2. Open **IAM**:
    1. In the AWS search bar, type **IAM**.
    2. Select **IAM** from the results.
3. In the left sidebar, go to **Policies**.
4. Search for the policy name provided.
5. Click the policy name, then select **Actions** → **Attach**.
    
    ![](Attach%20IAM%20Policy%20to%20IAM%20User/image.png)
    
6. Confirm the correct entity is selected (as provided in the policy details), then click **Attach policy**.
    
    ![](Attach%20IAM%20Policy%20to%20IAM%20User/image%201.png)
    
7. Confirm the policy is attached:
    1. Go to **Users**.
    2. Click the target user name.
    3. Open the **Permissions** tab and check **Permissions policies**.
    
    ![](Attach%20IAM%20Policy%20to%20IAM%20User/image%202.png)
    

### Quick check

- **Location:** IAM → Users → *username* → Permissions
- **Expected result:** The policy appears under **Permissions policies** for the user