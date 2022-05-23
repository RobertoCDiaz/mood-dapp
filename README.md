# Mood dApp

My first descentralized application using the Ethereum's Blockchain.

It that changes a variable inside the state of a Ethereum Blockchain Contract.

## About the project

For this project to work, you will need a MetaMask extension installed on your browser, then connect it to one of your MetaMaks wallets.

Then, change the network that MetaMask will use to the *Ropsten Testnet*.

## Installation

1. Clone this repository and cd into it.

```bash
git clone https://github.com/RobertoCDiaz/mood-dapp
cd mood-dapp
```

2. Install npm dependencies.

```bash
npm i
```

## Run application

1. Compile and deploy the [Mood SmartContract](MoodContract.sol) using the [Remix IDE](remix.ethereum.org/#).

    - Copy the code inside the [MoodContract.sol](MoodContract.sol) file in the Remix IDE.
    - Click on the 'Compile' tab.
    - Compile the contract.
    - Switch to the 'Deploy' tab of the IDE.
    - Deploy the MoodContract using the 'Injected Web3' environment.
        - `Note: This environment (along with the account address) will be provided by MetaMask once it connects to the Remix IDE site.`

2. Run server

```bash
npm start
```

3. Connect MetaMask to the frontend using the browser extension.