# IT Service Operations Automation Suite

This is a custom ServiceNow scoped application that automates IT incidents, tasks, and change management with dashboards, SLAs, notifications, and catalog workflows.

---

## 🔧 Features

- Custom Incident, Task, and Change flows
- UI Policies and Client Scripts
- Server-side scripting: Business Rules, Script Includes
- SLA Definitions and Progress Tracking
- Notifications for Assignment, Breaches, and Completion
- Dashboards for Managers and Teams
- Service Catalog Integration (e.g., Request Software)
- REST API (Optional): External incident reporting

---

## 📸 Screenshots

| Feature | Screenshot |
|--------|------------|
| Incident Form | ![incident-form](Screenshots/incident-form.png) |
| Manager Dashboard | _Coming Soon_ |

---

## 📁 Project Structure

| File/Folder | Purpose |
|-------------|---------|
| `ScopedAppManifest/` | XML exports of the app |
| `Scripts/` | All server/client scripts |
| `Dashboards/` | Dashboard components/configs |
| `SampleData/` | JSON/CSV data for testing |
| `ProjectPlan.md` | Planning doc with requirements |

---

## 🚀 Getting Started

1. Import the Scoped App into ServiceNow Studio
2. Create tables or reuse core tables (`incident`, `task`, `change_request`)
3. Build flows, scripts, and policies
4. Populate sample data for testing
5. Build reports and dashboards

---

## 📅 Roadmap

- [x] Set up GitHub repository ✅
- [ ] Define tables and fields
- [ ] Configure UI Policies and Client Scripts
- [ ] Write Business Rules
- [ ] Design Flow Designer automations
- [ ] Build dashboards and sample data

---

## 📜 License

This project is licensed under the MIT License.
