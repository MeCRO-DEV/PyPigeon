# PyPigeon
PyPigeon - Securing Your Messages.

A tool to encrypt/decrypt your messages passing over any public chat application, such as Microsoft Teams, Skype, Slack, Whatsapp etc.

It encrypts your messages with AES256 and encodes it with Base64 so you can send it over any chat program. When the recipient receives it, PyPigeon can decode and decrypt it. It can also encrypt your sensitive information and save it to cloud such as OneNote, etc.

Features:
- Multiple layers of encryption with different passphrases
- AES algorithm with 256 bits key length

Usage:
- Install Python
- Create virtual environment (optional): python -m venv env
- Install dependencies: pip install -r requirements
- Run it: python PsPigeon.py

Dependencies:
- PyQt6
- PyCryptoDome

Screenshots:

![image](https://github.com/user-attachments/assets/0cb9d653-23b7-4286-8a40-dff92051769b)

![image](https://github.com/user-attachments/assets/da3c5be3-9959-41ce-b915-f6093808ba34)
