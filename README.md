# 🧘 Calmy Focus

A holistic productivity and mental wellness web application that integrates time management, habit formation, personal organization, and relaxation tools into a single, intuitive platform.

> Built for CPRO 2211 by Avi Pancholi, Pranav Talwar, and Sikander Kingra

---

## 📖 Overview

In today's fast-paced digital world, individuals often struggle to balance demanding workloads with self-care — leading to burnout and fragmented workflows. Calmy Focus solves this by bringing everything you need into one place.

---

## ✨ Features

### 🔐 User Authentication
- Secure registration and login using session cookies
- Middleware-protected routes to guard user data
- Passwords hashed before being stored in the database

### ⏱️ Productivity Timer
- Real-time focus timer with play, pause, and reset controls
- Built-in productivity tips (e.g. Pomodoro Technique)
- Helps users effectively log and manage daily focus sessions

### 📝 Personal Notes
- Full CRUD support — create, read, edit, and delete notes
- Notes are automatically persisted to the database
- Keeps all ideas and to-dos organized in one place

### 🔥 Habit Tracker
- Create and log daily habits
- Streak counter to keep users motivated and consistent
- Integrated with the Meditation Hub for automatic habit logging

### 🧘 Meditation Hub
- Start guided meditation sessions with ambient music
- Choose from multiple audio tracks (e.g. Ocean Waves)
- Sessions are automatically logged in the Habit Tracker

### 📅 Interactive Calendar
- Add and remove events with title, description, and time range
- Support for all-day events and color-coded categorization
- Visual overview of your daily and upcoming schedule

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Backend | C# / ASP.NET Core |
| Frontend | HTML, CSS, JavaScript |
| Database | MongoDB |
| Auth | Session Cookies + Middleware |

---

## 🚀 Getting Started

### Prerequisites
- [.NET SDK](https://dotnet.microsoft.com/download) (version 6.0 or higher)
- [MongoDB](https://www.mongodb.com/) running locally or a MongoDB Atlas connection string

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Pranav-Talwar/Calmy-Focus-App.git
   cd Calmy-Focus-App
   ```

2. **Configure your database connection**
   - Open the project settings or `appsettings.json`
   - Add your MongoDB connection string

3. **Run the application**
   ```bash
   dotnet run --project Calmy-Focus-App
   ```

4. Open your browser and navigate to `http://localhost:5000`

---

## 👥 Contributors

| Name | Role |
|------|------|
| Avi Pancholi | Developer |
| Pranav Talwar | Developer |
| Sikander Kingra | Developer |

---

## 📄 License

This project was created for academic purposes as part of CPRO 2211.
