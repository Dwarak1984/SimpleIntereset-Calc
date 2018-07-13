# Starter kit - Ethereum Project

## Introduction
  This is a starter project kit for Ethereum Projects. This project implementes _**Simple Interest**_ scenario.
  
## Getting Started 
  These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

1.Truffle Latest Version
2.Testrpc
3.Metamask
4.Node js (We need this to install truffle and testrpc)
 
### Installation Steps
**Case 1 : OS : Ubuntu 14.04 and 16.04** 
#### Install Packages
First, update and install packages
```
# sudo apt-get update && sudo apt-get -y upgrade
# sudo apt-get -y install curl git vim build-essential 

```
#### Install NodeJs
Install NodeJs to execute the DAPP
```
# curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -
# sudo apt-get install -y nodejs
# sudo npm install -g express

```
#### Install Truffle
Install Truffle packages
```
# sudo npm install -g truffle
```
#### Install testrpc
testprc uses ethereumjs to simulate full client behavior and make developing Ethereum
##### Install testrpc

```
# sudo npm install -g ethereumjs-testrpc

```
##### Launch testrpc

```

testrpc -m "Your browser seedwords for metamask"

```
#### Install Metamask for Crome

1. Go to : (https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=en)
2. Click on **Add to Crome** as shown in below image.
![Add to Crome](/images/0_G5l8hOVqhjQ1kxhC.png)
3. Click on Metamask plugin 
4. Create New Password
![Password](/images/download.png)
5. Save Seedwords
![SeedWords](/images/download(1).png)

**Case 2 : Windows 10**

1. Pre-step: Install Chocolatey

Install Chocolatey via (https://chocolatey.org/)

2. Install Windows tools with Chocolatey:

Open a PowerShell prompt as an Administrator and run the following commands (last command optional):

```
# choco install nodejs.install –y
# choco install git –y
# choco install VisualStudioCode -y  
```
3. Install the tools via npm:

Open a NEW PowerShell prompt as Administrator (to ensure that it reloads), then run the following commands:

```
# npm install -g npm
# npm install -g -production windows-build-tools
# npm install -g ethereumjs-testrpc
# npm install -g truffle

```

### Setting Application

1.git clone https://github.com/OriginProtocol/demo-dapp origin-demo-dapp && cd origin-demo-dapp

2.Unzip Starter_kit.zip

3.Open Terminal1 / Command promt

4.cd Starter_kit // Go to Startup-kit directory

5.truffle compile // This step will create build folder.

6.Open Terminal2 / Another Command promt

7.Start testrpc by command ->  testrpc -m "seedwords of Metamsk"

8.truffle migrate //migrate smart contract to running blockchain 

9.npm run dev // To run the application in browser

10.open "http://localhost:8080" in web browser



**Thats it folks!**

**Implement your own DApp.**
