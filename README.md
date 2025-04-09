# 🧠 FocusTroop – Capstone Project

**FocusTroop** is a collaborative productivity platform that helps individuals and groups stay focused using structured **Pomodoro sessions**, **goal tracking**, and **group accountability**. Built for students, remote teams, and solo workers who want to optimize their time and reduce distractions.

> Developed as part of the final year B.Tech CSE Capstone Project.

---

## 📚 Table of Contents

- [About](#about)
- [Problem Statement](#problem-statement)
- [Objectives](#objectives)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [System Architecture](#system-architecture)
- [Setup Instructions](#setup-instructions)
- [Screenshots](#screenshots)
- [Future Scope](#future-scope)
- [Team](#team)
- [License](#license)

---

## 📖 About

**FocusTroop** combines time management strategies with accountability tools in a clean, modern interface. It includes both **Solo Focus Mode** and **Group Focus Rooms**, allowing users to work alone or with friends on shared goals. The goal is to create a distraction-free digital environment that empowers consistent and mindful productivity.

---

## ❓ Problem Statement

In today's fast-paced and distraction-heavy digital world, maintaining consistent focus and productivity is challenging. Students and remote professionals often struggle with time management, motivation, and task completion due to lack of structure and accountability. There’s a need for a platform that promotes focused work and provides real-time collaboration.

---

## 🎯 Objectives

- Encourage deep work and consistent productivity using the Pomodoro Technique.
- Provide real-time group collaboration features for shared focus sessions.
- Enable personalized task planning with session allocation.
- Offer analytics and habit-tracking features to keep users motivated.

---

## 🚀 Features

| Feature | Description |
|--------|-------------|
| ⏳ **Pomodoro Timer** | Customizable focus and break intervals |
| 🧘 **Solo Mode** | Private workspace with personal tasks and stats |
| 👥 **Group Rooms** | Join or create rooms to co-work with others |
| 📊 **Dashboard** | Visual progress reports and productivity charts |
| 🧩 **Task Manager** | Create tasks with estimated Pomodoro counts |
| 🔔 **Notifications** | Smart alerts for start/end of sessions |
| 🌿 **White Noise** | Focus sounds to reduce mental fatigue |
| 📅 **Deadlines** | Set and manage due dates per task |

---

## 🧰 Tech Stack

```sh
Frontend: React + Tailwind CSS  
Backend: Node.js + Express  
Database: MongoDB  
Authentication: JWT + bcryptjs  
Real-time Collaboration: Socket.io  
Notifications: Browser Notifications / Custom Alerts  
UI Libraries: Shadcn UI, Framer Motion  
Hosting: Vercel (Frontend) + Render (Backend)
```

---

Client (React)
   ↓ HTTP / WebSocket (Socket.io)
Backend (Node.js + Express)
   ↓
MongoDB (Database)
   ↑
Real-time Updates (Socket.io)

---
