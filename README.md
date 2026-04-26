User Registration System (Python)
A simple and educational Python project that demonstrates how to build a basic user registration workflow using validation logic, exception handling, and in‑memory data storage.

🚀 Project Overview
This User Registration System simulates the core logic behind creating new user accounts. It validates user input (name, email, password), checks for duplicates, and stores successful registrations in memory. Failed attempts are logged with detailed error messages.

The project also includes a built‑in test suite that runs several registration scenarios to showcase both successful and failed outcomes.

🧩 Features
✔️ Input Validation
Name must contain at least 3 characters

Email must include @ and .

Password must:

Be at least 8 characters long

Contain at least one uppercase letter

Contain at least one digit

✔️ Duplicate Email Detection
Prevents users from registering with an email that already exists in the system.

✔️ Exception Handling
Validation errors are raised and captured cleanly, ensuring the program continues running while logging failures.

✔️ In‑Memory Storage
registered_users list stores successful registrations

failed_registrations list stores failed attempts with error messages

✔️ Test Suite Included
The run_tests() function demonstrates:

Successful registrations

Duplicate email handling

Invalid name, email, and password cases

📁 Project Structure
Code
├── validation functions
├── registration logic
├── simulated in-memory database
└── test runner
Everything is contained in a single Python file for simplicity and clarity.

🧪 How to Run
Clone the repository:

bash
git clone <your-repo-url>
Run the script:

bash
python user_registration.py
View the output of:

Successful registrations

Failed registrations

Error messages

🎯 Learning Objectives
This project helps you practice:

Writing clean, modular Python functions

Designing validation rules

Using exceptions effectively

Simulating simple data storage

Structuring small Python projects

Testing logic with sample inputs

🔮 Future Enhancements (Optional Ideas)
Add regex‑based email validation

Hash passwords before storing

Replace in‑memory lists with SQLite or JSON storage

Build a CLI or GUI interface

Add unit tests using pytest

📜 License
This project is open‑source and available under the MIT License.

If you want, I can also help you:

Add badges (Python version, license, etc.)

Write a CONTRIBUTING.md

Create a project logo or banner

Turn this into a more advanced version with file/database storage
