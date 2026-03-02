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
    
    <img width="1467" height="527" alt="image" src="https://github.com/user-attachments/assets/b179e13c-1e7c-4fc5-824a-67159062281e" />

6. Confirm the correct entity is selected (as provided in the policy details), then click **Attach policy**.
    
    <img width="1464" height="454" alt="image" src="https://github.com/user-attachments/assets/9662f1b5-6909-4d63-b51e-4f8dba0f3d84" />
    
7. Confirm the policy is attached:
    1. Go to **Users**.
    2. Click the target user name.
    3. Open the **Permissions** tab and check **Permissions policies**.
    
    <img width="1468" height="625" alt="image" src="https://github.com/user-attachments/assets/45197a64-9066-4235-8a17-95e929b2b528" />
    

### Quick check

- **Location:** IAM → Users → *username* → Permissions
- **Expected result:** The policy appears under **Permissions policies** for the user
