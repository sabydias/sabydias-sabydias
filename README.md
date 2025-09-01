# 👋 Hi, I'm Sebastian Dias  

💡 A Business Analyst & Tech Enthusiast passionate about bridging **business processes** with **tech-driven solutions**.  
⚡ Experienced in building and enhancing modules for **IMEXIO**, a trade & customs management platform in India.  

---

## 🚀 About Me  
- 🧑‍💻 4+ years of experience in **Business Analysis & Operations**  
- 🌐 Worked on **IMEXIO**, handling modules like:
  - Registration  
  - Payments  
  - Bill of Entry (BOE)  
  - Shipping Bill (SB)  
  - Notifications & Email Integration (SMTP/SignalR)  
  - User Access & Role Management  
  - API  
  - Master Management for Users  
  - Reports  
  - RoDTEP/Drawback Calculations  
- 🎯 Skilled in **requirement gathering, system design, and process optimization**  
- 📊 Exploring **ERP (SAP S4HANA)** and **Supply Chain Tech** for hybrid career growth 

---

## 🛠️ Tech & Tools  
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)  
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)  
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)  
![SAP](https://img.shields.io/badge/SAP-0FAAFF?style=for-the-badge&logo=sap&logoColor=white)  

---

## 📌 IMEXIO Modules Showcase  

### 🔹 Key Modules  
![Bill of Entry](https://img.shields.io/badge/Module-Bill_of_Entry-0A66C2?style=for-the-badge&logo=azuredevops&logoColor=white)
![Shipping Bill](https://img.shields.io/badge/Module-Shipping_Bill-ff6600?style=for-the-badge&logo=oracle&logoColor=white)
![Notifications](https://img.shields.io/badge/Feature-Email_Notifications-FF6C37?style=for-the-badge&logo=gmail&logoColor=white)
![Exchange Rates](https://img.shields.io/badge/Module-Exchange_Rates-00C853?style=for-the-badge&logo=googlefinance&logoColor=white)
![RoDTEP](https://img.shields.io/badge/Module-RoDTEP_%26_Drawback-512BD4?style=for-the-badge&logo=calculator&logoColor=white)
![Access Control](https://img.shields.io/badge/Feature-Role_Access_Management-009688?style=for-the-badge&logo=auth0&logoColor=white)

### 🔹 Email SMTP Flow (BOE/SB to ICEGATE)

```mermaid
flowchart LR
    A[IMEXIO User] -->|Submit BOE/SB| B[Digital Signing]
    B --> C[SMTP Mail Send]
    C --> D[ICEGATE Server]
    D --> E[ACK Email]
    E --> F[IMEXIO Notifications Panel]
```
sequenceDiagram
    participant U as User
    participant I as IMEXIO
    participant S as SignalR
    participant E as Email Service

    U->>I: Submit to ICEGATE
    I->>S: Open SignalR Connection
    S->>E: Monitor Emails
    E-->>S: New Email Received
    S-->>U: Real-time Notification

🌱 Outside of Work
⚽ Footballer (occasional matches, weak ankle but strong spirit 💪)
🏃 marathons - Completed 3 × 10K and 1 × 15K. Preparing for 21K
☕ Coffee lover (Americano all the way)
📚 Currently reading Object-Oriented Design & Analysis by Grady Booch
