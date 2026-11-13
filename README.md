<div align="center">

<img src="src/logo.png" width="115" alt="Campus Safety App Logo" />

# CAMPUS SAFETY
### & GBV PREVENTION SYSTEM

**Building safer campuses through technology, accountability and coordinated emergency response.**

<p>
  <img src="https://img.shields.io/badge/Platform-Android-3DDC84?style=flat-square&logo=android&logoColor=white" />
  <img src="https://img.shields.io/badge/Project-Campus%20Safety-2563EB?style=flat-square" />
  <img src="https://img.shields.io/badge/Focus-GBV%20Prevention-9333EA?style=flat-square" />
  <img src="https://img.shields.io/badge/Status-Development-orange?style=flat-square" />
</p>

**A technology-driven approach to safer educational institutions.**

</div>

---

## About the Project

The **Campus Safety & GBV Prevention System** is an integrated campus security solution designed to strengthen student safety, improve institutional accountability and support the prevention and response to Gender-Based Violence (GBV) at universities and TVET colleges.

The system combines a student mobile application, smart campus entry terminals and a centralised institutional platform.

Through this solution, students can securely access campus facilities, monitor their attendance records and request assistance when they feel unsafe or experience an emergency.

Our vision is to create an educational environment where students can access help more easily and where institutions can coordinate their safety responses more effectively.

## The Mobile Application

The student mobile application serves as the primary interface between students and the campus safety infrastructure.

It provides students with access to their campus credentials, attendance information and emergency assistance features.

### Application Screenshots

<!-- Replace these image paths with your actual screenshots -->

<div align="center">

| Home Screen | Attendance |
|:---:|:---:|
| <img src="assets/screenshots/home-screen.png" width="220" /> | <img src="assets/screenshots/attendance-screen.png" width="220" /> |

| Safety Centre | Emergency Assistance |
|:---:|:---:|
| <img src="assets/screenshots/safety-screen.png" width="220" /> | <img src="assets/screenshots/emergency-screen.png" width="220" /> |

| Student Profile |
|:---:|
| <img src="assets/screenshots/profile-screen.png" width="220" /> |

</div>

## Key Features

### 1. Smart Campus Access

Students can access authorised campus entrances using three proposed identification methods:

- **RFID Student Card:** Uses existing RFID-enabled student cards.
- **Dynamic QR Code:** Generates a time-limited QR credential through the mobile application.
- **NFC Technology:** Supports compatible smartphones with approved NFC credentials.

### 2. Student Attendance Tracking

The system automatically records validated campus entry and exit events.

Students can:

- View their attendance history.
- Check entry and exit timestamps.
- Monitor their recorded campus activity.
- Request corrections where attendance records are inaccurate.

### 3. Feeling Unsafe Alert

A dedicated safety feature allows students to request assistance when they feel unsafe, even when the situation is not an immediate emergency.

When activated:

- An alert is sent to on-duty campus security.
- The student's location can be shared with confirmation and appropriate permissions.
- Approved, trained and opted-in nearby responders may be notified.
- The incident receives a reference number and can be tracked by authorised personnel.

### 4. Emergency Response

A separate high-priority emergency feature is designed for situations requiring immediate assistance.

The proposed workflow includes:

- Immediate notification to designated campus security personnel.
- Live location sharing with authorised responders during an active alert.
- Emergency acknowledgement and responder assignment.
- An institutional escalation procedure for contacting the appropriate emergency services.
- Incident tracking and follow-up.

### 5. Centralised Security Management

The proposed institutional dashboard will enable authorised personnel to:

- Monitor incoming safety alerts.
- Manage on-duty security personnel.
- Assign responders to incidents.
- View authorised incident locations.
- Monitor response progress.
- Maintain incident records and audit trails.

---

## How the System Works

The solution consists of three interconnected components.

| Component | Responsibility |
|---|---|
| Mobile Application | Student access, attendance visibility and safety alerts. |
| Gate Hardware | RFID, QR and NFC credential validation. |
| Backend & Security Dashboard | Data management, attendance processing, alert routing and institutional monitoring. |

### System Architecture

```text
          STUDENT
             |
             v
     MOBILE APPLICATION
             |
       +-----+------+
       |            |
       v            v
  ATTENDANCE    SAFETY ALERTS
       |            |
       v            v
   GATE SYSTEM   SECURITY TEAM
       |            |
       +-----+------+
             |
             v
     CENTRAL BACKEND
             |
       +-----+------+
       |            |
       v            v
   DATABASE    ADMIN DASHBOARD