# W3Share - Decentralized Data Storage with IPFS and Blockchain 🌐

## Overview

W3Share is a cutting-edge decentralized application (dApp) designed to revolutionize data storage by combining the power of **IPFS (InterPlanetary File System)** and **Blockchain** technology. Built with **Next.js**, this project offers a secure, tamper-proof solution for storing and retrieving data. Users can upload files, store them on **web3.storage (IPFS)**, and register the IPFS hash on the blockchain through smart contracts, ensuring data integrity and transparency.

![image](https://github.com/user-attachments/assets/b5417dae-70cd-40c4-a2fc-42f49b09d066)

---

## Key Features

- **Decentralized Storage**: Leverage IPFS via **web3.storage** for secure and distributed data storage.
- **Blockchain Integration**: Immutably store file hashes on the blockchain for enhanced security and transparency.
- **Next.js Backend API**: Efficiently handle file uploads and interact with IPFS.
- **User-Friendly Interface**: Easily upload and retrieve files through a seamless client-side experience.
- **Tamper-Proof Records**: Ensure data integrity and verify ownership with blockchain-backed records.

---

## Technology Stack

- **Next.js**: A powerful framework for building the API and client-side interface.
- **web3.storage**: A decentralized storage solution based on IPFS.
- **Smart Contracts**: Blockchain-based mechanisms for recording and verifying data.
- **Ethereum / Polygon**: Blockchain networks used for storing IPFS hashes.

---

## How It Works

1. **Client Interaction**: Users interact with the application through a web interface.
2. **Data Upload**: Files are uploaded via an API request to the `/api/uploadData` endpoint.
3. **IPFS Storage**: The data is stored on **web3.storage (IPFS)**, generating a unique IPFS hash.
4. **Blockchain Recording**: The IPFS hash is recorded on the blockchain using a smart contract.
5. **Data Retrieval**: Users can retrieve and verify stored data using the IPFS hash.

---

## Getting Started

### Prerequisites

- **Node.js** (version 16.x or higher)
- **MetaMask** or any compatible Web3 wallet
- **Infura/Alchemy API key** (optional for blockchain interactions)

### Installation Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/Kamal007OLica/W3share.git
   cd W3share
   ```

2. Install the required dependencies:
   ```bash
   npm install
   ```

3. Set up the environment:
   ```bash
   cp .env.example .env
   ```
   Add your API keys and contract addresses to the `.env` file.

4. Start the development server:
   ```bash
   npm run dev
   ```

---

## Usage Instructions

1. Open the application in your browser at `http://localhost:3000`.
2. Connect your Web3 wallet (e.g., MetaMask or WalletConnect).
3. Upload a file to store it on IPFS.
4. The IPFS hash will be recorded on the blockchain.
5. Retrieve and verify your stored data using the IPFS hash.

---

## Deploying the Smart Contract

To deploy the smart contract:

1. Compile the contract:
   ```bash
   npx hardhat compile
   ```

2. Deploy the contract to your desired network:
   ```bash
   npx hardhat run scripts/deploy.js --network goerli  # Replace 'goerli' with your preferred network
   ```

---

## Contributing to W3Share

We welcome contributions! Here’s how you can get involved:

1. Fork the repository.
2. Create a new branch for your feature (`feature-name`).
3. Commit your changes (`git commit -m "Add feature"`).
4. Push your branch (`git push origin feature-name`).
5. Open a pull request.

---

## License

W3Share is licensed under the **MIT License**. For more details, see the [LICENSE](LICENSE) file.

