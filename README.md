# Sol_advance_4

The following is a Anchor Framework program designed to perform Create NFT, then stake and unstake it but then time difference between them will be the amount
of fungible token that will be minted.

## Description

This is a smart contract implemented in Devnet using the Anchor framework. A client program is provided for testing and interacting with the smart contract.

## Getting Started

### Executing program

To run the program, please follow these steps:

To run this you need to downgrade your solana version to 1.15.2

`npm i`

and install yarn if getting error.

**Build**

`anchor build`

**Deploy**

`anchor deploy`

Once you have completed the above steps,

you can interact with the contract using the following command:

`anchor test`

It will run the create-nft-program.ts file and then all the four functions will be called.
