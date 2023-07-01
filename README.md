# Lottery Game Smart Contract

This repository contains a Solidity smart contract that implements a Lottery game on the Ethereum blockchain. The game allows players to participate by using Ethereum cryptocurrency, and a winner is chosen randomly by the manager. The winner receives the reward, which increases with the number of players.

## Getting Started

To get started with the Lottery game smart contract, follow the steps below:

1. Clone this repository to your local machine or download the source code files.

2. Open the Remix IDE (https://remix.ethereum.org) in your web browser.

3. Create a new file in the Remix IDE and copy the contents of the `Lottery.sol` file from this repository into the new file.

4. Compile the smart contract in the Remix IDE by selecting the appropriate Solidity compiler version (0.8.0 or higher).

5. Deploy the smart contract on the Ethereum network of your choice using the Remix IDE's deployment feature. Make sure you have sufficient Ether for gas fees to deploy and interact with the contract.

## How to Play

The Lottery game has the following rules:

- A minimum of 3 players must participate for the game to start.

- Players can participate in the game by sending a specified amount of Ether to the smart contract.

- The reward for the winner is calculated based on the total amount of Ether sent by all participants.

- After the minimum number of players has been reached, the manager can trigger the random selection of a winner.

- The winner receives the entire reward, and the contract is reset for a new round of the game.

- If there is a tie between multiple players, the reward will be equally distributed among the winners.

## Smart Contract Functions

The smart contract provides the following functions:

- `enter()`: Allows a player to enter the Lottery game by sending the specified amount of Ether to the contract.

- `getPlayers()`: Retrieves the list of addresses that have entered the game.

- `pickWinner()`: Allows the manager to randomly select a winner from the list of participants. The winner receives the entire reward.

- `getBalance()`: Retrieves the current balance of the Lottery smart contract.

## Security Considerations

Please note the following security considerations when using the Lottery game smart contract:

- This smart contract is provided as-is without any warranties or guarantees. It is your responsibility to review and understand the code before deploying it.

- Ensure that the Remix IDE is connected to a secure Ethereum network and that you are using a reputable Ethereum provider.

- Be cautious when interacting with smart contracts and sending Ether. Double-check the recipient address and the amount of Ether you are sending.

- The contract is deployed and run on the Ethereum blockchain, which is subject to potential security vulnerabilities. Exercise caution and conduct proper testing before using the contract with real funds.

## Acknowledgements

This Lottery game smart contract is inspired by various open-source examples and tutorials available in the Ethereum community. Thanks to the developers and contributors who have shared their knowledge and code.
