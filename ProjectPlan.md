# 📘 Project Plan: IT Service Operations Automation Suite

---

## 🎯 Objective

Design and build a scoped ServiceNow application that automates the lifecycle of IT incidents, tasks, and changes. The app will include dashboards, SLA tracking, client/server scripts, and a service catalog interface to enhance IT operations efficiency and transparency.

---

## 👤 Target Users

- **IT Support Agent** – Resolves Incidents & Tasks
- **Change Manager** – Approves & Oversees Change Requests
- **Employees** – Submit issues and requests via Catalog
- **IT Operations Manager** – Monitors performance via dashboards

---

## 🧩 Functional Modules

| Module | Description |
|--------|-------------|
| **Incident Management** | Capture, track, and resolve incidents |
| **Task Management** | Break down incidents or changes into tasks |
| **Change Requests** | Raise and approve changes (auto-triggered from P1s) |
| **Service Catalog** | Submit requests like "New Software" or "Request Access" |
| **SLA Management** | Monitor response & resolution times |
| **Dashboards** | Visualize metrics like open incidents, SLA breaches |
| **Notifications** | Keep users and managers informed via email |
| **Access Controls** | Role-based access for agents, managers, and requesters |
| **APIs (Optional)** | Scripted REST endpoint to expose incidents for external systems |

---

## 🏗️ Technical Features

### ✅ Tables Used

- `incident` (OOB)
- `task` (OOB)
- `change_request` (OOB)
- `sc_req_item`, `sc_task`, `sc_cat_item` (Service Catalog)
- `sla_definition`, `task_sla` (SLAs)

### ✅ Customization Features

| Feature Type | Example |
|--------------|---------|
| **UI Policies** | Show/hide priority based on impact/urgency |
| **Client Scripts** | Alert on large attachment size |
| **Business Rules** | Auto-create Task on Incident creation |
| **Flow Designer (Catalog)** | Request New Software → Approval → Task → Notification |
| **Flow Designer**
