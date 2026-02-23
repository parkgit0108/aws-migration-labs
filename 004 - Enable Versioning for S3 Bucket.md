# Enable Versioning for S3

<aside>

**Purpose:** Enable **S3 Versioning** on **`datacenter-s3-21157`** so objects can be recovered after accidental deletion or corruption.

</aside>

---

### Procedure

1. Sign in to the AWS Console using the provided credentials and URL.
2. Open **Amazon S3**.
    
    ![image.png](Enable%20Versioning%20for%20S3/image.png)
    
3. Select the bucket **`datacenter-s3-21157`**.
4. Go to **Properties**.
    
    ![image.png](Enable%20Versioning%20for%20S3/image%201.png)
    
5. Click **Edit**.
6. Select **Enable**, then click **Save changes**.
    
    ![image.png](Enable%20Versioning%20for%20S3/image%202.png)
    
7. Confirm the success message appears and **Bucket Versioning** shows as **Enabled**.
    
    ![image.png](Enable%20Versioning%20for%20S3/image%203.png)
    

---

### Quick check

- **Bucket:** `datacenter-s3-21157`
- **Location:** S3 → Bucket → Properties → Bucket Versioning
- **Expected result:** Status shows **Enabled**