# Cryptographic-Technique-for-Communication-System
<br>
Project Overview
This project presents a hybrid cryptographic method for enhancing the security of digital communications. It combines two classical ciphers—Vigenère Cipher and Polybius Square Cipher—to encrypt plaintext in two layers, improving resistance to common cryptographic attacks.

Authors
Sitlendra Pratap Singh (201810101110096)

Abhay Singh Chauhan (201810101110079)

Supervised by Ms. Kanchan Pandey

Shri Ramswaroop Memorial University

Key Features
Uses a combination of substitution (Vigenère) and numerical encoding (Polybius)

Python implementation suitable for low-resource systems

Improves resistance to brute-force and frequency analysis attacks

Tested using platforms like Google Colab and Spyder IDE

Encryption Process
Vigenère Cipher is used to encrypt the plaintext using a keyword.

Polybius Cipher is then applied to convert the output into a numeric code.

Example:
Plaintext: INDIA

Key: AYUSH

Vigenère Output: ILXAH

Polybius Output: 24 13 55 11 32

How to Use
Run the Vigenère encryption function in Python with your input text and key.

Pass the result into the Polybius cipher function.

The final output will be a numeric ciphertext.

Technologies Used
Python 3

Jupyter Notebook / Google Colab / Spyder

Future Enhancements
Add support for digits and special characters

Randomize Polybius grid for added security

Develop a graphical interface for easier use
