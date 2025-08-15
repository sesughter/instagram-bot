# Instagram bot
This is a **safe, demonstration-only** Python automation script that simulates the skills required for building a private Instagram comment-like tool **without** interacting with Instagram.  
It uses the public demo site **https://quotes.toscrape.com/** for all automation actions.

---

## Features
- **Browser automation** with Selenium
- **Multi-account support** via CSV file
- **Optional proxy support** for each account
- **Random delays** to mimic human behavior
- **Simple GUI** built with Tkinter
- Works on **Windows** and **macOS**

---

## Requirements
- **Python 3.8+**
- **Google Chrome or Chromium**
- **Selenium** (v4.6+ recommended for auto ChromeDriver management)

Install dependencies:
pip install selenium

---

## Usage

### Run the tool with the GUI
python comment_click_demo.py
1. Enter a username, password, and optional proxy.
2. Click "Run Single Demo" to perform the sample action.
3. Or click "Run from CSV" to process multiple accounts.

### Run in batch mode with CSV
python comment_click_demo.py accounts.csv

CSV format:
username,password,proxy
user1,pass1,http://proxy1:port
user2,pass2,
user3,pass3,http://proxy3:port
- proxy column is optional.

---

## What this demo does
- Opens the demo site https://quotes.toscrape.com/
- Simulates human scrolling
- Finds the first author link on the page and clicks it
  (This click stands in for "liking a comment" in a real project)

---

## Notes
- **This script does NOT interact with Instagram** — it is purely for demonstration purposes.
- To adapt this for Instagram, the same automation techniques can be applied to simulate comment likes while respecting safe delay patterns and using account proxies.
- Always use automation tools responsibly and in compliance with the target platform’s terms of service.

---

## Author
**Sesugh Iortsor**
Python Developer | Automation Specialist
