# 🔐 Advanced Encryption Tool (AES-256)

**Author:** Arjun  
**Description:** A Python-based utility for encrypting and decrypting files of any type (text, audio, video, images) using AES-256 in CBC mode.  

---

## ✨ Features
- AES-256 encryption (secure and industry-standard).
- Works with any file type: text, images, audio, video, etc.
- Automatically generates and stores a persistent AES key (`aes.key`).
- Simple command-line interface for encryption/decryption.
- Logging for clear feedback on operations.

---

## 📦 Requirements
- Python 3.x
- [PyCryptodome](https://pycryptodome.readthedocs.io/en/latest/) library

Install dependencies:
```bash
pip install pycryptodome



🚀 Usage
Run the script:
python3 aes_tool.py


You’ll be prompted to choose:
- E → Encrypt a file
- D → Decrypt a file
🔒 Encrypt a file
Encrypt or Decrypt (E/D): E
Enter file path: example.txt


Output: example.txt.enc
🔓 Decrypt a file
Encrypt or Decrypt (E/D): D
Enter file path: example.txt.enc


Output: example.txt.dec

📂 File Handling
- Encrypted files are saved with .enc extension.
- Decrypted files are saved with .dec extension.
- AES key is stored in aes.key (auto-generated if not present).

⚠️ Notes
- Keep your aes.key file safe — losing it means you cannot decrypt your files.
- This tool uses AES in CBC mode with PKCS7 padding.
- Suitable for personal file protection, but not intended as a full enterprise-grade solution.

🛠 Example Workflow
- Place your file (e.g., photo.jpg) in the same directory.
- Run the tool and choose E to encrypt → photo.jpg.enc.
- Later, choose D to decrypt → photo.jpg.dec.

📜 License
This project is released under the MIT License.
Feel free to use, modify, and share.

Would you like me to also add a **"Developer Notes" section** with example Python snippets showing how to use the `AESTool` class directly in code (instead of the CLI)? That would make your README useful both for end-users and developers.


