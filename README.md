# React Voting Application

## 📌 Project Overview
The **React Voting Application** is a decentralized voting system built using **React.js**, **Hardhat**, and **Solidity**. It allows users to securely cast votes on the blockchain while ensuring transparency and integrity.

## 🚀 Features
- 🔐 Secure blockchain-based voting
- 📊 Real-time vote counting
- 📜 Smart contract integration using Hardhat
- 🎨 Responsive UI with React.js

## 📂 Folder Structure
```
React-Voting-Application/
├── contracts/          # Solidity smart contracts
├── scripts/            # Deployment scripts
├── src/                # React frontend code
├── test/               # Smart contract tests
├── public/             # Public assets
├── hardhat.config.js   # Hardhat configuration
├── package.json        # Node dependencies
└── README.md           # Project documentation
```

## 🛠 Installation & Setup
### Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/)
- [MetaMask](https://metamask.io/)
- [Hardhat](https://hardhat.org/)

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/your-username/React-Voting-Application.git
cd React-Voting-Application
```

### 2️⃣ Install Dependencies
```sh
npm install
```

### 3️⃣ Set Up Environment Variables
Create a `.env` file and add:
```
VOLTA_URL=https://volta-rpc.energyweb.org/
PRIVATE_KEY=your_private_key_here
```

### 4️⃣ Compile & Deploy Smart Contracts
```sh
npx hardhat compile
npx hardhat node
npx hardhat run scripts/deploy.js --network localhost
```

### 5️⃣ Run the Frontend
```sh
npm start
```
The app will be available at **http://localhost:3000**.

## 🧪 Running Tests
To run smart contract tests:
```sh
npx hardhat test
```

## 🤝 Contributing
1. **Fork** the repo
2. **Create a new branch** (`feature/your-feature`)
3. **Commit changes** (`git commit -m "Added new feature"`)
4. **Push to GitHub** (`git push origin feature/your-feature`)
5. **Submit a Pull Request**

## 📜 License
This project is licensed under the **MIT License**.


---
🚀 **Happy Coding!**

