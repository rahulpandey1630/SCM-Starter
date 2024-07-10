# Starter Next/Hardhat Project

This project is a simple Ethereum smart contract and frontend application using Next.js and Hardhat. The smart contract allows deposits, withdrawals, and displays a greeting message.

## Prerequisites

- Node.js and npm installed
- MetaMask extension in your browser

## Getting Started

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
## Install dependencies:

bash
Copy code
npm install
Open three terminals in your project directory:

First terminal: For running the frontend.
Second terminal: For running the Hardhat local blockchain.
Third terminal: For deploying the contract.
Run the Hardhat local blockchain (in the second terminal):

bash
Copy code
npx hardhat node
Deploy the smart contract (in the third terminal):

bash
Copy code
npx hardhat run --network localhost scripts/deploy.js
Run the frontend application (in the first terminal):

bash
Copy code
npm run dev
Access the application:

Open your browser and go to http://localhost:3000.

Usage
 Connect your MetaMask wallet to interact with the contract.
 Deposit: Add 1 ETH to the contract balance.
 Withdraw: Remove 1 ETH from the contract balance.
 Get Greeting: Retrieve a greeting message from the contract.
## Smart Contract Details
 Assessment.sol: Contains functions for deposit, withdrawal, balance retrieval, and a greeting message.
# Functions:
 getBalance(): Returns the contract balance.
 deposit(uint256 _amount): Allows the owner to deposit a specified amount.
 withdraw(uint256 _withdrawAmount): Allows the owner to withdraw a specified amount.
 getGreeting(): Returns a greeting message.
## Frontend
 Built with Next.js and Ethers.js for interacting with the Ethereum blockchain.
 Styled using simple CSS for a clean and minimal interface.
## Important Notes
Make sure your MetaMask is connected to the localhost:8545 network.
Use the accounts provided by the Hardhat local node for testing.
## License
This project is licensed under the MIT License.
