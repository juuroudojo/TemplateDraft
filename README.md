# 🌎 Camino Builder

🏬 Learn how to deploy and work with smart contracts on Camino network. Dive into different features and techniques employed in smart contracts. This repo will walk you through all of it and teach you how to build the travel industry of the future in simple terms.


## Contents

- [Requirements](#requirements)
- [Quickstart](#quickstart)
- [Deploy the contracts to columbus](#deploy-the-contracts-to-columbus)
- [Interacting with Smart Contracts](#interacting-with-smart-contracts)
- [Contributing to Camino Builder](#contributing-to-camino-builder)

## Requirements

Before you begin, you need to install the following tools:

To run and interact with these projects, you will need:

- [Node.js](https://nodejs.org/en/download/) (version 14.x or higher)
- [npm](https://www.npmjs.com/get-npm) (usually bundled with Node.js)
- [Hardhat](https://hardhat.org/getting-started/#overview) development environment
- [Camino Wallet](https://wallet.camino.foundation/)

## Quickstart

To get started with Camino Builder, follow the steps below:
Clone this repo & install dependencies

```
git clone https://github.com/camino-builder
cd camino-builder
npm install


Create a `.env` file in the root directory and configure it with your MetaMask wallet's private key and a [Columbus testnet]() API key for deploying to testnets:

```dotenv
PRIVATE_KEY="your_private_key"
COLUMBUS_API_KEY="your_columbus_api_key"
```

Compile the smart contracts:

```bash
npx hardhat compile
```

Deploy the contracts to a local test network or a public testnet using Hardhat:

```bash
npx hardhat run scripts/deploy.ts --network localhost
```

## Start Building
 - 🍋  [Create your first NFT](https://github.com/camino-builder/tree/nft)
 - 🍇  [Build a staking smart contract](https://github.com/camino-builder/tree/staking)
 - 🥝  [Deploy a token](https://github.com/camino-builder/tree/token)
 - 🍓  [Build a Liquidity Pool](https://github.com/camino-builder/tree/liquidity-pool)


