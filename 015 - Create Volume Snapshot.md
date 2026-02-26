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
    
    ![image.png](Create%20Volume%20Snapshot/image.png)
    
6. Fill out the required fields with information provided, then click **Create snapshot**.
    
    ![image.png](Create%20Volume%20Snapshot/image%201.png)
    
7. Confirm the snapshot was created:
    1. In the left sidebar, go to **Elastic Block Store → Snapshots**.
    2. Find the snapshot you just created.
    3. Wait for **Status** to show **Completed**.
        
        ![image.png](Create%20Volume%20Snapshot/image%202.png)
        
- **Expected result:** Snapshot shows **Completed** and matches the source **Volume ID**