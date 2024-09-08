# Python-Project-Otp-Verification-System-via-Email

# Introduction
This project implements an OTP (One-Time Password) Verification System that enhances security for user authentication processes like online banking or account verification. The system generates a 6-digit OTP, sends it via email, and verifies it upon user input.

# Features
OTP Generation: Generates a 6-digit OTP using Python's random module.
Email Delivery: Sends the OTP securely to the user's email via the smtplib and MIME modules.
OTP Verification: Users input the OTP they receive, which the system verifies.
Error Handling: The system manages incorrect OTP entries, limiting retries to 3 attempts.
OTP Expiry: Ensures the OTP expires after 60 seconds to enhance security.
Optional GUI: A Tkinter-based GUI for improved user experience.

# Project Requirements
Python 3.x
Libraries:
smtplib
email.mime
random
Tkinter (for GUI)

# System Architecture
OTP Generation: Generate a random 6-digit OTP.
Send OTP via Email: Securely send the OTP using SMTP.
User Input: The user receives the OTP and enters it into the system.
OTP Verification: The system compares the input OTP with the generated one.
Error Handling: If the OTP is incorrect, the user has 3 attempts. OTP expires after 60 seconds.

# Testing
Tested with valid and invalid OTPs.
Tested OTP expiry after 60 seconds.
Limited the user to 3 attempts for wrong OTP entries.

# Future Enhancements
Add the ability to send OTPs via SMS.
Improve the GUI with additional features for a better user experience.

# Conclusion
The OTP Verification System provides a secure method of user authentication by generating, sending, and verifying one-time passwords. Its robust error handling and user-friendly interface make it a reliable tool for securing digital access.

