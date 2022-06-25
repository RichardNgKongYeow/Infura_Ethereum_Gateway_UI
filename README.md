# Blockchain (B1)

### Tech Stack
1. HTML
→ Hypertext Markup Language, a standard markup language for documents designed to
be displayed in a web browser.
2. Web3.js API
→ collection of libraries which allows interaction with Ethereum nodes and smart
contracts.
→ https://web3js.readthedocs.io/en/v1.3.0/
3. JavaScript

### Tools
- Your favorite code editor, or Visual Studio Code (recommended, download from https://code.visualstudio.com/) .
- Infura
→ infrastructure that allows us to easily connect to the Ethereum network, think of it as a
personal Ethereum node.
- Etherscan
→ Ethereum blockchain explorer
→ https://etherscan.io
- Terminal
→ For Windows: Git Bash (recommended), or Command Prompt
→ For Mac: Terminal
- Curl
→ Command-line tool for transferring data using various protocols.

### Objective
1. To understand how to connect to Ethereum blockchain through gateway
2. To understand how to retrieve (read) information about the state of Ethereum blockchain using web3js API

### Instructions
1. Create an infura account
2. Get an infura token and replace it in the web3 provider slot (the line above web3 initialisation has been commented out for you)
3. Save the file and click on the index.html icon from your folders
4. A browser will pop up
5. The page will return the latest block height and gas limit
6. By inputting a 0x address and clicking on submit, it will return the balance of that account

For index2.html:
1. Get an infura token and replace it in the web3 provider slot (the line above web3 initialisation has been commented out for you)
2. Save the file and click on the index.html icon from your folders
3. A browser will pop up
4. The browser should show the latest 20 blocks on the Ethereum blockchain, including the block hash, timestamp, gas price