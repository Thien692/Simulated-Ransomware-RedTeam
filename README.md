# Simulated-Ransomware-RedTeam
A red team simulation that mimics modern ransomware behavior using Python. Includes AES-256 file encryption, GUI ransom note, Telegram key exfiltration, and .exe generation.
# 🛡️ Simulated Ransomware – Python Red Team Lab

This project simulates the behavior of modern ransomware in a controlled lab environment using Python. It was developed as part of a red team training exercise to better understand attacker techniques, from encryption to key exfiltration and ransom note delivery.

---

## 🎯 Objectives

- Simulate real-world ransomware infection chain
- Implement AES-256 file encryption (CBC mode)
- Extract and transmit encryption keys to an external server (Telegram API)
- Generate a GUI ransom note using `tkinter`
- Convert script to `.exe` using PyInstaller for simulation purposes

---

## ⚙️ Features

- 🔐 **AES-256 Encryption**: Encrypts all files in a target folder
- ☁️ **Telegram Key Exfiltration**: Sends AES keys to Telegram via bot API
- 💬 **GUI Ransom Note**: Displays a fake ransom demand (with timer)
- 🛠️ **.EXE Payload Creation**: Built using PyInstaller to simulate deployment
- 📁 **Folder Targeting**: Encrypts contents of specific user directories

---

## 🧰 Technologies Used

- Python 3.x
- `pycryptodome`
- `tkinter`
- Telegram Bot API
- `pyinstaller`

---

## 📸 Screenshots

### Ransom Note GUI  
![Ransom Note GUI][download (2)](https://github.com/user-attachments/assets/09232b69-bff4-4670-8693-ed9f4616de2b)


### Telegram Key Exfiltration  
![Telegram Bot Logs][download (1)](https://github.com/user-attachments/assets/6467b150-decc-48a1-9d9b-3beeb224d6b8)


---

## ⚠️ Disclaimer

This ransomware simulation was built **strictly for educational and ethical red team training purposes**. It was executed in an isolated lab environment with no internet-facing services.  
**Never use this code on unauthorized systems. You are responsible for your own actions.**

---

## ✅ Status

Project completed – functional and tested in a virtual lab.

---

