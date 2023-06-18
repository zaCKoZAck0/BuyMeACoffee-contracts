# BUY ME Coffee (Smart Contract)

## Getting Used to hardhat
```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```
## Folder Structure
```shell
thatguyintech@albert BuyMeACoffee-contracts % tree -C -L 1
.
├── README.md
├── contracts
├── hardhat.config.js
├── node_modules
├── package-lock.json
├── package.json
├── scripts
└── test
```
- contracts - folder where your smart contracts live
in this project we'll only create one, to organize our BuyMeACoffee logic
- scripts - folder where your hardhat javscript scripts live
    - we will write deploy logic
    - example buy-coffee script
    - and a withdraw script to cash out our tips
- hardhat.config.js - configuration file with settings for solidity version and deployment

