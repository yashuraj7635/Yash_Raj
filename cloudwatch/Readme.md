# ☁️ AWS CloudWatch Billing Alert Project

## 📌 Project Description
This project demonstrates setting up **AWS CloudWatch Billing Alerts** to monitor AWS usage costs and receive notifications when charges exceed a defined threshold.  
The objective is to prevent unexpected billing by enabling **cost monitoring and alerts** using AWS CloudWatch and Billing preferences.

---

## ☁️ AWS Services Used
- Amazon CloudWatch
- AWS Billing & Cost Management
- CloudWatch Alarms
- AWS Free Tier Alerts

---

## 🛠️ Tools & Technologies
- AWS Management Console
- CloudWatch Metrics & Alarms
- Billing Preferences
- Email Notifications

---

## 🚀 Project Implementation

### **1️⃣ Enable Billing Alerts**
- Enabled **CloudWatch billing alerts** from AWS Billing preferences  
- Enabled **AWS Free Tier usage alerts**  
- Configured email notifications for alerts  

---

### **2️⃣ Create CloudWatch Billing Alarm**
- Created a CloudWatch alarm using:
  - **Namespace:** `AWS/Billing`
  - **Metric:** `EstimatedCharges`
  - **Statistic:** Maximum
  - **Currency:** USD  

---

### **3️⃣ Configure Alert Threshold**
- Set billing threshold to
- text
- EstimatedCharges >= $1.20
- Evaluation period set to 6 hours
- Alarm triggers when cost exceeds the defined limit

---

### **4️⃣ Configure Notification**
- Linked the alarm to email notifications
- Alerts delivered successfully to registered email address
- Alarm status monitored via CloudWatch dashboard

### **5️⃣ Monitor Billing Status**
-Verified alarm visibility in CloudWatch

- Billing alarm displayed under Billing → Alarms
- Ensured cost monitoring is active and working

### **🌐 Output**
- CloudWatch billing alarm successfully created
- Email alerts enabled for billing and Free Tier usage
- Real-time visibility into AWS estimated charges
- Protection against unexpected AWS costs
