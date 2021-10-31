# Running Locally

1. Install the dependencies

```sh
yarn
```

2. Start the local test node

```sh
npx hardhat node
```

4. Deploy the contract

```sh
npx hardhat run scripts/deploy.js --network localhost
```

5. Update __src/App.js__ with the values of your contract addresses (`greeterAddress` and `tokenAddress`)

6. Run the app

```sh
npm start
```

# Troubleshooting

### Nonce to high error

uninstall metamask and reinstall, then add the private key from npx hardhat node
