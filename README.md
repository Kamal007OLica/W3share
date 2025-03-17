# W3Share - Decentralized Data Storage with IPFS and Blockchain 🌐

## Overview 🌍

**W3Share** is a decentralized application (dApp) that leverages **IPFS (InterPlanetary File System)** and **Blockchain** technology to provide a secure, tamper-proof data storage solution. Built with modern web technologies, W3Share allows users to upload files, store them on IPFS, and register the IPFS hash on the blockchain for immutable proof of storage.


 ![image 275@2x](https://github.com/user-attachments/assets/4d4056d5-8409-4bbf-8481-9f0c2d599cd5) 


---

## Features ✨

- **Decentralized Storage**: Securely store files on IPFS via **web3.storage**.
- **Blockchain Integration**: Immutably record file hashes on the blockchain for transparency and security.
- **User-Friendly Interface**: Built with **React** for a seamless user experience.
- **JWT Authentication**: Secure API interactions with JSON Web Tokens (JWT).
- **Tamper-Proof Records**: Ensure data integrity and ownership verification.

---

## Tech Stack 🛠️

- **React**: Frontend framework for building the user interface.
- **IPFS**: Decentralized storage solution for distributed data storage.
- **Blockchain**: Smart contracts for recording and verifying data storage.
- **JWT**: Secure authentication for API interactions.

---

## Architecture Overview 🏗️


1. **Client**: The user interface where users interact with the application.
2. **API Request**: Users send requests to upload or retrieve data.
3. **Next.js**: Handles the backend logic and processes API requests.
4. **POST Request**: Data is sent to the `/api/uploadData` endpoint.
5. **API Response**: The server responds with the IPFS hash and blockchain transaction details.
6. **web3.storage**: Stores the data on IPFS and generates a unique hash.
7. **Smart Contract**: Records the IPFS hash on the blockchain for immutable proof.

Here’s the architecture diagram for W3Share:

<img src="https://github.com/user-attachments/assets/04e3a2af-d633-4faf-b6e1-5d861bad0fec" alt="W3Share Architecture" height="700px" />  

This diagram illustrates how data flows through the system, from the client to IPFS and the blockchain. 


## Getting Started 🚀

### Prerequisites

- **Node.js** (version 16.x or higher)
- **MetaMask** or any compatible Web3 wallet
- **JWT Token**: Required for secure API interactions.
- **Gateway Address**: Dedicated gateway address for IPFS.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Kamal007OLica/W3share.git
   cd W3share
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up your environment:
   - Add your **JWT token** and **dedicated gateway address** in the appropriate configuration files.

4. Run the application:
   ```bash
   npm start
   ```

---

## Usage 📂

1. Open the application in your browser (typically `http://localhost:3000`).
2. Connect your Web3 wallet (e.g., MetaMask).
3. Upload a file to store it on IPFS.
4. The IPFS hash will be recorded on the blockchain.
5. Retrieve and verify your stored data using the IPFS hash.

---

## Contributing 🤝

We welcome contributions! Here’s how you can get involved:

1. Fork the repository.
2. Create a new branch (`feature-name`).
3. Commit your changes (`git commit -m "Add feature"`).
4. Push your branch (`git push origin feature-name`).
5. Open a pull request.

---

## License 📜

This project is licensed under the **The Unlicense**. This means you can freely use, modify, and distribute the content without any restrictions. For more details, see the [LICENSE](LICENSE) file.
