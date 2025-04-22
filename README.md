This project sets up **Gitea** and **Grafana** with **Single Sign-On (SSO)** using **Authelia**, all behind an **Nginx reverse proxy**, containerized with **Docker**.

---

## 🔧 Tech Stack

- **Gitea** – Git repository manager  
- **Grafana** – Monitoring and dashboards  
- **Authelia** – SSO & 2FA for secure access  
- **Nginx** – Reverse proxy and traffic router  
- **Docker Compose** – Service orchestration  

---

## 🚀 Quick Start

git clone https://github.com/yourusername/sre-ii-assignment.git
cd sre-ii-assignment
docker-compose up -d
Gitea: http://localhost/gitea

Grafana: http://localhost/grafana

Login via Authelia (SSO prompt)

📁 Structure

├── docker-compose.yml
├── config/
│   ├── nginx/         # Reverse proxy config
│   ├── authelia/      # Auth config and users
│   ├── gitea/
│   └── grafana/

✅ Features
🔐 SSO login with Authelia

🔄 Centralized access via Nginx

🐳 Dockerized and easy to run

🧱 Ready for extension (Terraform, logging, etc.)

📘 Docs
[Gitea | Grafana](https://docs.gitea.io/)
https://grafana.com/docs
https://nginx.org/en/docs
