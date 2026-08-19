# 🏰 Empire Bot

A feature-rich economy & RPG bot for **Bale** messenger with coins, gems, jobs, shop, inventory, bank, levels and more.

ربات اقتصاد و نقش‌آفرینی (RPG) پیشرفته برای پیام‌رسان **بله** با سیستم سکه، جواهر، شغل، فروشگاه، اینونتوری، بانک، لول و بسیاری قابلیت‌های دیگر.

---

## ✨ Features / ویژگی‌ها

**English:**
- Player progression system (Level + XP)
- Currency system: Coins & Gems
- Jobs & Work system with cooldown
- Shop and Inventory management
- Bank system
- Crypto-related commands
- Profile viewing
- Admin commands
- Modular command structure

**فارسی:**
- سیستم پیشرفت بازیکن (لول + XP)
- سیستم ارز: سکه و جواهر
- سیستم شغل و کار با کول‌داون
- فروشگاه و مدیریت اینونتوری
- سیستم بانک
- دستورات مرتبط با کریپتو
- مشاهده پروفایل
- دستورات ادمین
- ساختار ماژولار دستورات

---

## 📁 Project Structure

```
Empire-bot/
└── Empire bot v2/
    ├── main.py              # Bot entry point
    ├── config.py            # Settings & Token
    ├── router.py            # Message router
    ├── database.py          # Database handling
    ├── commands_map.py      # Command mapping
    ├── commands/            # Individual command modules
    │   ├── start.py
    │   ├── work.py
    │   ├── jobs.py
    │   ├── shop.py
    │   ├── inventory.py
    │   ├── bank.py
    │   ├── crypto.py
    │   ├── profile.py
    │   ├── admin.py
    │   └── help.py
    └── utils/
        └── level.py
```

---

## 🚀 Installation & Run

1. Clone the repo
2. Install dependencies (bale library + others)
3. Put your Bale bot token in `config.py` (or better: use environment variables)
4. Run:
```bash
python "Empire bot v2/main.py"
```

---

## ⚠️ Security Warning

**The bot token is currently hardcoded in `config.py`.**  
Please move it to environment variables or a `.env` file immediately and never commit real tokens.

**توکن ربات در حال حاضر داخل فایل `config.py` به صورت هاردکد قرار دارد.**  
لطفاً آن را به متغیر محیطی منتقل کنید و هرگز توکن واقعی را در گیت‌هاب قرار ندهید.

---

## 👤 Author

**Commander004**  
[GitHub Profile](https://github.com/Commander004)

---

Built for the Bale community ❤️
