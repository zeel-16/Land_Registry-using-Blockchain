# 🏡 Land Registry Smart Contract

This project is a **Land Registry Smart Contract** developed in **Solidity** using the **Remix Ethereum IDE**. It enables secure and transparent management of land ownership records on the **Ethereum blockchain**.

## 🚀 Features

- 📜 **Register Land** – Allows landowners to register their property.
- 🔄 **Transfer Ownership** – Enables ownership transfer between users.
- 🛡️ **Secure Transactions** – Ensures security using Ethereum smart contracts.
- 📊 **Immutable Records** – Stores data permanently on the blockchain.

## 🛠️ Technologies Used

- Solidity (`.sol`)
- Remix Ethereum IDE
- Ethereum Blockchain
- Web3.js (optional for frontend integration)

## 🏗️ Setup & Deployment

1. **Open Remix IDE**:  
   Go to [Remix Ethereum IDE](https://remix.ethereum.org/).
   
2. **Upload `LandRegistry.sol`**:  
   - Click on `File Explorer (📂)` in Remix.
   - Create a new file named `LandRegistry.sol` and paste the contract code.

3. **Compile the Smart Contract**:  
   - Navigate to the `Solidity Compiler` tab.
   - Select `0.8.x` compiler version.
   - Click **Compile LandRegistry.sol**.

4. **Deploy to Ethereum Network**:  
   - Go to the `Deploy & Run Transactions` tab.
   - Select `Injected Web3` (for MetaMask) or `Remix VM` (for local testing).
   - Click **Deploy** and confirm the transaction in MetaMask.

## 📜 Smart Contract Functions

| Function | Description |
|----------|------------|
| `registerLand()` | Registers a new land property. |
| `transferOwnership()` | Transfers ownership of the land to another address. |
| `getLandDetails()` | Retrieves details of a specific land. |

## 📌 Example Usage

To interact with the smart contract after deployment:

1. Call **registerLand** with land details.
2. Use **getLandDetails** to fetch registered properties.
3. Execute **transferOwnership** to transfer the land to a new owner.


