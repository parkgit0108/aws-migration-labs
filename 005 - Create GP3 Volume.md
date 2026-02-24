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
    
    ![image.png](Create%20GP3%20Volume/image.png)
    
5. Fill out the form using the provided requirements.
6. Click **Create volume**.
7. Confirm the volume appears in the list, then rename or tag it as required.
    
    ![image.png](Create%20GP3%20Volume/image%201.png)
    

---

### Quick check

- **Location:** EC2 → Elastic Block Store → Volumes
- **Expected result:** New volume exists in the list with:
    - **Type:** gp3
    - **State:** Available (or In-use if attached)
    - **Name/Tags:** Match the provided requirements
        
        ![image.png](Create%20GP3%20Volume/image%202.png)