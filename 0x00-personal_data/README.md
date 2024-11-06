# 0x00. Personal Data 🔒

![Python](https://img.shields.io/badge/Python-3.7-blue?style=flat-square&logo=python) ![Authentication](https://img.shields.io/badge/Authentication-PII_Management-green?style=flat-square&logo=security)

## 📖 Project Overview
This project involves handling and protecting **Personally Identifiable Information (PII)** using Python. You’ll work on implementing secure logging, encrypting sensitive data, and authenticating database connections to build a foundation in data security and privacy.

## 🎯 Learning Objectives
- 🕶️ **PII Obfuscation**: Implement log filters to obfuscate sensitive data.
- 🔑 **Password Encryption**: Use bcrypt to securely hash and validate passwords.
- 🗄️ **Database Authentication**: Securely connect to a database using environment variables.

## 🛠️ Technologies Used
- ![Python](https://img.shields.io/badge/Python-3.7-blue?style=flat-square&logo=python) **Python 3.7** on **Ubuntu 18.04 LTS**
- **Pycodestyle** (v2.5) for code formatting
- **bcrypt** for password hashing and verification

## 📋 Requirements
- Python files must be interpreted on **Ubuntu 18.04 LTS** using `python3` (version 3.7).
- Files must start with `#!/usr/bin/env python3`.
- Code should follow **Pycodestyle** guidelines (v2.5).
- Modules, classes, and functions should have meaningful documentation.
- All functions should be type annotated.

## 🚀 Installation

1. Install required packages:
    ```bash
    sudo apt-get install python3-bcrypt
    ```

2. Clone the repository:
    ```bash
    git clone https://github.com/Alogyn/alx-backend-user-data
    cd alx-backend-user-data/0x00-personal_data
    ```

## 📂 Project Structure
- **filtered_logger.py**: Implements log obfuscation and secure logging.
- **encrypt_password.py**: Contains functions for hashing and verifying passwords.
- **main.py**: Test file for executing and validating implemented features.

## 📝 Task Breakdown

1. **Regex-ing PII Fields** 🔍:
   - Write a function `filter_datum` to replace sensitive fields in log messages with a placeholder.

2. **Log Formatter** 📝:
   - Create a custom formatter `RedactingFormatter` to mask PII data in logs automatically.

3. **Creating a Logger** 🛠️:
   - Implement a `get_logger` function to set up a secure logger with a `StreamHandler` and PII obfuscation.

4. **Database Connection** 🔐:
   - Create a `get_db` function to securely connect to a database using credentials stored in environment variables.

5. **Reading and Filtering Data** 📊:
   - Implement a `main` function to retrieve and display database records with sensitive fields obfuscated.

6. **Password Encryption** 🔑:
   - Write a `hash_password` function to hash passwords with bcrypt.

7. **Password Verification** ✅:
   - Create an `is_valid` function to check if an input password matches the hashed password.

## 📌 Example Usage
```python
# Running the main script
./main.py
```

## 🌐 Resources
- [What Is PII, non-PII, and Personal Data?](https://piwik.pro/blog/what-is-pii-personal-data/)
- [logging documentation](https://docs.python.org/3/library/logging.html)
- [bcrypt package](https://github.com/pyca/bcrypt/)
- [Logging to Files, Setting Levels, and Formatting](https://www.youtube.com/watch?v=-ARI4Cz-awo)

## ⚖️ License
This project is licensed under the [ALX Software Engineering Program.](https://www.alxafrica.com/)
© 2024 ALX. All rights reserved.
