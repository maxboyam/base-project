# 🚀 My Base Project

A decentralized application built on **[Base](https://base.org)** — the secure, low-cost, developer-friendly Layer 2 blockchain incubated by **Coinbase**.

---

## 🧠 Overview

This project demonstrates how to build and deploy smart contracts and dApps on the **Base network**, leveraging Ethereum’s security and Base’s scalability.

It includes:
- Smart contract deployment on Base
- Frontend integration via Ethers.js / Web3.js
- Wallet connection (MetaMask / Coinbase Wallet)
- Base Mainnet & Testnet configuration

---

## 🧩 Tech Stack

| Layer | Technology |
|-------|-------------|
| Blockchain | [Base Network](https://base.org) |
| Language | Solidity (Smart Contracts) |
| Frontend | React / Next.js |
| Wallet Integration | MetaMask, Coinbase Wallet |
| Libraries | Ethers.js, Wagmi, RainbowKit |
| Tools | Hardhat / Foundry / Remix |

---

## ⚙️ Installation & Setup

```bash
# Clone the repository
git clone https://github.com/<your-username>/<repo-name>.git

# Move into project folder
cd <repo-name>

# Install dependencies
npm install

# Compile contracts
npx hardhat compile

# Run local development
npm run dev

---
##Base Mainnet
```bash
Network Name: Base Mainnet
RPC URL: https://mainnet.base.org
Chain ID: 8453
Currency Symbol: ETH
Block Explorer: https://basescan.org

---
##Base Sepolia
```bash
Network Name: Base Sepolia
RPC URL: https://sepolia.base.org
Chain ID: 84532
Currency Symbol: ETH
Block Explorer: https://sepolia.basescan.org

---
##🧱 Deployment (Hardhat Example)
```bash
npx hardhat run scripts/deploy.js --network base



