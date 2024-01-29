# AI NFT Generator

Ethereum-backed AI-NFT Generator
Welcome to the Ethereum-backed AI-NFT Generator, a project that merges the power of Ethereum, artificial intelligence, and non-fungible tokens (NFTs) into a unique and innovative web experience. Crafted by a proficient web developer mastering HTML, CSS, JavaScript, TypeScript, SCrypt, Solidity, and React.js, this project allows users to generate AI-generated images, store them as IPFS files, and mint them as NFTs by connecting their Web3 wallets.

# Project Overview
Technologies Used
[Solidity]: Writing smart contracts to manage the creation and minting of NFTs on the Ethereum blockchain.
[React.js]Developing the front end to interact with users and handle the image generation process.
[NFT.Storage](https://nft.storage/) (Connection to IPFS)
[Hugging Face](https://huggingface.co/) (AI Models)
[Hardhat](https://hardhat.org/) (Development Framework)
[Ethers.js](https://docs.ethers.io/v5/) (Blockchain Interaction)
[MetaMask] Web3 Integration: Allowing users to connect their Web3 wallets for secure transactions and NFT minting.

# Features
AI Image Generation: Users input words to generate unique images using an AI image generator API.

IPFS Storage: Generated images are stored securely on the decentralized IPFS network.

Web3 Wallet Connection: Users can connect their Web3 wallets for secure identity verification.

NFT Minting: Pay a fee to mint NFT versions of generated images on the Ethereum blockchain.

How to Use
Generate AI Image: Input words and generate a unique image using the AI image generator.

Connect Wallet: Securely connect your Web3 wallet to the application.

Mint NFT: Pay a fee to mint an NFT version of your generated image on the Ethereum blockchain.

# Getting Started
## Requirements For Initial Setup
- Install [NodeJS](https://nodejs.org/en/)

## Setting Up
### 1. Clone/Download the Repository

### 2. Install Dependencies:
`$ npm install`

### 3. Setup .env file:
Before running any scripts, you'll want to create a .env file with the following values (see .env.example):

- **REACT_APP_HUGGING_FACE_API_KEY=""**
- **REACT_APP_NFT_STORAGE_API_KEY=""**

You'll need to create an account on [Hugging Face](https://huggingface.co/), visit your profile settings, and create a read access token. 

You'll also need to create an account on [NFT.Storage](https://nft.storage/), and create a new API key.

### 4. Run tests
`$ npx hardhat test`

### 5. Start Hardhat node
`$ npx hardhat node`

### 6. Run deployment script
In a separate terminal execute:
`$ npx hardhat run ./scripts/deploy.js --network localhost`

### 7. Start frontend
`$ npm run start`

# Contributions
Contributions to enhance features, security, or the user interface of the AI-NFT Generator are welcome. Feel free to fork the repository, make improvements, and submit pull requests.

# License
This project is licensed under the MIT License, providing flexibility in using, modifying, and distributing the code.

# Acknowledgments
This project was crafted to explore the intersection of AI, NFTs, and blockchain technology. Special thanks to Greg @ DappUniversity for inspiration and guidance. If you have any feedback or suggestions, please don't hesitate to reach out. Enjoy using the Ethereum-backed AI-NFT Generator!
