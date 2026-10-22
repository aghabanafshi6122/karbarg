<div align="center">

<img src="https://raw.githubusercontent.com/aghabanafshi6122/karbarg/refs/heads/main/main-content/content.svg" alt="Purple Panel Logo" width="150"/>

# 🟣 Purple Panel

**پنل مدیریتی ساخت کانفیگ پرسرعت V2ray | Fast V2ray Configuration Panel**

با یک داشبورد ساده و زیبا، کانفیگ‌های V2ray خودت رو بساز و مدیریت کن!
A clean and elegant dashboard to build and manage your V2ray configurations!

[![GitHub](https://img.shields.io/badge/GitHub-aghabanafshi6122-181717?style=for-the-badge&logo=github)](https://github.com/aghabanafshi6122/myprojectt)
[![Railway](https://img.shields.io/badge/Deploy-Railway-0B0D0E?style=for-the-badge&logo=railway)](https://railway.app)
[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python)](https://python.org)

</div>

---

## ✨ معرفی | Overview

**Purple Panel** یک پنل مدیریتی سبک و کاربرپسند برای ساخت و مدیریت کانفیگ‌های **V2ray** است. با استفاده از این پروژه می‌توانید تنها با چند کلیک، پنل شخصی خود را روی [Railway](https://railway.app) راه‌اندازی کنید و از داشبورد مدیریتی آن لذت ببرید.

**Purple Panel** is a lightweight, user-friendly management panel for creating and managing **V2ray** configurations. With just a few clicks, you can deploy your personal panel on [Railway](https://railway.app) and enjoy its management dashboard.

> 💡 نیازی به دانش برنامه‌نویسی ندارید — فقط مراحل زیر را قدم به قدم دنبال کنید!
> 💡 No programming knowledge required — just follow the steps below!

---

## 🧩 ویژگی‌ها | Features

| فارسی | English |
|-------|---------|
| ✅ رابط کاربری ساده و زیبا | ✅ Clean and minimal web interface |
| ✅ ساخت و مدیریت کانفیگ‌های V2ray | ✅ Create and manage V2ray configurations |
| ✅ پشتیبانی از VLESS | ✅ VLESS support |
| ✅ ربات تلگرام | ✅ Telegram bot integration |
| ✅ مدیریت محدودیت سرعت | ✅ Speed / rate limiting |
| ✅ نصب آسان روی Railway | ✅ One-click deploy on Railway |
| ✅ پایداری تنظیمات با Volume | ✅ Persistent storage via volumes |
| ✅ چک‌های سلامت و عیب‌یابی | ✅ Health-check and diagnostics |

---

## 🚀 راه‌اندازی سریع | Quick Start (Deploy in 5 Minutes)

### 📌 قدم اول — ثبت‌نام در GitHub | Step 1 — Create a GitHub Account

اگر هنوز حساب کاربری ندارید، در سایت [github.com](https://github.com) با ایمیل خود ثبت‌نام کنید.

If you don't have one yet, sign up at [github.com](https://github.com).

### 📌 قدم دوم — ثبت‌نام در Railway | Step 2 — Create a Railway Account

به سایت [railway.app](https://railway.app) بروید و با همان اکانت GitHub ثبت‌نام کنید.

Go to [railway.app](https://railway.app) and sign up using your GitHub account.

### 📌 قدم سوم — Deploy پروژه | Step 3 — Deploy the Project

**فارسی:**
۱. در صفحه اصلی Railway روی گزینه **Deploy** کلیک کنید.
۲. گزینه **Github Repository** را انتخاب کنید.
۳. روی **Install Github App** بزنید.
۴. در پنجره باز شده، دسترسی **All Repository** را بدهید و روی **Install & Authorize** کلیک کنید.
۵. به صفحه اصلی Railway برگردید و دوباره مسیر **Deploy → Github Repository** را طی کنید.
۶. در کادر بالا، آدرس زیر را وارد کنید:

**English:**
1. On the Railway dashboard, click **Deploy**.
2. Choose **GitHub Repository**.
3. Click **Install GitHub App**.
4. Grant **All Repository** access and click **Install & Authorize**.
5. Return to the Railway dashboard and repeat **Deploy → GitHub Repository**.
6. In the input field, paste:

```
github.com/aghabanafshi6122/myprojectt
```

۷. روی **Deploy Repo** کلیک کنید تا پنل نصب شود.
7. Click **Deploy Repo** and wait for the build to finish.

### 📌 قدم چهارم — تنظیم دامنه | Step 4 — Generate a Domain

**فارسی:**
۱. روی آیکون پروژه کلیک کنید.
۲. روی دکمه **Settings** بزنید.
۳. روی دکمه **Generate Domain** کلیک کنید.
۴. اگر شماره‌ای خواست، عدد **8080** را وارد کنید.

**English:**
1. Click on your project card.
2. Open the **Settings** tab.
3. Click **Generate Domain**.
4. If prompted for a port, enter **8080**.

پس از این مرحله، لینکی به شما داده می‌شود، مثلاً:
You will receive a URL like:

```
https://myprojectt-production-a45r.up.railway.app/
```

> ⚠️ **توجه:** ابتدا باید پنل به حالت **Online** برود، سپس وارد شوید.
> ⚠️ **Note:** Wait until the service status shows **Online** before opening the URL.

### 📌 قدم پنجم — ورود به پنل | Step 5 — Sign In

در انتهای آدرس، عبارت `/login` را اضافه کنید:
Append `/login` to the URL:

```
https://myprojectt-production-a45r.up.railway.app/login
```

سپس **رمز پیش‌فرض** را وارد کنید.
Enter the **default password** (see environment variables or logs).

🎉 **تبریک!** شما الان یک پنل شخصی ساخت کانفیگ دارید.
🎉 **Congratulations!** Your personal panel is now live.

---

## 💾 ذخیره تنظیمات | Persistent Storage (Recommended)

اگر می‌خواهید بعد از آپدیت‌های پنل، کانفیگ‌های شما **ذخیره بمانند** و کار کنند، مراحل زیر را انجام دهید:

To keep your data safe across redeploys and updates:

**فارسی:**
۱. روی پروژه در Railway **کلیک راست** کنید.
۲. روی گزینه **Attach Volume** کلیک کنید.
۳. در کادر بالا عبارت `/data` را وارد کنید.
۴. کلید **Enter** را بزنید و صبر کنید تا فرآیند Deploy تمام شود.

**English:**
1. **Right-click** on your project in Railway.
2. Select **Attach Volume**.
3. Enter `/data` as the mount path.
4. Press **Enter** and wait for the redeploy to finish.

✅ از این به بعد تنظیمات شما پایدار خواهند ماند!
✅ Your settings and data will now persist between deployments.

---

## 📁 ساختار پروژه | Project Structure

| فایل / File | توضیحات / Description |
|-------------|------------------------|
| `Dockerfile` | پیکربندی ساخت کانتینر / Container build configuration |
| `doctor.py` | ماژول سلامت و عیب‌یابی / Health-check and diagnostics |
| `jinx_api.py` | ماژول API بک‌اند / Backend API module |
| `jinx.js` / `jinx.css` | فایل‌های فرانت‌اند / Frontend assets |
| `lock.py` | کنترل دسترسی و نشست / Session and access control |
| `ensure_admin.py` | ابزار تنظیم ادمین / Admin setup utility |
| `start.sh` | اسکریپت شروع / Startup script |
| `nginx.conf` | پیکربندی پروکسی معکوس / Reverse-proxy configuration |
| `railway.json` | پیکربندی استقرار Railway / Railway deployment configuration |
| `variables.env` | متغیرهای محیطی (نمونه) / Environment variables (example) |
| `donate.html` / `donate-config.js` | صفحات و تنظیمات دونیت / Donation page assets |
| `download` | فایل‌های صفحه دانلود / Download page assets |
| `sub.html` | قالب صفحه اشتراک / Share page template |
| `enforce_hosts.py` | ماژول اعتبارسنجی هاست / Host validation module |
| `ws.inc` / `gate.inc` | قالب‌های پارشال / Partial template includes |
| `xray_config.json` | فایل پیکربندی برنامه / Application configuration file |
| `locked_inbound.json` | فایل تنظیمات قفل‌شده / Locked settings file |
| `iran-relay.sh` | اسکریپت راه‌اندازی نود / Node setup script |

---

## ⚙️ متغیرهای محیطی | Environment Variables

| متغیر / Variable | توضیحات / Description | پیش‌فرض / Default |
|------------------|------------------------|--------------------|
| `PORT` | پورت اجرای برنامه / Port the app listens on | `8080` |
| `PASSWORD` | رمز ورود به داشبورد / Dashboard login password | *(از لاگ‌ها ببینید / see logs)* |
| `DATA_DIR` | مسیر داده‌های پایدار / Path for persistent data | `/data` |

---

## 🖼️ تصاویر | Screenshots

برای مشاهده تصاویر پروژه، فایل [`screenshots.md`](./screenshots.md) را بررسی کنید.
Check [`screenshots.md`](./screenshots.md) for previews of the dashboard.

---

## 🛠️ فناوری‌ها | Tech Stack

- 🐍 **Python 3.x**
- 🌐 **HTML / CSS / JavaScript**
- 🐳 **Docker**
- ☁️ **Railway**
- 🤖 **Telegram Bot API**

---

## 🤝 مشارکت | Contributing

اگر ایده، پیشنهاد یا باگی دارید، خوشحال می‌شویم در [بخش Issues](https://github.com/aghabanafshi6122/myprojectt/issues) مطرح کنید.

Ideas, suggestions, or bug reports are always welcome!
Please open an issue in the [Issues](https://github.com/aghabanafshi6122/myprojectt/issues) section.

---

## 📄 لایسنس | License

This project is released for personal use. Please respect the original author.

---

<div align="center">

<img src="https://raw.githubusercontent.com/aghabanafshi6122/karbarg/refs/heads/main/main-content/content.svg" alt="Purple Panel Logo" width="80"/>

**⭐ اگر این پروژه برایتان مفید بود، یک ستاره به آن بدهید!**
**⭐ If you find this project useful, please give it a star!**

ساخته شده با 💜 توسط [aghabanafshi6122](https://github.com/aghabanafshi6122)
Made with 💜 by [aghabanafshi6122](https://github.com/aghabanafshi6122)

</div>
