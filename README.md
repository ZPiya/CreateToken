# CreateToken
A project to create a token under the module of Solidity

# Overview
This repository contains a Solidity smart contract for a token named "META". The contract includes functionalities for minting new tokens and burning existing tokens.

# Solidity Version
The contract is written in Solidity version 0.8.18.

# Public Variables

- tokenName: Name of the token ("META").
- tokenAbbrv: Abbreviation of the token ("MTA").
- totalSupply: Total supply of tokens initially set to 0.

# Mapping
- balances: Maps addresses to their token balances.

# Functions

## Mint Function
Increases the total supply of tokens and adds the specified amount to the balance of `_address`.

## Burn Function
Reduces the total supply of tokens and deducts the specified amount from the balance of `_address`. Includes a check to ensure the address has enough tokens to burn.

## Usage
To use this contract:
1. Deploy the contract to a supported Ethereum network.
2. Interact with the contract using a web3-enabled application or framework.
3. Use the `mint` function to create new tokens.
4. Use the `burn` function to destroy tokens.
