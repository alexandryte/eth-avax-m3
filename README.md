# Mytoken

## Description

Mytoken is a Solidity smart contract that implements the ERC20 standard for a custom token named "JewelAnne" with the symbol "JA". It extends the functionality of OpenZeppelin's ERC20 and Ownable contracts.

## Features

- **ERC20 Standard**: Implements the ERC20 standard for fungible tokens.
- **Token Name and Symbol**: The token is named "JewelAnne" with the symbol "JA".
- **Minting**: The contract creator can mint new tokens to a specified address.
- **Initial Supply**: Upon deployment, 1,000,000 JewelAnne tokens are minted to the contract deployer.
- **Transfers**: Allows token holders to transfer their tokens to other addresses.
- **Ownership**: Utilizes Ownable to ensure that only the owner can mint new tokens.
- **Burning**: Token holders can burn their own tokens.
