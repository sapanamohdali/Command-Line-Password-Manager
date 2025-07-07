# Command-Line-Password-Manager
Stores and retrieves encrypted passwords with a master key. Uses getpass, keyring, and secure hashing for authentication.
“Command-Line Password Manager”


A secure Python CLI application that stores and retrieves encrypted passwords using a master key. Built with AES encryption and `getpass`, it keeps your credentials safe and local.

Features
-  Master password authentication
-  Remember multiple site credentials securely
-  AES encryption using Fernet (`cryptography`)
-  Stores data in a local JSON vault file
-  View saved passwords only after successful login
-  Easy to use, secure, and portable


Technologies Used
- Python 3.x
- `cryptography` (for AES encryption)
- `getpass` (for secure password entry)
- `json` (for local data storage)

Getting Started
git clone https://github.com/your-username/cli-password-manager.git
cd cli-password-manager
python -m venv .venv
.venv\Scripts\activate   # Or source .venv/bin/activate (Linux/Mac)
pip install cryptographypython password_manager.py

Install dependencies
pip install cryptography

Run the application
main.py
