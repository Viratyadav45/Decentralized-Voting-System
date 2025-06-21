# Decentralized Voting System

## Project Description

The Decentralized Voting System is a blockchain-based solution for conducting secure, transparent, and tamper-proof elections. Built using Solidity, this system ensures that voters can only vote once, and the votes are stored on the blockchain, making them immutable and auditable. This smart contract eliminates traditional issues such as voter fraud and vote tampering.

## Project Vision

The vision behind this project is to create a voting platform that:
- Provides a decentralized solution to voting that is free from the control of centralized entities.
- Enhances transparency by making the voting process immutable and auditable on the blockchain.
- Ensures that every user’s vote is counted fairly, and once cast, cannot be altered.

## Key Features

- **Secure Voting**: Voters can only vote once, and the voting process is transparent and auditable.
- **Ownership of Candidates**: Only the contract owner can add new candidates to the election.
- **Vote Count**: Easily viewable vote count for each candidate in the election.
- **Event Logging**: The contract emits an event each time a vote is cast, which makes it easier to track and verify the process.
- **Immutable**: Votes are stored on the Ethereum blockchain, ensuring they can never be tampered with.

## Future Scope

- **Multiple Elections**: Allow users to run multiple elections within the same contract, each with different sets of candidates and voters.
- **Voting Power**: Implement a system of weighted voting, where users with more tokens or higher reputation can cast more votes.
- **Anonymous Voting**: Use zero-knowledge proofs to implement anonymous voting, ensuring that voters' identities are not revealed while maintaining transparency.
- **Gas Optimization**: Improve the contract for lower gas costs by optimizing functions and storage.

## Setup

1. Clone the repository: `git clone https://github.com/yourusername/DecentralizedVotingSystem.git`
2. Install dependencies: `npm install`
3. Deploy using Truffle or Hardhat:
    - Using Truffle: `truffle migrate --network your_network`
    - Using Hardhat: `npx hardhat run scripts/deploy.js --network your_network`


contract address
0x5ad9baa60ba6659f2211167dc04a33862505cf1d

![image](https://github.com/user-attachments/assets/f88a65f6-e57f-4937-89e1-d3bee3215583)
