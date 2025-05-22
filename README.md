# Phishing_URL_Detector_for_Real_Time_Web_Security_Analysis

## 🌟 Overview

This project is a lightweight, browser-based tool designed to detect **phishing URLs** in real time using rule-based heuristics. It acts as a quick-access security layer for users before accessing potentially harmful websites.

---

## 🎯 Features

- 🚨 Real-time Phishing URL Detection
- 💻 Responsive UI with simple inputs and results
- 🛡️ Checks for known suspicious patterns, domains, and URL characteristics
- 📱 Works offline in any modern browser
- 🌈 Visually alerts users with color-coded results

---

## 🧠 How It Works

The detection is done using JavaScript logic, based on common phishing patterns. The URL is analyzed for:

- ❗ Use of IP addresses instead of domain names  
- 🔑 Presence of suspicious keywords like `login`, `secure`, `bank`, `verify`  
- 📦 Dangerous file extensions like `.exe`, `.zip`, `.scr`  
- 🔗 URL shorteners like `bit.ly`, `tinyurl.com`, etc.  
- 🚫 Long URLs, too many slashes, or hyphens in domains  
- 🧪 Nested or random-looking subdomains  
- 🕵️‍♂️ Unusual symbols like `@`, or `//` in the path  

If any red flags are found, a phishing warning is displayed.


---

## 💻 How to Run

### ✅ Option 1: Open Locally
1. Download or clone the project.
2. Open `index.html` in any modern browser.
3. Enter a URL and hit "Check URL".

### ⚙️ Option 2: Run via VS Code
1. Install the **Live Server** extension.
2. Open the folder in VS Code.
3. Right-click `index.html` → **Open with Live Server**.

---

### 🖼️ Sample Output 1
![Sample Output 1](https://github.com/Bhavanaviswanath/Phishing_URL_Detector_For_Real_Time_Web_Security_Analysis/blob/bcaf4fd8610848fb14070db923399bb814b6f73a/Sample%20output1.jpeg?raw=true)

### 🖼️ Sample Output 2
![Sample Output 2](https://github.com/Bhavanaviswanath/Phishing_URL_Detector_For_Real_Time_Web_Security_Analysis/blob/bcaf4fd8610848fb14070db923399bb814b6f73a/Sample%20output2.jpeg?raw=true)

### 🖼️ Sample Output 3
![Sample Output 3](https://github.com/Bhavanaviswanath/Phishing_URL_Detector_For_Real_Time_Web_Security_Analysis/blob/bcaf4fd8610848fb14070db923399bb814b6f73a/Sample%20output3.jpeg?raw=true)


---

## 🛠️ Technologies Used

- ✅ **HTML5** for structure
- 🎨 **CSS3** for styling
- 🧠 **JavaScript (Vanilla)** for real-time detection logic

---

## 🔮 Future Scope

- 🤖 Integrate actual ML models (Logistic Regression, Random Forest)
- 🌍 Use live threat databases (e.g., PhishTank API)
- 🧩 Turn into a browser extension
- 💬 Add logging and user feedback system

---

## 👩‍💻 Author

**Natuva Bhavana**  
📧 natuvabhavana@gmail.com   
🔗 [Hugging Face Profile](https://huggingface.co/Bhavvanna)

---


## 💡 Acknowledgment

This tool was created as part of a web security mini-project to demonstrate how simple heuristics and rules can be used to mitigate phishing attacks in real time.

---
