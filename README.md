<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket

## Environments and Technologies Used

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

---
## Operating Systems Used

- Windows 10 (21H2)

---
## Ticket Lifecycle Stages

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

---
## Lifecycle Stages

**As an end-user, create the following ticket**
- Entire mobile/online banking system is down

**As a Help Desk Agent (john), observe the ticket’s properties**
- Priority
- Department
- SLA
- Assigned To

**Set Properties to the ticket**
- Sev-A (1 hour, 24/7)
- Online Banking Department

**Attempt to observe the ticket again as “john”.** Can you view or change?

**Work the ticket to completion as jane**

---

**As an end-user, create the following ticket**
- Accounting department needs adobe upgrade, broken

**As a Help Desk Agent (john)**, observe the ticket’s properties
- Priority
- Department
- SLA
- Assigned To

**Set Properties to the ticket**
- Sev-B (4 hours, 24/7)
- Support
 
**Work the ticket to completion as john**

---

**As an end-user, create the following ticket**
- CFO’s laptop will no longer turn on

**As a Help Desk Agent (john)**, observe the ticket’s properties
- Priority
- Department
- SLA
- Assigned To

**Set Properties to the ticket**
- Sev-B (4 hours, 24/7)
- Support
 
**Work the ticket to completion as john**

---

**Set Properties to all the tickets**; do SEV-A (SysAdmins last), observe ticket becomes inaccessible
- Switch to admin panel and assign yourself View-access to Sys Admins
- Switch to agent panel and observe the escalated ticket
- Observe that you can no longer make changes to it

**Solve all of the tickets**
- Explain in most ticketing systems (probably this one too) there is an email capability so every time you update the ticket, the user gets a copy and they can respond

**Explain ticket intake IRL:**
- Sometimes tickets get created via phone, chat app, email, web form, or maybe even you run into someone in your hall or they roll up on you at your desk.
- A lot of the time people will randomize you and try to get you to fix stuff on the spot. It’s fine to fix things on the spot, but generally speaking, you want to create tickets for EVERYTHING you do. (metrics are important)

