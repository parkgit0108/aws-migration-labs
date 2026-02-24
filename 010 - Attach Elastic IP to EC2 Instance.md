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
    
    <img width="1468" height="792" alt="image" src="https://github.com/user-attachments/assets/87342767-dbd4-488f-924f-0c0084de3e5a" />
    
6. Fill out the fields with the provided information, then click **Associate**.
    
    <img width="1473" height="532" alt="image" src="https://github.com/user-attachments/assets/9e4646d9-094b-45fc-82f8-e1cbb578b9ae" />
    
7. Confirm the instance now shows the Elastic IP:
    1. Go to **Instances → Instances**.
    2. Select the instance.
    3. Check the instance **Details** section.
        
        <img width="1471" height="875" alt="image" src="https://github.com/user-attachments/assets/a9f9a957-8454-4861-ad94-bf841804aee0" />
        

### Quick check

- **Location:** EC2 → Network & Security → Elastic IPs
- **Expected result:** Instance shows the Elastic IP in the instance details panel
