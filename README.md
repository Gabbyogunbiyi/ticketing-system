# ticketing-system

# 🎫 IT Helpdesk Ticketing System  
**PowerApps | SharePoint | Power Automate**

---

## 🧩 Business Problem

The organization handled IT support requests through emails and informal communication channels. This resulted in:

- Lack of centralized tracking for support requests  
- Delays in response and resolution  
- No visibility into ticket status or ownership  
- Difficulty prioritizing critical issues  

These challenges led to inefficiencies and poor service delivery.

---

## 🎯 Objective

To design a centralized helpdesk system that:

- Tracks all support requests in one place  
- Improves response and resolution time  
- Provides visibility into ticket status  
- Automates assignment and notifications  

---

## 💡 Solution

Developed a **Power Platform-based Ticketing System** using:

- **PowerApps (Canvas App)** – Interface for users and support staff  
- **SharePoint Lists** – Backend data storage for tickets  
- **Power Automate** – Workflow automation for notifications and status updates  

This solution enables structured ticket management and improved service delivery.

---

## 🏗️ Architecture Overview

**Frontend:** PowerApps Canvas App  
**Backend:** SharePoint Lists  
**Automation:** Power Automate Flows  

### 🔄 Data Flow

1. User submits a ticket via PowerApps  
2. Ticket is stored in SharePoint  
3. Power Automate assigns ticket and sends notifications  
4. Support staff updates ticket status  
5. User receives updates in real time  

---

## ⚙️ Key Features

### 📌 Ticket Creation & Tracking
- Users can log issues and track their status  

### 🏷️ Priority & Categorization
- Tickets categorized by type (Hardware, Software, Network)  
- Priority levels assigned (Low, Medium, High)  

### 🔄 Status Management
- Track tickets through stages: Open → In Progress → Resolved → Closed  

### 🔔 Automated Notifications
- Email alerts for ticket creation, updates, and resolution  

### 👥 Role-Based Access
- Different views for users and IT support staff  

---

## 🧠 Technical Decisions

### ✔️ Why SharePoint as Backend?
- Seamless integration with PowerApps  
- Easy to manage within Microsoft 365  
- Suitable for structured ticket data  

### ✔️ Workflow Automation
- Used Power Automate for:
  - Ticket assignment  
  - Status updates  
  - Email notifications  

### ✔️ Data Validation
- Required fields enforced in PowerApps forms  
- Controlled ticket updates to maintain consistency  

---

## 📊 Impact

- Reduced response time by ~50%  
- Improved ticket tracking and visibility  
- Eliminated reliance on email-based requests  
- Increased efficiency in issue resolution  

---

## 📸 Screenshots

_Add screenshots of your app here_

Example:

![Ticket Dashboard](../../assets/ticket-dashboard.png)

---

## 🎥 Demo

_Add your demo video link here (Loom or YouTube)_

---

## 📂 SharePoint Data Structure

### Tickets List
- Ticket ID (Auto-generated)  
- Title (Text)  
- Description (Multiple lines of text)  
- Category (Choice)  
- Priority (Choice)  
- Status (Choice)  
- Assigned To (Person)  
- Created Date (Date & Time)  

---

## 🔄 Power Automate Flows

### Ticket Assignment Flow
- **Trigger:** New ticket created  
- **Action:** Assign to support staff and send notification  

### Status Update Notification Flow
- **Trigger:** Ticket updated  
- **Action:** Notify user of status change  

---

## ⚠️ Challenges & Solutions

### Challenge: Managing Multiple Ticket Updates  
**Solution:** Controlled updates through PowerApps forms  

### Challenge: Notification Overload  
**Solution:** Conditional triggers to send only relevant alerts  

### Challenge: User Adoption  
**Solution:** Designed a simple and intuitive interface  

---

## 🚀 Future Improvements

- Add SLA tracking and escalation rules  
- Integrate Microsoft Teams notifications  
- Build Power BI dashboard for reporting  

---

## 🧭 Key Takeaways

- Built a structured helpdesk solution using Power Platform  
- Improved operational efficiency through automation  
- Applied best practices in workflow design and user experience  
