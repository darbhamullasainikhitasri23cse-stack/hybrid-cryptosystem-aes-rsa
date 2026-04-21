# 🔐 Hybrid Cryptosystem — AES-256 + RSA-2048

![Node.js](https://img.shields.io/badge/Backend-Node.js-green)
![React](https://img.shields.io/badge/Frontend-React-blue)
![Crypto](https://img.shields.io/badge/Security-AES--256%20%7C%20RSA--2048-red)
![License](https://img.shields.io/badge/License-MIT-yellow)

A **full-stack secure messaging application** that implements a real-world **Hybrid Cryptographic System** — combining the speed of **AES-256-CBC** with the secure key exchange of **RSA-2048-OAEP**.

> 🚀 Built to demonstrate how modern encryption systems (HTTPS, VPNs, banking apps) securely transmit data using hybrid cryptography.

---

## 🚀 Demo Flow

1. Generate a **2048-bit RSA key pair**
2. Enter a secret message
3. Encrypt message using **AES-256-CBC**
4. Encrypt the AES key using **RSA-2048-OAEP**
5. Decrypt using the RSA private key

---

## 🧠 Why This Project Matters

Most real-world systems don’t use just AES or RSA — they use **both together**.

This project demonstrates:
- 🔐 Secure key exchange (RSA)
- ⚡ Fast data encryption (AES)
- 🔁 End-to-end encryption workflow
- 🧩 Real-world cryptographic architecture

---

## 🛠️ Tech Stack

| Layer        | Technology |
|-------------|----------|
| Frontend    | React 18, CSS3 |
| Backend     | Node.js, Express 4 |
| Cryptography| node-forge |
| API         | REST (JSON) |

---

## 🔐 How It Works

- AES-256-CBC encrypts the message
- A random AES key + IV are generated per session
- RSA-2048-OAEP encrypts the AES key
- Only the private key holder can decrypt the message

---

## 📦 Use Cases

- 💳 Banking Systems  
- 💬 Secure Messaging  
- ☁️ Cloud Storage Encryption  
- 🔒 VPN & HTTPS Protocols  
- 📁 File Encryption Systems  

---

## ⚙️ Setup & Run Locally

```bash
# Clone the repo
git clone https://github.com/your-username/hybrid-cryptosystem-aes-rsa.git

# Backend
cd backend
npm install
npm start

# Frontend
cd frontend
npm install
npm start
