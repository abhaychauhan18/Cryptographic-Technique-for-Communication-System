<h1>🔐 Cryptographic Technique for Secure Communication</h1>
<br>
A lightweight encryption system that combines Vigenère Cipher and Polybius Square Cipher to enhance security in communication systems.

## 📘 About the Project
In today's digital world, securing sensitive data during transmission is critical. This project proposes a hybrid cryptographic model that integrates two classical encryption methods to make communication more secure and resilient against attacks like brute-force, frequency analysis, and chosen-plaintext attacks.

This project was developed as part of the final year B.Tech curriculum at Shri Ramswaroop Memorial University.

## 👨‍💻 Authors
Sitlendra Pratap Singh (201810101110096)

Abhay Singh Chauhan (201810101110079)

Supervisor: Ms. Kanchan Pandey, Assistant Professor

## 🔧 Features
✅ Vigenère Cipher for alphabetic substitution

✅ Polybius Square for numeric encryption

✅ Hybrid flow increases complexity and confusion

✅ Implemented in Python for ease of testing and execution

## 🔄 How It Works
Vigenère Cipher: Encrypts plaintext using a repeating key pattern.

Polybius Cipher: Converts the Vigenère output into numeric coordinates via a grid.

## 🔤 Example
Step	                Output
Plaintext	            INDIA
Key	                  AYUSH
Vigenère Output	      ILXAH
Polybius Output	      24 13 55 11 32

## 💻 Technologies Used
Python 3.x

Google Colab / Jupyter Notebook / Spyder IDE

## 🗂️ Project Structure

📁 cryptography-hybrid
- ├── vigenere_cipher.py       # Handles Vigenère encryption
- ├── polybius_cipher.py       # Handles Polybius conversion
- ├── hybrid_encryption.py     # Runs both steps together
- └── README.md                # Project documentation

## 🚀 Getting Started
- Clone this project or download the files.

- Run hybrid_encryption.py in your preferred Python environment.

- Follow the prompts to enter plaintext and a key.

- Get the encrypted numeric output.

## 📈 Future Improvements
- Add support for digits and special characters

- Allow grid randomization for the Polybius cipher

- Create a GUI for user-friendly interaction

## 📚 References
Vigenère Cipher – Wikipedia

Polybius Square – Wikipedia



