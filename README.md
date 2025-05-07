# Ethereum Blockchain Network Project

This project demonstrates how to create a simple Ethereum blockchain network using Truffle and Ganache CLI with a basic Solidity smart contract.

## Prerequisites

- Node.js and npm installed
- Git installed (optional)

## Setup Instructions

1. Clone the repository or download the project files.

2. Install dependencies:

```bash
npm install
```

3. Start Ganache CLI (local Ethereum blockchain):

```bash
npm run ganache
```

This will start Ganache on `http://127.0.0.1:8545`.

4. In a new terminal, compile and deploy the smart contract:

```bash
npm run migrate
```

5. You can now interact with the deployed contract using Truffle console or build your own frontend.

## Project Structure

- `contracts/`: Contains Solidity smart contracts.
- `migrations/`: Deployment scripts for smart contracts.
- `truffle-config.js`: Truffle configuration file.
- `package.json`: Project dependencies and scripts.

## Notes

- The sample contract `SimpleStorage` allows you to store and retrieve a single unsigned integer.
- Ganache CLI simulates a local Ethereum blockchain for development and testing.
