MyToken - ERC-20 Token on Ethereum

MyToken (MTK) is a fully compliant ERC-20 token deployed on the Ethereum blockchain, designed to enable efficient and secure peer-to-peer digital transactions. This repository includes the smart contract written in Solidity, allowing for easy implementation of MyToken on Ethereum.

Table of Contents

Overview

Features

Installation

Usage

Smart Contract Details

Testing

Deployment

License



---

Overview

MyToken provides a simple, scalable, and customizable ERC-20 implementation. Built with Solidity, MyToken includes core token functionalities such as transfers, approvals, and allowances, following Ethereum's ERC-20 standards.

Key Token Specifications

Token Name: MyToken

Symbol: MTK

Decimals: 18

Initial Supply: Defined at deployment


Features

Transferable: Enables token transfers between accounts

Allowance System: Allows authorized third-party transfers

Decentralized: Fully compatible with Ethereum’s decentralized blockchain

Customizable Initial Supply: Define token supply at contract creation


Installation

Prerequisites

To work with MyToken, you need:

Node.js and NPM

Truffle or Hardhat for development

Metamask wallet for interacting with the Ethereum network

Remix IDE (optional) for quick contract deployment


Clone the Repository

Clone this repository to your local machine:

git clone https://github.com/yourusername/mytoken
cd mytoken

Usage

To get started with MyToken, you can deploy the smart contract and begin interacting with its functions using either Truffle, Hardhat, or Remix IDE.

Example: Deploying with Remix IDE

1. Open Remix IDE.


2. Create a new file MyToken.sol and copy-paste the smart contract code.


3. Compile the contract using the Solidity compiler.


4. Deploy the contract, specifying the _initialSupply parameter.



Smart Contract Details

The MyToken contract provides the following key functions:

constructor(uint256 _initialSupply): Initializes the token with a given supply.

transfer(address _to, uint256 _value): Sends _value tokens to the _to address.

approve(address _spender, uint256 _value): Allows _spender to withdraw from the caller’s account multiple times, up to _value.

transferFrom(address _from, address _to, uint256 _value): Transfers tokens from _from to _to on behalf of another address, according to allowances.


Each function follows ERC-20 standards to ensure compatibility and seamless integration with Ethereum-based applications.

Testing

To test the contract functions:

1. Write unit tests in JavaScript using the Truffle or Hardhat framework.


2. Run tests using the framework’s testing tools to verify token functionality and compliance.
3. Example command to run tests in Truffle:

truffle test

Deployment

Deploying the MyToken contract to an Ethereum network can be done through a development environment like Truffle, Hardhat, or directly with Remix for ease of use.

Deployment Example (with Truffle)

1. Update truffle-config.js with your network settings.


2. Deploy to your network of choice:

truffle migrate --network <network_name>



License

This project is licensed under the MIT License - see the LICENSE file for details.



Example command to run tests in Truffle:truffle test

Deployment

Deploying the MyToken contract to an Ethereum network can be done through a development environment like Truffle, Hardhat, or directly with Remix for ease of use.

Deployment Example (with Truffle)

1. Update truffle-config.js with your network settings.


2. Deploy to your network of choice:

truffle migrate --network <network_name>



License

This project is licensed under the MIT License - see the LICENSE file for details.

