# Internet Speed Twitter Bot

## Overview
This Python script automates the process of measuring internet speed using "Speedtest.net" and then tweeting at the internet service provider (ISP) if the speed is below the promised threshold. It's a practical application of Selenium for web automation, handling tasks like navigating websites, clicking buttons, and filling out forms programmatically.

## Output


https://github.com/sarvesh-2109/Twitter-Bot/assets/113255836/4eb5c4f3-4fcf-49cf-bffe-a4a5fb82b56a



## Features
- Automatically navigates to Speedtest.net and initiates an internet speed test.
- Waits for the test to complete and fetches the download and upload speeds.
- Logs into Twitter and composes a tweet to the ISP if the internet speed is below the promised limits.
- Fully automated with minimal manual intervention required.

## Dependencies
- Python
- Selenium WebDriver
- ChromeDriver

## Setup
1. **Install Python:** Make sure Python is installed on your system. If not, download and install it from [python.org](https://www.python.org/).

2. **Install Selenium:** Run `pip install selenium` in your terminal or command prompt to install the Selenium package.

3. **Download ChromeDriver:** Download the version of ChromeDriver that matches your Chrome browser version from [ChromeDriver - WebDriver for Chrome](https://sites.google.com/a/chromium.org/chromedriver/). Extract it to a known location on your system.

4. **Update Script Constants:** Modify the `TWITTER_USERNAME`, `TWITTER_PASSWORD`, `PROMISED_DOWN`, and `PROMISED_UP` constants in the script to match your Twitter credentials and promised internet speed thresholds.

## Usage
1. Open a terminal or command prompt.
2. Navigate to the directory containing the script.
3. Run the script with `python main.py`.
4. The script will automatically perform the speed test, check against the promised speeds, and tweet at your ISP if necessary.

## Note
- The `time.sleep(45)` in `get_internet_speed` is used to provide sufficient time for the speed test to complete. This may need adjustment based on your internet speed.
- Ensure your Chrome browser is updated to the latest version compatible with the downloaded ChromeDriver.
- Always use this script responsibly and ensure it complies with the terms of service for Speedtest.net, Twitter, and your ISP.

## Disclaimer
This script is intended for educational purposes only. It demonstrates the capabilities of Selenium for browser automation. Users should ensure they comply with the terms of service of the involved websites and use this script ethically and responsibly.
