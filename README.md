# Peculium - Ethereum smart contracts



Last version of the Peculium PCL token contract

All contracts are in the contracts/ folder

Peculium.sol is the contract of the PCL token

PeculiumOld.sol is the contract of the old PCL token

All other contracts are from OpenZeppelin and are dependencies for the PCL contract


# Requirements

NodeJs and npm

Solc (the Solidity compiler)
```
npm install -g solc
```

# Deployment
```
solc --bin contracts/Peculium.sol
```

copy the EVM bytecode from terminal

paste it into MyEtherWallet (tab "Contracts:create a contract")

pay gas fees and deploy it
