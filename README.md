# Playwright-project-repository

# IT3040 Assignment 1 – Singlish Transliteration Testing

## Prerequisites
- Python 3.11 or 3.12
- Google Chrome

## Installation
pip install -U pip
pip install playwright openpyxl
playwright install

## How to Run
cd D:\test_automation
python test_automation.py --excel "test_automation/Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
