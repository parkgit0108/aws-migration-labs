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
    
    ![image.png](Create%20IAM%20User/image.png)
    
5. Enter the required details:
    1. **User name**
    2. Select the appropriate access type for the use case, otherwise leave as it is.
6. Set permissions for the user (choose one):
    - leave as is if no other information provided.
7. Review the settings, then click **Create user**.
    
    ![image.png](Create%20IAM%20User/image%201.png)
    

### Quick check

- **Location:** IAM → Users
- **Expected result:** New user appears in the list and has the intended permissions (group/policies)