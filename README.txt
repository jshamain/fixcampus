FIXCAMPUS WEB APPLICATION — DEMO PROTOTYPE

HOW TO RUN
1. Extract FixCampus_WebApp.zip.
2. Open index.html in Chrome, Edge, or Firefox.
3. Use the navigation to open Home, Report Concern, Maintenance Chat, or Admin Login.

DEMO ADMIN LOGIN
Email: admin@fixcampus.demo
Password: FixCampus123!

FEATURES IN THIS PROTOTYPE
- Working navigation buttons and "Enter"/report/chat paths.
- Admin demo login with visible error message for invalid credentials.
- Admin dashboard for viewing submitted concerns.
- Request status updates: Open, In Progress, Resolved.
- Export requests to CSV.
- Student/teacher-facing Report Concern and Maintenance Chat.
- Role-aware navigation and a guard against opening the admin dashboard as a non-admin.
- Requests and messages are stored in the current browser's localStorage.

IMPORTANT LIMITATIONS
This is a front-end demonstration, not a production-ready secure web application.
The demo credentials and role checks are inside browser JavaScript and can be inspected or bypassed.
There is no real server, database, live chat connection, or multi-user synchronization.
Data remains in the browser/device where it was entered and can be lost if browser storage is cleared.
Do not use real personal or sensitive information.

FOR A REAL DEPLOYMENT
Use a backend and database (for example, Supabase or Firebase), server-side authentication,
role-based access control enforced on the server/database, secure admin account provisioning,
and a real-time messaging service if required. Never rely on front-end checks alone to protect admin data.
