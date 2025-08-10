# M-ENC - Marshal Encryptor

**M-ENC** is a Termux-based Python tool that can easily encrypt any Python file into `marshal` bytecode.  
After encryption, the original source code cannot be directly viewed, but the file can still be executed.

---

## ✨ Features
- Quickly converts Python scripts into marshal bytecode.
- Keeps the original source code unchanged.
- Encrypted files can be executed directly with the `python` command.
- Works directly in Termux (no version mismatch issues).

---

## 📦 Installation

Run the following commands in Termux:

```bash
pkg update && pkg upgrade -y
pkg install python git -y
git clone https://github.com/lucifer-fernandez/M-ENC.git
cd M-ENC
```

---

🚀 Usage

In Termux, run:
```bash
python encrypt.py
```
Then:

1. Enter the source file name you want to encrypt (e.g., script.py)


2. Enter the output encrypted file name you want to create (e.g., script_enc.py)




---

📌 Example

$ python encrypt.py

[*] Enter source file name (e.g., script.py): xyz.py
[*] Enter output encrypted file name (e.g., xyz_enc.py):

>>>>> Encrypting your file...

[✓] File encrypted successfully as xyz_enc.py
➤ Run it with: python xyz_enc.py


---

⚠️ Disclaimer

This tool is created for educational purposes only. Any misuse for illegal activities is strictly prohibited.
The author is not responsible for any misuse.


---

📧 Contact

Facebook: [Mohammad Rayhan Khan](https://www.facebook.com/azad.farabi.2024)

GitHub: [lucifer-fernandez](https://github.com/lucifer-fernandez)

Telegram : [Md Rayhan Khan](@rayhankhan4you)

Gmail: [G-mail](rayhankhan4u@gmail.com)

Youtube: [Cyber Tesla](https://youtube.com/@cyber_tesla?si=cNaVnhQ1YvGzKYj3)
