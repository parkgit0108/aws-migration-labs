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
        
        ![image.png](Launch%20EC2%20Instance/image.png)
        
6. Click **Launch instance**.
7. Confirm the instance appears in the list and is **Running**, then rename or tag it as required.
    
    ![image.png](Launch%20EC2%20Instance/image%201.png)
    

---

### Quick check

- **Location:** EC2 → Instances → Instances
- **Expected result:** New instance exists in the list with:
    - **State:** Running
    - **Key pair:** Matches the provided requirements
    - **Security group:** Matches the provided requirements
    - **Name/Tags:** Match the provided requirements