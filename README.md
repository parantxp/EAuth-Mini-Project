# EAuth-Mini-Project
E-Authentication System Using QR Code and OTP

This project is a two-factor authentication system that allows users to log in through either QR code scanning or OTP verification. Users register by entering basic details such as name, mobile number, email, and gender, which are stored securely in a database. After registration, they can choose their preferred login method.

Features

Dual Authentication Options:
Users can authenticate using either a QR code or a one-time password.

User Registration:
The system collects and securely stores user details during registration.

QR Code Login:
When users select QR login, the system generates a unique QR code linked to their mobile number and sends it to their registered phone. The webcam scans the QR code using Instascan. If the scanned mobile number matches the database record, access is granted.

OTP Login:
When users select OTP login, the system generates a random OTP through the Fast2SMS API and sends it to the registered mobile number. Access is granted after successful OTP verification.

Technologies Used

Frontend: HTML, CSS, JavaScript
Backend: PHP
QR Code Scanning: Instascan
OTP Service: Fast2SMS API
QR Code SMS Service: Sinch API

Prerequisites

Web server with PHP support
Webcam for QR scanning
Mobile phone for OTP verification
Fast2SMS API key
Sinch API key
