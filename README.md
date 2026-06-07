# Github-actions-project

# 🚀 GitHub Actions CI/CD – Node.js Docker Deployment

## 📌 Project Overview

This is a DevOps learning project where I implemented a simple CI/CD pipeline using **GitHub Actions and Docker**.

The pipeline automatically builds and deploys a Node.js application whenever code is pushed to the main branch.

This project is built for **learning purposes** to understand real-world CI/CD workflows.

---

## ⚙️ Tech Stack

- Node.js
- Express.js
- Git & GitHub
- GitHub Actions
- Docker

---

## 🔄 CI/CD Workflow
Code Push → GitHub Actions Trigger → Docker Build → Stop Old Container → Run New Container


---

## 🏗 Project Structure

```

.
├── app.js
├── package.json
├── Dockerfile
└── .github/workflows/deploy.yml
