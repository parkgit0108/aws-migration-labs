# Terminate EC2 Instance

---

<aside>

**Purpose:** Permanently **terminate** an EC2 instance when it is no longer needed.

</aside>

---

### Procedure

1. Sign in to the AWS Console using the provided credentials and URL.
2. Navigate to the **EC2 dashboard**.
3. In the left sidebar, go to **Instances → Instances**.
4. Select the instance you want to terminate.
5. Go to **Instance state → Terminate instance** (or **Actions → Instance state → Terminate instance**, depending on the console layout).
    
    <img width="1456" height="591" alt="image" src="https://github.com/user-attachments/assets/bdb72a8d-fd9c-4bb2-a730-b7a8039b98a2" />
    
6. Confirm the termination when prompted.
    
    <img width="1342" height="720" alt="image" src="https://github.com/user-attachments/assets/997a50fd-3457-4102-9677-a42eaa434f47" />
    
7. Verify the instance state changes to **Shutting-down**, then **Terminated**.
    
    <img width="1463" height="235" alt="image" src="https://github.com/user-attachments/assets/fed91f62-1e7b-4ed6-b087-a17c551ffa58" />
    

### Quick check

- **Location:** EC2 → Instances → Instances
- **Expected result:** Instance state shows **Terminated**
