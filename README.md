Storage Contract Deployment
This project deploys and verifies a simple Storage.sol contract on the Sepolia (Ethereum) and CoreDAO Sepolia testnets using Remix.
Project Structure

contracts/: Contains the Storage.sol contract.
Storage.sol: A simple contract that stores and retrieves a number.

Deployed Contract Addresses

Sepolia (Ethereum):
Remix: 0x123... 


CoreDAO Sepolia:
Remix: 0x456...



Setup Instructions

Remix Setup:
Open https://remix.ethereum.org.
Create Storage.sol and paste the contract code.
Compile with Solidity version 0.8.20.


MetaMask Setup:
Add Sepolia and CoreDAO Sepolia networks to MetaMask.
Fund wallet with test ETH using faucets:
Sepolia: https://sepoliafaucet.com or https://www.alchemy.com/faucets/ethereum-sepolia
CoreDAO Sepolia: https://bridge.testnet.coredao.org




Deployment:
In Remix, use "Injected Provider - MetaMask" to deploy on Sepolia and CoreDAO Sepolia.
Note the contract addresses from the "Deployed Contracts" section.


Verification:
Verify on https://sepolia.etherscan.io for Sepolia using Standard Input JSON from Remix.
Verify on https://sepolia.explorer.coredao.org for CoreDAO Sepolia using the same JSON.



Usage

Interact with contracts via block explorers (sepolia.etherscan.io or sepolia.explorer.coredao.org).
Use store(uint256) to set a number and retrieve() to get the stored number.
