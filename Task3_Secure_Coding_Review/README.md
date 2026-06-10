🔐 Secure Coding Review

📌 Project Description

This project was completed as part of the CodeAlpha Cyber Security Internship. The objective of this task is to review source code, identify security vulnerabilities, analyze associated risks, and recommend secure coding practices.


🎯 Objectives

✅ Identify security vulnerabilities in source code

✅ Analyze potential security risks

✅ Learn secure coding practices

✅ Improve application security


🛠️ Technologies Used

🔹 Python

🔹 GitHub

🔹 Microsoft Word / PDF


🔍 Code Reviewed

username = input("Enter Username: ")
password = input("Enter Password: ")

if username == "admin" and password == "admin123":
    print("Login Successful")
else:
    print("Login Failed")

🚨 Vulnerabilities Identified

🔴 Hardcoded Credentials

❌ Username and password are directly stored in the source code.

🔴 Weak Password

❌ The password "admin123" is easy to guess and vulnerable to attacks.

🔴 Plain Text Password Handling

❌ Passwords are stored and compared in plain text format.

🟠 Lack of Input Validation

❌ User inputs are accepted without validation or sanitization.


🛡️ Security Recommendations

✅ Remove hardcoded credentials from source code

✅ Use strong and complex passwords

✅ Store passwords using secure hashing algorithms

✅ Validate and sanitize user inputs

✅ Implement Multi-Factor Authentication (MFA)

✅ Conduct regular security reviews and testing


📂 Project Files

📄 vulnerable_code.py

📄 Secure_Coding_Review_Report.pdf

📘 README.md


📖 Learning Outcomes

✔️ Understanding secure coding practices

✔️ Identifying software vulnerabilities

✔️ Risk assessment and mitigation

✔️ Improving application security


🏁 Conclusion

The code review identified several security weaknesses that could lead to unauthorized access and security breaches. Applying secure coding practices and recommended security controls can significantly improve the security and reliability of the application.


AUTHOR
Muskan Raj