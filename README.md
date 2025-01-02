# AI & Blockchain for Safe Drug Distribution
A supply chain solution for the safe distribution of medicines using Blockchain and AI.

# Motivation
Counterfeit drugs pose a serious threat to public health as it is difficult for people to know the true value of purchased medicines due to a significant lack of transparency in the current system. Additionally, tampering within the supply chain is difficult to investigate when suspicion of illegal or unethical practices arises.
Pharma-Chain leverages Blockchain and AI to ensure secure, transparent, and verifiable medicine distribution throughout the supply chain, improving trust and traceability.

# Solution Overview
Our solution combines the power of Blockchain and AI to provide an efficient and transparent medicine distribution system.
Blockchain: Uses an open, decentralized, and immutable ledger to ensure transparency and traceability of each transaction in the supply chain.
AI in Pharmacology: Enhances customer service, loyalty, and access to blockchain-based medical intelligence, offering a smarter way to track drugs.

# Key Features:
Secure Distribution: Blockchain ensures that each transaction between entities in the supply chain is secure and tamper-proof.
Smart Contracts: Transactions are automated using smart contracts, ensuring authenticity and reducing human error.
Medicine Traceability: Products can be traced back to their origin through event-based requests and responses within the supply chain.
Rasa Chatbot Integration: Provides an interface for ordering, tracing medicines, and enhancing credit evaluation.
React DApp: A decentralized app built with React Framework for frontend interactions with the blockchain.

# System Overview
Components:
Blockchain: Smart contracts deployed on Ganache and connected through Web3.js and Truffle framework.
Rasa Chatbot: A chatbot integrated to help users interact with the system.
Frontend: Built using React, the DApp interfaces with the blockchain to provide an interactive user experience.
Mobile App: A Flutter app integrated with Rasa for a seamless experience in medicine ordering, tracing, and evaluation.

# Getting Started
# Prerequisites:
Ganache: Install and create a workspace.
Truffle: Install the Truffle npm package globally
npm install -g truffle
Metamask: Download and install the Metamask Chrome extension for blockchain interaction

# Deploy Smart Contracts:
Update the from: address in the truffle-config.js file with an address from your Ganache workspace.

Run the migration command:

truffle migrate --reset

The smart contract will be deployed to the blockchain.

# Run React Development Server:
Navigate to the blockchain directory:
cd blockchain

Install dependencies:
npm install

Start the development server:
npm start

# Run Node.js Server:
Navigate to the server directory:

cd server

Install dependencies:

npm install

Start the server:

npm start
