# Password Maker

A flexible Python script for generating secure, customizable passwords and saving them to a file.

## Features

- Choose the password length.
- Select which character sets to include (letters, digits, punctuation).
- Secure random generation using Python’s `secrets` module.
- Saves the generated password to `generated_password.txt`.

## Requirements

- Python 3.6 or higher.

## Usage

1. **Clone or download** this repository.
2. Make sure you have Python installed.
3. Run the script:
   ```
   python PasswordMaker.py
   ```
4. Follow the prompts:
   - Enter the desired password length (must be a positive integer).
   - Choose whether to include letters, digits, and/or punctuation by responding with `y` (yes) or `n` (no) to each prompt.
5. The generated password will be displayed and saved to `generated_password.txt` in the same folder.

## Example

```
Enter password length (positive integer): 16
Include letters? (y/n): y
Include digits? (y/n): y
Include punctuation? (y/n): n
Generated password: iFvKq7B8hJmWdX2L
Password saved to generated_password.txt
```

## Error Handling

- If you enter an invalid value (e.g. a non-integer or a number less than or equal to zero), the script will display an error message and exit.
- At least one character set (letters, digits, punctuation) must be selected.

## Notes

- The script uses the `secrets` module for secure random password generation.
- The password is written to `generated_password.txt` in the script’s directory.
