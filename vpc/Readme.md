# ☁️ AWS VPC Creation using CloudFormation

## 📌 Project Description
This project demonstrates the creation of a **custom Amazon VPC** using **AWS CloudFormation Infrastructure Composer**.  
The VPC architecture includes public and private subnets, route tables, an Internet Gateway, and a NAT Gateway, all deployed using **Infrastructure as Code (IaC)**.

---

## ☁️ AWS Services Used
- Amazon VPC
- AWS CloudFormation
- Infrastructure Composer
- Subnets (Public & Private)
- Internet Gateway
- NAT Gateway
- Route Tables
- Elastic IP

---

## 🛠️ Tools & Technologies
- AWS Management Console
- CloudFormation Infrastructure Composer
- YAML (CloudFormation Template)
- Networking concepts (CIDR, routing)

---

## 🚀 Project Implementation

### **1️⃣ Design VPC Architecture**
- Designed the VPC visually using **Infrastructure Composer**
- Defined public and private subnets across availability zones
- Planned routing and internet access

---

### **2️⃣ Create CloudFormation Template**
- Automatically generated a **YAML template** from Infrastructure Composer
- Template included:
  - VPC
  - Internet Gateway
  - NAT Gateway with Elastic IP
  - Public & Private Subnets
  - Route Tables and Associations

---

### **3️⃣ Configure Networking**
- Public Route Table configured with:
- text
- 0.0.0.0/0 → Internet Gateway

---

### **4️⃣ Deploy Stack**
- Validated the CloudFormation template
- Created the stack using CloudFormation
- AWS automatically provisioned all VPC resources

---

### **5️⃣ Verify Resources**
- Verified VPC, subnets, gateways, and route tables
 Confirmed public and private subnet behavior
- Ensured secure and isolated network design

--- 

### **🌐 Output**
- Custom VPC successfully created using CloudFormation
- Public subnets have internet access
- Private subnets are securely isolated
- Fully automated and repeatable network setup
