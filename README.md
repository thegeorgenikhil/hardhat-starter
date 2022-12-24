# Hardhat Starter

A Token Contract made with Hardhat by using the official [Hardhat documentation](https://hardhat.org/tutorial).

## Useful Scripts

### Running the tests

```bash
npx hardhat test
```

### Deploy the contract to the Goerli testnet

Copy the `.env.example` file to `.env` and fill in the private key and alchemy project key url for the Goerli testnet.

```bash
cp .env.example .env
```

Then run the deploy script.

```bash
npx hardhat run scripts/deploy.js --network goerli
```

### Verify the contract on Etherscan

```bash
npx hardhat verify --network goerli <CONTRACT_ADDRESS>
```
