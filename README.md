
# Image Sharing - Blockchain-Based File Sharing System

This project is a decentralized image-sharing platform that leverages blockchain technology for secure and immutable image ownership and access control. It allows users to upload, share, and view images in a decentralized manner, ensuring data privacy and security.

## Features

- **Decentralized Image Storage**: Images are stored on IPFS (InterPlanetary File System) to ensure decentralization and immutability.
- **Blockchain-based Ownership**: The ownership of images is managed through Ethereum smart contracts, ensuring secure access and control over image data.
- **User Authentication**: Users interact with the platform through a simple web interface built with React.
- **Smart Contract**: Ethereum-based smart contract for image ownership and access control.
- **Secure Access**: Only authorized users can view or share specific images using the smart contract's access control mechanisms.

## Tech Stack

- **Frontend**: React.js
- **Blockchain**: Ethereum, Solidity
- **Storage**: IPFS (via Pinata API)
- **Smart Contracts**: Solidity
- **Web3**: Web3.js for blockchain interaction
- **Ethereum Testnet**: Deployed on an Ethereum testnet (such as Rinkeby or Goerli)

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/BSirichandana/Image-Sharing.git
   cd Image-Sharing
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the development server**:
   ```bash
   npm start
   ```

4. **Connect your Metamask wallet**: Make sure your Ethereum wallet (e.g., Metamask) is connected to the Ethereum testnet.

5. **Deploy the smart contracts**:
   You may need to deploy your smart contracts to an Ethereum testnet using Hardhat or Truffle.

## Usage

- Upload an image: Select an image from your device and upload it to the platform.
- Share an image: After uploading, the image’s ownership will be stored on the blockchain, allowing for controlled access.
- View an image: Only authorized users can view shared images, depending on the permissions set by the owner.


## Acknowledgements

- [IPFS](https://ipfs.io) for decentralized storage.
- [Ethereum](https://ethereum.org) for blockchain-based image ownership.
- [Pinata API](https://www.pinata.cloud) for managing IPFS storage.
- [Web3.js](https://github.com/ethereum/web3.js/) for blockchain interactions.
