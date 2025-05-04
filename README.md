# 🔐 Password Strength Checker (Python)

This is a simple Python script that evaluates the strength of a user-provided password based on multiple criteria, and provides feedback to help improve it. It's a handy utility for ensuring secure password practices.

## 🚀 Features

- Checks password strength based on:
  - Minimum length (8 characters)
  - At least one uppercase letter
  - At least one lowercase letter
  - At least one digit
  - At least one special character (e.g., !@#$%^&*)
- Returns a strength level:
  - Very Strong 💪
  - Strong 🔐
  - Moderate 🛡️
  - Weak ⚠️
  - Very Weak ❌
- Provides suggestions to improve weak passwords

## 🧾 How It Works

The script uses Python's `re` module (Regular Expressions) to validate password criteria. Based on how many criteria the password satisfies, it assigns a strength level and optionally returns suggestions.
