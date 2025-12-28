# 📚 Librario – Library Management System

A full-stack **Library Management System** built using **Spring Boot + React**, featuring user/member management, book management, borrowing/return system, overdue handling, notifications and **Razorpay online payment integration**.

---

## 🚀 Features

### 👤 User & Authentication
- User/Librarian/Admin roles
- Login / Registration
- JWT Based Authentication (optional toggle)
- Session token support

### 📚 Library Management
- Books Add/Update/Delete
- Borrow & Return books
- Track due dates
- Overdue charge calculation
- Membership Plans

### 🔔 Notifications
- Real-time notifications using WebSockets (configurable)
- Member overdue notifications
- Book borrow/return updates

### 💳 Payments (Integrated)
- Razorpay Payment Gateway
- Create Order → Open Popup → Verify Signature
- Store transaction into DB
- View Payment History per member

### 📊 Admin / Librarian dashboards
- Manage Members
- Manage Books
- Track Borrowing Records
- View return/renewal requests

---

## 🛠 Tech Stack

| Type | Technology |
|------|------------|
| Backend | Spring Boot, Hibernate, JPA |
| Frontend | React, Tailwind CSS |
| Database | MySQL |
| Auth | JWT + Session Token |
| Payment | Razorpay Orders + Signature Verification |
| Websocket | STOMP, SockJS (optional) |

---

## 🗂 Project Structure

