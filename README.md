# 📷 Decentralized Image Upload and Sharing

This project facilitates decentralized image upload and sharing on the blockchain using **Solidity** for the smart contract and **React** for the front-end interface. It enables users to securely upload images to **IPFS (InterPlanetary File System)** and share access with specified users through smart contract functionality.

---

## ✨ Features

- 🗄 **Decentralized Storage:** Images are uploaded to **IPFS**, ensuring decentralized and immutable storage.
- 🔒 **Smart Contract:** Utilizes **Solidity** smart contracts on the Ethereum blockchain for access control and ownership management.
- 🔑 **Access Control:** Users can grant or revoke access to their uploaded images through the smart contract.

---

## 🛠 Technologies Used

- 📝 **Solidity** – Smart contract development for ownership and access control.
- ⚛ **React** – Front-end interface for uploading images and managing access.
- 🌐 **IPFS** – Decentralized storage protocol for hosting uploaded images.

---

## 🚀 Installation

### 1️⃣ Clone the repository:
```bash
git clone https://github.com/your-username/decentralized-image-upload.git
```

### 2️⃣ Install dependencies for Hardhat:
```bash
# Navigate to the root directory
cd decentralized-image-upload
# Install Hardhat dependencies
npm install
```

### 3️⃣ Compile the smart contract:
```bash
# Compile Smart Contract
npx hardhat compile
```

### 4️⃣ Deploy the Solidity smart contract:
```bash
# Deploy Smart Contract
npx hardhat run scripts/deploy.js --network <network-name>
```

### 5️⃣ Install dependencies for the React front end:
```bash
# Navigate to the React client directory
cd client
# Install React dependencies
npm install
```

### 6️⃣ Run the React application:
```bash
# Start React Application
npm start
```

---

## ⚙ Configuration

### 🌍 Set up environment variables:
- Obtain API keys for **Pinata** to interact with **IPFS**.
- Update the React component (`FileUpload.js`) with your **Pinata API keys**.

### 📌 Update Contract Address:
- After smart contract deployment, update the **contract address** in `App.js` within the React application.

---

## 📌 Usage Guide

### 🦊 1. Install Metamask
- Ensure **Metamask** is installed and configured in your browser for Ethereum interactions.

### 📤 2. Upload Image Before "Get Data"
- Click **"Get Data"** only after uploading an image on **Pinata**.
- Otherwise, it will throw an error stating: ❌ *"You don't have access"*.

### 👥 3. Access Other Users' Images
- Use the **"Get Data"** button to access other users' images.
- Input the **user's address** in the designated box.
- ✅ You can only access their images **if they've granted you access**.
- ❌ Otherwise, an error will appear: *"You don't have access"*.

---

Following these steps ensures **smooth navigation** and **secure access control** while maintaining the decentralized nature of the system. 🎯

---

## 🤝 Contributing
Pull requests are welcome! Feel free to **fork** the repository and submit improvements.

