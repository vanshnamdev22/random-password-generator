Random Password Generator
A simple Python script that generates strong, secure passwords using letters, digits, and special characters.

🚀 Features
Generates random passwords of custom length

Uses uppercase, lowercase, digits, and punctuation

Input validation for robustness

Easy to use in terminal or integrate in other projects

🧰 Requirements
Python 3.x

No additional libraries required — uses only Python’s built-in random and string modules.

▶️ Usage
Run the script:
bash
Copy code
python password_generator.py
Replace password_generator.py with the actual filename if different.

Sample interaction:
bash
Copy code
Enter the desired password length: 16
Generated password: V@B6d!pTz3L$k#X2
⚙️ How It Works
Combines:

string.ascii_letters (A–Z, a–z)

string.digits (0–9)

string.punctuation (!, @, #, etc.)

Randomly selects characters to match the specified length

Handles invalid or non-integer input gracefully
