![Bayer VR Learning Module Simulator](./assets/cover-image.png)

# 🌾 Bayer VR Learning Module Simulator

The **Bayer VR Learning Module Simulator** is an **enterprise-grade virtual reality training solution** built to replicate the **seed packaging line process with high accuracy**.  

This system allows **trainees to learn, practice, and be assessed** in an interactive VR environment, while **administrators gain real-time visibility of progress** through a secure intranet-based dashboard.  

What if trainees could **step into a fully scanned packaging line**, interact with machinery, and follow workflows safely in VR **without interrupting live production**?  
What if administrators could **monitor every trainee’s progress, quiz results, and session status in real time** through a **secure internal dashboard**?  
What if training could be **modular, language-friendly, and trackable**, ensuring both trainees and administrators gain **clear insights into performance and progress**?  

This project brings together **LIDAR scanning, Unity XR Toolkit, AutoHands package, multilingual support, and custom backend APIs** to deliver a **complete VR learning ecosystem**.  

---

## 📑 Contents
- [🌍 Overview](#-overview)  
- [🔄 Workflow Summary](#-workflow-summary)  
- [🏗 Virtual Environment](#-virtual-environment)  
- [🗣 Multilingual Support](#-multilingual-support)  
- [🎮 User Interaction](#-user-interaction)  
- [📝 Quizzing System](#-quizzing-system)  
- [🔗 Backend Integration](#-backend-integration)  
- [📊 Admin Dashboard & Trainee Panel](#-admin-dashboard--trainee-panel)  
- [🎯 Technology Stack](#-technology-stack)  
- [✅ Outcome](#-outcome)  
- [🔐 Data Privacy & Security](#-data-privacy--security)  

---

## 🌍 Overview
The training program is divided into **four VR modules**, each further broken down into **short chapters (under 7 minutes)** to minimize VR fatigue while ensuring effective learning:  
1. Packaging Roller  
2. Production Process  
3. Labelling & Packaging Workflow  
4. Hybrid Changeover Process  

Learners log in with allocated accounts, select their **preferred language (English or Telugu)**, and progress through interactive workflows.  
➡️ Each chapter ends with a **5-question quiz** to reinforce knowledge.  

---

## 🔄 Workflow Summary
- **Process Understanding** → Gathered operational details of the seed packaging line directly from client inputs  
- **UX Flow (Figma)** → Designed training structure with modules mapped to client workflows  
- **3D Capture & Modeling** → Used **LIDAR and cameras** to scan the packaging line; optimized via Blender retopology  
- **Unity Development (URP + XR Toolkit + AutoHands)** → Developed VR modules using **C# scripts** and **AutoHands** for natural VR hand interactions  
- **Scene Setup** → Imported optimized 3D assets, applied materials, configured lighting for realism  
- **Backend Integration** → Built **custom APIs** for Unity ↔ intranet server communication with JSON-based data exchange  
- **Progress Tracking** → Unity sends **progress updates every 60 seconds** for granular monitoring of interactions  

---

## 🏗 Virtual Environment
- Real-world packaging line **scanned via LIDAR + cameras**  
- Retopologized in **Blender** for performance-optimized VR assets  
- Imported into **Unity URP** for interactive simulation  

---

## 🗣 Multilingual Support
- Trainee can choose **English or Telugu** at login  
- Ensures **accessibility for regional and global trainees**  

---

## 🎮 User Interaction
- Developed with **Unity XR Toolkit + AutoHands package**  
- Natural **VR hand interactions** for handling equipment  
- **Process-driven interactions** mapped directly to real workflows  

---

## 📝 Quizzing System
- Each chapter ends with a **5-question quiz (5 marks total)**  
- **Scoring Rules**:  
  - 1 mark → correct first attempt  
  - 0.5 mark → correct second attempt  
- Results displayed instantly and logged to backend  

---

## 🔗 Backend Integration
- Custom **intranet-based backend server** for account and data management  
- APIs created for Unity to **send/receive JSON data securely**  
- Player progress updates sent **every 60 seconds** (including interaction completions)  

---

## 📊 Admin Dashboard & Trainee Panel

### 🛡️ Admin Panel Features
- Leaderboard  
- User reports (login logs, chapter status, quiz data, progress)  
- Trainee account management  

### 👨‍🎓 Trainee Dashboard
- Personal progress tracking  
- Quiz results and performance overview  

---

## 🎯 Technology Stack

### 🔹 Backend
- Intranet server (custom)  
- Laravel (PHP framework)  
- PHP  
- Docker (containerized deployment)  
- REST APIs (JSON communication)  
- Database for user & training data  

### 🔹 Frontend
- Unity C# + XR Toolkit  
- Blender (3D optimization)  
- Figma (UX flow design)  
- React + Java + HTML/CSS (Admin Dashboard)  

---

## ✅ Outcome
The **Bayer VR Learning Module Simulator** provides a **safe, interactive, and trackable VR training solution** for **seed packaging line operations**.  

With **multilingual support, structured modules, quizzes, and real-time backend reporting**, it ensures:  
- Trainees gain **hands-on experience** in VR  
- Administrators maintain **complete oversight** of progress and performance  

👉 A secure, **enterprise-ready VR training ecosystem**.  

---

## 🔐 Data Privacy & Security
Our **data handling approach** prioritizes **client data sovereignty** through:  
- **On-premises deployment**  
- **Comprehensive security controls**  
- **Transparent operational practices**  

All solutions operate **within client infrastructure**, ensuring:  
- Complete **data ownership and control**  
- Maintenance of **enterprise-grade security standards** throughout the **project lifecycle**  

---
