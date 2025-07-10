# 🐧 Selenoid Deployment with Ansible

## 📋 Requirements

- Ansible installed on your local machine (e.g., macOS or Linux)
- Remote Ubuntu server accessible via SSH

---

## ▶️ Command to Run

```bash
cd ./selenoid/playbook
ansible-playbook -i hosts tasks.yml --ask-become-pass
