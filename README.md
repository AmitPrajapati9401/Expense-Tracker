# 💰 Expense Management System

A full-stack Expense Management System built with the **MERN Stack** that helps users efficiently track, categorize, and analyze their expenses. The application provides insightful dashboards, secure authentication, and comprehensive reporting to improve financial management.

---

## 📑 Table of Contents

- [Demo](#-demo)
- [Project Description](#-project-description)
- [Objectives](#-objectives)
- [Features](#-features)
- [Technical Architecture](#-technical-architecture)
- [Getting Started](#-getting-started)
- [Environment Variables](#-environment-variables)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Screenshots](#-screenshots)
- [Roadmap](#-roadmap)
- [Contribution](#-contribution)
- [License](#-license)

---

# 🚀 Demo

Coming Soon

You can also run the application locally by following the installation instructions below.

---

# 📖 Project Description

The Expense Management System is a web-based application designed to help individuals and organizations manage their daily expenses effectively.

Built using the **MERN Stack (MongoDB, Express.js, React.js, and Node.js)**, the application provides an intuitive interface for tracking expenses, managing categories, and generating insightful financial reports.

---

# 🎯 Objectives

- Simplify expense tracking.
- Improve financial decision-making.
- Analyze spending habits.
- Organize expenses by categories.
- Generate meaningful reports and visualizations.
- Provide a seamless experience across all devices.

---

# ✨ Features

## 🔐 Authentication & Authorization

- User Registration and Login
- Secure JWT Authentication
- Protected Routes
- Session Management

---

## 💳 Expense Management

Users can:

- Create expenses
- Edit expenses
- Delete expenses
- Categorize transactions
- Add descriptions
- Track expenses by date

---

## 📊 Dashboard & Analytics

The dashboard provides:

- Total Expenses
- Expenses by Category
- Recent Transactions
- Monthly Expense Summary
- Interactive Charts
- Spending Pattern Analysis

Supported visualizations include:

- Pie Charts
- Bar Graphs

---

## 📱 Responsive Design

The application is fully responsive and optimized for:

- Desktop
- Tablets
- Mobile Devices

Reusable React components ensure maintainability and scalability.

---

# 🏗 Technical Architecture

## Frontend

Built using:

- React.js
- Redux
- React Bootstrap
- Material Icons
- tsparticles
- react-datepicker
- moment
- unique-names-generator

Features include:

- Component-based architecture
- State management with Redux
- Responsive UI
- Reusable components

---

## Backend

Built with:

- Node.js
- Express.js

Features:

- RESTful APIs
- JWT Authentication
- Middleware-based authorization
- API validation
- Error handling

---

## Database

MongoDB is used for storing:

- Users
- Expenses
- Categories
- Authentication data

Implemented using:

- Mongoose ODM
- Schema Validation

---

## Deployment

Deployment strategy:

| Service | Platform |
|---------|----------|
| Frontend | AWS |
| Backend | Render |
| Database | MongoDB Atlas |

CI/CD pipelines can be integrated for automated deployments.

---

# 🚀 Getting Started

## Clone Repository

```bash
git clone https://github.com/Priyanshu9898/Expense-Tracker-App.git

cd Expense-Tracker-App
```

---

## Install Frontend Dependencies

```bash
cd frontend

npm install
```

---

## Install Backend Dependencies

```bash
cd backend

npm install
```

---

## Run Frontend

```bash
npm start
```

Frontend runs at:

```bash
http://localhost:3000
```

---

## Run Backend

```bash
npm run dev
```

Backend typically runs at:

```bash
http://localhost:5000
```

---

# 🔑 Environment Variables

Create a **config** folder inside the backend directory.

Inside it, create a file named:

```bash
config.env
```

Add the following variables:

```env
MONGO_URL=your_mongodb_connection_string

PORT=5000

JWT_SECRET=your_secret_key
```

---

# 💻 Tech Stack

### Frontend

- React.js
- Redux
- React Bootstrap
- Material Icons
- tsparticles
- react-datepicker
- moment

### Backend

- Node.js
- Express.js

### Database

- MongoDB
- Mongoose

### Authentication

- JWT

### Deployment

- AWS
- Render
- MongoDB Atlas

---

# 📁 Project Structure

```text
Expense-Tracker-App
│
├── frontend
│   ├── src
│   ├── public
│   └── package.json
│
├── backend
│   ├── config
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── middleware
│   └── server.js
│
├── README.md
└── package.json
```

---

# 📷 Screenshots

## Dashboard

![Dashboard](https://i.postimg.cc/6qLR3WNt/Expense-Management-System-Brave-19-04-2023-11-08-53.png)

---

## Transactions

![Transactions](https://i.postimg.cc/DynLNXqZ/Expense-Management-System-Brave-19-04-2023-11-08-59.png)

---

## Analytics

![Analytics](https://i.postimg.cc/Dy6L3wgc/Expense-Management-System-Brave-19-04-2023-11-15-46.png)

---

## Categories

![Categories](https://i.postimg.cc/13YF47bn/Expense-Management-System-Brave-19-04-2023-11-15-54.png)

---

## Reports

![Reports](https://i.postimg.cc/rwpWV2Z2/Expense-Management-System-Brave-19-04-2023-11-16-01.png)

---

# 🛣 Roadmap

- [ ] Add recurring expenses
- [ ] Export reports to PDF
- [ ] Dark Mode Support
- [ ] Budget Planning Module
- [ ] Expense Notifications
- [ ] Multi-currency Support
- [ ] Unit Testing
- [ ] Docker Support

---

# 🙌 Contribution

Contributions are welcome.

### Steps to Contribute

Fork the repository.

Create a new branch:

```bash
git checkout -b feature/new-feature
```

Commit changes:

```bash
git commit -m "Added new feature"
```

Push changes:

```bash
git push origin feature/new-feature
```

Open a Pull Request.

---

# 📄 License

This project is licensed under the **MIT License**.

For more details, see the `LICENSE` file.

---
