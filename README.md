<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket - Ticketing System Workflow

This repository documents the **end-to-end workflow** of handling support tickets in **osTicket**, an open-source help desk system.

## Table of Contents
- [Overview](#overview)
- [Environments and Technologies Used](#environments-and-technologies-used)
- [Operating Systems Used](#operating-systems-used)
- [Ticket Workflow Steps](#ticket-workflow-steps)
  - [1. Creating a Ticket](#1-creating-a-ticket)
  - [2. Assigning and Updating Ticket Severity](#2-assigning-and-updating-ticket-severity)
  - [3. Resolving a Ticket](#3-resolving-a-ticket)
  - [4. Closing a Ticket](#4-closing-a-ticket)
  - [5. Viewing Closed Tickets](#5-viewing-closed-tickets)
  - [6. Final Review - All Tickets Resolved](#6-final-review---all-tickets-resolved)
- [Conclusion](#conclusion)

---

## Overview
This guide walks through a **real-world use case** of how a support team can handle **customer issues** efficiently using osTicket. The workflow includes:
✅ **Ticket creation** by end-users  
✅ **Ticket assignment** and prioritization by agents  
✅ **Updating severity** and reassigning tickets  
✅ **Resolving and closing tickets**  

---

## Environments and Technologies Used
- **Microsoft Azure** (Virtual Machines for hosting osTicket)
- **osTicket** (Open-source ticketing system)
- **Remote Desktop** (Agent and admin access)
- **MySQL Database** (Backend storage for tickets)

---

## Operating Systems Used
- **Windows 10** (End-user portal access)
- **Windows Server 2019** (Hosting osTicket on IIS)

---

## Ticket Workflow Steps

### 1. Creating a Ticket
An end-user (**Karen Doe**) creates a ticket through the **osTicket Support Center** regarding an issue with the **online banking system** being down.

![image](https://github.com/user-attachments/assets/149d3ad9-77b5-4630-8bdd-fda0fc8f388c)


Karen provides:
- **Contact Information**
- **Help Topic**: "Report a Problem"
- **Issue Summary**: "Entire mobile/online banking system is down"
- **Detailed Description**: Employees unable to access the banking portal.

---

### 2. Assigning and Updating Ticket Severity
A support agent (**John Doe**) logs into osTicket, reviews the submitted ticket, and updates the **ticket severity and assignment**.

![image](https://github.com/user-attachments/assets/13d7297d-ad8a-40d6-9457-9d6d87d063c4)


![image](https://github.com/user-attachments/assets/eb6f8298-15a7-44bb-b1e2-62a71bb63eb4)

- **Severity Updated**: SLA Plan changed from **Default SLA (18 hrs)** to **Sev-A (1 hr - Emergency)**
- **Reassignment**: John assigns the ticket to the **Online Banking team** for specialized handling.

---

### 3. Resolving a Ticket

#### Ticket #1: Online Banking System Down
The **Online Banking team (Jane Doe)** investigates and resolves the issue by rolling back a system update.

![image](https://github.com/user-attachments/assets/d10fb97f-b48f-40a0-b443-6417752e6bd2)

![image](https://github.com/user-attachments/assets/a9172578-0284-4d5e-b539-43422d81a1d1)

Steps taken:
1. **John identifies wide impact** and escalates the ticket.
2. **Ticket is assigned to Jane Doe (Banking Specialist)**.
3. **Jane tests, finds the issue**, and **rolls back the update**.
4. **Online banking system restored** and customers notified.

---

#### Ticket #2: Microsoft Excel Not Working
A user (**Ken Doe**) reported that **Microsoft Excel was not working** for the accounting department. 


![image](https://github.com/user-attachments/assets/ae805c46-c61d-40b0-9a4a-9839d7b3c674)


- **Issue**: Excel not launching for multiple users in the accounting department.
- **Assigned to**: **John Doe** (IT Support Agent)
- **SLA Updated**: Severity changed to **Sev-B (4 hrs)**

John troubleshoots and **resolves the issue** by restarting the system.

![image](https://github.com/user-attachments/assets/a8caf3e4-98f1-49f9-b60c-50239029c2c5)


- **Fix**: System reboot restored Excel functionality.
- **User Verified**: Ken confirmed Excel was working post-restart.
- **Ticket Marked Resolved**.

---

#### Ticket #3: Laptop Not Powering On
A user (**Karen Doe**) reported that their **CFO's laptop was not turning on**.

![image](https://github.com/user-attachments/assets/c16fe5f0-5606-4317-893b-041b9979b5ac)


- **Issue**: Laptop not powering on despite pressing the power button.
- **Assigned to**: **John Doe**
- **SLA Updated**: Severity changed to **Sev-B (4 hrs)**

John investigates and finds that the **charger was broken**, replaces it, and confirms the fix.

![image](https://github.com/user-attachments/assets/5d7984b4-6a0c-4158-be4d-16b4e07e7da6)


- **Fix**: New charger provided.
- **User Verified**: CFO confirmed laptop now works.
- **Ticket Closed**.

---

### 4. Closing a Ticket
Once issues are confirmed as resolved, agents **close the tickets** in osTicket.

![image](https://github.com/user-attachments/assets/ce1738c5-9bc0-436d-ad75-3e55e95ba508)


- **Final Update**: Ticket is marked as **Resolved**.
- **End-user notification** sent via osTicket.
- **Case closed in the system**.

---

### 5. Final Review - All Tickets Resolved
The support team successfully **closed all tickets**, ensuring that no unresolved issues remain.

![image](https://github.com/user-attachments/assets/6c71b535-4caf-4c52-bf10-e2fd7d747b2b)

- **Final Check**: All tickets have been processed and resolved.
- **Agents can review past tickets** to improve response times and efficiency.

---

## Conclusion
This guide showcases a **real-world example** of handling support issues using **osTicket**. The structured workflow ensures:
✅ **Efficient Ticket Management**  
✅ **Proper Ticket Prioritization (SLA)**  
✅ **Clear Team Assignments**  
✅ **Faster Issue Resolution**  

---
