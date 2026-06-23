# Encryption and Hash Verification System

A Python-based security project that demonstrates encryption, decryption, hashing, and integrity verification using the Caesar Cipher and SHA-1 algorithms.

## Overview

This project allows users to encrypt a message using the Caesar Cipher algorithm, generate a SHA-1 hash value for the original message, decrypt the encrypted message, and verify data integrity by comparing hash values before and after decryption.

## Features

- Caesar Cipher Encryption
- Caesar Cipher Decryption
- SHA-1 Hash Generation
- Integrity Verification
- Input Validation
- Command-Line Interface (CLI)

## Technologies Used

- Python 3
- hashlib
- os
- time

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/encryption-hash-verification.git
```

2. Navigate to the project folder:

```bash
cd encryption-hash-verification
```

3. Run the program:

```bash
python main.py
```

## Project Workflow

### Encryption Phase
- Enter a plaintext message.
- Choose a shift key between 1 and 25.
- The message is encrypted using Caesar Cipher.
- A SHA-1 hash is generated for the original message.

### Decryption Phase
- Enter the encrypted message.
- Provide the decryption key.
- The original message is recovered.

### Hash Verification Phase
- A new SHA-1 hash is generated from the decrypted message.
- The system compares both hash values.
- If they match, integrity verification is successful.

## Example Output

```text
Enter the message to encrypt: HELLO
Enter the encryption key: 3

Cipher Text: KHOOR

Enter the cipher to decrypt: KHOOR
Enter the decryption key: 3

Decrypted Message: HELLO

Integrity Verification: SUCCESS
```

## Learning Outcomes

This project demonstrates:

- Basic Cryptography Concepts
- Caesar Cipher Implementation
- Hash Functions and SHA-1
- Data Integrity Verification
- Secure Information Processing

## Author

Shahad Alanazi

Artificial Intelligence Student
