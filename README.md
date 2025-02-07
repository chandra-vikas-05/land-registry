# 🌍 Blockchain Land Registry 🏡

A decentralized land registry system leveraging blockchain technology, built using Solidity and deployed on Ethereum via the Remix IDE. This system ensures secure, transparent, and tamper-proof records of land ownership and property transactions. 🌐

## 📜 Overview

The Blockchain Land Registry system enables the recording and transfer of land ownership in a transparent, immutable way. With the power of blockchain, all ownership records are secured and easily verifiable. This project uses smart contracts written in Solidity, developed and deployed using Remix IDE, to handle land titles, ownership transfers, and property transactions. 🚜

## 🛠️ Key Features
- **Immutable Ownership Records:** 🔒 The ownership details of land are recorded on the blockchain, making them tamper-proof.
- **Smart Contracts for Transactions:** 🤖 Secure property transactions and ownership transfers via smart contracts.
- **Decentralized Database:** 💻 No central authority is needed to verify land ownership or handle transactions.
- **Secure and Transparent:** 🔍 Property transactions can be verified by all parties through the blockchain, without reliance on third-party intermediaries.

## 🚀 Getting Started

Follow these instructions to set up the Blockchain Land Registry system using Remix IDE.

### 🖥️ Prerequisites
- **Remix IDE** - You can use Remix IDE in your browser for Solidity development.
- **Metamask** - A browser extension that acts as a wallet for interacting with Ethereum. Install it from [metamask.io](https://metamask.io).
- **Ethereum Testnet (Rinkeby, Ropsten, or Ganache)** - You can use Remix's integrated environment for local development or connect to a testnet via Metamask.

### 📥 Installation & Setup
1. **Open Remix IDE**  
   Open Remix IDE in your browser.

2. **Clone the Repository**  
   Clone the repository to your local machine or manually download the contract files. You can create a new workspace in Remix IDE and upload the `.sol` files.

   Alternatively, you can simply copy the contract code directly into Remix.

3. **Load Contracts in Remix**  
   In Remix IDE, navigate to the "File Explorers" tab and create new files under the "contracts" folder (for example, `LandRegistry.sol`). Paste the Solidity code of your smart contracts into these files.

4. **Compile Contracts**  
   In the "Solidity Compiler" tab in Remix, select the appropriate compiler version (make sure it matches the Solidity version in the contracts). Click "Compile" to ensure the smart contracts are error-free.

5. **Deploy Contracts**  
   In the "Deploy & Run Transactions" tab, select the environment (e.g., "Injected Web3" to deploy to a testnet like Rinkeby via Metamask or "JavaScript VM" for local testing).

   - Make sure you have connected your Metamask wallet to Remix (for deployment to a testnet).
   - Click "Deploy" to deploy the smart contract to the Ethereum network or the testnet.

6. **Interact with the Smart Contract**  
   After deployment, you can interact with the contract directly from Remix. The deployed contract's functions will appear in the "Deployed Contracts" section.

## 📝 Smart Contracts

### Contract: `LandRegistry.sol`

This contract stores and manages land ownership records and allows the following functions:

- **registerLand:** Registers a new piece of land with unique details such as land ID, owner name, and area.

  ```solidity
  function registerLand(string memory _landID, string memory _ownerName, uint256 _area) public;
   function transferOwnership(string memory _landID, address _newOwner) public;
  function getOwner(string memory _landID) public view returns (address);

## 👨‍💻 Author
🔹 vikas    
🔗 [LinkedIn]( www.linkedin.com/in/c-vikas-30813a314 ) | [GitHub](https://github.com/chandra-vikas-05)
