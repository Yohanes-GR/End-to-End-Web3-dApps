## End-to-End Web3 dApps
![Algorand Protocol Participation](https://images.prismic.io/algorandfoundationv2/54ad62d1-e7b3-4a74-afdb-0ee376d5ce22_protocol.png)

### Introduction
Web3 technology is inherently about the user controlled internet. It is being achieved by a growing stack of decentralized technologies, such as blockchains, smart contracts, oracles, crypto wallets, storage networks, and more.

### Objective of the Project
This project tries to enable clients to be able to solve the challenges ensuring that certificates are available to all trainees in a secure way, and (if possible) that certificate holders can benefit from smart contract actions now and in the future. At present, certificates are distributed as simple PDF files, without the ability to verify their authenticity nor can trainer undertake smart actions with the trainees/their contracts.

### Setup
To setup you should create a Python 3 virtual environment and then clone this repository. The packages can then be installed from requirements.txt file.

``` 
git clone https://github.com/bkget/AlgodApp.git
cd AlgodApp
pip install -r requirements.txt
```

In order to access the algorand network, the easiest way to get started is by creating an account
at https://developer.purestake.io/login. 
The API keys referenced in this project (found in files `indexer.py` and `algod.py`) should be replaced with your own. 

### How to run the Repository?
To run the repository, simply run `wsgi.py` or use `flask run `.
