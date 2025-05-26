# Full-Stack-Student-Registration-System

A web application that allows administrators to manage student profiles including uploading profile images, inputting student details, and viewing all registered students in an interactive interface.

## 📸 Preview

![Preview Screenshot](./Screenshot%202025-04-11%20231421.png)

## 🛠️ Technologies Used

### Frontend
- **React.js** — For building a dynamic, responsive, and interactive UI.
- **Axios** — For API communication

### Backend
- **.NET (ASP.NET Core)** — Provides RESTful APIs and server-side logic.
- **Entity Framework (EF)** — ORM tool to interact with SQL Server database easily.

### Database
- **SQL Server** — Stores student data securely and efficiently.

---

## 🚀 Features

- Upload student profile pictures
- Input student name and course of study
- Display all registered students with:
  - Name
  - Course of study
  - CGPA
  - Profile image

---

## 🔧 Setup Instructions

### Prerequisites
- Node.js and npm
- .NET SDK
- SQL Server

### Frontend Setup (React)
```bash
cd client
npm install
npm start
```

### Backend Setup (.NET)
```bash
cd server
dotnet restore
dotnet run
```

### Database Setup
```bash
dotnet ef migrations add InitialCreate
dotnet ef database update
```

---

## ✨ Future Improvements

- 🔐 Authentication & Authorization: Implement a secure login system
- 🤖 AI-powered Chatbot Assistant: Integrate an AI chatbot to provide real-time assistance to users
- 📄 Multi-Page Application Structure: Refactor the project into a multi-page layout for better organization and user navigation
- 🌐 Deployment: Deploy the system to a cloud platform such as Vercel, Netlify, or Azure App Services to make it accessible online. This will involve setting up CI/CD pipelines for streamlined deployment and updates.
