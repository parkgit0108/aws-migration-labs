# Configuring Secure SSH Access to an EC2 Instance

---

<aside>

**Purpose:** Configure **secure SSH access** to a new **EC2 instance** using an **SSH key pair** generated on the client.

</aside>

---

### Procedure

1. Create an EC2 instance (no key pair):
    1. Click **Launch instance**.
    2. Set the instance **name** and select settings as required.
    3. For **Key pair**, select **Proceed without a key pair** (No key pair).
    4. Click **Launch instance**.
2. On the AWS client, generate a key pair:
    1. Run `ssh-keygen`.
    2. Confirm where the key is saved.
        
        ![image.png](Configuring%20Secure%20SSH%20Access%20to%20an%20EC2%20Instance/image.png)
        
3. Copy the public key content:
    1. Run `cat /root/.ssh/id_rsa.pub`.
    2. Copy the output.
        
        ![image.png](Configuring%20Secure%20SSH%20Access%20to%20an%20EC2%20Instance/image%201.png)
        
4. Add the public key to the EC2 instance `authorized_keys`:
    1. Select the EC2 instance and **connect** to the console.
        
        ![image.png](Configuring%20Secure%20SSH%20Access%20to%20an%20EC2%20Instance/image%202.png)
        
    2. Open `/root/.ssh/authorized_keys` in **nano** or **vi**.
    3. Paste the public key output from the previous step.
    4. Save and exit.
5. Test SSH connectivity:
    1. From the AWS client, SSH to the EC2 **public IP**.
        
        ![image.png](Configuring%20Secure%20SSH%20Access%20to%20an%20EC2%20Instance/image%203.png)
        

### Quick check

- **Location:** AWS client terminal
- **Expected result:** SSH connection succeeds using the key you generated