# avax-i

This repository contains the code and instructions for deploying and interacting with smart contracts on a custom EVM subnet using the Avalanche platform. The project demonstrates how to deploy smart contracts, configure the network, and interact with them using Remix and Metamask.

## Tools Used

- **Unix Computer (MacOS or Linux)**: The development environment for running commands and scripts.
- **Solidity**: The programming language used to write smart contracts.
- **Remix**: An online IDE for writing, compiling, and deploying Solidity smart contracts.
- **Metamask**: A browser extension for managing Ethereum-compatible wallets and interacting with decentralized applications.
- **Web Browser**: For accessing Remix and Metamask.

## Your Project: Step by Step

### 1. Deploy your EVM Subnet using the Avalanche CLI

First, set up and deploy your custom EVM subnet using the Avalanche CLI. Follow the official Avalanche documentation to configure and deploy your subnet.

### 2. Add your Subnet to Metamask

Once your subnet is deployed, add it to Metamask as a custom network:
1. Open Metamask.
2. Click on the network dropdown at the top.
3. Select "Custom RPC" and enter the details of your subnet.

### 3. Make Sure it is Your Selected Network in Metamask

Ensure that your newly added subnet is selected as the current network in Metamask. This will allow you to interact with your deployed smart contracts on this network.

### 4. Connect Remix to Your Metamask

Open Remix in your web browser and connect it to your Metamask wallet:
1. Go to the Remix website.
2. Open the "Deploy & Run Transactions" plugin.
3. In the "Environment" dropdown, select "Injected Web3". This will prompt Metamask to connect.

### 5. Use the Injected Provider

Once connected, Remix will use the injected provider from Metamask, allowing you to deploy contracts directly to your subnet.

### 6. Deploy the Smart-Contracts

With Remix connected to your subnet via Metamask:
1. Write or import your Solidity smart contract in Remix.
2. Compile the contract using the "Solidity Compiler" plugin.
3. Deploy the contract using the "Deploy & Run Transactions" plugin, ensuring the correct contract and account are selected.

### 7. Test Your Application

After deploying your smart contracts, thoroughly test your application:
1. Use Remix to interact with your deployed contracts.
2. Deploy tokens, create pools, and test other functionalities as needed.
3. Verify that all interactions work as expected on your custom subnet.

## Using Remix to Interact with Your Deployed Smart-Contracts

Remix can be used to manage and interact with your deployed contracts. This includes deploying new tokens, managing pools, and more. Ensure you are connected to your custom subnet in Metamask to interact with the contracts deployed on that network.

## Conclusion

Following these steps, you should be able to deploy and interact with smart contracts on a custom EVM subnet using the Avalanche platform. This README provides a high-level overview of the process; refer to the respective tool documentation for detailed instructions and troubleshooting.

Happy coding!
