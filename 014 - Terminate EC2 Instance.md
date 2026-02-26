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
    
    ![image.png](Terminate%20EC2%20Instance/image.png)
    
6. Confirm the termination when prompted.
    
    ![image.png](Terminate%20EC2%20Instance/image%201.png)
    
7. Verify the instance state changes to **Shutting-down**, then **Terminated**.
    
    ![image.png](Terminate%20EC2%20Instance/image%202.png)
    

### Quick check

- **Location:** EC2 → Instances → Instances
- **Expected result:** Instance state shows **Terminated**