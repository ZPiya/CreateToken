# CreateToken
This Solidity program is a project to create a token named "META". The purpose of this program is to provide a basic implementation of token functionalities such as minting and burning tokens, which can serve as a foundation for more advanced token projects.

## Description
This repository contains a Solidity smart contract for a token named "META". The contract includes functionalities for minting new tokens and burning existing tokens. The contract is written in Solidity version 0.8.18 and includes public variables for the token's name, abbreviation, and total supply, as well as a mapping to keep track of token balances.

## Solidity Version
The contract is written in Solidity version 0.8.18.

## Public Variables
- `tokenName`: Name of the token ("META").
- `tokenAbbrv`: Abbreviation of the token ("MTA").
- `totalSupply`: Total supply of tokens, initially set to 0.

## Mapping
- `balances`: Maps addresses to their token balances.

## Functions

### Mint Function
Increases the total supply of tokens and adds the specified amount to the balance of `_address`.

### Burn Function
Reduces the total supply of tokens and deducts the specified amount from the balance of `_address`. Includes a check to ensure the address has enough tokens to burn.

## Getting Started

### Usage
To use this contract, follow these steps:
1. **Deploy the contract**: Deploy the contract to a supported Ethereum network.
2. **Interact with the contract**: Use a web3-enabled application or framework to interact with the contract.
3. **Mint tokens**: Use the `mint` function to create new tokens.
4. **Burn tokens**: Use the `burn` function to destroy tokens.


## License
This project is licensed under the MIT License - see the LICENSE.md file for details.
