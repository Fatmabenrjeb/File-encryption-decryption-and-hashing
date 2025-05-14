# Secure File Processing Web Application

This project is a secure web application that allows users to encrypt, decrypt, hash, digitally sign, and verify the signature of files. Built using Django and Python, the app ensures file confidentiality, integrity, and authenticity through a simple and user-friendly interface.

## 🔐 Features

- **Encryption & Decryption**
  - Symmetric (AES)
  - Asymmetric (RSA)
- **Hashing**
  - SHA-256 for file integrity verification
- **Digital Signature**
  - File signing using RSA private key
- **Signature Verification**
  - Validates file authenticity using public key
- **File Upload/Download**
  - Secure handling of user files

## 🧱 System Architecture

- **Presentation Layer**:  
  Web interface built with Django Templates (HTML/CSS/JS)

- **Application Logic Layer**:  
  Core cryptographic operations using Python and Django Views:
  - Encryption/Decryption Module
  - Hashing Module
  - Digital Signature & Verification Module
  - Key Management Module

- **Data Layer**:  
  SQLite/PostgreSQL for metadata and temporary file storage

## 🔄 Functional Flow

1. User uploads a file
2. Selects operation: Encrypt | Decrypt | Hash | Sign | Verify
3. Backend processes the file accordingly
4. Result is displayed or provided for download

## 🧰 Tools & Technologies

- **Python 3.x** – Core programming language
- **Django** – Web framework
- **HTML/CSS/JavaScript** – Frontend
- **cryptography, hashlib** – Cryptographic functions
- **SQLite/PostgreSQL** – Metadata storage
- **Git/GitHub** – Version control
- **VS Code** – Development environment

## 👤 User Role

- Regular users can upload files, choose an operation, and download or copy the result.

## 📦 Development Phases

1. Planning and requirements
2. Environment setup
3. Backend and frontend development
4. Integration and testing
5. Security enhancements
6. Documentation and finalization

## 📌 Conclusion

This project demonstrates the application of modern cryptographic techniques in a web environment. Users can securely manage their files using encryption, hashing, and digital signatures, with a clear and maintainable system architecture built on Django and Python.

