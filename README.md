# osTicket Ticket Management Lab 

## Overview
This repository documents a hands-on lab focused on creating, managing, and resolving tickets in an osTicket helpdesk environment. The lab explores ticket properties, escalations, department restructuring, and real-world ticketing workflows.

## Components
- Primary System: Windows 10 (Azure Virtual Machine)
- osTicket Version: 1.15.8
- Database: MySQL 5.5.62

## Steps Taken
1. Accessing osTicket
   - Admin/Analyst Login Page: http://localhost/osTicket/scp/login.php
   - End Users osTicket URL: http://localhost/osTicket
2. Restructuring Departments
    - Converted SysAdmins into a Top-Level Department
    - Deleted (not archived) Maintenance Department
3. Creating and Managing Tickets
   1. Ticket 1: Banking System Outage
    - Created by End-User: "Entire mobile/online banking system is down"
    - Observed by Help Desk Agent (John):
      - Priority
      - Department
      - SLA
      - Assigned To
    - Properties Set:
      - SLA: Sev-A (1 hour, 24/7)
      - Department: Online Banking
   - Access Check:
      - John attempts to observe the ticket again → Unable to modify
    - Resolved by: Jane

   2. Ticket 2: Adobe Upgrade for Accounting
      - Created by End-User: "Accounting department needs Adobe upgrade, broken"
      - Observed by Help Desk Agent (John):
         - Priority
         - Department
         - SLA
         - Assigned To
      - Properties Set:
         - SLA: Sev-B (4 hours, 24/7)
         - Department: Support
         - Resolved by: John
   3. Ticket 3: CFO’s Laptop Failure
      - Created by End-User: "CFO’s laptop will no longer turn on"
      - Observed by Help Desk Agent (John):
         - Priority
         - Department
         - SLA
         - Assigned To
      - Properties Set:
         - SLA: Sev-B (4 hours, 24/7)
         - Department: Support
      - Resolved by: John

## Verification Screenshots
![Ticket #1 - John's Account](https://github.com/user-attachments/assets/7ab57270-70c5-4bcf-8a53-403c7e682d77)
![Assigning Ticket #1](https://github.com/user-attachments/assets/3a5ae8bf-f419-459d-900e-fe8d7db8e43b)
![Ticket #1 Closure](https://github.com/user-attachments/assets/1bc6c911-0ef7-492f-8e0e-792169aea198)
![Ticket #2](https://github.com/user-attachments/assets/d161cdc8-4697-4824-8d80-9c849090029c)
![Ticket #3](https://github.com/user-attachments/assets/8472c0ab-97b7-42a4-b802-1d0a3cf1fa1a)

