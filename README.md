
## Virtual Private Cloud (VPC)

### Name: HEMA LOKITHA P

### Register Number: 212223110014

---

## AIM
To study the steps involved in setting up a private cloud using **AWS** or **Microsoft Azure** platforms and explore its core features and services.

---

## PROCEDURE

### **Step 1: Create a Cloud Account**
- Sign up for an account on **AWS** or **Microsoft Azure**.
- Complete verification using your **email** and **credit card**.
- Log in to the **AWS Management Console** or **Azure Portal**.

---

### **Step 2: Set Up a Virtual Private Cloud (VPC / VNet)**
- **For AWS:**
  1. Go to **VPC Dashboard** → Click **Create VPC**.
  2. Enter a name and specify the **CIDR block** (e.g., `10.0.0.0/16`).

- **For Azure:**
  1. Navigate to **Virtual Network (VNet)** in Azure Portal.
  2. Create a VNet by defining **name**, **region**, and **address space**.

---

### **Step 3: Configure Subnets and Routing**
- Create **Public** and **Private Subnets** within the VPC or VNet.
- Configure **Route Tables** to manage traffic between subnets and the internet.
- Attach an **Internet Gateway** to the public subnet for external connectivity.
- Keep private subnets isolated for internal communication.

---

### **Step 4: Create and Launch Instances**
- Launch an **EC2 Instance** (AWS) or **Virtual Machine** (Azure) within your VPC/VNet.
- Choose an appropriate **AMI** or **OS Image** (Ubuntu, Amazon Linux, Windows).
- Assign each instance to the respective subnet (Public/Private).

---

### **Step 5: Security Configuration**
- Create **Security Groups** (AWS) or **Network Security Groups (NSGs)** (Azure).
- Configure **inbound/outbound rules**:
  - Allow `SSH (22)` for Linux access.
  - Allow `RDP (3389)` for Windows access.
  - Allow `HTTP (80)` for web servers.
- Ensure private subnet instances are **not directly accessible** from the internet.

---

### **Step 6: Storage and Networking**
- Attach **Elastic Block Store (EBS)** volumes or **Azure Managed Disks**.
- Configure **Load Balancers** and **NAT Gateways** if needed.
- Verify DNS, IP allocation, and subnet connectivity.

---

### **Step 7: Testing**
- Use `ping`, `ssh`, or **RDP** to check connectivity between instances.
- Test public instance access through the internet.
- Confirm internal communication between private instances.

---

## OUTPUT


<img width="1917" height="953" alt="Screenshot 2025-10-30 113008" src="https://github.com/user-attachments/assets/08e32227-3589-439e-beb8-9060491d9b24" />


<img width="1890" height="869" alt="Screenshot 2025-10-30 114121" src="https://github.com/user-attachments/assets/57c01c54-a553-44b2-a952-0edb10c3acc6" />


<img width="1231" height="886" alt="Screenshot 2025-10-30 114257" src="https://github.com/user-attachments/assets/cc853a60-ff5b-41fe-b7b8-24a4c748d932" />

<img width="1912" height="946" alt="image" src="https://github.com/user-attachments/assets/a63fd41f-a094-4851-b5fd-66f9996b9443" />


<img width="1915" height="1005" alt="image" src="https://github.com/user-attachments/assets/1a748236-f063-4535-bc81-ccb722f396e4" />



## RESULT
A **private cloud environment** was successfully created using the **AWS/Azure** platform.  
Core components such as **VPC/VNet**, **Subnets**, **Instances**, and **Security Groups** were configured.  
The setup was tested and verified for **internal communication** and **external access** as per the configuration.
