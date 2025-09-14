# Mini Blockchain (JavaScript)

A simple blockchain in a single file, built while learning the fundamentals of blockchains.

## ✨ Features
- Block with `index`, `timestamp`, `data`, `previousHash`, and computed `hash`
- SHA256 hashing using `crypto-js`
- Genesis block creation
- `addBlock` automatically links to the previous block

## 📦 Requirements
- Node.js 18+  
- Dependency: `crypto-js`

## 🚀 Run
```bash
npm init -y
npm install --save crypto-js
node index.js
```

## 🖥 Example Output
<img width="1522" height="1108" alt="image" src="https://github.com/user-attachments/assets/c0cb77fd-92cf-45a5-b824-ecee0e33829a" />

## 🧠 What I Learned
- How blocks reference previous hashes to form a chain
- How SHA256 secures data integrity
- Why a genesis block bootstraps the chain
