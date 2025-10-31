# web3-curriculum-ethereum_aymmj

Rebuilt Ethereum-focused Web3 curriculum from freeCodeCamp's original. Build Solidity smart contracts, Hardhat tests, EVM dApps, and L2 integrations. 8 modules, 250+ hours, project-based for job-ready skills. Carbon-neutral via testnets.

## Overview

This repository contains a comprehensive, project-based curriculum for learning Ethereum development in the Web3 space. It's a rebuilt and focused version of freeCodeCamp's original Web3 curriculum, emphasizing Ethereum-specific technologies like Solidity for smart contracts, Hardhat for testing and deployment, EVM-compatible dApps, and Layer 2 (L2) integrations for scalability. 

The curriculum is designed to be carbon-neutral by using testnets for all deployments and interactions, avoiding the energy-intensive mainnet where possible. It's structured into 8 hands-on modules, each building on the previous one, with over 250 hours of content including code-alongs, projects, and challenges to develop job-ready skills.

This curriculum is inspired by Patrick Collins' in-depth blockchain course and tailored for Ethereum enthusiasts.

## Prerequisites

Before starting, you should have:
- Basic knowledge of JavaScript (variables, functions, async/await).
- Familiarity with command-line tools (e.g., Terminal or Command Prompt).
- Node.js (v16+) and npm installed.
- A code editor like VS Code.
- A MetaMask wallet for testnet interactions.
- Basic understanding of blockchain concepts (recommended but not required; Module 1 covers this).

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/mja2001/web3-curriculum-ethereum_aymmj.git
   ```

2. Navigate to the project directory:
   ```
   cd web3-curriculum-ethereum_aymmj
   ```

3. Install dependencies (if any global tools are needed; individual modules may have their own setups):
   ```
   npm install
   ```

4. For each module, follow the specific instructions in its directory (e.g., `cd module-1` and run `npm install` if applicable).

## Getting Started

- Start with Module 1 for foundational knowledge.
- Each module includes:
  - Source code examples.
  - Step-by-step tutorials.
  - Projects to build and deploy.
  - Tests to verify your work.
- Use testnets like Sepolia or Goerli for deployments to keep it carbon-neutral.
- Refer to the `docs/` folder (if present) or inline comments for additional guidance.

## Modules

The curriculum is divided into 8 progressive modules. Each module focuses on practical projects to reinforce concepts.

### Module 1: Blockchain Basics
- Introduction to blockchain technology and Ethereum.
- What is a blockchain and what does it do?
- Purpose of smart contracts.
- Blockchain benefits and real-world applications.
- Making your first transaction.
- Gas concepts.
- How blockchains work (consensus, signing transactions).
- **Project**: Simulate a simple transaction.

### Module 2: Welcome to Remix! Simple Storage
- Setting up Remix IDE.
- Basic Solidity: Types, functions, arrays, structs, mappings.
- Compiler errors, warnings, and debugging.
- Memory, storage, and calldata.
- Deploying your first contract.
- EVM overview.
- **Project**: Build and deploy a simple storage contract.

### Module 3: Remix Storage Factory
- Importing and interacting with contracts.
- Inheritance and overrides.
- Contract factories.
- **Project**: Create a storage factory contract that deploys child contracts.

### Module 4: Remix Fund Me
- Sending ETH and handling reverts.
- Chainlink oracles and price feeds.
- Importing from GitHub/NPM.
- Math in Solidity, libraries, loops.
- Constructors, modifiers.
- Advanced Solidity: Immutable, constants, custom errors, receive/fallback.
- Testnet demo.
- **Project**: Build a funding contract using Chainlink price feeds.

### Module 5: Ethers.js Simple Storage
- Local development setup.
- Compiling Solidity with JavaScript.
- Networks and Ganache.
- Using Ethers.js for interactions.
- Environment variables and private key management.
- Deploying to testnets.
- Verifying contracts on block explorers.
- **Project**: Deploy and interact with the simple storage contract using Ethers.js.

### Module 6: Hardhat Simple Storage
- Hardhat setup and configuration.
- Deploying contracts with Hardhat.
- Custom tasks and local nodes.
- Testing with Hardhat.
- Gas reporting and coverage.
- **Project**: Test and deploy the simple storage contract using Hardhat.

### Module 7: Hardhat Fund Me
- Linting and advanced Hardhat setup.
- Mocking dependencies.
- Solidity style guide.
- Testing (unit, breakpoints, debugging).
- Gas optimizations.
- Staging tests on local nodes.
- **Project**: Full testing and deployment of the Fund Me contract with Hardhat.

### Module 8: HTML/JavaScript Fund Me (Full Stack dApp)
- Connecting web frontends to wallets (e.g., MetaMask).
- JavaScript setup with async programming.
- Sending transactions from a website.
- Listening for events.
- Reading blockchain data.
- Building a simple UI.
- **Project**: Create a full-stack dApp frontend for the Fund Me contract.

## Advanced Topics
For learners ready to go beyond the core 8 modules, explore additional resources in the repo or the original course:
- Smart Contract Lottery (Chainlink VRF and Keepers).
- NFTs (ERC721, IPFS storage).
- DeFi integrations (Aave borrowing/lending).
- Upgradable contracts and DAOs.
- Security and auditing.

## Contributing

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m "Add feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

Please follow the Solidity style guide and include tests for new features.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Based on freeCodeCamp's original Web3 curriculum.
- Inspired by Patrick Collins' blockchain development course.
- Thanks to the Ethereum community, Chainlink, and Hardhat teams.

For questions or feedback, open an issue or contact the maintainer. Happy coding in Web3! 🚀
