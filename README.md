# 🔍 Fake Website Finder

A beginner-friendly **Flask web app** that checks a URL with simple rules and tells you whether it looks **FAKE ⚠️** or **REAL ✅**, with clear reasons.

## 🚀 Features
- 🔒 Detects missing HTTPS
- 📏 Flags unusually long URLs (over 75 characters)
- 🔢 Identifies IP addresses used instead of domain names
- 🕵️ Scans for suspicious keywords (login, verify, secure, update, bank, account)

## 🛠 Setup

```bash
git clone https://github.com/epsonraj050-art/ai-fake-web-detector.git
cd ai-fake-web-detector
pip install flask
python app.py
```

Then open **http://127.0.0.1:5000** in your browser.

## ⚠️ Limitations
- Rule-based only, so it can give false positives and false negatives.
- Use it for learning, not as your only security check.

See also: [aifakewebdetector](https://github.com/epsonraj050-art/aifakewebdetector) for the full README.
