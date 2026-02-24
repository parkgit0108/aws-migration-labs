# Attach Elastic IP to EC2 Instance

---

<aside>

**Purpose:** Associate an **Elastic IP** to an EC2 instance so it has a static public IP address.

</aside>

---

### Procedure

1. Sign in to the AWS Console using the provided credentials and URL.
2. Navigate to the **EC2 dashboard**.
3. In the left sidebar, go to **Network & Security → Elastic IPs**.
4. Select the Elastic IP you want to attach.
5. Go to **Actions → Associate Elastic IP address**.
    
    ![image.png](Attach%20Elastic%20IP%20to%20EC2%20Instance/image.png)
    
6. Fill out the fields with the provided information, then click **Associate**.
    
    ![image.png](Attach%20Elastic%20IP%20to%20EC2%20Instance/image%201.png)
    
7. Confirm the instance now shows the Elastic IP:
    1. Go to **Instances → Instances**.
    2. Select the instance.
    3. Check the instance **Details** section.
        
        ![image.png](Attach%20Elastic%20IP%20to%20EC2%20Instance/image%202.png)
        

### Quick check

- **Location:** EC2 → Network & Security → Elastic IPs
- **Expected result:** Instance shows the Elastic IP in the instance details panel