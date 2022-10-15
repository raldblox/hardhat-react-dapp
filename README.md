# Hardhat-React Boilerplate

This repository contains a sample project that you can use as the starting point for Ethereum project. It's also a great fit for learning the basics of smart contract development.

This repo is forked from the excellent [Hardhat Beginners Tutorial](https://github.com/NomicFoundation/hardhat-boilerplate) and you would be able to follow it by yourself by reading the README and exploring its `contracts`, `tests`, `scripts` and `frontend` directories.

## Development & Testing

### 1. Clone this repository and install its dependencies:

```sh 
git clone https://github.com/raldblox/hardhat-react-dapp
cd hardhat-boilerplate
npm install
```

### 2. Run Hardhat's testing network and Deploy your contract:

```sh
npx hardhat node
npx hardhat run scripts/deploy.js --network localhost
```

### Run the frontend

```sh
cd frontend
npm install
npm start
```

Open [http://localhost:3000/](http://localhost:3000/) to see your Dapp. You need to have [Metamask](https://metamask.io) installed and listening to
`localhost 8545`.

## Guides

You can find detailed instructions on using this repository and many tips in [its documentation](https://hardhat.org/tutorial).

- [Writing and compiling contracts](https://hardhat.org/tutorial/writing-and-compiling-contracts/)
- [Setting up the environment](https://hardhat.org/tutorial/setting-up-the-environment/)
- [Testing Contracts](https://hardhat.org/tutorial/testing-contracts/)
- [Setting up Metamask](https://hardhat.org/tutorial/boilerplate-project#how-to-use-it)
- [Hardhat's full documentation](https://hardhat.org/docs/)

For a complete introduction to Hardhat, refer to [this guide](https://hardhat.org/getting-started/#overview).

## Technicals

This repository uses the recommended hardhat setup, by using [`@nomicfoundation/hardhat-toolbox`](https://hardhat.org/hardhat-runner/plugins/nomicfoundation-hardhat-toolbox). This plugin able to:

- Deploy and interact with your contracts using [ethers.js](https://docs.ethers.io/v5/) and the [`hardhat-ethers`](https://hardhat.org/hardhat-runner/plugins/nomiclabs-hardhat-ethers) plugin.
- Test your contracts with [Mocha](https://mochajs.org/), [Chai](https://chaijs.com/) and our own [Hardhat Chai Matchers](https://hardhat.org/hardhat-chai-matchers) plugin.
- Interact with Hardhat Network with our [Hardhat Network Helpers](https://hardhat.org/hardhat-network-helpers).
- Verify the source code of your contracts with the [hardhat-etherscan](https://hardhat.org/hardhat-runner/plugins/nomiclabs-hardhat-etherscan) plugin.
- Get metrics on the gas used by your contracts with the [hardhat-gas-reporter](https://github.com/cgewecke/hardhat-gas-reporter) plugin.
- Measure your tests coverage with [solidity-coverage](https://github.com/sc-forks/solidity-coverage).

This project also includes [a simple frontend/Dapp](./frontend), which uses [Create React App](https://github.com/facebook/create-react-app).

## License

Code License: MIT
