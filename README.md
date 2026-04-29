# 🚀 CrowdFunding DApp (Web3 Blockchain Project)

A decentralized crowdfunding platform built using **Solidity, Hardhat, React, and Web3**, where users can create campaigns and receive funding securely using blockchain technology.

---

## 🌟 Project Overview

This project is a **Web3-based crowdfunding application** that eliminates intermediaries and enables **trustless fundraising**.
Users can create campaigns, donate ETH, and track contributions transparently on the blockchain.

---

## ✨ Features

* 🔗 Connect wallet using MetaMask
* 📢 Create fundraising campaigns
* 💰 Donate ETH to campaigns
* 📊 View all campaigns dynamically
* 🔐 Secure transactions via smart contracts
* 🧾 Track campaign donations
* ⚡ Real-time blockchain interaction

---

## 🛠 Tech Stack

### Frontend

* React.js (Vite)
* Tailwind CSS

### Blockchain

* Solidity
* Hardhat

### Web3 Integration

* Ethers.js
* MetaMask

---


## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/TheSiddCode/CrowdFunding.git
cd CrowdFunding
```

---

### 2️⃣ Install Dependencies

#### Frontend

```bash
cd client
npm install
```

#### Smart Contracts

```bash
cd ../web3
npm install
```

---

### 3️⃣ Run Local Blockchain

```bash
cd web3
npx hardhat node
```

---

### 4️⃣ Deploy Smart Contract

```bash
npx hardhat run scripts/deploy.js --network localhost
```

---

### 5️⃣ Run Frontend

```bash
cd ../client
npm run dev
```

---

## 🔑 MetaMask Setup

* Network Name: Localhost
* RPC URL: http://127.0.0.1:8545
* Chain ID: 31337
* Import private key from Hardhat

---

## 📌 Future Improvements

* 🌍 Deploy on Sepolia Testnet
* 📷 Fix image upload system
* 🔍 Add campaign filtering & search
* 📊 Add analytics dashboard
* 🔐 Add authentication layer

---

## 👨‍💻 Author

**Siddhant Singh**

* GitHub: https://github.com/TheSiddCode

---

## ⭐ Show your support

If you like this project, please ⭐ the repo and share it!
