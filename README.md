# Proveably random raffle contracts

## About

This code is to create proveably random smart contracts lottery

## What we want it to do

1. Users can enter by paying for a ticket
   - the ticket fees are going to go to the winner during the draw
2. After X period of time, the lottery will automatically draw a winner
   - the winner is chosen programmatically
3. We're going to by using:
   - Chainlink VRF - randomness
   - Chainlink automation - time based trigger

## Tests!

1. Write some deploy scripts
2. Write tests:
   - for a local chain
   - for a forked testnet
   - for a forked mainnet
