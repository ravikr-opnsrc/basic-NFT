# A basic NFT Token, ERC-721 


#Prerequisites
Make sure you have MetaMask with Sepolia Ether in your wallet,  
Download and install Node.js on your computer
You need to have Quick Node RPC URL as well as your private key of your wallet. 

#Setting up Hardhat and run following command one after another

'''
npm init --yes
npm install --save-dev hardhat @nomicfoundation/hardhat-toolbox
npx hardhat 
npm install --save-dev @openzeppelin/contracts
'''

# Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```

npx hardhat run scripts/deploy.js --network sepolia
it will compile your contract and then deploy to the Sepolia Test Network. It will also give you the contract address of the deployed contract.

<img width="1440" alt="Screenshot 2023-08-16 at 11 41 38 PM" src="https://github.com/ravikr-opnsrc/basic-NFT/assets/135989427/8f5a2bb0-e24d-4231-8415-a10d3471f542">


 
