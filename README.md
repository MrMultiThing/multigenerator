# multigenerator

A lightweight terminal utility for generating strong and random passwords.

## Features

* Secure password generation using Python's `secrets` module
* Password lengths from 16 to 32 characters
* Includes uppercase letters, lowercase letters, numbers, and symbols
* Interactive terminal interface
* Built-in error handling with dedicated error codes
* Generate multiple passwords without restarting the program

## Requirements

* Python 3.x

No additional dependencies are required.

## Installation

```bash id="0e3s4x"
git clone https://github.com/MohssineX/multigenerator.git
cd multigenerator
```

## Usage

Run the program:

```bash id="cwsv9u"
python multigenerator.py
```

If your system uses `python3`:

```bash id="7njdgl"
python3 multigenerator.py
```

## How It Works

1. Start the program
2. Enter a password length between **16** and **32**
3. A secure random password will be generated instantly
4. Choose:

   * `r` to generate another password
   * `q` to quit

## Password Composition

Generated passwords are created using a combination of:

* Uppercase letters (`A-Z`)
* Lowercase letters (`a-z`)
* Numbers (`0-9`)
* Special characters (`!@#$%^&*-_=+`)

The program uses Python's `secrets` module to ensure cryptographically secure randomness.

## Error Codes

| Code   | Description                                                   |
| ------ | ------------------------------------------------------------- |
| err101 | Invalid input (letters or symbols entered instead of numbers) |
| err102 | Invalid password length (must be between 16 and 32)           |
| err103 | Invalid action (must be `r` or `q`)                           |

---

## License

This project is licensed under the **[GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.html)**

---

## Author

**Mohssine :**
[ https://github.com/MohssineX](https://github.com/MohssineX)

---

## 🐱 Special Thanks

A special thanks to mimi — the legendary, the great, the gentle cat.
