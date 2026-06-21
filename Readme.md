# ── M I M I ─ B O T ──
> Automated WhatsApp Assistant System

<p align="center">
  <img src="https://img.shields.io/github/stars/timnasax/Mimi-bot-?style=for-the-badge&color=purple" alt="Stars"/>
  <img src="https://img.shields.io/github/forks/timnasax/Mimi-bot-?style=for-the-badge&color=blue" alt="Forks"/>
  <img src="https://img.shields.io/github/license/timnasax/Mimi-bot-?style=for-the-badge&color=green" alt="License"/>
  <img src="https://img.shields.io/badge/Deploy%20To-Heroku-purple?style=for-the-badge&logo=heroku" alt="Heroku"/>
</p>

---

## ⚡ VIPENGELE (FEATURES)
- [x] Muundo thabiti na wa haraka (Baileys Based).
- [x] Amri za usimamizi wa makundi (Group Management).
- [x] Ulinzi thabiti wa mfumo.
- [x] Rahisi ku-deploy na kusanidi.

---

## 🚀 JINSI YA KUDEPLOY KWENYE HEROKU

Fuata hatua hizi rahisi ili kurusha bot yako hewani kwa kutumia Heroku:

### 1. Pata Session ID
Kabla ya kuanza, hakikisha umepata `SESSION_ID` yako kwa kuskani QR Code kupitia tovuti ya kuunganishia (Pairing/Scan site) uliyopewa.

### 2. Deploy kwa Kubofya Moja (One-Click Deploy)
Bofya kitufe kilicho hapo chini ili kuanza mchakato wa ku-deploy moja kwa moja kwenye akaunti yako ya Heroku:

[![Deploy To Heroku](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new?template=https://github.com/timnasax/Mimi-bot-)

---

## 🛠️ CONFIGURATION VARIABLES (VARS)

Wakati wa ku-deploy kwenye Heroku, utahitaji kujaza `Config Vars` zifuatazo:

| VARIABLE | MAELEZO | MFANO |
| :--- | :--- | :--- |
| `SESSION_ID` | Id ya siri uliyofanikisha baada ya kuskani | `MIMI_BOT~xxxx...` |
| `PREFIX` | Alama ya kuanzia amri (Command Prefix) | `.` au `!` |
| `OWNER_NAME` | Jina la mmiliki wa bot | `Timnasa Timoth` |
| `OWNER_NUMBER` | Namba ya mmiliki (Pamoja na kodi ya nchi) | `255xxxxxxxxx` |
| `MODE` | Mfumo wa bot (Public au Private) | `public` |

---

## 🔄 MWONGOZO WA NJIA YA MKONO (MANUAL DEPLOYMENT)

Kama unapendelea kutumia Heroku CLI, tumia amri hizi kwenye terminal yako:

```bash
# Clone repository husika
git clone [https://github.com/timnasax/Mimi-bot-.git](https://github.com/timnasax/Mimi-bot-.git)
cd Mimi-bot-

# Ingia kwenye akaunti yako ya Heroku
heroku login

# Tengeneza app mpya ya Heroku
heroku create jina-la-app-yako

# Sukuma codes kwenda Heroku
git push heroku main
