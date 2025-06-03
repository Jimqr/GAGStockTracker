# 🌱 Grow A Garden Stock Notifier

A script that monitors item stock from  
[VulcanValues - Grow A Garden](https://vulcanvalues.com/grow-a-garden/stock)  and notifies you when selected items are back in stock.  

It displays color-coded stock lists in your terminal and sends push notifications via [ntfy.sh](https://ntfy.sh).

---

## ✨ Features

- 🕵️‍♂️ Scrapes and displays current stock items by category  
- 🎨 Highlights items with **custom color codes**  
- 📲 Sends push notifications for selected items via **ntfy.sh**  
- ⏰ Refreshes every 5 minutes + 1 minute + 1 second (e.g., 00:01, 05:01, etc.)  
- 🚫 Avoids duplicate alerts to reduce noise  

---

## ⚙️ Requirements

- Python 3  
- `requests`  
- `beautifulsoup4`  

Install dependencies with:  
```bash
pip install requests beautifulsoup4
```
---
## 🚀 Usage

Run the notifier script with:

```bash
python main.py
```

---

## 🛠 Customization

- **Notification items:** Edit the `notify_items` list in the script to choose which items trigger alerts.
- **Color coding:** Modify the `color_map` dictionary for custom terminal colors.
- **Notification channel:** Replace `https://ntfy.sh/gag-jim` with your own ntfy topic URL.

---

## 💡 Notes

- Ensure your terminal supports **ANSI color codes** for proper colored output.
- Stop the script anytime using `Ctrl + C`.

---

## 📄 License

This project is **open-source** and free to use.

---
Created by **Jim**

*Made with 🌿 and Python*

