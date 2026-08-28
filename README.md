# 🏠 Smart Hostel Management System

A modern and responsive web application designed to simplify and digitize hostel management operations. The system provides separate portals for administrators and students, making hostel management easier, faster, and more organized.

## 🚀 Features

### 🏠 Landing Page
- Modern and responsive design
- Project introduction
- Feature overview
- Easy navigation to login

### 🔐 Authentication UI
- Admin login
- Student login
- Role-based redirection
- Password visibility toggle
- Remember me option
- Forgot password UI

### 🛡️ Admin Dashboard
- Hostel overview dashboard
- Student statistics
- Room statistics
- Occupancy overview
- Open complaints overview
- Recent students table
- Quick actions
- Navigation sidebar

### 👨‍🎓 Student Management
- View all students
- Search students by name, ID, or email
- Add new students
- Student statistics
- Active and pending student status
- Student information management

### 🎓 Student Portal
- Separate student dashboard
- Role-based access structure
- Ready for future student features

## 🛠️ Tech Stack

- Next.js
- TypeScript
- Tailwind CSS
- React
- Lucide React Icons

## 📁 Project Structure

```text
my-app/
│
├── app/
│   ├── admin/
│   │   ├── students/
│   │   │   └── page.tsx
│   │   ├── layout.tsx
│   │   └── page.tsx
│   │
│   ├── auth/
│   │   └── login/
│   │       └── page.tsx
│   │
│   ├── student/
│   │   └── page.tsx
│   │
│   ├── globals.css
│   ├── layout.tsx
│   └── page.tsx
│
├── components/
│   ├── layout/
│   │   └── AdminSidebar.tsx
│   │
│   ├── shared/
│   └── ui/
│
├── lib/
├── types/
├── public/
└── package.json
