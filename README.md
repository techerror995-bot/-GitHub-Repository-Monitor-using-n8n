# 📦 GitHub Repository Monitor using n8n

## 📌 Project Overview

GitHub Repository Monitor is an automated workflow built with **n8n**, the **GitHub REST API**, and **Telegram**. It periodically retrieves repository statistics, formats the data into a readable report, and sends updates directly to Telegram.

Built as part of my **30-Day n8n Automation Portfolio**, this project demonstrates API integration, scheduled automation, JSON data processing, and real-time notifications using free services.

---

## 🎯 Objectives

* Automate GitHub repository monitoring
* Track repository statistics
* Deliver scheduled Telegram updates
* Demonstrate REST API integration
* Build a portfolio-ready automation workflow

---

## 🏗️ Workflow Architecture

```text
Schedule Trigger
        │
        ▼
HTTP Request
        │
        ▼
Edit Fields (Set)
        │
        ▼
Telegram
```

---

## ⚙️ Workflow Implementation

### 1. Schedule Trigger

Runs the workflow automatically at a scheduled interval.

---

### 2. HTTP Request

Retrieves repository information from the GitHub REST API.

Example endpoint:

```
https://api.github.com/repos/n8n-io/n8n
```

You can replace it with any public GitHub repository.

---

### 3. Edit Fields (Set)

Extracts and formats repository information, including:

* Repository Name
* Description
* Stars
* Forks
* Watchers
* Open Issues
* Default Branch
* Repository URL
* Last Updated

---

### 4. Telegram

Sends a formatted repository report directly to Telegram.

Example:

```text
📦 GitHub Repository Report

📁 Repository:
n8n-io/n8n

⭐ Stars:
127,532

🍴 Forks:
38,450

👀 Watchers:
127,532

🐞 Open Issues:
915

🌿 Default Branch:
master

📅 Last Updated:
2026-07-01T03:20:00Z

🤖 Generated automatically with n8n.
```

---

## 🛠️ Technologies Used

* n8n
* GitHub REST API
* HTTP Request
* Telegram Bot API

---

## 📁 Repository Structure

```text
GitHub-Repository-Monitor/
│
├── README.md
├── workflow.json
│
├── screenshots/
│   ├── workflow.png
│   ├── telegram-output.png
│   └── workflow-execution.png
│
└── assets/
```

---

## 📸 Screenshots

Include the following screenshots:

* Complete Workflow
* Workflow Execution
* Telegram Output

---

## 🚀 Key Features

* ✅ Scheduled Workflow Automation
* ✅ GitHub REST API Integration
* ✅ Repository Statistics Monitoring
* ✅ Automated Telegram Notifications
* ✅ JSON Data Processing
* ✅ Fully Automated Workflow
* ✅ Uses Free GitHub API

---

## 🎓 Lessons Learned

Through this project, I gained experience in:

* Building scheduled automation workflows
* Integrating REST APIs with n8n
* Processing JSON responses
* Formatting API data for messaging
* Automating Telegram notifications
* Designing reliable monitoring workflows

---

## 📈 Impact

This workflow automates GitHub repository monitoring by delivering up-to-date repository statistics directly to Telegram. It demonstrates how workflow automation can simplify API monitoring and reporting without requiring manual checks.

---

## 📜 License

MIT License

---

## 👨‍💻 Author

**Belio C. Sinangote**

BS Information Technology Student
Cebu Technological University (CTU)

GitHub: [https://github.com/belioautomation](https://github.com/belioautomation)

This project is part of my **30-Day n8n Automation Portfolio**, showcasing practical workflow automation using n8n, APIs, and automation best practices.
