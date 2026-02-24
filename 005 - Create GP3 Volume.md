# Create GP3 Volume

<aside>

**Purpose:** Create a new **EBS gp3** volume in EC2 using the provided requirements so it can be attached/used as needed.

</aside>

---

### Procedure

1. Sign in to the AWS Console using the provided credentials and URL.
2. Navigate to the **EC2 dashboard**.
3. In the left sidebar, go to **Elastic Block Store → Volumes**.
4. Click **Create volume**.
    
    <img width="1474" height="993" alt="image" src="https://github.com/user-attachments/assets/e1e8eaa5-d3d4-4bed-9ef8-029e627c076a" />

    
5. Fill out the form using the provided requirements.
6. Click **Create volume**.
7. Confirm the volume appears in the list, then rename or tag it as required.
    
    <img width="1471" height="656" alt="image" src="https://github.com/user-attachments/assets/01b197b5-b047-4719-912c-ca6c9b99023b" />

    

---

### Quick check

- **Location:** EC2 → Elastic Block Store → Volumes
- **Expected result:** New volume exists in the list with:
    - **Type:** gp3
    - **State:** Available (or In-use if attached)
    - **Name/Tags:** Match the provided requirements
        
    <img width="1475" height="973" alt="image" src="https://github.com/user-attachments/assets/a343acdd-b9e7-4d1a-95f8-e54c8f6b80ba" />
