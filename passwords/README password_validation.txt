# Password Validation Script

## Overview
This JavaScript script validates an array of passwords based on a predefined pattern. It checks whether each password meets the specified criteria and logs whether each password is valid or invalid.

## Features
### 1. Password Validation
The script validates passwords using a regular expression (`regex`). The validation criteria include:
- The password must be between **8 and 20 characters** long.
- The password must only contain **uppercase letters (A-Z), lowercase letters (a-z), and numbers (0-9)**.

### 2. Iterating Over a List of Passwords
The script:
- Iterates through an array of sample passwords.
- Checks each password against the validation regex.
- Logs whether each password is valid or invalid.

## Code Explanation
- **`passwords`**: An array of sample passwords to validate.
- **`validatePasswords(passwords)`**: Function that checks each password using a regular expression.
- **`regex = /^[a-zA-Z0-9]{8,20}$/`**: Regular expression ensuring passwords meet the specified criteria.
- **`console.log()`**: Outputs the validation results.

## Usage
1. Open your web browser.
2. Go to the inspect section by right clicking on a blank area and clicking inspect. 
3. Open the browser's developer console and execute the script.
4. The output will indicate whether each password is valid or invalid.

## Example Output
```
Password123 is valid.
short is invalid.
ValidPass123 is valid.
too_long_password_example is invalid.
12345 is invalid.
```

## Notes
- The script does not enforce special character or symbol requirements.
- The regex can be modified to include additional password strength rules.

## Author
This script is intended for educational purposes to demonstrate JavaScript regex-based password validation.

