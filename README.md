# Runner-game_Blockchain
## A runner game built on Blockchain technology in which points earned can be converted into real-world assets.

## Technology Stack & Dependencies

- Solidity (Writing Smart Contract)
- HTML, Css, Javascript For the website
- [Infura](https://infura.io/) Account on Infura as a node provider
- [NodeJS](https://nodejs.org/en/) To install Dependencies
- [Hardhat](https://hardhat.org/) Ethereum development environment
- [Ethers.js](https://docs.ethers.io/v5/) To interact with the blockchain

### 1. Download the Repository

### 2. Install Dependencies:
```
$ cd contracts
```
```
$ npm install
```

### 3. Deploy NFT collection to Polygon Mumbai testnet
```
npx hardhat run scripts/deployNFTCollection.js --network mumbai
```

### 4. Deploy Run token to Polygon Mumbai testnet
```
npx hardhat run scripts/deployRunToken.js --network mumbai

```

### 5. Provide the smart contract addresses in blockchain.js file

