# Secure Voting System using Ethereum's Blockchain
## **Description:**
A Secure E-Voting Decentralised App using Ethereum Blockchain and Node.js

## **Requirements for compiling and interacting with the Voting DApp:**


### **Packages**: 
1. Open a terminal (make sure you have permissions to download and install packages)
2. Run these commands to install git, nodejs, npm, and truffle framework
```bash
sudo apt-get install git
sudo apt install nodejs
sudo apt-get install npm
sudo apt-get install build-essential
sudo npm install -g truffle
```

### **Steps to compile and host the voting DApp**:
1. Change into Secure_voting directory
```bash
cd Secure_voting
```
2. Open two new terminals in the project directory (so you should have three different terminals in the Secure_voting directory)
3. In terminal 3, run the nodejs component of Secure_voting
```bash
cd app/javascripts
node node.js
```
4. In terminal 2, run the virtual memory blockchain (testrpc/ganache-cli)
```bash
./node_modules/.bin/ganache-cli
```
5. In terminal 1, we will compile the voting smart contracts and deploy them onto the virtual memory blockchain
```bash
truffle migrate
```
6. In terminal 1 again, we will host the voting DApp
 ```bash
npm run dev
```

