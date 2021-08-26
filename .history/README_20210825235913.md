
## Getting Started

install dependencies

```
yarn
```

Next, run a local Ethereum node:

```sh
npx hardhat node
```

Deploy the smart contract to the local node:

```sh
npx hardhat run scripts/deploy.js --network localhost
```

Running the above command should print out the addresses where the contract was deployed. Update `config.js` with those values:

```javascript
export const nftaddress = "nft-contract-address"
export const nftmarketaddress = "marketplace-address"
```

Next, run the development server:

```bash
npm run dev
# or
yarn dev
```
