# jadeCoin Project Documentation

## Description

jadeCoin is a simple Ethereum-based token contract that demonstrates basic functionalities of an ERC20-like token.

It allows users to mint (create) and burn (destroy) tokens while keeping track of the total supply and individual token balances.

Getting Started

To get started with jadeCoin, follow these steps:

## Prerequisites

An Ethereum development environment (e.g., Remix, Truffle)

An Ethereum wallet (e.g., MetaMask) for testing on a local blockchain or testnet

## Installing

Clone the jadeCoin repository from GitHub:


  $ git clone https://github.com/yourusername/jadecoin.git
  $ cd jadecoin
Open the project in your preferred Ethereum development environment.
Deploying the Contract
Compile the jadecoin.sol smart contract using the Solidity compiler.

Deploy the contract to a local blockchain or a testnet of your choice.

## Interacting with the Contract

**Mint Tokens:**

Call the mint function, providing an address and an amount to mint.

  function mint(address _address, uint _amount) public {...}

  
**Burn Tokens:**

Call the burn function, specifying an address and an amount to burn.

  function burn(address _from, uint _amount) public {...}
  
**Authors**

Jade

**License**

This project is licensed under the MIT License.

