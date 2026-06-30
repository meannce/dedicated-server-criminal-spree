# 🎮 Dedicated Server Criminal Spree 🚔

[![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://docs.docker.com/compose/)
[![Memory Consumption](https://img.shields.io/badge/RAM_Estimate-~13_GB-FF6B6B?style=for-the-badge&logo=ram&logoColor=white)]()

> *"Want to go to jail? Just `docker compose up -d`"*

📺 **Context:** [Minecraft private servers are illegal, according to the ESA.](https://www.youtube.com/watch?v=RgmtdeBIZ2s)

---
## ⚡ Disclaimer & Status
* **Status:** *Untested Chaos.* The images download successfully and most containers spin up, but the rest of the tinkering, and performance is left to you. Good luck, criminal.
---

## 🚀 Quick Reference Guide

### 🟢 Start the Syndicate
Spin up all game servers in detached mode (background):
```bash
docker compose up -d
```

Stop everything:
```bash
docker compose down
```

Stop and delete everything:
```bash
docker compose down -v
```

Logs (you'll need it more than I do):
```bash
docker compose logs -f [service-name]
```

Bye.
