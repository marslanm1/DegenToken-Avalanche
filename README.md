# DegenToken-Avalanche
# Degen Token (ERC-20): Unlocking the Future of Gaming 🎮

## Overview
**Degen Token (DGN)** is an ERC-20 token deployed on the Avalanche Fuji Testnet, developed for Degen Gaming. The token is a reward system to enhance player engagement and loyalty by allowing players to earn tokens, redeem rewards, and trade items in the in-game store. This project demonstrates a practical implementation of an ERC-20 token that can integrate seamlessly into the gaming ecosystem.

## Features
- **Minting New Tokens**: Only the contract owner can mint new tokens and distribute them to players as rewards.
- **Transferring Tokens**: Players can transfer tokens to others for trading or in-game transactions.
- **Redeeming Tokens**: Players can redeem tokens to claim items from the in-game store.
- **Checking Balance**: Players can check their token balance at any time.
- **Burning Tokens**: Players can burn tokens they own if they are no longer needed.

## Technology Stack
- **Smart Contract Language**: Solidity (version ^0.8.23)
- **Development Environment**: Remix IDE
- **Blockchain Platform**: Avalanche Fuji Testnet
- **Libraries Used**: OpenZeppelin (ERC20 & Ownable)

## Getting Started
### Prerequisites
- **MetaMask**: Install MetaMask and connect to the Avalanche Fuji Testnet.
- **Remix IDE**: Access [Remix](https://remix.ethereum.org/) to write, compile, and deploy the smart contract.
- **AVAX Faucet**: Obtain AVAX tokens from the Avalanche Fuji Testnet Faucet to cover gas fees.

### Deployment Steps
1. **Compile the Smart Contract**: Open `DegenToken.sol` in Remix IDE and compile it using the Solidity compiler.
2. **Connect to MetaMask**: 
   - Set the environment to **Injected Provider - MetaMask** in Remix.
   - Ensure MetaMask is connected to the **Avalanche Fuji Testnet**.
3. **Deploy the Contract**: Deploy the compiled contract using Remix.
4. **Test the Contract**: 
   - Use Remix to interact with the contract functions (e.g., mint, transfer, redeem).
   - Verify successful transactions on [Snowtrace](https://testnet.snowtrace.io/).

### Contract Functions
- **mintTokens(address to, uint256 amount)**: Mint new tokens and assign them to a specific address (only owner).
- **redeemSword(uint256 quantity)**: Redeem tokens for in-game items.
- **burnTokens(uint256 amount)**: Burn tokens owned by the sender.
- **transferTokens(address to, uint256 amount)**: Transfer tokens to another player.
- **checkBalance(address account)**: Check the balance of tokens for a specific address.
- **checkSwordsOwned(address user)**: Check the number of in-game swords owned by a player.

### Testing the Contract
- **Minting**: As the contract owner, mint a specified amount of DGN tokens and distribute them to players.
- **Transferring**: Test transferring tokens between different accounts.
- **Redeeming & Burning**: Ensure players can redeem tokens for rewards and burn tokens they no longer need.
- **Checking Balances**: Verify that the token balance functions correctly for different accounts.

## Smart Contract Address
- Deploy on the Avalanche Fuji Testnet
- Verified on Snowtrace: [Link to Verification](https://testnet.snowtrace.io/)


## Acknowledgements
- **OpenZeppelin**: For providing secure and reusable smart contract templates.
- **Avalanche**: For supporting a fast and low-fee blockchain platform ideal for gaming.

## License
This project is licensed under the MIT License.
