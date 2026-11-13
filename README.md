<p align="center">
  <img src="src/hero-banner.svg" alt="Campus Safety & GBV Prevention System" width="100%"/>
</p>

---

## About the Project

The **Campus Safety & GBV Prevention System** is an integrated campus security solution designed to strengthen student safety, improve institutional accountability and support the prevention and response to Gender-Based Violence (GBV) at universities and TVET colleges.

The system combines a student mobile application, smart campus entry terminals and a centralised institutional platform.

Through this solution, students can securely access campus facilities, monitor their attendance records and request assistance when they feel unsafe or experience an emergency.

Our vision is to create educational environments where students can access help more easily and institutions can coordinate their safety responses more effectively.

---

## Mobile Application

The mobile application is designed for both **Android and Apple devices**, providing students with a centralised platform for campus access, attendance monitoring and safety assistance.

### Application Screenshots

<div align="center">

#### Student Pass

<img src="src/passcreen.png" width="250" alt="Student Pass Screen"/>

#### Student Profile

<img src="src/profilescreen.png" width="250" alt="Student Profile Screen"/>

#### Application Settings

<img src="src/settingscreen.png" width="250" alt="Application Settings Screen"/>

</div>

---

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
- Monitor recorded campus activity.
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

The solution consists of three interconnected components:

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
        +-------+-------+
        |               |
        v               v
   ATTENDANCE       SAFETY ALERTS
        |               |
        v               v
    GATE SYSTEM     SECURITY TEAM
        |               |
        +-------+-------+
                |
                v
         CENTRAL BACKEND
                |
          +-----+-----+
          |           |
          v           v
        DATABASE   ADMIN DASHBOARD