# Enable Versioning for S3

<aside>

**Purpose:** Enable **S3 Versioning** on **`datacenter-s3-21157`** so objects can be recovered after accidental deletion or corruption.

</aside>

---

### Procedure

1. Sign in to the AWS Console using the provided credentials and URL.
2. Open **Amazon S3**.
    
    <img width="1473" height="663" alt="image" src="https://github.com/user-attachments/assets/2d5589a3-43eb-4956-916d-88a827142046" />

    
3. Select the bucket **`datacenter-s3-21157`**.
4. Go to **Properties**.
    
    ![image.png](attachment:1bfbf509-9fbc-410b-89b8-8619248b09c7:image.png)
    
5. Click **Edit**.
6. Select **Enable**, then click **Save changes**.
    
    ![image.png](attachment:4b48d4cb-0fab-4d8c-b3b4-d421b6a75b3c:image.png)
    
7. Confirm the success message appears and **Bucket Versioning** shows as **Enabled**.
    
    ![image.png](attachment:66b8f8ef-6aba-4052-8eb9-61457a072bc5:image.png)
    

---

### Quick check

- **Bucket:** `datacenter-s3-21157`
- **Location:** S3 → Bucket → Properties → Bucket Versioning
- **Expected result:** Status shows **Enabled**
