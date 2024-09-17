# Solidity-MyToken-Contract

## Overview
This is a basic smart contract called MyToken, consist of a basic token implementation allowing the owner to mint tokens and users to transfer tokens to others. It was developed during the HackQuest Ethereum & Solidity Training and is designed to be deployed and tested using the Ethereum testnet via Remix IDE.

## Features

- Minting: Only the contract owner can mint new tokens and assign them to an address.
- Transfer: Any user can transfer tokens to another user, provided they have sufficient balance.
- Balance Query: Anyone can check the token balance of an address.

## How to Deploy and Test on Remix IDE
1. **Open Remix IDE: Navigate to Remix IDE**.

2. **Create a New File**:

  - In the Remix IDE file explorer, create a new file called MyToken.sol.
  - Copy and paste the contract code into the file.

3. **Compile the Contract**:

  - Go to the "Solidity Compiler" tab in Remix and select the compiler version 0.8.17 (or higher).
  - Click the "Compile MyToken.sol" button.

4. **Deploy the Contract**:

  - In the "Deploy & Run Transactions" tab, ensure the environment is set to Injected Web3 for testnet (e.g., Goerli or Sepolia).
  - Connect your MetaMask wallet to the Remix IDE.
  - Click the "Deploy" button to deploy the contract to the selected Ethereum testnet.
  - After deployment, the contract will appear in the Deployed Contracts section.
5. **Interact with the Contract**:

  - Mint Tokens: As the contract owner, you can call the mint function to mint tokens to any address.
  - Check Balances: Use the balanceOf function to query the balance of any address.
  - Transfer Tokens: Use the transfer function to send tokens to other users.

6. **Test the Contract**:

  - Use a test account from MetaMask to simulate transfers.
  - Monitor the balances before and after transfers using balanceOf.
