
## CONTRACT
First, deploy the contract server:

1) Add your metamask mnemonic to .env.
2) Deploy contract to fantomtestnet

```bash
npx hardhat run scripts/deploy.js --network fantomtest

```
3) Copy the contract address to .env

## FRONTEND

Then, run the development server:

```bash
npm run start

```
Open http://localhost:4200 with your browser to see the result.
