# 📦 GitHub Repository Monitor using n8n

An automated workflow built with **n8n** that monitors a GitHub repository using the GitHub REST API and sends repository statistics directly to **Telegram**.

This project demonstrates API integration, scheduled automation, JSON parsing, data transformation, and Telegram bot notifications using only free services.

---

## 📌 Overview

This workflow automatically performs the following tasks:

- Runs every day at a scheduled time.
- Retrieves the latest repository information from GitHub.
- Extracts useful repository statistics.
- Formats the information into a readable report.
- Sends the report directly to Telegram.

---

## 🚀 Features

- ⏰ Daily scheduled execution
- 📦 GitHub repository monitoring
- ⭐ Displays repository statistics
- 📲 Telegram notification
- 🌐 Free GitHub REST API
- 🔑 No API key required
- 💯 Fully automated

---

## 🛠 Tech Stack

- n8n
- GitHub REST API
- HTTP Request
- Telegram Bot API

---

## 📂 Workflow

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

## ⚙️ Workflow Explanation

### 1. Schedule Trigger

Automatically runs the workflow every day at the configured time.

---

### 2. HTTP Request

Retrieves repository information from the GitHub REST API.

**API Endpoint**

```
https://api.github.com/repos/n8n-io/n8n
```

You can replace the repository with any public GitHub repository.

Examples:

```
facebook/react

microsoft/vscode

laravel/laravel

tensorflow/tensorflow
```

**Method**

```
GET
```

**Authentication**

```
None
```

---

### 3. Edit Fields (Set)

Formats the API response into a professional repository report.

Example Output:

```
📦 GitHub Repository Report

📁 Repository:
n8n-io/n8n

📝 Description:
Fair-code workflow automation platform.

⭐ Stars: 127,532
🍴 Forks: 38,450
👀 Watchers: 127,532
🐞 Open Issues: 915

🌿 Default Branch:
master

🔗 Repository:
https://github.com/n8n-io/n8n

📅 Last Updated:
2026-07-01T03:20:00Z

🤖 Generated automatically with n8n.
```

---

### 4. Telegram

Sends the formatted repository report directly to your Telegram account.

---

## 📁 Project Structure

```
GitHub-Repository-Monitor/
│
├── README.md
├── workflow.json
└── screenshots/
    ├── workflow.png
    ├── telegram-output.png
    └── workflow-execution.png
```

---

## 📸 Screenshots

Include the following screenshots:

- Workflow Editor
- Successful Workflow Execution
- Telegram Output

Example:

```
screenshots/
    workflow.png
    workflow-execution.png
    telegram-output.png
```

---

## 💡 Use Cases

- Monitor your own GitHub repositories
- Track open-source project statistics
- Learn GitHub REST API integration
- Receive repository updates automatically
- Portfolio automation project

---

## 🔮 Future Improvements

- Monitor multiple repositories
- Compare repository growth over time
- Save statistics to Google Sheets
- Notify when stars reach a milestone
- Monitor new releases
- Monitor new issues and pull requests
- Send notifications to Discord or Slack

---

## 📚 What I Learned

This project helped me gain hands-on experience with:

- Workflow automation using n8n
- GitHub REST API integration
- HTTP Request node
- JSON parsing
- Data transformation
- Telegram Bot integration
- Scheduled workflows

---

## 🏷 Skills Demonstrated

- n8n
- Workflow Automation
- GitHub REST API
- HTTP Request
- REST API Integration
- JSON Parsing
- Data Transformation
- Telegram Bot API
- Scheduled Automation
- No-Code / Low-Code Development

---

## 📄 License

This project is licensed under the MIT License.

---

⭐ If you found this project helpful, consider giving it a star!
