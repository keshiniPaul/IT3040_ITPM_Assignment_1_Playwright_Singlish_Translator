# IT3040_ITPM_Assignment_1_Playwright_Singlish_Translator
Transliteration Accuracy Testing using Playwright for ITPM Assignment 1 option 1 singlish translator.
IT23206496- Paul K.A

## Project Overview
This project tests the accuracy of the Chat Sinhala Transliteration feature available at:

https://www.pixelssuite.com/chat-translator

The goal is to identify scenarios where the system fails to correctly convert Singlish input into Sinhala output.

## Testing Approach
- 50 negative test cases were identified
- Covers all 24 Singlish input types (Appendix 1)
- Each test case was automated using Playwright
- Results are recorded in the provided Excel file

## Technologies Used
- Python
- Playwright
- OpenPyXL (Excel handling)

## Setup Instructions

### 1. Clone the repository

git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
### 2. Install dependencies
pip install -r requirements.txt
playwright install

## 3. Run the automation script
python test_automation.py --excel "Assignment 1 - Test cases.xlsx"

