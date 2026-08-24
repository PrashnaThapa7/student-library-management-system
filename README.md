# Student Library Management System

A React + Vite Student Library Management System built for the CSE 220 course project.

## Main features
- Admin, Librarian, and Student accounts
- Dashboard
- Manage Books
- Manage Users
- Issue and Return Books
- Requested Books
- Status
- Student Information
- Profile
- Notifications/account controls
- In-memory demo data (resets on page refresh) — see Section 5.3 of the project report
- React Router pages, so menu buttons open inside the app without manually typing localhost URLs

## Run
\```bash
npm install
npm run dev
\```

## Demo passwords
- Admin: admin@library.com / admin123
- Librarian: librarian@library.com / library123
- Any student: student123

## Known Limitations
As documented in the project report (Chapter 6 & 9):
- Return status does not sync across all pages (BR-04)
- My Borrowing is not filtered per student (BR-05)
- Borrowing history page not implemented (ST-01)
- Book editing not implemented (ST-03)
- Report generation not implemented (ST-04)

## Team
Bebo Rajbahak, Aasha, Prashna Thapa, Reshma — CSE 220, Summer 2026, IAU

## Project Structure

The project is organized into different folders for the system design, requirements, project management, testing, and source code.

- design/ – Contains UML diagrams and system design documents.
- requirements/ – Contains project requirements and stakeholder analysis.
- project-management/ – Contains sprint, backlog, Gantt chart, and team role files.
- testing/ – Contains test cases and testing documents.
- src/ – Contains the main application source code.
- docs/ – Contains project documentation and reports.

## Report
Full project report: `docs/Final-Project-Report.docx`
## Testing
Test cases are included in the testing folder.