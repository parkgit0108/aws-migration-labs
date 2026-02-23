# Create Subnet

<aside>

**Purpose:** Create a new **subnet** in the **default VPC** without overlapping existing IPv4 CIDR ranges.

</aside>

---

### Procedure

1. Sign in to the AWS Console using the provided credentials and URL.
2. Search for **VPC** and open the **VPC Dashboard**.
3. In the left sidebar, click **Subnets**, then click **Create subnet**.
4. In the **VPC** dropdown, select the **default VPC**.
5. Fill out the form with the provided information.
    - For **IPv4 subnet CIDR block**, make sure it does **not overlap** any existing subnet.
    - Use the **next arrow** button to select the next available subnet range.
   <img width="502" height="125" alt="image" src="https://github.com/user-attachments/assets/4c8fdb9f-e118-47ae-a711-36f3572650c3" /> 
    
6. Click **Create subnet**.
    
    <img width="1889" height="1128" alt="image" src="https://github.com/user-attachments/assets/2cb9f14b-8318-46a0-9b8f-bca187929acf" />

---

### Quick check

- **Location:** VPC → Subnets
- **Expected result:** The new subnet appears in the subnet list and shows the expected IPv4 subnet CIDR block  
