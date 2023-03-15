# Foundry Hardhat Template

A simple project template that uses foundry with hardhat and allows writing tests or scripts in both typescript and solidity, along with linting.

Cloning the repo:
```bash
git clone https://github.com/apoorvsingal/foundry-hardhat-template
```

Installing dependencies:
```bash
pnpm deps:install
```

Running tests:
```bash
pnpm test
```

Project layout:
```bash
.
├── contracts
│   ├── Counter.sol
│   └── Lock.sol
├── test
│   ├── Lock.ts
│   └── foundry # foundry tests go here (they don't have to but it's nice to have the separation)
│       └── Counter.t.sol
├── scripts
│   ├── Lock.ts
│   └── foundry # foundry scripts go here (again, they don't have to)
│       └── Counter.t.sol
├── mocks
│   └── MockCounter.sol
├── lib # foundry libraries installation directory
│   ├── ds-test
│   ├── forge-std
│   └── ...
├── ...
```