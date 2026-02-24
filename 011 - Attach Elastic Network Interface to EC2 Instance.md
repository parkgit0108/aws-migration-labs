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
    
    ![image.png](Attach%20Elastic%20Network%20Interface%20to%20EC2%20Instance/image.png)
    
6. Fill out the fields with the provided information, then click **Attach**.
    
    ![image.png](Attach%20Elastic%20Network%20Interface%20to%20EC2%20Instance/image%201.png)
    
7. Confirm the instance now shows the attached network interface:
    1. Go to **Instances → Instances**.
    2. Select the instance.
    3. Go to the **Networking** section and confirm the interface is listed.
        
        ![image.png](Attach%20Elastic%20Network%20Interface%20to%20EC2%20Instance/image%202.png)
        

### Quick check

- **Location:** EC2 → Network & Security → Network Interfaces
- **Expected result:** Network interface is listed under the instance’s **Networking** section