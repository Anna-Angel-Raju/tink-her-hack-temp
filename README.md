Campus Pulse 🎯
Real-Time Campus Infrastructure Monitoring & Feedback System

Basic Details
Developer
Anna Angel Raju - College of Engineering Trivandrum (CET)

Hosted Project Link:


Project Description
Campus Pulse is a real-time, role-based feedback management system. It bridges the gap between students and administrative staff, ensuring that facility issues—like maintenance, connectivity, or cleanliness—are reported, tracked, and resolved efficiently.

The Problem statement:
Universities often lack a centralized, transparent channel for students to report infrastructure issues. Reports are often made informally, get lost, or are duplicated, leading to slow response times and frustration.

The Solution
A web-based, real-time dashboard where students can submit categorized feedback. Admins manage these reports through an authenticated dashboard, featuring workflow automation, data analytics, and duplicate detection to streamline maintenance.

Technical Details
Technologies Used
Frontend: HTML5, CSS3, Tailwind CSS

Backend/Database: Firebase Firestore

Real-time Sync: Firebase onSnapshot listener

Authentication: Role-Based Access Control (Custom Admin Secret)

Features
Real-Time Feed: Updates automatically when new issues are submitted or statuses change.

Smart Duplicate Detection: Prevents multiple students from reporting the same active issue in the same location.

Admin Analytics: Live metric cards tracking Total, Pending, and Resolved issues.

Live Search & Filter: Dynamic filtering to help admins prioritize categories like 'Internet', 'Maintenance', or 'Safety'.

Workflow Management: Update ticket status (Pending ➔ In Progress ➔ Resolved) with immediate visual feedback.

Interactive UI: Modern, responsive design with "Glassmorphism" headers, pulse animations, and custom typography.

Admin Access
Password: campus123

Note: This password is for demonstration purposes during the hackathon submission.

Implementation
How to Run
Clone the repository:

Open:
Since this is a client-side web application with a Firebase backend, simply open index.html in any modern web browser. (Recommended: Use the "Live Server" extension in VS Code).

Project Documentation
Screenshots
The student interface showing the issue submission form and the live incident feed.

The Admin interface showing the incident cards, analytics cards, and status workflow controls.

Professional toast notifications providing instant feedback for actions.

System Architecture
The application uses a reactive frontend architecture. The frontend handles UI state and user input, while Firebase Firestore acts as the single source of truth, handling all data persistence. The app uses the Firebase onSnapshot listener to ensure the Admin dashboard and Student feed are always perfectly synced in real-time.

AI Tools Used (For Transparency)
Tool Used: Google Gemini (Gemini 3 Flash)

Purpose:

Architecting the Firestore data structure.

Implementation of the real-time onSnapshot listener and sorting logic.

UI/UX refinement using Tailwind CSS (Modals, Toasts, responsive Grids).

Debugging of search filter logic and the duplicate prevention algorithm.

Percentage of AI-assisted development: ~60%

Human Contributions:

Logic refinement and requirements planning.

Integration of Firebase SDK configurations.

Final CSS/Tailwind styling tweaks and design adjustments.

Deployment and testing.

License
This project is licensed under the MIT License - see the  file for details.

Made with ❤️ at TinkerHub
