# HRMS (Human Resource Management System) 🚀

A comprehensive, modern, and robust Human Resource Management System built to streamline employee data, attendance tracking, leave requests, and payroll processes. This system provides an intuitive interface with Role-Based Access Control for both Admins and Employees.

## ✨ Key Features

- **Authentication & Security**: Secure JWT-based login system with role-based routing (Admin vs. Employee dashboards).
- **Employee Directory & Profiles**: Detailed employee profiles storing personal information, banking details, skills, certifications, and emergency contacts.
- **Attendance Tracking**: Daily check-in and check-out system to track work hours, breaks, and extra hours.
- **Leave Management**: Apply for leaves, manage leave balances, and allow Admins to approve/reject requests.
- **Payroll System**: Automated tracking and management of employee payroll, basic salary, allowances, and deductions.

## 🛠️ Tech Stack

**Frontend**: React 19, Vite, Tailwind CSS, React Router v6, React Hook Form, Zod, TanStack React Query, Lucide React.
**Backend**: Node.js, Express.js, Prisma ORM, PostgreSQL (with SQLite support), JSON Web Tokens (JWT), Bcrypt.js.

---

## 📸 Screenshots & Previews

### Authentication
**Sign In & Registration**
Access the platform securely.
![Sign In](client/public/signin.png)
![Register](client/public/register.png)

### 👑 Admin Dashboards
**Admin Overview & Dashboard**
Get a birds-eye view of your organization's key metrics.
![Admin Dashboard](client/public/admin%20dashboard.png)

**Employee Management**
Manage the employee directory and organizational structure.
![Admin Employees](client/public/admin%20employees.png)

**Attendance Tracking (Admin)**
Monitor organization-wide daily attendance.
![Admin Attendance](client/public/admin%20attendance.png)

**Leave Requests Management**
Review, approve, or reject employee leave requests.
![Admin Leave Requests](client/public/admin%20leave%20req.png)

**Payroll Management**
Calculate and manage employee payroll effortlessly.
![Admin Payroll](client/public/admin%20payroll.png)

**Admin Profile**
Manage administrative settings and personal details.
![Admin Profile](client/public/admin%20profile.png)


### 👤 Employee Dashboards
**Employee Dashboard**
Personalized dashboard for every employee to view their quick stats.
![Employee Dashboard](client/public/employee%20dashboard.png)

**Attendance (Employee)**
Easy check-in, check-out, and break tracking for employees.
![Employee Attendance](client/public/Employee%20attendance.png)

**Leave Application**
Employees can easily apply for leaves and check their leave balance.
![Employee Leave](client/public/employee%20leave.png)

**Employee Profile**
Employees can view and update their personal profiles, skills, and certifications.
![Employee Profile](client/public/employee%20profile.png)

---

## 🏃‍♂️ Quick Start & Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/SnehashisDas024/OdooHackathon.git
cd OdooHackathon
```

### 2. Setup the Database & Backend
```bash
cd server
npm install

# Setup your .env with DATABASE_URL
# Push schema and seed demo accounts
npx prisma db push
npm run db:seed

# Start the server
npm run dev
```
*(Backend runs on http://localhost:5000)*

### 3. Start the Frontend
```bash
cd client
npm install
npm run dev
```
*(Frontend runs on http://localhost:3000)*

## 🔑 Demo Accounts (Seeded)

- **Admin Account**: `admin@hrms.com` / `Admin@1234`
- **Employee Account**: `arjun.sharma@hrms.com` / `Employee@1234`
