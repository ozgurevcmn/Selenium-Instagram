# Instagram Followers Scraper (Outdated)

This Python script utilizes Selenium WebDriver to automate the process of scraping followers from an Instagram account. It logs into the Instagram website, navigates to the user's profile page, and extracts the list of followers.

## Description
The script interacts with the Instagram website using Selenium WebDriver, a tool for automating web browser interactions. It performs the following steps:
- Opens a Firefox browser window and navigates to the Instagram login page.
- Logs into the user's Instagram account using the provided username and password.
- Navigates to the user's profile page and clicks on the followers button to view the list of followers.
- Scrolls through the followers list to load all followers dynamically.
- Retrieves the usernames of all followers and saves them to a text file named "followers.txt" in UTF-8 encoding.

## Usage
Before running the script, make sure you have installed Python and the required dependencies (`selenium` and `geckodriver` for Firefox). Additionally, provide your Instagram username and password in a separate Python module named `loginInfo.py`, as shown below:
```python
# loginInfo.py
username = "your_instagram_username"
password = "your_instagram_password"

