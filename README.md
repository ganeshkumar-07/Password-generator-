# Password-generator-


A simple command‑line Python program that generates a random password using letters, digits, and special characters.  

# Features

- Asks the user how long the password should be.
- Uses uppercase letters, lowercase letters, digits, and symbols: `!@#$%^&*()`.
- Randomizes the character order before printing the final password.
- Lets the user decide whether to generate a password or exit the program.

# How It Works

1. Imports the `string` and `random` modules.
2. Creates a list of characters from:
   - `string.ascii_letters` (A–Z, a–z)  
   - `string.digits` (0–9)  
   - A set of special characters `!@#$%^&*()`
3. When the user chooses to generate a password:
   - Asks for the desired length.
   - Randomly picks characters from the list using `random.choice`.
   - Shuffles the selected characters.
   - Joins them into a single string and prints the password.
4. If the user chooses not to generate a password, the program ends.

# Requirements

- Python 3.x

No external libraries are needed; only the standard library modules `string` and `random` are used.

# Usage

1. Save the script as `password_generator.py`.
2. Open a terminal or command prompt in the folder where the file is saved.
3. Run:

4. When prompted:

- Enter `Yes` to generate a password.
- Enter `No` to exit.

5. If `Yes`:
- Enter the desired password length when asked (e.g., `12`).
- The generated password will be printed to the screen.

# Example
Do You Want To Generate A Password? (Yes/No): Yes
How Much Long Password You Need: 12
H7s@P9f!K3aL

# Notes

- Entering something that is not a number for the length will cause an error.
- You can customize the character set by editing the `characters` list in the code.

