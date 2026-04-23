# 🔐 SecureShare – Decentralized Encrypted File Sharing

> **A complete end-to-end secure file storage & sharing system built with AES-GCM encryption, IPFS, and Ethereum Smart Contracts.**

![SecureShare Preview](https://placehold.co/1000x400/0d1117/58a6ff?text=SecureShare+Preview+%28Insert+Your+Screenshot+Here%29)

---

## 📖 Overview

SecureShare is a Web3-powered decentralized file-sharing platform. It ensures maximum privacy and security by encrypting files locally using AES-GCM before uploading them to the InterPlanetary File System (IPFS). Access control, sharing permissions, and audit logs are securely managed on the Ethereum blockchain via Smart Contracts, ensuring transparency and immutability.

---

## ✨ Key Features

- **End-to-End Encryption:** Files are encrypted using AES-GCM before ever leaving the user's device.
- **Decentralized Storage:** Utilizes IPFS (via Pinata/Web3.storage) to store files securely without a central point of failure.
- **Blockchain Access Control:** Solidity smart contracts manage who can access and decrypt files.
- **MetaMask Integration:** Seamless Web3 wallet authentication.
- **Audit Logs:** Immutable tracking of file access and sharing history.
- **Modern UI:** Built with React, Vite, and responsive design principles.

---

## 🛠️ Technology Stack

### Frontend
- **React.js & Vite** for lightning-fast performance
- **Ethers.js** for blockchain interaction
- **Bootstrap / Custom CSS** for styling

### Backend
- **Node.js & Express.js** for API handling
- **MongoDB** for off-chain metadata (demo/cache mode)
- **Multer** for file handling

### Blockchain & Web3
- **Solidity** for Smart Contracts
- **IPFS** for decentralized storage
- **Ethereum Network** for execution

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v16+)
- MongoDB (Local or Docker)
- MetaMask Extension installed in your browser

### 1. Clone the Repository
```bash
git clone https://github.com/manjeet266/SecureShare-main.git
cd SecureShare-main
npm install
```

### 2. Start the Backend Server
```bash
cd backend
npm install
npm start
```
*The backend will run on `http://localhost:5001`.*

### 3. Start the Frontend App
```bash
cd frontend
npm install
npm run dev
```
*The frontend will run on `http://localhost:5176`.*

---

## 🖼️ Application Screenshots

### Dashboard Area
![Dashboard](https://placehold.co/800x400/0d1117/3fb950?text=Dashboard+Screenshot)

### File Upload & Encryption
![Upload](https://placehold.co/800x400/0d1117/a371f7?text=Upload+Screenshot)
*(Add a screenshot of your upload process here)*

---

## 🔐 API Reference

| Endpoint | Method | Description |
|---|---|---|
| `/auth/login` | `POST` | User login authentication |
| `/auth/register` | `POST` | User registration |
| `/files/upload` | `POST` | Encrypt and upload a file |
| `/files/download/:id` | `GET` | Fetch and decrypt a file |

---

## 📜 License

This project is open-source and ready for college submission.