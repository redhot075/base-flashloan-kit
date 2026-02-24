# Base Flashloan Starter Kit\n\nAave flashloan example for Base Sepolia/Mainnet. Borrow/repay in one tx.\n\n## Quick Start\n1. Install: `npm i hardhat @nomicfoundation/hardhat-toolbox @aave/core-v3`\n2. Config: Edit hardhat.config.js (private key)\n3. Deploy: `npx hardhat run scripts/deploy.js --network baseSepolia`\n4. Execute flashloan: Call executeFlashLoan(amount)\n\nSee full guide.

## Verification & Usage

1. Compile: `npx hardhat compile`
2. Deploy: `npx hardhat run scripts/deploy.js --network baseSepolia`
3. Flashloan: Call executeFlashLoan(USDC, amount)

**Aave Pool Provider:** Base Sepolia: 0x... (docs.base.org)

Deps: `npm i @aave/core-v3 @nomicfoundation/hardhat-toolbox`

## Verification & Usage

1. Compile: `npx hardhat compile`
2. Deploy: `npx hardhat run scripts/deploy.js --network baseSepolia`
3. Flashloan: Call executeFlashLoan(asset, amount)

**Aave Pool Provider Base Sepolia:** Check docs.base.org

Deps: `npm i @aave/core-v3 @nomicfoundation/hardhat-toolbox`
