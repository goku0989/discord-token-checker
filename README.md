# discord-token-checker

## 🔐 Discord Token Checker & Bot Auto-Configurator

This tool allows you to **check Discord user tokens**, **retrieve account information**, **list associated bot applications**, and **automatically reset and configure bot settings** using Discord's API (v9). It's designed to help developers or bot managers handle multiple tokens and bots in bulk.

### ✅ Features

- **Token Validator**: Checks validity of Discord user tokens.
- **User Info Fetcher**: Retrieves detailed account info (username, email, phone, etc.).
- **Application Lister**: Lists all bot applications linked to the account.
- **Bot Token Resetter**: Automatically resets bot tokens and stores new ones.
- **Bot Configuration**: Auto-configures bot settings:
  - Enables `integration_public`
  - Disables `integration_require_code_grant`
  - Updates description and flags

### 📁 Files

- `main.py` — Place your user tokens here (one per line).
- `tokens.txt` — Generated file containing the newly reset bot tokens.

### ⚠️ Disclaimer

This tool uses **private/internal Discord APIs**, which may violate Discord’s Terms of Service. **Use at your own risk.** This project is for **educational and testing purposes only**.
![image](https://github.com/user-attachments/assets/72639a01-7324-4a48-875d-8d443e700e05)

