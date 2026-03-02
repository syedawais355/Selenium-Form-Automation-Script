# Selenium Form Automation Script

A Python project demonstrating web form automation using Selenium WebDriver.  
The script navigates to a practice form page, fills text inputs, radio buttons, checkboxes, dropdown menus, handles alerts, and submits the form.

## Features

- Automated filling of a complete web form with predefined data
- Interaction with various HTML form elements (text fields, radio buttons, checkboxes, select menus)
- JavaScript alert handling using try-except
- Reusable helper function for cleaner and more maintainable code

## Prerequisites

- Python 3.8 or higher
- Google Chrome browser
- ChromeDriver matching your Chrome version  
  (download from: https://googlechromelabs.github.io/chrome-for-testing/)

## Installation

1. Clone the repository

   ```
   git clone https://github.com/syedawais355/Selenium-Form-Automation-Project.git
   cd Selenium-Form-Automation-Project
   ```

2. Create and activate a virtual environment (recommended)

   ```
   # macOS / Linux
   python -m venv venv
   source venv/bin/activate

   # Windows (Command Prompt)
   python -m venv venv
   venv\Scripts\activate

   # Windows (PowerShell)
   python -m venv venv
   .\venv\Scripts\Activate.ps1
   ```

3. Install dependencies

   ```
   pip install --upgrade pip
   pip install -r requirements.txt
   ```

## Usage

Run the script:

```
python main.py
```

The script will:
- Open a Chrome browser window
- Navigate to the practice form
- Fill all fields with test data
- Handle any JavaScript alert
- Submit the form
- Wait briefly and close the browser

## Demo

https://github.com/user-attachments/assets/dc448979-2bb9-473c-bfd3-471689d57a55

## Project Structure

```
Selenium-Form-Automation-Project/
├── main.py               Main automation script
├── requirements.txt      Project dependencies
└── README.md
```
