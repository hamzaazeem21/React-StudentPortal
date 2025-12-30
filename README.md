# Smart Campus Portal (Frontend)

Responsive, role-based frontend for the **SMART CAMPUS PORTAL — Deliverable-I** described in `../report.md`.

## Tech stack

- React + TypeScript (Vite)
- Tailwind CSS (responsive UI)
- React Router (routing + guards)
- Zustand (auth/session state)
- Recharts (analytics charts)
- Lucide icons

## Run locally

```bash
npm install
npm run dev
```

Build:

```bash
npm run build
```

## Demo accounts

Use these credentials on the login screen:

| Role | Email | Password |
| --- | --- | --- |
| Super Admin | `super@campus.edu` | `super123` |
| Admin | `admin@campus.edu` | `admin123` |
| Finance Officer | `finance@campus.edu` | `finance123` |
| Faculty/Teacher | `faculty@campus.edu` | `faculty123` |
| Staff | `staff@campus.edu` | `staff123` |
| Student | `student@campus.edu` | `student123` |

## What’s implemented

- **User Management**: create users, assign roles, reset passwords (demo)
- **Academic Management**: course list, enrollment add/drop (student), faculty assignment (admin)
- **Attendance & Timetable**: weekly timetable, attendance marking (faculty/admin), student summary
- **Fee & Finance**: challans, student payments, finance challan generation, transactions
- **Library Management**: catalog search, issue/return, reservations (demo), staff add-book
- **Hostel & Transport**: room overview + assignment (staff/admin), routes, complaint tickets
- **Notifications & Alerts**: inbox, mark read/unread, admin publisher
- **Reporting & Analytics**: attendance + finance charts and CSV exports

## Demo storage

All data is stored in the browser using `localStorage` and is auto-seeded on first load.


