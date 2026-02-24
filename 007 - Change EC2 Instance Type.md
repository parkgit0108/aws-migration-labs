# Change EC2 Instance Type

<aside>

**Purpose:** Change an existing **EC2 instance type** (resize) by stopping the instance, updating the type, then starting it again.

</aside>

---

### Procedure

1. Sign in to the AWS Console using the provided credentials and URL.
2. Navigate to the **EC2 dashboard**.
    
    <img width="1466" height="1092" alt="image" src="https://github.com/user-attachments/assets/661c3aec-7d31-4fdd-b56c-885790e312a0" />

3. In the left sidebar, go to **Instances → Instances**.
4. Wait for the **Status checks** to complete.
    - This typically takes **3 to 5 minutes** after launch.
5. Select the instance you want to change.
6. Stop the instance.
    - Go to **Instance state → Stop instance**.
    - Wait for the **Instance state** to change to **Stopped**.
    
    <img width="1471" height="697" alt="image" src="https://github.com/user-attachments/assets/775397f6-a43e-4212-b06e-a0cc914a6125" />
    
7. Change the instance type.
    - Go to **Actions → Instance settings → Change instance type**.
    
    <img width="1463" height="842" alt="image" src="https://github.com/user-attachments/assets/08411c2f-b510-454f-8464-f3a85115953b" />
    
8. Select the required instance type, then click **Change instance type**.
    
    <img width="1471" height="1150" alt="image" src="https://github.com/user-attachments/assets/6c339ced-1e81-4860-a814-da064ff138ab" />
    
9. Start the instance.
    - Go to **Instance state → Start instance**.
10. Confirm the instance type and state.
    - **Instance state:** Running
    - **Instance type:** Updated as required
    
    <img width="1475" height="393" alt="image" src="https://github.com/user-attachments/assets/8190a3e2-4769-43a3-b3a5-70446b4c8406" />
    

---

### Quick check

- **Location:** EC2 → Instances → Instances
- **Expected result:**
    - Instance is **Running**
    - **Instance type** matches the required value
