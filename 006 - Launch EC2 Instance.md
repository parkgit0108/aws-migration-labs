# Launch EC2 Instance

<aside>

**Purpose:** Launch a new **EC2 instance** using the provided requirements so it can be accessed/used as needed.

</aside>

---

### Procedure

1. Sign in to the AWS Console using the provided credentials and URL.
2. Navigate to the **EC2 dashboard**.
3. In the left sidebar, go to **Instances → Instances**.
4. Click **Launch instances**.
5. Fill out the form using the provided requirements.
    - Select the required **AMI** and **instance type**.
    - Choose or create the required **key pair**.
    - Choose or create the required **security group**.
        
        <img width="1468" height="1317" alt="image" src="https://github.com/user-attachments/assets/daa675ef-c4ca-40be-bb6b-838786c4b6e8" />

        
6. Click **Launch instance**.
7. Confirm the instance appears in the list and is **Running**, then rename or tag it as required.
    
    <img width="1445" height="1309" alt="image" src="https://github.com/user-attachments/assets/5661f46f-8ba0-48fd-8842-786c17d779d6" />

    

---

### Quick check

- **Location:** EC2 → Instances → Instances
- **Expected result:** New instance exists in the list with:
    - **State:** Running
    - **Key pair:** Matches the provided requirements
    - **Security group:** Matches the provided requirements
    - **Name/Tags:** Match the provided requirements
