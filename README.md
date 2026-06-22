## Auto Job Applier for LinkedIn 🤖

An AI-assisted LinkedIn job application automation tool designed to streamline the job search process. The system automatically discovers relevant opportunities, fills application forms, answers screening questions, and simplifies the LinkedIn Easy Apply workflow.

## 🚀 Features

* Automated LinkedIn Easy Apply workflow
* Intelligent job discovery based on custom filters
* Automated form filling and question handling
* Resume and profile-based application support
* Configurable job title, location, and experience filters
* Stealth browser mode support
* Application history dashboard
* OpenAI, Gemini, and AI integration support
* Customizable search preferences
* Human-like interaction behavior through randomized actions

---

## 📋 Table of Contents

* Features
* Installation
* Configuration
* Usage
* Project Structure
* Dashboard
* Disclaimer
* License

---

## ⚙️ Installation

### Prerequisites

* Python 3.10 or later
* Google Chrome
* LinkedIn Account

### Install Dependencies

```bash
pip install undetected-chromedriver pyautogui setuptools openai flask-cors flask
```

### Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/auto-job-applier-for-linkedin.git
cd auto-job-applier-for-linkedin
```

### ChromeDriver

If `stealth_mode = True`, ChromeDriver installation is usually handled automatically.

For manual installation:

Download the ChromeDriver version matching your Chrome browser version and place it in the appropriate location.

---

# 🔧 Configuration

All configuration files are available inside the `config/` directory.

### personals.py

Configure personal information:

* Full Name
* Email
* Phone Number
* Address
* Work Authorization
* Experience Details

### search.py

Configure job search preferences:

* Job Titles
* Locations
* Remote / Hybrid Filters
* Experience Levels
* Keywords
* Blacklist Terms

### questions.py

Configure answers for application questions.

Examples:

* Notice Period
* Current Salary
* Expected Salary
* Sponsorship Requirements
* Work Authorization

### secrets.py

Configure:

* LinkedIn Credentials
* OpenAI API Key (Optional)
* Gemini API Key (Optional)

### settings.py

Configure automation settings:

* Stealth Mode
* Background Execution
* Randomized Click Delays
* Screen Awake Mode
* Application Safety Settings

---

# ▶️ Usage

Run the automation bot:

```bash
python runAiBot.py
```

Run the application history dashboard:

```bash
python app.py
```

Open:

```text
http://localhost:5000
```

---

# 📂 Project Structure

```text
Auto Job Applier for LinkedIn
│
├── config/
├── modules/
├── templates/
├── setup/
├── app.py
├── runAiBot.py
└── README.md
```

---

# 📊 Dashboard

The dashboard provides:

* Applied Jobs History
* Application Tracking
* Status Monitoring
* Application Logs

Access through:

```text
http://localhost:5000
```

---

# 🛠 Technologies Used

* Python
* Selenium
* Undetected ChromeDriver
* PyAutoGUI
* Flask
* OpenAI API
* Google Gemini API
* HTML
* JavaScript

---

## ⚠️ Disclaimer

This project is intended for educational, automation, and productivity purposes.

Users are responsible for ensuring compliance with LinkedIn's Terms of Service and all applicable laws and regulations.

Use this software responsibly and at your own risk.

---

## 📄 License

This repository follows the license provided within the project.

Please review the LICENSE file before redistributing or modifying the software.

---

## 👨‍💻 Maintained By

### Ajay Sagar

B.Tech Computer Science Engineering

AI • Machine Learning • Full Stack Development

---

### Version

Current Customized Edition
