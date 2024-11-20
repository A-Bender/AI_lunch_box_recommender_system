# Lunch_Box_Recommender_System

This Python script  provides the user with a weekly list for grocery shopping and recipes from their local supermarket.


[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/cajjster/lunch_box_planner.svg)](https://github.com/cajjster/lunch_box_planner/stargazers)
[![Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://your-live-demo-link.com)

---

## Table of Contents

1. [About the Project](#about-the-project)
2. [Getting Started](#getting-started)
3. [Usage](#usage)
4. [Features](#features)
5. [License](#license)

---

## About the Project

Summary:
- This script saves the user time and effort by allowing them to instantly put together a list for grocery shopping and recipes on a weekly basis.
- It collects weekly offers from ICA which is put into a list and generates recipes for the user.
- The shopping list and recipes are saved into text files. 
- it uses Selenium to automate the browser and Bautiful Soup for HTML parsing.
- 
Include relevant screenshots or a demo GIF:
![image](https://github.com/user-attachments/assets/5a7d7fd9-ee9f-462b-b371-003617959367)

---

## Getting Started

Step-by-step instructions to get a local copy running.
1. Create OPENAI API KEY - at (https://platform.openai.com/)
2. Create Twilio account - acquire Twilio phone number, Account SID, Auth token - (twilio.com)
4. Set up virtual environment
5. In an .env file, set your variables for: account token, account sid, twilio number, your phone number and API key
6. 

### Prerequisites

List tools and dependencies needed:
- Python 3.10+
- Git
- Google Chrome
- Twilio for account credentials
- OPENAI for API Key
- pippipenv install python-dotenv
- Libraries and tools:
    from selenium import webdriver
    from selenium.webdriver.common.by import By
    from selenium.webdriver.support.ui import WebDriverWait
    import requests
    from bs4 import BeautifulSoup
    from openai import OpenAI
    from twilio.rest import Client
    from dotenv import load_dotenv
    import os

### Installation

# Clone the repo
git clone https://github.com/yourusername/repo.git

# Navigate to the project directory
cd repo

# Install dependencies
pip install -r requirements.txt

```


## License

Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgments

If there are any
