<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket - Ticket Lifecycle & Resolution

This lab walks through the lifecycle of support tickets within osTicket. From ticket creation to agent login, assignment, resolution, and closure, each step mimics how an actual IT support desk would handle incoming service requests.

---

## 🧰 Tools & Technologies Used

- Microsoft Azure (Virtual Machine Hosting)
- Remote Desktop Connection
- osTicket (Ticketing System)
- Windows 10 Pro (21H2)

---

## 🎯 Objective

To demonstrate how tickets are submitted by users, processed by support agents, and resolved using osTicket’s built-in tools such as SLAs, help topics, roles, and teams.

---

## 📸 Ticket Lifecycle in Action

### 📝 Step 1: A user submits a support ticket

<p align="center">
  <img src="https://github.com/Herkamal/Ticket-Lifecycle/blob/main/ticket1.png?raw=true" width="80%"/>
</p>
A user submits the first ticket by selecting a relevant help topic and describing their issue. This enters the ticket into the system's queue for agents to pick up and triage.

---

### 🔐 Step 2: John logs into the Agent Panel

<p align="center">
  <img src="https://github.com/Herkamal/Ticket-Lifecycle/blob/main/john-login.png?raw=true" width="70%"/>
</p>
John, one of the assigned agents, logs into the osTicket Agent Panel to begin working on open tickets in the queue.

---

### 🎯 Step 3: John opens and reviews Ticket #1

<p align="center">
  <img src="https://github.com/Herkamal/Ticket-Lifecycle/blob/main/john-ticket1.png?raw=true" width="80%"/>
</p>
John views the details of Ticket #1. He can now respond to the user, take ownership, and begin working toward a resolution.

---

### 🔐 Step 4: Jane logs into the Agent Panel

<p align="center">
  <img src="https://github.com/Herkamal/Ticket-Lifecycle/blob/main/Jane-login.png?raw=true" width="70%"/>
</p>
Jane, another support agent, logs in to handle a separate ticket assigned to her.

---

### 🧾 Step 5: Jane reviews and resolves a banking issue

<p align="center">
  <img src="https://github.com/Herkamal/Ticket-Lifecycle/blob/main/jane-bank-fix.png?raw=true" width="80%"/>
</p>
<p align="center">
  <img src="https://github.com/Herkamal/Ticket-Lifecycle/blob/main/jane-bank.png?raw=true" width="80%"/>
</p>
Jane works on a ticket related to a business-critical banking issue. The screenshots show the resolution in progress and the final state of the ticket.

---

### 📝 Step 6: A second user ticket is submitted

<p align="center">
  <img src="https://github.com/Herkamal/Ticket-Lifecycle/blob/main/ticket2.png?raw=true" width="80%"/>
</p>
A new ticket enters the system — this one is categorized under a different help topic and will be routed based on department or team setup.

---

### 🎯 Step 7: John resolves Ticket #2

<p align="center">
  <img src="https://github.com/Herkamal/Ticket-Lifecycle/blob/main/john-ticket2-fix.png?raw=true" width="80%"/>
</p>
John handles the second ticket and adds internal notes or public replies as needed. Once the issue is resolved, he marks the ticket as closed.

---

### 📝 Step 8: A third user ticket is submitted

<p align="center">
  <img src="https://github.com/Herkamal/Ticket-Lifecycle/blob/main/ticket3.png?raw=true" width="80%"/>
</p>
Yet another ticket is submitted by a user. Each submission demonstrates a new use case and helps reinforce agent handling practices.

---

### 🎯 Step 9: John resolves Ticket #3

<p align="center">
  <img src="https://github.com/Herkamal/Ticket-Lifecycle/blob/main/john-ticket3-fix.png?raw=true" width="80%"/>
</p>
John resolves the final ticket in the queue, demonstrating the complete cycle from login to resolution. This reinforces best practices for documenting fixes and closing tickets appropriately.

---

## ✅ Conclusion

Through this lab, I gained a full understanding of how tickets flow through a support system using osTicket. From multiple agent logins to help topic routing, SLAs, and resolution workflows — I was able to simulate real-world IT support desk procedures.

---


