# Electronic-health-record-Monitoring-System

### Project Structure
```
EHR-Blockchain/
│── client/                 # Frontend (React.js + Vite)
│── contracts/              # Smart Contracts (Solidity)
│── server/                 # Backend (Node.js + Express)
│── blockchain/             # Blockchain config (Hardhat)
│── README.md               # Project Documentation
│── package.json            # Dependencies
│── hardhat.config.js       # Hardhat for deployment
│── .gitignore              # Ignore unnecessary files
```

---
 1️⃣ Setting Up the Smart Contract
 Navigate to the `contracts/` folder and create `EHR.sol`

2️⃣ Deploying Smart Contracts
 Install dependencies:
```bash
npm install --save-dev hardhat ethers
```
Compile contract:
```bash
npx hardhat compile
```
Deploy contract (`scripts/deploy.js`):
```javascript

```
#### Run deployment (Goerli Testnet example):
```bash
npx hardhat run scripts/deploy.js --network goerli
```
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
### **Possible Errors & Fixes**
1️⃣ **Error: "Hardhat not found"**  
**Fix:** Ensure Hardhat is installed: `npm install --save-dev hardhat`

2️⃣ **Error: "Invalid JSON RPC response"**  
**Fix:** Check your **Infura or Alchemy API key** in Hardhat config.

3️⃣ **Error: "MetaMask transaction fails"**  
**Fix:** Ensure enough **ETH balance** in your test wallet.

---

### **General Steps to Run the Project**
1️⃣ **Install Dependencies:**  
   ```bash
   npm install
   ```
2️⃣ **Compile & Deploy Contract:**  
   ```bash
   npx hardhat compile
   npx hardhat run scripts/deploy.js --network goerli
   ```
3️⃣ **Start Frontend:**# Electronic-health-Record-System-Using-Block-Chain
