# Create IAM User

---

<aside>

**Purpose:** Create an **IAM user** so someone (or a system) can securely access AWS with the right permissions.

</aside>

---

### Procedure

1. Sign in to the AWS Console using the provided credentials and URL.
2. Open **IAM**:
    1. In the AWS search bar, type **IAM**.
    2. Select **IAM** from the results.
3. In the left sidebar, go to **Users**.
4. Click **Create user**.
    
    <img width="1469" height="562" alt="image" src="https://github.com/user-attachments/assets/61bf2a3b-8225-40ce-b28f-009647e98a73" />
    
5. Enter the required details:
    1. **User name**
    2. Select the appropriate access type for the use case, otherwise leave as it is.
6. Set permissions for the user (choose one):
    - leave as is if no other information provided.
7. Review the settings, then click **Create user**.

   <img width="1473" height="603" alt="image" src="https://github.com/user-attachments/assets/50d98c08-0c62-4997-bb9d-7c9af2733af8" />
    

### Quick check

- **Location:** IAM → Users
- **Expected result:** New user appears in the list and has the intended permissions (group/policies)
