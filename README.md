# Blockchain-Loan Payment System-Dapp <br />
It is Basic Dapp for Blockchain, Creation using Solidity Smartcontract+Truffle+JS using HTML+CSS as front end <br />

# Installation: <br />
1.First update and install packages <br />
```
sudo apt-get update && sudo apt-get -y upgrade
sudo apt-get -y install curl git vim build-essential
```
2.Install NodeJs to execute the DAPP <br />

```
curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash - 
sudo apt-get install -y nodejs
sudo npm install -g express
```
3. Install Truffle packages <br />
      ```sudo npm install -g truffle```
4. Install testrpc(testprc uses ethereumjs to simulate full client behavior and make developing Ethereum) <br />
   ```sudo npm install -g ethereumjs-testrpc```
  
 Clone:  <br />
 clone the repository to your project Directory <br />

# Execution:
1. Open a terminal & change the directory to SimpleInterest-Dapp & run following Commands <br />
      ```truffle compile # compiling solidity files```

2. Open a another terminal and run TestRPC as Dummy Blockchain <br />
      ```testrpc```
   
3. Again open a first Terminal for Remaining Execution <br />
```
truffle migrate
npm run dev
```
pick the url: http://localhost:8080 <br />
4. Then, Paste url in Browser

# Peer-to-Peer-Loan-System
