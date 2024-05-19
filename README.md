## Description

This project provides a simple tool to generate secure passwords and check their strength.

## Features

### Generate Passwords

- Prompts user for the length of the desired password (minimum 8 characters)
- Uses 4 functions to get random characters, includes: (uppercase, lowercase, numbers, symbols)
- Using `generate()` function it takes length of the password and generates random characters accordingly and returns an strong password.

### Check Password Strength

- Using `check()` function, it takes parameter password and check if the password is empty.
- In `check()` function, using Regular Expressions, it checks the strength of the password and prompts whether the password is strong, medium, or weak.

## Libraries

- Random (random): randomly selects characters from a set of specified characters that are stored in 4 different variables.
- Regular Expression (re): variables `strong_regex` and `medium_regex` that contain regular expression patterns, which are then matched with the given password to check the strength of the passwords.
- Tkinter (tkinter): used for the GUI of the application.
