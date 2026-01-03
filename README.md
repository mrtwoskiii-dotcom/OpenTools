# 🛠️ Open Tools

A collection of lightweight, privacy-focused web utilities hosted entirely on GitHub Pages. No tracking, no backend, and no data collection.

## 🚀 Live Access
**[Click here to open the Toolbox](https://mrtwoskiii-dotcom.github.io/open-tools/)**

---

## 🧰 Included Tools

### 🔗 URL Cleaner & Tracker Stripper
Sanitize links before sharing them. This tool automatically identifies and removes common marketing trackers such as:
* **UTM Parameters** (`utm_source`, `utm_medium`, etc.)
* **Social Click IDs** (`fbclid`, `gclid`)
* **Email Tracking Tags** (`mc_eid`, `_hsenc`)

### 🔑 Password Suite
A dual-purpose security utility for managing credentials:
* **Generator:** Uses cryptographically secure random values (`window.crypto`) to create high-entropy 16-character passwords.
* **Strength Tester:** A real-time analysis tool that evaluates password complexity based on length, casing, numbers, and special characters.

---

## 🛡️ Privacy & Security
* **Zero Logs:** Since this is a static site, your data never leaves your browser.
* **Open Source:** The logic is fully transparent and viewable within this repository.
* **No Dependencies:** Built with vanilla JavaScript and Tailwind CSS for maximum speed and security.

---

## 📂 How to Add More
Each tool is contained within its own `.html` file. To add a new utility:
1. Create a new `tool-name.html` file.
2. Link it in the `index.html` dashboard.
3. Commit the changes.
