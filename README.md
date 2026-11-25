# Taif High School: School Management System

> **Client project** · Built by [Rahimi Tech Solution](https://github.com/AbdulRahmanRahimi) · The source code is private to the client.

A complete school management system for **Taif High School** in Jalalabad, Afghanistan. It runs in the browser and as a Windows desktop app, and covers students, attendance, exams, fees and the school's finances.

## Features

- **Students and classes**: student records, classes by grade and section, parent contact details, and yearly promotion with a full history and undo
- **Attendance at the gate**: students scan in with QR codes, limited to one scan per day
- **Exams and marks**: teacher portal for entering marks, an approval workflow, and grade reports
- **Fees**: fees by grade, monthly dues, numbered receipts and daily reconciliation
- **Finance**: income, expenses, staff payroll and tax
- **Reports** generated as PDF documents
- **WhatsApp messages to parents**, with up to two numbers per student
- **Afghan Solar Hijri (Shamsi) calendar**, academic years and holidays
- **Roles**: administrator, finance and teacher logins
- **Backups** of the school's data

## Tech stack

| Layer | Tools |
|---|---|
| Backend | Node.js, Express, PostgreSQL, JWT authentication, bcrypt |
| Frontend | HTML, CSS, JavaScript |
| Desktop | Electron (Windows installer) |
| Other | Puppeteer (PDF), QR codes, WhatsApp Web automation, WebSockets |
| Hosting | Render · Neon PostgreSQL |

---

Designed, built and deployed by **Abdul Rahman Rahimi**.
