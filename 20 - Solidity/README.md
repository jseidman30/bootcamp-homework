# Unit 20 - "Looks like we've made our First Contract!"

---
### Requirements

* public addresses of all you are looking to pay simultaneously
* an ethereum account with enough ETH in it to perform a transaction
* preferably, Metamask
        
	**you will need to set up a custom, localnet, network in metamask. screenshots can be seen [here](www.github.com)

* preferably, Ganache, to help with network setup and details. also, to see transactions and blocks happening in realtime
* preferably, Remix, to compile the code from scratch if desired. not strictly necessary though

### Instructions

* choose a way to interact with the smart contract. I used Remix
	** contract address: 0x0355BD12676B61cc86fb528A578Cac54cfDc842D

'''''''''''If using Remix'''''''''''''''''''
* copy in/import code from GitHub
* compile code, ensure no errors
* on deploy and run transactions tab, use injected web3 environment to connect to your Metamask
* input all relevant fields, and select the contract just compiled
* deploy code, input addresses for transfer output. Click transact
* be sure to enter a value large enough to verify transaction success in the "value" field, and then click "deposit" under "deployed contracts" below
* confirm transaction success on Ganache or a block explorer like Etherscan

''''''''''''''''''''''''''''''''''''''''''''

If accessing the smart contract within other code:
* call the "deposit" function, providing a value of 0 or greater in Gwei
