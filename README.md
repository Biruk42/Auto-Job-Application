# LinkedIn Job Application Bot

## Overview
This Python script automates the job application process on LinkedIn by logging into your LinkedIn account, navigating to the job listings page, and applying to each job listing.

## Requirements
- Python 3.x
- `selenium` library
- Chrome WebDriver (ChromeDriver)

## Installation
1. Clone this repository to your local machine.
2. Install the `selenium` library using pip:
    ```shell
    pip install selenium
    ```
3. Download the Chrome WebDriver (ChromeDriver) from the official website: [ChromeDriver Downloads](https://sites.google.com/a/chromium.org/chromedriver/downloads).
4. Set the `chrome_driver_path` variable in the script to the path where you saved the ChromeDriver executable.

## Configuration
- Replace the placeholders in the script with your LinkedIn email, password, and phone number.
- Update the LinkedIn URL in the script to the URL of the LinkedIn login page.

## Usage
1. Run the script by executing:
    ```shell
    python linkedin_job_bot.py
    ```
2. The script will automatically log in to your LinkedIn account, navigate to the job listings page, and apply to each job listing.
3. It will skip jobs where you have already applied or jobs that are no longer accepting applications.

## Disclaimer
This script is for educational purposes only. Use it responsibly and ensure compliance with LinkedIn's terms of service. Automated job applications should be used judiciously to avoid spamming employers.

## Note
- Ensure that you have a stable internet connection while running the script.
- Be cautious when automating actions on websites like LinkedIn to avoid account suspension or other consequences.

## Contributions
Contributions are welcome! If you find any issues or have suggestions for improvement, feel free to open an issue or create a pull request.
