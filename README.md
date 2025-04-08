# Regular-Expression-Console-Based
🧾 User Information Input Validator

This is a Python-based command-line utility that collects user information such as **Name**, **Date of Birth**, **Email ID**, and **Mobile Number**, ensuring each input is strictly validated using regular expressions.

🎯 Project Motivation

Often in beginner projects or user-facing scripts, data validation is overlooked or implemented poorly. This simple utility demonstrates how to:

- Properly validate various types of user input using `regex`.
- Format user-friendly output after capturing data.
- Prevent incorrect data from entering your system.
- Apply basic Python programming practices like loops, conditionals, regex, and string manipulation.

📌 Features

- ✅ **Name validation:** Accepts only alphabetic characters and spaces.
- 📅 **DOB validation:** Accepts format `DD-MM-YYYY` and displays the month as a string.
- 📧 **Email validation:** Accepts Gmail addresses only (e.g., `example@gmail.com`).
- 📱 **Mobile number validation:** Accepts numbers in `XXX-XXX-XXXX` format.
- 📤 User inputs are formatted and printed cleanly after successful collection.

🧪 Sample Run

### Input:
```
Enter Your Name: Alice Johnson
Enter Date of Birth (DD-MM-YYYY): 01-12-2000
Enter Email ID: alice123@gmail.com
Enter Mobile Number (XXX-XXX-XXXX): 999-888-7777
```

### Output:
```
-----User Details-----
Name         : Alice Johnson
Date of Birth: 1-Dec-2000
Email ID     : alice123@gmail.com
Mobile       : 9998887777
```

---

🔧 Customization
| Feature | Description |
|--------|-------------|
🌐 Email Support | Allow domains beyond `gmail.com` like `yahoo.com`, `outlook.com` |
🌎 Country Codes | Add international number formats or Indian-specific format validation |
📊 Data Storage | Store data in a CSV, JSON, or even a database |
🎨 GUI Version | Use `Tkinter`, `PyQt`, or `Flask` for a visual interface |
🔐 Login System | Turn it into a basic sign-up form with username/password fields |

🚀 Future Enhancements

- Save validated input to a file (CSV/JSON)
- Add support for address input with pincode validation
- Add test cases for regex patterns
- Convert into a class-based design
- Web version using Flask or Django

📦 Requirements
- Python 3.x  
- No external dependencies — only uses built-in `re` module

