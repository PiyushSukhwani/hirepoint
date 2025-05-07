# HirePoint – Full-Stack Job Portal

**Live Site:** [https://hirepoint.vercel.app](https://hirepoint.vercel.app)

## 📌 Overview

**HirePoint** is a modern full-stack job portal web application built with **React JS**, **Tailwind CSS**, **Supabase**, **Clerk Authentication**, and **ShadCN UI**. It supports secure authentication and role-based access, allowing users to interact as either recruiters or employees.

---

## 🔑 Features

### 🔐 Authentication

- Role-based login via **Clerk** (Email / Google OAuth)
- Profile management for both recruiters and employees

### 🧑‍💼 Recruiter Panel

- Post new job listings
- View applicants for each job
- Track applicant status
- Add a new company profile
- View “My Created Jobs”
- Delete job postings

### 👨‍🎓 Employee Panel

- Browse job listings
- Advanced job search and filtering
- Save and unsave jobs
- View “My Applications” page

---

## 🛠️ Tech Stack

- **Frontend**: React.js, Tailwind CSS, ShadCN UI
- **Backend**: Supabase
- **Authentication**: Clerk (Email / Google)
- **Form Handling**: React Hook Form + Zod
- **State Management**: Redux
- **Data Fetching**: Custom React Hook

---

## 📁 Project Structure Highlights

- `/components`: Reusable UI components
- `/pages`: Route-based structure for Recruiter and Employee views
- `/hooks`: Custom hooks for API requests
- `/api`: Utility functions (e.g., API calls, constants)

---