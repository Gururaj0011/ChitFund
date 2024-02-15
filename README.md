# ChitFundsToken Readme

## Overview
ChitFundsToken is a Solidity smart contract that facilitates the management of tokenized chit fund contributions. It allows users to mint, burn, transfer, and redeem tokens representing their contributions to various levels of chit funds.

## Functionality
### Token Minting and Burning
- The contract owner can mint tokens to any address using the `mintTokens` function.
- Users can burn their tokens using the `burnTokens` function, provided they have a sufficient balance.

### Contribution Redemption
- Users can redeem their tokens for contributions to different levels of chit funds.
- There are three contribution levels: Local Chit, High Class Chit, and Superior Chit, each with different costs.
- Users initiate redemption by calling the `redeemContribution` function with the desired contribution type.
- Upon successful redemption, the user's balance is deducted, and their contribution level is recorded.

### Token Transfer
- Users can transfer their contribution tokens to other addresses using the `transferContributionTokens` function.

## Contract Details
- **Contract Name:** ChitFundsToken
- **Token Name:** CHITS
- **Token Symbol:** CHT

## Usage
1. Deploy the contract to a blockchain network.
2. Mint tokens to the desired addresses using the `mintTokens` function.
3. Users can burn their tokens if needed using the `burnTokens` function.
4. Users can redeem their tokens for contributions to chit funds by calling the `redeemContribution` function with the appropriate contribution type.
5. Tokens can be transferred between addresses using the `transferContributionTokens` function.

## License
This project is licensed under the MIT License. See the SPDX-License-Identifier tag in the contract file for more details.

## Author

Gururaj B M 

gururaj48103@gmail.com

