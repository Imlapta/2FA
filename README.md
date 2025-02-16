# 2FA Verification Bot

A **Telegram 2FA verification bot** that helps users secure their accounts with two-factor authentication. This bot supports deployment on **VPS** and **Heroku**.

## Features
- Secure **2FA authentication** via Telegram
- Supports **VPS & Heroku** deployment
- Easy setup and configuration
- Open-source and customizable

---

## 🚀 Deployment Guide

### 1️⃣ Deploy on Heroku
#### **Step 1:** Click the Button Below
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/DAXXTEAM/2FA)

#### **Step 2:** Set Environment Variables
- `BOT_TOKEN` → Your Telegram Bot Token
- `API_ID` → Your Telegram API ID
- `API_HASH` → Your Telegram API Hash

#### **Step 3:** Deploy & Start Bot
- Click **Deploy** on Heroku
- After deployment, go to **Resources** and enable the bot's worker dyno.

---

### 2️⃣ Deploy on VPS
#### **Step 1:** Install Dependencies
```bash
sudo apt update && sudo apt install -y python3 python3-pip git
```

#### **Step 2:** Clone the Repository
```bash
git clone https://github.com/DAXXTEAM/2FA.git && cd 2FA
```

#### **Step 3:** Install Python Requirements
```bash
pip3 install -r requirements.txt
```

#### **Step 4:** Configure Environment Variables
Edit `2FA.py` file or export manually:
```bash
export BOT_TOKEN='your-bot-token'
export API_ID='your-api-id'
export API_HASH='your-api-hash'
```

#### **Step 5:** Run the Bot
```bash
python3 2FA.py
```

---

## 📜 License
This project is open-source and available under the **MIT License**.

## 📞 Contact & Support
- GitHub: [DAXXTEAM](https://github.com/DAXXTEAM/2FA)
- Telegram: [Support Group](https://t.me/vlubtech)

> **Note:** Ensure your bot is properly configured to avoid security risks.
> 
