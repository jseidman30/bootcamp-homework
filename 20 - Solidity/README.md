# Unit 20 - "Looks like we've made our First Contract!"

### Submission

Create a `README.md` that explains how each of the contracts work and what the motivation for each of the contracts is. Also, please provide screenshots to illustrate the functionality (e.g. how you send transactions, how the transferred amount is then distributed by each of the contracts, and how the timelock functionality can be tested with the `fastforward` function). Alternatively, you can also record your interactions with the contract as a gif (e.g. https://www.screentogif.com/)


Upload the `README.md` to a Github repository and provide the testnet address for others to interact with the contract.

---
### Requirements

* public addresses of all you are looking to pay simultaneously
* an ethereum account with enough ETH in it to perform a transaction
* preferably, Metamask
        ** you will need to set up a custom, localnet, network in metamask. screenshots can be seen [here](www.github.com)
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


<details>
<summary>Option 1</summary>

#### Contract Setup  (35 points)

##### To receive all points, your code must:

* Define all public variables using the assigned criteria. (8 points)
* Create a constructor function that accepts `address payable _one`. (9 points)
* Create a constructor function that accepts `address payable _two`. (9 points)
* Create a constructor function that accepts `address payable _three`. (9 points)

#### Contract Functionality  (35 points)

##### To receive all points, your code must:

* Create the `balance` function using the assigned criteria. (9 points)
* Create the `deposit` function using the assigned criteria. (9 points)
* Create the `fallback` function using the assigned criteria. (9 points)
* Test the contracts tested and add screenshots to your ReadMe.md. (8 points)

#### Coding Conventions and Formatting (10 points)

##### To receive all points, your code must:

* Place imports at the beginning of the file, just after any module comments and docstrings and before module globals and constants. (3 points)
* Name functions and variables with lowercase characters and with words separated by underscores. (2 points)
* Follow Don't Repeat Yourself (DRY) principles by creating maintainable and reusable code. (3 points)
* Use concise logic and creative engineering where possible. (2 points)

#### Deployment and Submission (10 points)

##### To receive all points, you must:

* Submit a link to a GitHub repository that’s cloned to your local machine and contains your files. (5 points)
* Include appropriate commit messages in your files. (5 points)

#### Code Comments (10 points)

##### To receive all points, your code must:

* Be well commented with concise, relevant notes that other developers can understand. (10 points)

</details>