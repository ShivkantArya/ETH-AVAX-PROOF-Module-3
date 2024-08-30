# SimpleToken

A simple ERC20 token contract implemented in Solidity using OpenZeppelin's ERC20 library.

## Overview

`SimpleToken` is a basic ERC20 token contract that demonstrates the implementation of an ERC20 token using OpenZeppelin’s standard library. The token is named "Simple" and has the symbol "SIMP". Upon deployment, the contract mints 100 tokens to the deployer's address.

## Features

- **Token Name**: Simple
- **Token Symbol**: SIMP
- **Initial Supply**: 100 tokens (minted to the deployer's address)
- **Decimals**: Standard (18 decimals)

## Prerequisites

- [Node.js](https://nodejs.org/) (for development tools)
- [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/) (package manager)
- [Hardhat](https://hardhat.org/) (Ethereum development environment)
- [OpenZeppelin Contracts](https://docs.openzeppelin.com/contracts/4.x/) (for ERC20 implementation)

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/ShivkantArya/ETH-AVAX-PROOF.git
* First, go to the Remix Site (https://remix.ethereum.org/).
* Now Copy the Code below in the IDE and Save the file with .sol (eg. MyTransaction.sol) extension.
  
```javascript
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

import "@openzeppelin/contracts/token/ERC20/ERC20.sol";

contract SimpleToken is ERC20 {
    constructor() ERC20("Simple", "SIMP") {
        // Mint 100 tokens to the contract deployer
        _mint(msg.sender, 100 * 10 ** decimals());
    }
}
```
* #### Compile the Contract:
    Open the “Solidity Compiler” tab in the left-hand sidebar, ensure that the “Compiler” option is set to version “0.8.7” (or Auto Compile is enabled , it will 
    automatically select the suitable version) and then click on the “Compile MyTransaction.sol” button.
* #### Deploy the Contract:
    Navigate to the “Deploy & Run Transactions” tab in the left-hand sidebar, from the dropdown menu, select the “MyTransaction” contract and then click on the “Deploy” button.
* #### Interact with the contract
    Once the contract is deployed , you can interact by calling the "deploy", "withdraw" and "invest" function.


## Authors

ShivkantArya

shivkantarya588@gmail.com@gmail.com

## License

This project is licensed under the MIT License - see the LICENSE.md file for details
