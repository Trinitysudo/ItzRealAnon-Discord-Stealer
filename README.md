## Info 📂

   ❗ **Disclaimer!**: This project is maintained by one person and is updated frequently. As of 01/16/2025, please check the `crash.log` file for any errors, and feel free to submit feature requests or bug reports. Enjoy!

## Features ℹ️

   This bot is designed to gather various pieces of information from a target system. It is important to note that this tool is created for educational purposes only.

   🔵 **Information Acquisition:**

   *   **Discord Information:**
      * User token
      * User password (Note: This is not directly retrievable; it is based on saved tokens.)
      * User email (if available through Discord's API)
   *   **Browser Data:**
      * Cookies (exported as Netscape formatted file)
      * Saved passwords (decrypted where possible)
      * Browsing history
   *  **Game Data:**
      * Minecraft session information
      * Roblox cookie
   *   **System Information:**
      *   System architecture
      *   CPU and GPU Names
      *   Installed antivirus software/VPNs
      *   Installed libraries
      *   List of running tasks
      *   User account details (username, email)
      *   Hardware specifications (CPU, GPU, RAM, disk space)
      *   Microsoft accounts (username and login status)
    *   **Location & Network:**
      *  Local IP address
      *  Physical address (street, city, state, country when available)
      *  Internet service provider
      *  WiFi information (if available)
      *  MAC address
      *  Hardware ID (HWID)
   *   **Screenshot:**
      *  Desktop screenshot (saved as a PNG file)
   *  **Clipboard**
      * Displays the content of the clipboard

## Usage 🔧

   💻 **Command List** 🧑‍💻
      /ip: Display IP configuration.
   /shutdown: Shut down the computer.
   /tasks: Upload running tasks.
   /upload: Upload a file to the bot.
   /download: Download a file from the bot.
   /cookies: Export browser cookies.
   /clear: Clear channel messages.
   /tokens: Retrieve Discord tokens.
   /dir: Browse Directories.
   /clipboard: Displays the host's clipboard.
   /screenshot: Take a screenshot.
   /systeminfo: Displays system information, including user details, AV/VPNs, location, CPU, GPU, and Microsoft accounts
   
## Installation/Guide 📘

1.  Ensure you have Python installed. You can download it from [python.org](https://www.python.org/). ⬇️

2.  Install the required dependencies using pip: ⬇️

   ```bash
     pip install discord.py python-dotenv cryptography pyautogui geopy wmi
   ```

3.  Edit the `.env` file and set the `BOT_TOKEN` variable with your bot token. 🗄

4.  Navigate to the directory where your files are located (replace `C:\Users\User\downloads\ItzRealStealer` with your actual path): 📂

    ```bash
       cd C:\Users\User\downloads\ItzRealStealer
    ```

5.  Run the bot and check for any errors: 🤖

   ```bash
      python bot_commands.py
   ```

## License 🌍

[Free use, but please use responsibly. You can fork it or create your own derivative works.]

---

## 🔴 **Disclaimer**

**This project is intended for educational and research purposes ONLY. It is designed to demonstrate potential vulnerabilities and dangers related to data exfiltration. Use it responsibly and ethically, with explicit consent. Misuse of this code could lead to severe legal and ethical consequences.**

**Do not use this tool to target individuals or systems without their explicit permission. Always adhere to ethical guidelines and legal frameworks when using this code.**
