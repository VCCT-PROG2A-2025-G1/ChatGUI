# 🛡️ CyberChatbotGUI – Cybersecurity Assistant  
**Module:** Programming 2A (PROG6221)  
**Student Name:** Morné Viljoen  
**Student Number:** ST10374994  

---

## 📘 Overview

**CyberChatbotGUI** is a WPF desktop application that integrates multiple cybersecurity-focused features:

- ✅ Task Assistant with reminders (Part 1)
- ✅ Chatbot with keyword detection, sentiment analysis, and memory (Part 2)
- ✅ Cybersecurity Quiz Mini-Game (Part 2)
- ✅ Activity Log viewer (Part 3)

This application simulates a productivity and education tool focused on cybersecurity awareness and self-organization.

---

## 🖥️ Setup Instructions

### Requirements
- Visual Studio 2022 or newer
- .NET 6 SDK or higher

### How to Run
1. Open the solution file `CyberChatbotGUI.sln` in Visual Studio.
2. Set `CyberChatbotGUI` as the startup project.
3. Press `F5` to build and run the application.

---

## 🚀 Key Features

### 🗂️ Task Assistant
- Add tasks with descriptions
- Optional reminder date picker
- Automated reminder alerts (via `DispatcherTimer`)
- Logged in the activity log

### 🤖 Chatbot Assistant
- Understands questions and keywords (e.g. phishing, VPN, passwords)
- Responds to emotional cues (e.g. anxious, curious)
- Memory: remembers your interests for follow-up
- Handles flexible sentence structures via NLP-style matching

### 🎯 Quiz Mini-Game
- 10 random cybersecurity questions
- Immediate feedback after each answer
- Summary score at the end
- Educational explanations after each question

### 📜 Activity Log
- Tracks all interactions:
  - Tasks created/deleted
  - Quiz attempts
  - Chatbot queries
- Log entries displayed in popup format for review

---

## 📂 Folder Structure
CyberChatbotGUI/
├── CyberChatbotGUI.sln
├── MainWindow.xaml
├── MainWindow.xaml.cs
├── Models/
│ └── CyberTask.cs
├── Services/
│ └── Logs.cs
│ └── MemoryManager.cs
├── QuizQuestion/
│ ├── QuizWindow.xaml
│ ├── QuizWindow.xaml.cs
│ └── QuizQuestion.cs
├── POE_Part_2_CybersecurityChatbot/
│ ├── ResponseManager.cs
│ └── Utilities.cs
└── README.md

---

## 🧠 AI-like Behavior (Part 2)

| Feature             | Description |
|---------------------|-------------|
| **Keyword Matching** | Bot recognizes key terms like `2fa`, `firewall`, etc. |
| **Sentiment Detection** | Detects words like "anxious", "frustrated", "curious" |
| **Memory**          | Remembers what you're interested in and follows up |
| **NLP Responses**   | Can process flexible, natural language phrasing |
| **Log Feedback**    | Every response is tracked in a central log system |

---

## 🧪 GitHub & Versioning

- ✔️ Commit history tracks progression from Part 1 → Part 3
- ✔️ Example Tags:
  - `v1.0-task-manager`
  - `v2.0-chatbot-quiz`
  - `v3.0-final-submission`
- ✔️ Optional: GitHub Actions for CI/CD (recommended but not required)

---

## 📸 Screenshot Suggestions
To enhance this `README`, include screenshots of:
- Task reminder popup
- Chatbot conversation (with sentiment)
- Quiz question screen + feedback
- Activity Log popup

---

## 🏁 Final Notes

**CyberChatbotGUI** demonstrates the integration of three major programming components into one functional desktop application, combining project-based learning with real-world GUI development.

> Submitted by **Morné Viljoen** (ST10374994)  
> Module: **Programming 2A – PROG6221**
