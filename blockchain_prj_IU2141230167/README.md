# 🗳️ Voting DApp

### This is a decentralized application (DApp) for a blockchain-based voting system. It provides a user-friendly interface for both administrators (proposal creators) and voters to interact with the decentralized voting process.

# Admin Features:
### Create Proposal: Admin can create new proposals for voting.
### View Votes: Admin can monitor vote counts and check results in real-time.

# User Features:
### Vote on Proposals: Users can cast votes on active proposals.
### View Proposals: Users can browse available proposals to vote on.
### MetaMask Integration: Users can connect their MetaMask wallet to securely vote using the blockchain.

## ⚙️ Project Setup

### Prerequisites:
- **Node.js** (v14 or later)
- **MetaMask**: Browser extension to interact with Ethereum-compatible networks.
- **GoChain Volta Testnet**: Blockchain network used for testing.

### Installation Steps:
 clone the repository:
```
git clone https://github.com/vp2008a/blockchain_prj_IU2141230204.git

```
After you cloned the repository, you want to install the packages using:
```
  npm install
```
### Install project dependencies:
Set up environment variables:
Create a .env file in the root directory and configure it as follows:
```
API_URL=https://volta-rpc.energyweb.org
PRIVATE_KEY=your_private_key_here
CONTRACT_ADDRESS=deployed_contract_address_here
```
🛠️ Usage
Running the App:
To deploy the contract on GoChain Volta testnet, run:
``` npx hardhat run scripts/deploy.js --network volta```


## Features

- **Proposals**: Users can create proposals that are stored on the blockchain.
- **Voting Mechanism**: Registered voters can cast one vote per proposal.
- **Result Calculation**: The smart contract calculates and stores the results on the blockchain for transparency.



## Deployment

This DApp can be deployed on any Ethereum-compatible testnet such as GoChain Volta or Ethereum Rinkeby.


  


  
