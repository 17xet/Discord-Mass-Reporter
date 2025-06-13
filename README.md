Discord Mass Reporter

![Screenshot 2025-06-13 162607](https://github.com/user-attachments/assets/59cc5853-ad7e-416f-a949-8460d8f569fb)

⚠️ **Disclaimer:** This project is intended strictly for **educational purposes and self-testing only**. It should not be used to harass, spam, or violate the Terms of Service of any platform, including Discord. The developer assumes no responsibility for misuse of this tool.

## 💡 About

A Python-based command-line tool that interacts with Discord's API to simulate message reporting. Built with the intention of learning about:

- HTTP request handling in Python
- Multithreading
- Working with headers and payloads
- CLI formatting with `colorama`

## ⚙️ Features

- Takes user token input and verifies it
- Accepts server, channel, and message IDs for targeting
- Sends report payloads to Discord's API
- Multithreaded simulation to understand concurrent requests

## 📦 Requirements

- Python 3.8+
- `requests`
- `colorama`

Install dependencies:

```bash
pip install requests colorama
````

## 🚀 Usage

```bash
python mass_reporter.py
```

You'll be prompted to enter:

* Your Discord token
* Reason code for reporting
* Server ID, Channel ID, and Message ID

## ❗ Educational Use Only

This script is built for **personal, non-malicious** testing and should never be used on others' content or accounts. Misuse may result in disciplinary action by Discord or other services.

---

## 📚 Learning Goals

If you're interested in API interaction, consider these ethical project ideas:

* Build a Discord bot using `discord.py`
* Simulate moderation tools locally without using real API endpoints
* Practice rate-limited API request handling with safe, public APIs

---

## 👤 Author

Made with ❤️ by 17xet
GitHub: [github.com/17xet](https://github.com/17xet)

```
