# sit-ticket-management-system
B2B IT ticket management system built on Microsoft Power Platform (capstone project)
# SIT - IT Service Ticket Management System

Final-year capstone project — B.Sc. Industrial Engineering & Management (Information Systems).
A B2B IT service-desk ticketing system built on the Microsoft Power Platform for an
IT services company (~70 employees), replacing a manual process previously run on a legacy CRM.

## Problem
Support requests were handled manually with no single source of truth: hard to track
status, ownership, history, or keep customers updated.

## Solution
A centralized ticketing system where customers open and follow up on tickets **by email only**
(no separate portal), and the support team manages the full lifecycle inside a Power Apps app.

## Tech stack
- **Power Apps** (Canvas app) — front end
- **SharePoint Online** — data layer (Tickets, Statuses, History, Messages, Customers, Priorities, Attachments)
- **Power Automate** — email-to-ticket intake and notification flows
- **Office 365 / Outlook** integration

## Key features
- Email-to-ticket intake — a customer email automatically creates a ticket
- Full status lifecycle (New → In Process → Pending → In Approval → WFC → R&D → Closed / Cancelled)
- Automatic email notification to the customer on every status change
- Ticket history / audit trail, internal messages, attachments, and priorities
- Internal-employee detection and inactive-customer handling on intake

## Methodology
Developed with the V-Model. A feasibility study compared Microsoft 365, Zendesk, and SysAid
using an Expected Utility Model (benefit + normalized cost); Microsoft 365 was selected.

## Screenshots
**Create a new ticket screen**
<img width="832" height="454" alt="create new case - 1" src="https://github.com/user-attachments/assets/617252ed-de77-4d65-bc1e-2d31c74f6986" />
**Ticket queue screen**
<img width="832" height="454" alt="ticket queue - 2" src="https://github.com/user-attachments/assets/8e2eae5e-5383-4d5f-ab22-b2993150f2a4" />
**Ticket details screen**
<img width="832" height="454" alt="ticket details - 3" src="https://github.com/user-attachments/assets/abb58ef5-2ef9-47fc-b22e-3a285e419e28" />
**Settings screen**
<img width="832" height="454" alt="settings - 4" src="https://github.com/user-attachments/assets/3bfd7975-ace0-4df2-95a5-6d1d04165eab" />
**Dashboard screen**
<img width="857" height="454" alt="dashboard - 5" src="https://github.com/user-attachments/assets/940ac4b1-11ca-4167-932f-8541524f3209" />
**Overdue tickets screen**
<img width="832" height="454" alt="overdue tickets - 6" src="https://github.com/user-attachments/assets/485a07e9-5fc3-41dd-8144-2239542f4563" />


## Role
Built as a two-person team as part of an academic capstone, under academic and organizational supervision.
