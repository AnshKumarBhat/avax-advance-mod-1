# avax-advance-mod-1

## Introduction

Welcome to the DeFi Kingdom Clone project! This repository focuses on setting up an EVM subnet on the Avalanche network and deploying foundational smart contracts to build a DeFi Kingdom clone. While it's important to understand the intricacies of how DeFi works and how to generate value for users, this guide will primarily focus on the technical setup and deployment process.

## Table of Contents

1. [Prerequisites](#prerequisites)
2. [Setup](#setup)
   - [Installing Dependencies](#installing-dependencies)
   - [Configuring the EVM Subnet](#configuring-the-evm-subnet)
3. [Deploying Smart Contracts](#deploying-smart-contracts)
4. [Testing and Verification](#testing-and-verification)
5. [Contributing](#contributing)
6. [License](#license)

## Prerequisites

Before starting, ensure you have the following:

- Node.js and npm installed
- Avalanche CLI installed
- Solidity compiler
- MetaMask or another Web3 wallet
- Basic understanding of blockchain and smart contracts

## Setup

### Installing Dependencies

Clone the repository and navigate to the project directory:

```sh
git clone https://github.com/yourusername/defi-kingdom-clone.git
cd defi-kingdom-clone
```

Install the necessary dependencies:

```sh
npm install
```

### Configuring the EVM Subnet

1. **Initialize the Avalanche CLI:**

    Follow the [official Avalanche documentation](https://docs.avax.network/) to set up the Avalanche CLI and configure your network.

2. **Create a New Subnet:**

    ```sh
    avalanche subnet create mySubnet
    ```

3. **Deploy the Subnet:**

    ```sh
    avalanche subnet deploy mySubnet
    ```

4. **Connect MetaMask to the New Subnet:**

    Add the new subnet to MetaMask by configuring a custom RPC network with the details from your deployed subnet.

## Deploying Smart Contracts

1. **Compile the Smart Contracts:**

    ```sh
    npm run compile
    ```

2. **Deploy Contracts:**

    Use a deployment script or framework like Truffle or Hardhat. For example, with Hardhat:

    ```sh
    npx hardhat run scripts/deploy.js --network yourNetwork
    ```

3. **Verify Deployment:**

    Ensure the contracts are deployed correctly by checking their addresses and interactions on a blockchain explorer or using tools like Etherscan.

## Testing and Verification

Run the test suite to verify the functionality of your smart contracts:

```sh
npm test
```

Make sure all tests pass and the contracts behave as expected.

## Contributing

We welcome contributions from the community! Please follow these steps to contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Create a new Pull Request

Please ensure your code follows our coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Thank you for your interest in the DeFi Kingdom Clone project! We look forward to building a thriving DeFi ecosystem together. If you have any questions or need further assistance, feel free to open an issue or join our community discussions.
