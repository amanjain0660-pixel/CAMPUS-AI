# CampusConnect – Student Portal Demo

CampusConnect is a frontend-only student portal prototype using sample data for ABES Engineering College, Ghaziabad.

> **Important:** This is an independent demo project. It is not an official ABES Engineering College website, and the schedules, faculty, notices, attendance and other records are fictional sample data.

## Features
- Demo student login
- Student dashboard with academic overview
- Weekly timetable
- Subject-wise attendance
- Subjects and faculty directory
- Assignment tracking and demo submission
- Examination schedule
- Campus announcements with search and filters
- Events with demo interest registration
- Student profile editing
- Light/dark theme preference
- Responsive desktop and mobile layout
- LocalStorage-based demo session and preferences

## Technology
- HTML5
- CSS3
- Vanilla JavaScript (ES6+)
- Browser LocalStorage

No frontend framework or backend is required.

## Run locally
1. Extract the ZIP.
2. Open the `CampusConnect` folder.
3. Start a local static server (recommended), for example with the VS Code Live Server extension.
4. Open `index.html` through the local server.

You can also open `index.html` directly in a browser, but a local server is recommended for consistent navigation.

## Demo credentials
- Email: `student@abes.ac.in`
- Password: `student123`

## Project structure
```text
CampusConnect/
├── index.html
├── dashboard.html
├── timetable.html
├── attendance.html
├── subjects.html
├── assignments.html
├── examinations.html
├── announcements.html
├── faculty.html
├── events.html
├── profile.html
├── settings.html
├── css/
│   └── style.css
├── js/
│   ├── auth.js
│   └── app.js
├── assets/
│   ├── images/
│   └── icons/
├── README.md
└── .gitignore
```

## GitHub
Create a repository named `CampusConnect` and upload the contents of this folder. Keep `index.html` and the other page files at the repository root.

## Future improvements
- Connect an authenticated backend
- Integrate verified college timetable and notices
- Add faculty/admin dashboards
- Add secure student identity and role-based access
- Add real attendance and assignment submission services
