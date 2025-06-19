# 002-HelloWorldBank
A simple Ethereum smart contract written in Solidity that functions as a basic bank. Users can deposit and withdraw Ether, and the contract owner has special privileges to withdraw all funds.

## Notes
- This contract is for learning purposes only and not audited.
- Always test thoroughly before deploying to the mainnet.

## Features
- Users can deposit Ether into the contract.
- Users can withdraw a specific amount (if they have enough balance).
- Contract keeps track of each user's balance.
- Owner can withdraw all funds from the contract.
- Red Flag: A Simple access control using an 'onlyOwner' modifier.

## How It Works
- deposit() | Users send Ether to the contract and increase their balance.
- withdraw() | Users can withdraw a specified amount from their balance.
- getBalance() | Returns the balance for the caller.
- withdrawAll() | Allows only the owner to withdraw all funds from the contract.
- isOwner() | Checks if the caller is the owner of the contract.

## Requirements
- Node.js
- Hardhat
- MetaMask ( for testing and interacting)
- Etherenum test network (Sepolia)
