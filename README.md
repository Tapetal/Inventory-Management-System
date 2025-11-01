# Complete Inventory Management System

A full-featured inventory management web app built with TypeScript, React, Express, and MongoDB.

The system allows businesses to manage items, transactions, and users securely with role-based access control. It includes a modern dashboard, detailed reports, and intelligent workflows for deletions and user management. Everything is built from scratch with a focus on security, reliability, and user experience.

---

## Overview

Using a structured role system, admins can invite staff, approve deletion requests, and configure global settings. Staff can handle daily inventory transactions like adding stock in/out, generating reports, and viewing item summaries.  

The system tracks all actions, provides analytics, and ensures data integrity — even supporting soft deletes, password resets, and email-based activation.

---

🚀 Features

- **Authentication:** JWT-based login, password reset, and secure setup flow.  
- **Role Management:** Admin and Staff roles with different permissions.  
- **Inventory Control:** Add, edit, and track stock with balance calculations.  
- **Deletion Workflow:** Request, review, and approve deletions with full audit logs.  
- **Reporting:** Generate and export reports (PDF/Excel) with filters and summaries.  
- **User Preferences:** Theme, timezone, and data display customization.  
- **Dashboard:** Real-time analytics and quick access to key actions.  
- **Security:** Rate limiting, input validation, hashed passwords, and CORS protection.  
- **Responsive Design:** Built with Tailwind CSS for seamless use on all devices.

---

🧠 Tech Stack

**Frontend:** React + TypeScript + Vite + TailwindCSS  
**Backend:** Node.js + Express + TypeScript + MongoDB  
**Extras:** JWT, bcrypt, Nodemailer, PDFKit, ExcelJS  
**Deployment:** Frontend (Vercel), Backend (Render), Database (MongoDB Atlas)

---

## Quick Start

### Backend Setup
```bash
cd backend
npm install
npm run dev
