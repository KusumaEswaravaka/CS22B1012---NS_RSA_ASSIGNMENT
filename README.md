# NS_RSA_Algorithm

## Project Overview
This repository provides a Python-based implementation of the RSA (Rivest-Shamir-Adleman) algorithm for encryption and decryption. It highlights the key mathematical concepts behind RSA, including prime number generation, key pair generation, message encryption, and message decryption.

---

## Repository Contents
- **CS22B1012_Report.docx**: A detailed project report describing the RSA algorithm, code explanation, sample output, and security aspects.
- **main.py**: Python script that contains the complete RSA algorithm implementation.
- **output.png**: Screenshot showing the execution output of the program.
- **RSA_algorithm.png**: Diagram explaining the working of RSA visually.

---

## Key Features
- **Prime Number Validation**: Efficient method to validate prime numbers using optimized trial division.
- **Key Pair Generation**: Creation of RSA public and private keys based on user-provided primes.
- **Encryption and Decryption**: Securely encrypts plaintext messages and decrypts ciphertext using RSA logic.
- **Interactive CLI**: Simple command-line interface for entering prime numbers and messages.

---

## How to Run
1. Make sure Python 3 is installed on your system.
2. Clone this repository or download the `main.py` file.
3. Open your terminal (or command prompt) and navigate to the project directory.
4. Execute the following command:
   ```bash
   python main.py
   ```
5. Follow the prompts:
   - Enter two distinct prime numbers.
   - Enter the message to encrypt and decrypt.

---

## Sample Execution
During execution, the program will display:
- Generated **Public Key (e, n)** and **Private Key (d, n)**.
- **Encrypted Message** (as a series of numbers).
- **Decrypted Message** (original plaintext).

### Example
```
Public Key (e, n): (17, 3233)
Private Key (d, n): (2753, 3233)

Encrypted Message: 855 2200 1241
Decrypted Message: Hi
```

---




