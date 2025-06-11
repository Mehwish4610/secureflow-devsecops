# 🚀 SecureFlow DevSecOps Platform

A **complete, production-grade, end-to-end DevSecOps pipeline** that showcases Site Reliability Engineering (SRE), CI/CD automation, observability, and security-first engineering.




## 🏷 Project Highlights

- 🔒 **Security First** — Integrated static analysis (Semgrep) and container scanning (Trivy)
- ⚙️ **Full CI/CD Pipeline** — Built entirely with GitHub Actions
- 📊 **Real-time Observability** — Prometheus + Grafana monitoring stack
- 📦 **Dockerized Microservices** — Fully containerized application
- 📣 **Slack Alerts** — Instant notifications on build failures
- 🧪 **Linting & Code Quality** — Python linting via Flake8
- 💻 **Modern UI** — FastAPI powered app with custom Jinja2 frontend

## 📂 Folder Structure

```bash
secureflow-devsecops/
│
├── app/                # FastAPI backend code
│   └── main.py
│
├── templates/          # Frontend templates (Jinja2)
│   └── index.html
│
├── docker/             # Dockerfile for application
│   └── Dockerfile
│
├── prometheus.yml      # Prometheus scrape config
│
├── docker-compose.yml  # Entire stack orchestration
│
├── .semgrepignore      # Ignore file for Semgrep scans
│
└── .github/
    └── workflows/
        └── devsecops.yml  # Full CI/CD pipeline definition

```
## 💡 System Architecture Diagram


![App Screenshot](https://github.com/Mehwish4610/secureflow-devsecops/blob/main/ChatGPT%20Image%20Jun%2011%2C%202025%2C%2009_57_18%20PM.png)

## 🔧 Technologies Used



| Area                             | Tool                   |
| -------------------------------- | ---------------------- |
| Web Framework                    | FastAPI                |
| Template Engine                  | Jinja2                 |
| Containerization                 | Docker, Docker Compose |
| CI/CD Pipeline                   | GitHub Actions         |
| Static Code Analysis             | Semgrep                |
| Container Vulnerability Scanning | Trivy                  |
| Monitoring                       | Prometheus             |
| Visualization                    | Grafana                |
| Notification                     | Slack                  |
| Linting                          | Flake8                 |



## 🚀 Getting Started

### ✅ Prerequisites

- Docker Desktop installed (Windows, Mac, Linux)

- Git installed

- A Slack Webhook URL (for Slack alerts)

- GitHub repository for CI/CD integration

### ✅ Clone Repository

```bash
git clone https://github.com/<your-username>/secureflow-devsecops.git

cd secureflow-devsecops

```

### ✅ Setup Slack Webhook Secret in GitHub

- Go to your GitHub repo → Settings → Secrets → Actions

- Create new repository secret:

### ✅ Run Project Locally via Docker Compose
```bash
docker compose up --build
Access Services:
```

Service	URL

🔵 FastAPI UI	http://localhost:8080

🔵 Metrics Endpoint	http://localhost:8080/metrics

🔵 Prometheus UI	http://localhost:9090

🔵 Grafana UI	http://localhost:3000

Grafana Login:

Username: admin

Password: admin



### ✅ Grafana Initial Setup
---

- Import FastAPI Dashboard:

- Go to Dashboards → Import

- Use Dashboard ID: 14803

- Select Prometheus data source (http://prometheus:9090)

- Explore beautiful real-time monitoring 📊

## 🧪 Full CI/CD Pipeline (GitHub Actions)

| Stage            | Description                         |
| ---------------- | ----------------------------------- |
| ✅ Checkout       | Pull latest source code             |
| ✅ Python Linting | Flake8 static linting               |
| ✅ Docker Build   | Application Docker image build      |
| ✅ Semgrep        | Code-level static security scan     |
| ✅ Trivy          | Docker image vulnerability scanning |
| ✅ Slack Alerts   | Failure notifications sent to Slack |

✅ Fully automated on every push and pull request to main branch.


## 🔐 Security & Code Quality

| Tool    | Purpose                                 |
| ------- | --------------------------------------- |
| Flake8  | Python code linting                     |
| Semgrep | Code security scanning                  |
| Trivy   | Docker container vulnerability scanning |


## 🏷 Real-World Use Case

This project simulates how modern engineering teams enforce:

✅ Shift-left security

✅ Continuous compliance scanning

✅ SRE-grade observability pipelines

✅ Unified DevSecOps practice
## 🤝 Credits 

Created & Designed by: - [@Mehwish4610](https://github.com/Mehwish4610)

## Screenshots

Flask App

![App Screenshot](https://github.com/Mehwish4610/secureflow-devsecops/blob/main/Screenshot%202025-06-11%20214109.png)

---
Prometheus Metrics

![App Screenshot](https://github.com/Mehwish4610/secureflow-devsecops/blob/main/Screenshot%202025-06-11%20214124.png)

---
Docker

![App Screenshot](https://github.com/Mehwish4610/secureflow-devsecops/blob/main/Screenshot%202025-06-09%20170258.png)

---
Grafana Dashboard

![App Screenshot](https://github.com/Mehwish4610/secureflow-devsecops/blob/main/Screenshot%202025-06-11%20174501.png)

---
GitHub Workflow Actions

![App Screenshot](https://github.com/Mehwish4610/secureflow-devsecops/blob/main/Screenshot%202025-06-09%20164435.png)

---
Slack Alerts

![App Screenshot](https://github.com/Mehwish4610/secureflow-devsecops/blob/main/Screenshot%202025-06-09%20164150.png)

