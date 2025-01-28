# 🌅 Nodepay
Automation approach for nodepay.ai chrome extension

<div align="center">
  <img src="https://i.ibb.co/5rnpVBN/photo-2025-01-13-12-41-53.jpg">
  <img src="https://i.ibb.co/qDjBkp9/photo-2025-01-13-12-42-57.jpg">
  
  <p align="center">
    <a href="https://t.me/qtttttttttttttt">
      <img src="https://img.shields.io/badge/Telegram-Chat-blue?style=for-the-badge&logo=telegram" alt="Telegram Chat">
    </a>
  </p>
</div>

## 📋 Table of Contents
- [Features](#-features)
- [Requirements](#-requirements)
- [Installation](#-installation)
- [Configuration](#%EF%B8%8F-configuration)
- [Usage](#-usage)
- [Troubleshooting](#-troubleshooting)

## 🚀 Features

- ✨ **Auto Farm**
- 🤖 **Account activation**
- 🔄 **Auto recconect after proxy error**
- 📉 **Zero captcha usage**
- 📊 **Multiple connection launch by 1 line in config**
- ✅ **Complete Daily Check-in's**
- 🌾 **Missions Claim**
- 🧩 **Survey complition**
- 📋 **Telegran notification for soft status (Today farmed points, Total farmed points)**
- 🔒 **Low trafic usage**

## Pricing
💰 $29

## 💻 Requirements

- Stable internet connection
- Valid email accounts
- Working proxies (HTTP/SOCKS5)
- Captcha service subscription (2captcha/capmonster)

## 🛠️ Installation

1. **Unpack archive**
2. **Setup all nessesary (accounts/proxies/.env file)**

## ⚙️ Configuration

### 📁 .env

```.env
TG_BOT_TOKEN1 = ""
CHAT_ID = ""
TG_TITLE = '[Nodepay]' # Title that will appeear in tg messages

ACTIVATE_ACCOUNT_ONLY = False #activate account and finish program
LOWER_TRAFFIC_USAGE = True #perform only pings
CONNECTION_PER_ACCOUNT = 3 
RANDOM_SLEEP_BEFORE_START = [1, 300] #delay before each task start
CHECK_POINTS_DELAY = 12000 # in seconds
CHECK_MISSIONS_DELAY = 84600

CAPMOSTER_API_KEY = ''
TWO_CAPTCHA_API_KEY = ''

PROXIES_FILE_PATH = 'data/proxies.txt'
ACCOUNT_FILE_PATH = 'data/accounts.txt'
TOKENS_FILE_PATH = 'data/tokens_db.json'
```

### 📁 Input Files Structure

#### data/accounts.txt
```
email:password
email:password
```

#### data/proxies.txt
```
scheme://user:pass@ip:port
```

## 🚀 Usage

1. Configure all necessary files as described above
2. Start the main.exe

## 🔧 Troubleshooting

### Common Issues and Solutions

#### 🌐 Cloud Flare Exception
- Use good proxies
- If error occurs more frequently, turn off soft for hour or two and then run again (after proxies rotate - problem should be solved)

## 📞 Contact

For any question for buying software:
- 💬 [Contact](https://t.me/qtttttttttttttt)
