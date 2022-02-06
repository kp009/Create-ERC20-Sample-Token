## Sample ERC20 Token Creation (Udacity Blockchain)

#### 1) To install Truffle (v5.0.2) latest version use the command 
```bash
    npm install -g truffle
```
#### 2) To create a directory and install required packages
```bash
      mkdir SampleToken
      cd SampleToken
      npm init
      npm install --save truffle-hdwallet-provider
      npm install openzeppelin-solidity@2.2.0
```
#### 3) Go to your contracts folder and create file SampleToken.sol

#### 4) Make sure to have ether in rinkeby testnet and connect your metamask to infura

#### 5) Go to your truffle-config.js file update your infura rinkeby endpoint and metamask seed

#### 6) To be able to deploy your token you will need to create a file 2_initial_migration.js in the migrations folder

#### 7) Steps to run a local ethereum network, and deploy your token contract to this local network
```bash
      truffle develop 
      compile
      migrate --reset
```
#### 8) Command to deploy to Rinkeby using Truffle
```bash
     truffle migrate --reset --network rinkeby
```
