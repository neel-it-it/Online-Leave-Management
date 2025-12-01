
<h1 align="center">🌓 Online Leave Management System</h1>

<p align="center">
  <img src="leavebanner.png" alt="Dark Banner" width="100%" />
</p>

<p align="center">
  A modern, secure & efficient leave tracking system built using <strong>ASP.NET Core MVC</strong>.
</p>

<p align="center">

  <!-- Badges -->
  <img src="https://img.shields.io/badge/.NET-8.0-blueviolet?style=flat-square" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" />
  <img src="https://img.shields.io/badge/Status-Active-success?style=flat-square" />
  <img src="https://img.shields.io/badge/Build-Passing-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/Platform-Web-lightgrey?style=flat-square" />

</p>

---

## 📌 **Overview**

The **Online Leave Management System** provides an intuitive and automated workflow for:
- Employees to apply and track leaves  
- Managers to review, approve, or reject leave applications  
- Organizations to maintain a transparent leave policy  

---

## 📂 **Project Features**

### 👨‍💼 Employee Features

| Feature | Description |
|--------|-------------|
| 📝 Submit Leave | Apply for any leave type with validation |
| 📌 Leave Status | Check approval, pending, rejected |
| 📜 Leave History | Complete record of older requests |
| 📱 Responsive Dashboard | Mobile-friendly clean UI |

---

### 👨‍💼 Manager Features

| Feature | Description |
|--------|-------------|
| 🔍 View All Requests | All employee leaves in one place |
| ✅ Approve / Reject / Pending | Employees can delete pending request |
| 🎯 Advanced Filters | Filter by status (Pending/Approved/Rejected) |
| 📄 Pagination | Smooth experience for large data |

---

## 🛠️ **Tech Stack**

| Layer | Technology |
|-------|------------|
| **Frontend** | HTML, CSS, Bootstrap 5, jQuery |
| **Backend** | ASP.NET Core MVC 8 |
| **Database** | SQL Server, EF


---


## **Steps to Connect**
## 2️⃣ **Configure Database**
In appsettings.json:

"ConnectionStrings": {
  "DefaultConnection": "Server=.;Database=LeaveDB;Trusted_Connection=True;"
}

## 3️⃣ **Run Migrations**
dotnet ef database update

## 4️⃣ **Start the Application**
dotnet run

## 5️⃣ **Open in Browser**
http://localhost:5000
