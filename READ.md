# 🏥 Hospital Appointment & Bed Management CRM System

## 📌 Project Overview
The **Hospital Appointment and Bed Management CRM System** is a Salesforce-based enterprise CRM solution designed to streamline hospital operations such as patient appointment scheduling, doctor availability management, bed allocation, approvals, and real-time reporting.

The project is developed **phase-wise**, following **real-world Salesforce implementation methodology**, from requirement analysis to reporting dashboards.

---

## 🎯 Business Problem
Healthcare institutions face operational challenges such as:
- High patient inflow
- Limited doctor availability
- Restricted bed capacity
- Appointment conflicts and overlaps
- Manual record handling
- Lack of centralized reporting and visibility

---

## 💡 Proposed Solution
A **Salesforce CRM system** that automates:
- Appointment scheduling
- Doctor availability tracking
- Bed allocation
- Approval workflows
- Notifications and alerts
- Operational dashboards and reports

---

## 🏗️ Project Architecture (Phase-wise)

### 🔹 Phase 1: Problem Understanding & Industry Analysis
- Identified healthcare operational gaps
- Mapped hospital workflows to Salesforce capabilities
- Defined stakeholders and responsibilities
- Justified Salesforce as the core platform

---

### 🔹 Phase 2: Org Setup & Configuration
- Company setup (CityCare Hospital)
- Business hours & holidays
- Users, profiles, and role hierarchy
- Org-wide defaults & login restrictions

---

### 🔹 Phase 3: Data Modeling & Relationships
**Objects Used:**
- `Contact` → Patient
- `Doctor__c`
- `Appointment__c`
- `Bed__c`

**Key Relationships:**
- Appointment → Patient (Lookup)
- Appointment → Doctor (Lookup)

**Features:**
- Record types (OPD & Emergency)
- Page layouts & compact layouts
- Schema validation

---

### 🔹 Phase 4: Business Logic & Automation
- Validation rules to prevent invalid bookings
- Doctor availability enforcement
- Emergency appointment controls
- Record-triggered flows
- Email alerts for critical cases

---

### 🔹 Phase 5: Apex Programming
- Bulk-safe Apex Trigger
- Automatic doctor availability updates
- Validation rule compliance
- Real-world lifecycle simulation
- Anonymous Apex testing strategy

---

### 🔹 Phase 6: UI Development
- Custom Lightning App
- Tabs for Doctors, Appointments, Beds
- Record pages using Lightning App Builder
- Home page dashboards
- Utility bar enhancements
- Lightning Web Components (LWC) integration

---

### 🔹 Phase 8: Data Management & Deployment
- Data Import Wizard for Doctor records
- Data Loader overview
- Duplicate management rules
- Change Sets & SFDX deployment
- Backup and export strategies

---

### 🔹 Phase 9: Reports & Dashboards
**Reports:**
- Available Doctors
- Unavailable Doctors
- Today’s Appointments
- Available Beds
- Occupied Beds
- Beds Under Maintenance

**Dashboard:**
- Hospital Overview Dashboard
- Real-time operational KPIs
- Visual insights for management

---

## 🧑‍⚕️ Stakeholders
| Role | Responsibility |
|----|----|
| Receptionist | Appointment scheduling |
| Doctor | Patient consultation |
| Hospital Manager | Approvals & oversight |
| System Admin | Configuration & security |
| Patient | Receives confirmations |

---

## 🛠️ Technologies Used
- Salesforce CRM
- Apex Triggers
- Salesforce Flows
- Lightning App Builder
- Lightning Web Components (LWC)
- Reports & Dashboards
- SFDX & VS Code

---

## ✅ Key Outcomes
- Prevented appointment overlaps
- Automated doctor availability tracking
- Improved bed utilization
- Centralized reporting & visibility
- Production-ready Salesforce solution

---

## 📌 Project Status
✔ Completed up to **Phase 9 (Reports & Dashboards)**  
✔ Fully functional and demo-ready  
✔ Follows enterprise Salesforce best practices

---

## 📎 Author
**Altamash Faruqui**  
Salesforce | CRM | Automation | Apex | LWC

---

## 🚀 Next Enhancements (Future Scope)
- Patient portal integration
- SMS notifications
- AI-based appointment predictions
- Integration with external hospital systems
