# BruteForce Script

A Python-based script for performing a brute force attack to find the correct password for a given username on a specified webpage. This script attempts to log in using a list of passwords and identifies the correct password based on the website's response.

## Features

- Attempts to log in with a list of passwords for a specified username
- Supports optional cookie value for authenticated requests
- Customizable to handle both GET and POST requests based on the target website
- Identifies successful login attempts based on a user-defined failure string

## Requirements

- Python 3.x
- `requests` library (`pip install requests`)

## Usage

1. **Clone the Repository:**

    ```sh
    git clone https://github.com/yourusername/bruteforce-script.git
    cd bruteforce-script
    ```

2. **Run the BruteForce Script:**

    ```sh
    python bruteforce.py
    ```

3. **Input the Required Information:**

    - **Page URL**: Enter the URL of the login page.
    - **Username**: Enter the username for the account you want to brute force.
    - **Password File**: Provide the path to a file containing a list of passwords to try.
    - **Login Failed String**: Enter a string that appears in the response when login fails (e.g., "invalid credentials").
    - **Cookie Value (Optional)**: Provide a cookie value if necessary for the login request.

## Example

```sh
[+] Enter Page URL: http://example.com/login
[+] Enter Username For The Account To Bruteforce: admin
[+] Enter Password File To Use: passwords.txt
[+] Enter String That Occurs When Login Fails: Invalid username or password.
Enter Cookie Value(Optional):
```

# Customization
## Request Method
The script can be customized to use either GET or POST requests based on the target website's login mechanism. By default, the script uses POST requests, but you can modify the cracking function to use GET requests if needed.

## Request Parameters
The request parameters in the script (e.g., username, password, Login) should be modified according to the target website's login form field names.

# Disclaimer
This tool is intended for educational purposes only. Unauthorized access to computer systems is illegal and unethical. Always ensure you have explicit permission from the system owner before using this tool.
