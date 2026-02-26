# Create Volume Snapshot

- **Location:** EC2 → Elastic Block Store → Snapshots

---

<aside>

**Purpose:** Create an **EBS snapshot** from an existing EBS volume for backup or to create new volumes later.

</aside>

---

### Procedure

1. Sign in to the AWS Console using the provided credentials and URL.
2. Navigate to the **EC2 dashboard**.
3. In the left sidebar, go to **Elastic Block Store → Volumes**.
4. Select the volume you want to back up.
5. Go to **Actions → Create snapshot**.
    
    <img width="1468" height="690" alt="image" src="https://github.com/user-attachments/assets/5ca84365-5761-417a-bf45-3bac62842466" />
    
6. Fill out the required fields with information provided, then click **Create snapshot**.
    
    <img width="1463" height="787" alt="image" src="https://github.com/user-attachments/assets/ab0c27e6-4dd9-4ec3-a5f1-f996426c9331" />
    
7. Confirm the snapshot was created:
    1. In the left sidebar, go to **Elastic Block Store → Snapshots**.
    2. Find the snapshot you just created.
    3. Wait for **Status** to show **Completed**.
        
        <img width="1470" height="984" alt="image" src="https://github.com/user-attachments/assets/8e8e7c05-fe1e-4416-8002-780fb0d0c0ff" />
        
- **Expected result:** Snapshot shows **Completed** and matches the source **Volume ID**
