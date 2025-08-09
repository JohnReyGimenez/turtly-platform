<h1>
  <img src="https://raw.githubusercontent.com/JohnReyGimenez/turtly-platform/blob/main/assets/images/icon.png" width="72" style="display: inline-block; vertical-align: middle;" />
  <span style="vertical-align: middle;">BLE-Based Attendance Monitoring System</span>
</h1>

BLE-Based Attendance Monitoring System is a hybrid hardware-software solution for automating classroom attendance using **Bluetooth Low Energy (BLE)**. It leverages **wearable tags**, **BLE scanners**, and a **mobile companion app** to accurately detect and log student presence in real time.

---

## Project Goals

- Build a **low-cost, tamper-resistant attendance system** using BLE technology.
- Eliminate manual roll calls through automated classroom scanners.
- Provide students and administrators with a **real-time, mobile-accessible dashboard**.
- Support historical attendance viewing, notifications, and tag diagnostics.
- Design a scalable system that works for multiple classrooms and institutions.

---

## Features (Planned)

### Student App (React Native)
- View attendance logs (daily/weekly/monthly).
- Receive late/absent alerts and notifications.
- Monitor BLE tag status.
- Report missing attendance or tag issues.

### Admin Dashboard
- Real-time attendance monitoring per classroom.
- Manual override for missed logs.
- Exportable attendance reports.
- Student-tag pairing and management.

### BLE-Based Attendance System
- Custom BLE tags worn by students.
- ESP32 BLE scanners at classroom entrances.
- Timestamps logged when students enter/leave.

---

## Tech Stack (Planned)

| Layer        | Technology                        |
|--------------|------------------------------------|
| **Frontend** | React Native (with Expo), Tailwind CSS (via NativeWind) |
| **Backend**  | Ruby on Rails API                 |
| **Hardware** | Arduino-compatible board + BLE module (e.g. ESP32), custom 3D-printed casing |
| **Database** | PostgreSQL (primary), Firebase (for real-time sync or notifications) |
| **Deployment** | Self-hosted on a VPS (e.g., DigitalOcean or Hetzner) |

---

## Project Status

| Phase              | Status |
|--------------------|--------|
| Planning & Design  | In Progress |
| Hardware Research  | BLE tag concept finalized |
| Frontend Design    | Sign-up form and dashboard in development |
| Backend Setup      | Not started |
| BLE Scanner Logic  | Not started |
| Mobile App BLE Pairing | Not started |

---

## Structure (Coming Soon)

```bash
/turtlytag-app      # React Native app
/turtlytag-api      # Rails backend
/turtlytag-hardware # Arduino + BLE tag code
