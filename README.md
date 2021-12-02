# Convex System Shutdown Benchmarks

This repository benchmarks performance of various Ethereum development frameworks by simulating a call to Convex's `systemShutdown` method. This method uses about 16M gas and performs a number of token transfers

Test commands:
- Hardhat: `yarn` then `yarn hardhat test`
- Dapptools: `dapp update` then `dapp test --rpc-url $ETH_RPC_URL`
- Foundry: `forge test --rpc-url $ETH_RPC_URL`