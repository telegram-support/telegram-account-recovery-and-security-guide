# Telegram Auth & Session Debugger

This toolkit is designed for developers to diagnose issues with Telegram's authentication flow. It helps identify why sessions are being terminated or why SMS codes are not reaching certain gateways.

## 🛠 Features
- **MTProto Debugging:** Detailed logs for connection timeouts.
- **Session Recovery:** Scripts to re-validate expired `.session` files.
- **Security Audit:** Check your current active sessions and 2FA status.

## 📖 Documentation
For a full guide on handling restricted accounts and bypassing common API errors, please refer to the **[Extended Documentation & Wiki](https://telegram.org/support)**.

## ⚠️ Requirements
Install the necessary dependencies before running the debugger:
`pip install -r requirements.txt`
