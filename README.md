# Accenture Testing Phase

## Overview

This project contains code and tests for validating email formats and password strength using Python. It also includes unit tests for verifying the correctness of the functions that check credentials (email and password). The project leverages `pytest` for testing.

## Project Structure

- **main.py**: Contains the functions to validate email and password formats.
- **testrunner.py**: Contains unit tests for the functions in `main.py`.
- **pyproject.toml**: Project configuration file using Poetry for dependencies.
- **replit.nix**: Configuration file for the Replit environment.

## Features

- **Email Validation**: Uses regular expressions to validate email formats.
- **Password Strength Checker**: Verifies if a password contains at least one uppercase letter, one digit, and is at least 7 characters long.
- **Password Matching**: Checks if two passwords are equal.
- **Credential Checker**: Verifies both email and password simultaneously.

## Installation

### Prerequisites

- Python 3.8 or above
- Poetry (for dependency management)

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/username/Accenture-Testing-Phase.git
   cd Accenture-Testing-Phase


2. Install dependencies (use the appropriate command for your package manager, e.g., `npm`, `pip`, etc.):
    ```bash
    poetry install
    ```

3. Configure the environment variables as required (add details if there are any `.env` or config files to be set up).

## Usage

1. Run the application & Tests:
    ```bash
    poetry run pytest
    ```
2. You can use the main.py file to check email and password validity by calling the respective functions:
  ```python
from main import check_credentials

email = "test@example.com"
psw1 = "Password123"
psw2 = "Password123"

if check_credentials(email, psw1, psw2):
    print("Valid credentials")
else:
    print("Invalid credentials")
```
3. The test cases are located in testrunner.py. You can run all the tests with:
```bash
poetry run pytest testrunner.py
```
##Testing
The project includes tests for email validation, password strength, and password matching. Here are a few examples:

1)test_email1:Validates a proper email.           
2)test_check_psw1: Tests a valid password with uppercase, lowercase, and digits.     
3)test_psw_equal1: Checks that two equal passwords return True.      
4)test_check_credentials1: Validates both correct email and password.       


## Contributing

Feel free to contribute by submitting issues or pull requests. For significant changes, please discuss with the team before making modifications.

## License

This project is licensed under the [MIT License](LICENSE).
### Contact
For more information, please contact Zai14 through his Socials:
 [![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/Za.i.14) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/zai14) [![X](https://img.shields.io/badge/X-black.svg?logo=X&logoColor=white)](https://x.com/Za_i14) [![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?logo=YouTube&logoColor=white)](https://youtube.com/@Za.i.14) [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:ZaidShabir67@gmail.com) 
.

 
