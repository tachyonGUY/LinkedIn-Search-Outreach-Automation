# LinkedIn Profile Discovery & Connect Automation
Automated LinkedIn workflow using Selenium, Edge DevTools Protocol, and Python.

![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)
![Selenium](https://img.shields.io/badge/Selenium-Automation-green.svg)
![Edge DevTools](https://img.shields.io/badge/Edge-DevTools-blue.svg)
![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)

---

## 📌 Overview  
This project is an advanced LinkedIn automation engine built on:

- Selenium WebDriver  
- Microsoft Edge Remote Debugging (DevTools Protocol)  
- Dynamic pagination logic  
- XPath-based UI interaction  
- Clean browser lifecycle & session control  

The tool allows you to:

- Perform automatic LinkedIn search  
- Apply the **People** filter  
- Extract unique profile URLs across multiple pages  
- Send connection requests automatically  
- Run batch-processing workflows  
- Operate through your real logged-in Edge browser session  

Designed for productivity, recruiter workflows, and research use cases.

---

## 🚀 Features

### 🔹 Automated Edge Debugging  
Uses Microsoft Edge with `--remote-debugging-port=9222`, letting Selenium attach to your already logged-in session.

### 🔹 Intelligent Search Automation  
Automates keyword search, waits for results, and triggers next steps safely.

### 🔹 Dynamic Pagination  
Iterates through results pages until no new profiles appear.

### 🔹 Clean Profile URL Extraction  
Removes unnecessary query parameters and deduplicates results.

### 🔹 Automated Connection Requests  
Scrapes profile names and sends connection requests using precise aria-label detection.

### 🔹 Process-Safe Browser Handling  
Only kills debug Edge instances — never your normal browser.

### 🔹 Batch Mode  
Scraped profile URLs are processed one by one with random delays.



