# Password-Manager 🔒
A simple and secure Password Manager built in Python. This project allows users to securely store, retrieve, and manage passwords for different websites using encryption.

## Features 📋
- Secure Encryption: Passwords are encrypted using the cryptography library.
- Password Storage: Store passwords securely for multiple websites.
- Retrieve Passwords: Easily retrieve usernames and passwords for stored websites.
- List Websites: View all websites for which passwords are stored.

## Requirements 🛠️
- Python 3.x
- Libraries:
cryptography

## Example Usage 💡
- Add Password: Enter a website, username, and password to securely store.
- Retrieve Password: Provide the website name to retrieve the stored username and password.
- List Websites: View a list of all stored websites.

## Security Notes ⚠️
The current implementation uses a fixed salt (b'salt_'). For production use, consider generating a unique random salt for each user and securely storing it.
Ensure the master password is strong and not easily guessable.

## Contributing 🤝
Contributions are welcome! Feel free to fork the repository and submit pull requests.

## License 📜
This project is licensed under the MIT License. See the LICENSE file for details.

