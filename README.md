# 📌 n8n Leave Approval Automation with Dashboard

## 📖 Overview
This project is an **automated leave management system** built using **n8n, Google Sheets, Gmail, and Power BI**.  
It streamlines the leave approval process by automatically validating requests, sending email notifications, and visualizing data in a dashboard.

---

## 🚀 Features

- ✅ Automated leave request processing  
- 📊 Conditional approval logic (based on leave count)  
- ✉️ Instant email notifications (Approval/Rejection)  
- 📁 Data logging in Google Sheets  
- 📈 Interactive Power BI Dashboard  
- ⚡ Real-time workflow execution  

---

## ⚙️ Workflow Explanation

1. **Google Sheets Trigger**
   - Detects new form responses automatically  

2. **Condition Check (IF Node)**
   - If `no of leaves > 3` → ❌ Rejected  
   - Else → ✅ Approved  

3. **Email Notification (Gmail)**
   - Sends approval/rejection email to employee  

4. **Data Storage**
   - Appends processed data back into Google Sheets  

---

## 🧩 Tech Stack

- **n8n** → Workflow automation  
- **Google Sheets** → Data storage & trigger  
- **Gmail API** → Email notifications  
- **Power BI** → Data visualization  

---



---

## 📂 Screenshots

### 🧠 n8n Workflow
![n8n Workflow](./screenshots/n8n-workflow.png)

---

### 📈 Power BI Dashboard
![Power BI Dashboard](./screenshots/powerbi-dashboard.png)

---


---

## 🔐 Requirements

- n8n (Cloud or Self-hosted)  
- Google Sheets API credentials  
- Gmail OAuth2 credentials  
- Power BI Desktop  

---

## 🛠️ Setup Instructions

1. Import the `workflow.json` file into n8n  
2. Connect:
   - Google Sheets account  
   - Gmail account  
3. Ensure your Google Sheet has columns:
   - `name`
   - `email`
   - `no of leaves`
4. Activate the workflow  
5. Submit a new form entry → automation will trigger  

---

## ✉️ Email Templates

### ❌ Rejection Email
- Subject: `Not Approved`  
- Message:
- 
### ✅ Approval Email
- Subject: `Approved`  
- Message:
- 
---

## 📊 Dashboard Insights

The Power BI dashboard provides:

- Total leave requests  
- Approved vs Rejected ratio  
- Leave trends over time  
- Employee-level analysis  

---

## 🔮 Future Improvements

- 🔁 Multi-level approval system (Manager + HR)  
- 📊 Leave balance tracking per employee  
- 🔔 Slack / Microsoft Teams integration  
- 📝 Approval/Rejection reason tracking  
- 📡 Real-time dashboard auto-refresh  
- 📉 Advanced analytics (department-wise insights, absenteeism trends)  

---

## 🎯 Use Cases

- HR automation for small organizations  
- Employee leave tracking systems  
- Workflow automation learning project  
- Data visualization portfolio project  

---

## 🧠 Learning Outcomes

- n8n workflow automation  
- API integration (Google Sheets & Gmail)  
- Conditional logic building  
- Dashboard creation in Power BI  
- End-to-end project implementation  

---

## 💡 Author

**Akshita Mittal**  
HR & Tech Enthusiast | Workflow Automation | Data Analytics  

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub!
