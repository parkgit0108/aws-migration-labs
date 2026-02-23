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
    
    <img width="1466" height="697" alt="image" src="https://github.com/user-attachments/assets/5820b45a-a22e-4239-a6f6-13866666f6b0" />

    
5. Click **Edit**.
6. Select **Enable**, then click **Save changes**.
    
    <img width="1478" height="645" alt="image" src="https://github.com/user-attachments/assets/2a601dd4-9874-4b0b-805b-62db737feb05" />

    
7. Confirm the success message appears and **Bucket Versioning** shows as **Enabled**.
    
    ![Uploading image.png…]()

    

---

### Quick check

- **Bucket:** `datacenter-s3-21157`
- **Location:** S3 → Bucket → Properties → Bucket Versioning
- **Expected result:** Status shows **Enabled**
