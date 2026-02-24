# Change EC2 Instance Type

<aside>

**Purpose:** Change an existing **EC2 instance type** (resize) by stopping the instance, updating the type, then starting it again.

</aside>

---

### Procedure

1. Sign in to the AWS Console using the provided credentials and URL.
2. Navigate to the **EC2 dashboard**.
    
    ![image.png](Change%20EC2%20Instance%20Type/image.png)
    
3. In the left sidebar, go to **Instances → Instances**.
4. Wait for the **Status checks** to complete.
    - This typically takes **3 to 5 minutes** after launch.
5. Select the instance you want to change.
6. Stop the instance.
    - Go to **Instance state → Stop instance**.
    - Wait for the **Instance state** to change to **Stopped**.
    
    ![image.png](Change%20EC2%20Instance%20Type/image%201.png)
    
7. Change the instance type.
    - Go to **Actions → Instance settings → Change instance type**.
    
    ![image.png](Change%20EC2%20Instance%20Type/image%202.png)
    
8. Select the required instance type, then click **Change instance type**.
    
    ![image.png](Change%20EC2%20Instance%20Type/image%203.png)
    
9. Start the instance.
    - Go to **Instance state → Start instance**.
10. Confirm the instance type and state.
    - **Instance state:** Running
    - **Instance type:** Updated as required
    
    ![image.png](Change%20EC2%20Instance%20Type/image%204.png)
    

---

### Quick check

- **Location:** EC2 → Instances → Instances
- **Expected result:**
    - Instance is **Running**
    - **Instance type** matches the required value