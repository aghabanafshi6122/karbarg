<div align="center">

<img src="https://raw.githubusercontent.com/aghabanafshi6122/karbarg/refs/heads/main/main-content/content.svg" alt="Purple Panel Logo" width="150"/>

# 🟣 Purple Panel

**Fast V2ray Configuration Management Panel**

A clean and elegant dashboard to build and manage your V2ray configurations!

[![GitHub](https://img.shields.io/badge/GitHub-aghabanafshi6122-181717?style=for-the-badge&logo=github)](https://github.com/aghabanafshi6122/myprojectt)
[![Railway](https://img.shields.io/badge/Deploy-Railway-0B0D0E?style=for-the-badge&logo=railway)](https://railway.app)
[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python)](https://python.org)

**🌐 [نسخه فارسی | Persian Version](./README-FA.md)**

</div>

---

## ✨ Overview

**Purple Panel** is a lightweight, user-friendly management panel for creating and managing **V2ray** configurations. With just a few clicks, you can deploy your personal panel on [Railway](https://railway.app) and enjoy its management dashboard.

> 💡 No programming knowledge required — just follow the steps below!

---

## 🧩 Features

- ✅ Clean and minimal web interface
- ✅ Create and manage V2ray configurations
- ✅ VLESS support
- ✅ Telegram bot integration
- ✅ Speed / rate limiting
- ✅ One-click deploy on Railway
- ✅ Persistent storage via volumes
- ✅ Health-check and diagnostics

---

## 🚀 Quick Start (Deploy in 5 Minutes)

### 📌 Step 1 — Create a GitHub Account

If you don't have one yet, sign up at [github.com](https://github.com).

### 📌 Step 2 — Create a Railway Account

Go to [railway.app](https://railway.app) and sign up using your GitHub account.

### 📌 Step 3 — Deploy the Project

1. On the Railway dashboard, click **Deploy**.
2. Choose **GitHub Repository**.
3. Click **Install GitHub App**.
4. Grant **All Repository** access and click **Install & Authorize**.
5. Return to the Railway dashboard and repeat **Deploy → GitHub Repository**.
6. In the input field, paste:

```
github.com/aghabanafshi6122/myprojectt
```

7. Click **Deploy Repo** and wait for the build to finish.

### 📌 Step 4 — Generate a Domain

1. Click on your project card.
2. Open the **Settings** tab.
3. Click **Generate Domain**.
4. If prompted for a port, enter **8080**.

You will receive a URL like:

```
https://myprojectt-production-a45r.up.railway.app/
```

> ⚠️ **Note:** Wait until the service status shows **Online** before opening the URL.

### 📌 Step 5 — Sign In

Append `/login` to the URL:

```
https://myprojectt-production-a45r.up.railway.app/login
```

Enter the **default password** (see environment variables or logs).

🎉 **Congratulations!** Your personal panel is now live.

---

## 💾 Persistent Storage (Recommended)

To keep your data safe across redeploys and updates:

1. **Right-click** on your project in Railway.
2. Select **Attach Volume**.
3. Enter `/data` as the mount path.
4. Press **Enter** and wait for the redeploy to finish.

✅ Your settings and data will now persist between deployments.

---

## 📁 Project Structure

| File | Description |
|------|-------------|
| `Dockerfile` | Container build configuration |
| `doctor.py` | Health-check and diagnostics module |
| `jinx_api.py` | Backend API module |
| `jinx.js` / `jinx.css` | Frontend assets |
| `lock.py` | Session and access control |
| `ensure_admin.py` | Admin setup utility |
| `start.sh` | Startup script |
| `nginx.conf` | Reverse-proxy configuration |
| `railway.json` | Railway deployment configuration |
| `variables.env` | Environment variables (example) |
| `donate.html` / `donate-config.js` | Donation page assets |
| `download` | Download page assets |
| `sub.html` | Share page template |
| `enforce_hosts.py` | Host validation module |
| `ws.inc` / `gate.inc` | Partial template includes |
| `xray_config.json` | Application configuration file |
| `locked_inbound.json` | Locked settings file |
| `iran-relay.sh` | Node setup script |

---

## ⚙️ Environment Variables

| Variable | Description | Default |
|----------|-------------|---------|
| `PORT` | Port the app listens on | `8080` |
| `PASSWORD` | Dashboard login password | *(see logs)* |
| `DATA_DIR` | Path for persistent data | `/data` |

---

## 🖼️ Screenshots

Check [`screenshots.md`](./screenshots.md) for previews of the dashboard.

---

## 🛠️ Tech Stack

- 🐍 **Python 3.x**
- 🌐 **HTML / CSS / JavaScript**
- 🐳 **Docker**
- ☁️ **Railway**
- 🤖 **Telegram Bot API**

---

## 🤝 Contributing

Ideas, suggestions, or bug reports are always welcome!
Please open an issue in the [Issues](https://github.com/aghabanafshi6122/myprojectt/issues) section.

---

## 📄 License

This project is released for personal use. Please respect the original author.

---

<div align="center">

<img src="https://raw.githubusercontent.com/aghabanafshi6122/karbarg/refs/heads/main/main-content/content.svg" alt="Purple Panel Logo" width="80"/>

**⭐ If you find this project useful, please give it a star!**

Made with 💜 by [aghabanafshi6122](https://github.com/aghabanafshi6122)

**🌐 [نسخه فارسی | Persian Version](./README-FA.md)**

</div>
