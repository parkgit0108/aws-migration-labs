# Attach Elastic Network Interface to EC2 Instance

---

<aside>

**Purpose:** Attach an **Elastic Network Interface (ENI)** to an EC2 instance.

</aside>

---

### Procedure

1. Sign in to the AWS Console using the provided credentials and URL.
2. Navigate to the **EC2 dashboard**.
3. In the left sidebar, go to **Network & Security → Network Interfaces**.
4. Select the network interface you want to attach.
5. Go to **Actions → Attach**.
    
    <img width="1469" height="985" alt="image" src="https://github.com/user-attachments/assets/c0d771ce-f681-4ad4-95bd-60a88ed90ece" />
    
6. Fill out the fields with the provided information, then click **Attach**.
    
    <img width="906" height="1251" alt="image" src="https://github.com/user-attachments/assets/0be568e1-9063-4942-802f-b587da51d6d9" />
    
7. Confirm the instance now shows the attached network interface:
    1. Go to **Instances → Instances**.
    2. Select the instance.
    3. Go to the **Networking** section and confirm the interface is listed.
        
        <img width="1465" height="1243" alt="image" src="https://github.com/user-attachments/assets/bc3e6c1b-9276-4244-87af-ccc631f9a6e9" />
        

### Quick check

- **Location:** EC2 → Network & Security → Network Interfaces
- **Expected result:** Network interface is listed under the instance’s **Networking** section
