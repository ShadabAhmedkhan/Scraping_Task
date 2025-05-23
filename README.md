# 🕵️ Dentons Professionals Scraper

[![Python](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Selenium](https://img.shields.io/badge/Selenium-Automation-brightgreen.svg)](https://www.selenium.dev/)
[![ChromeDriver](https://img.shields.io/badge/ChromeDriver-Compatible-yellow.svg)](https://sites.google.com/a/chromium.org/chromedriver/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> 🔎 Automatically scrape professional profiles from [Dentons](https://www.dentons.com/en/our-professionals), including name, job title, office, email availability, and phone number.

---

## 📸 Preview

![scraper-preview](https://user-images.githubusercontent.com/yourusername/yourrepo/scraper-preview.gif)

---

## 🚀 Features

- ✅ Scrapes **name, job title, office, email, and phone number**
- 🔁 Clicks **"Load more"** to reveal all professionals
- 🔐 Avoids duplicate scraping
- 💾 Saves output to `dentons_profiles.csv`
- ⚡ Uses `Selenium` for dynamic interaction

---

## 📂 Output CSV Format

| Name | Profile URL | Job Title | Office | Email Available | Phone Number |
|------|-------------|-----------|--------|------------------|---------------|

---

## 🛠 Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Shadabahmedkhan/dentons-scraper.git
cd dentons-scraper


2️⃣ Install Dependencies
bash
Copy
Edit
pip install selenium
3️⃣ Install ChromeDriver
Make sure ChromeDriver is installed and accessible via your system's PATH.
🔗 Download ChromeDriver

📌 Match the ChromeDriver version with your installed Chrome browser.

▶️ Run the Script
bash
Copy
Edit
python scrape_dentons.py
Opens the Dentons professionals page

Clicks "Load more" until all profiles are shown

Scrapes and saves to dentons_profiles.csv

📎 Notes
🕒 Avoids using sleep() where possible by using WebDriverWait for robustness

📞 Phone numbers are extracted from dynamically expanded HTML sections

📜 License
This project is licensed under the MIT License.
Feel free to use and modify with credit!

📬 Contact
Shadab Ahmed
📧 shadab.dev@outlook.com
📞 +971-50-1640519
🌐 GitHub

⭐️ Give a Star!
If you find this project helpful, please consider giving it a ⭐️ on GitHub!

yaml
Copy
Edit
