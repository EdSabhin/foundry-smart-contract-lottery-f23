# Provably Random Raffle Contracts

## About

This code is to create a provably smart contract lottery.

## What do we want to do?

1. Users can entern by paying for a ticket
  1.1 The ticket fees are going to go to the winner during the draw.

2. After X period of time the lottery will automatically draw a winner.
  2.1 This will be done programmatically.
  
3. Using Chainlink VRF & Chainlink Automation
  3.1 Chainlink VRF --> Randomness
  3.2 Chainlink Automation --> Time-based trigger

## Tests

1. Write some deploy scripts

2. Write tests
  1. Works on a local chain
  2. Forked Testnet
  3. Forked Mainnet