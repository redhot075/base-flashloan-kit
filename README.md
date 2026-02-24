# Base Flashloan Starter Kit

Aave V3 flashloan example for Base Sepolia/Mainnet. Borrow/repay in one tx.

## Quick Start

1. **Install:**
   ```
   npm init -y
   npm i @aave/core-v3 @nomicfoundation/hardhat-toolbox
   ```

2. **Config:** Edit `hardhat-config/hardhat.config.js` (private key).

3. **Deploy:**
   ```
   npx hardhat run scripts/deploy.js --network baseSepolia
   ```

4. **Execute flashloan:** Call `executeFlashLoan(asset, amount)`.

## Guide

### Contract
- `BaseFlashLoan.sol`: FlashLoanSimpleReceiverBase, executeOperation repay.

**Aave Pool Provider Base Sepolia:** Check docs.base.org.

Base ready! 🚀
