# InteractionLogger

## Overview
The **InteractionLogger** is a lightweight and efficient Solidity smart contract designed to log user interactions on the Ethereum blockchain. Each interaction is recorded with a timestamp, ensuring immutability and transparency. The contract provides a simple way to track engagement and activity on-chain while maintaining an event-driven architecture.

## Features
- Logs interactions with a timestamp.
- Emits an event (`InteractionLogged`) upon each interaction.
- Provides a function (`getInteractionCount()`) to retrieve the number of recorded interactions.
- No constructor or external dependencies, making it lightweight and easy to deploy.
- Suitable for tracking engagement in decentralized applications (DApps).

## How It Works
1. Users call the `logInteraction()` function to record an interaction.
2. The contract stores the timestamp of the interaction.
3. The event `InteractionLogged` is emitted for external monitoring.
4. Users can retrieve the total number of interactions using `getInteractionCount()`.

## Deployment
To deploy the contract:
1. Use any Solidity-compatible environment such as Remix, Hardhat, or Truffle.
2. Deploy the `InteractionLogger` contract.
3. Interact with it by calling the `logInteraction()` function.

## Use Cases
- Monitoring DApp user engagement.
- Verifying participation in blockchain events.
- Creating an immutable record of smart contract interactions.

## License
This project is open-source and available under the MIT License.
