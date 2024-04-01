# Decentralized Storybook

Welcome to Decentralized Storybook! This is a decentralized application (dApp) built on the Ethereum blockchain where users can share, read, and crowdfund stories using smart contracts.

## Features

- **Story Sharing**: Users can publish their stories and quotes on the platform for others to read. User can add like or also can contribute Ethers to the post.
- **Crowdfunding**: Any user can contribute to the creation of big novels and stories using a crowdfunding technique. Here's how it works: When a user writes a story, it becomes an option for a particular chapter. The story that garners enough support in terms of ethers from viewers within a given deadline will be selected for that chapter. This democratic approach ensures that the most captivating and supported stories become an integral part of the narrative, fostering a dynamic and engaging storytelling experience.
- **Decentralization**: Stories and transactions are stored on the Ethereum blockchain, ensuring transparency and censorship resistance.
- **Security**: Smart contracts govern the crowdfunding process, ensuring that funds are securely managed and distributed.

## Technologies Used

- **Ethereum Blockchain**: Smart contracts are deployed on the Ethereum blockchain to manage story crowdfunding and ownership.
- **Solidity**: Smart contracts are written in Solidity, Ethereum's smart contract programming language.
- **Next.js**: The frontend of the application is built using Next.js, a React framework for server-rendered applications.
- **ethers.js**: ethers.js is used to interact with the Ethereum blockchain from the frontend, enabling users to read stories and contribute funds.
- **IPFS (InterPlanetary File System)**: Story content is stored on IPFS for decentralized and immutable file storage. Here, Pinata has been used.
- **Truffle**: Truffle is used for smart contract development, testing, and deployment.

## Getting Started

### 1) Install Ganache

### 2) Install Metamask Extension
  ```bash
  - Create New Network with localhost and port in which Ganache is connected.
  - Using Private Key, Import the account to the metamask
  ```

### 3) Deploy Contract:
   ```bash
   cd Backend
   truffle migrate
   ```
  -  Create a config.tsx file in frontend and add contract address to it.

### 4) Run Next.js
  ```bash
  cd Frontend
  npm run dev
  ```
## Screenshots 

