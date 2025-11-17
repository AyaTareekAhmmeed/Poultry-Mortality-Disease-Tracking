# 🐓 Poultry Mortality & Disease Tracking App  
### Power Apps + Microsoft Dataverse

This project is a custom Power Apps solution built for **Organo Group Poultry Company** to digitize and streamline mortality and disease tracking across poultry farms.  
The app is fully integrated with **Microsoft Dataverse**, which acts as the core data backbone for all records, relationships, and analytics.

---

## 📌 Features

### 1️⃣ Mobile Data Entry  
- Simple, user-friendly interface for farm teams  
- Mortality and disease logs submitted directly from mobile devices  
- Automatic synchronization with Dataverse

### 2️⃣ Dataverse-Driven Data Model  
The strength of the app comes from Dataverse:  
- Hierarchical tables for disease categories, sub-conditions, and mortality types  
- Calculated columns for dynamic business logic  
- Relationships enforced at the data level  
- Secure, scalable, and centralized storage

### 3️⃣ Dynamic UI Components  
- **Power Apps Accordion** for mortality categories  
- Drill-down navigation for disease hierarchy  
- Editable galleries for validation and inline correction

### 4️⃣ Real-Time Monitoring  
- Every record is instantly available across departments  
- Integrity and accuracy ensured through Dataverse rules  
- Fully prepared for Power BI dashboards

---

## 🧱 Architecture Overview

### **Power Apps**  
- Frontend UI  
- Validation logic  
- Offline-friendly input screens

### **Microsoft Dataverse**  
- Core tables (Mortality, Disease, Farms, Conditions, Categories)  
- Hierarchical relationships  
- Business rules and calculated columns

### **Power BI (Optional)**  
- Analytics dashboards using Dataverse connector  
- Trends for mortality, diseases, and farm performance

---

## 🛠️ Technologies Used
- **Power Apps Canvas App**  
- **Microsoft Dataverse**  
- **Power Fx**  
- **Power Automate** (Optional for notifications)  
- **Power BI**

---

## 📄 How to Use
1. Log in using your organization account  
2. Select the farm and date  
3. Enter mortality or disease details  
4. Submit — data flows directly into Dataverse  
5. Review or edit through editable galleries
