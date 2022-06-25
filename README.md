# Crypto_Wallet

## Imports
```python
import os
import requests
from dotenv import load_dotenv
load_dotenv()
from bip44 import Wallet
from web3 import Account
from web3.auto.infura.kovan import w3
from web3 import middleware
from web3.gas_strategies.time_based import medium_gas_price_strategy
```

## Instructions
The steps for this challenge are broken out into the following sections:

* Import Ethereum Transaction Functions into the Fintech Finder Application
* Sign and Execute a Payment Transaction
* Inspect the Transaction on Ganache
### Step 1: Import Ethereum Transaction Functions into the Fintech Finder Application

* Add your mnemonic seed phrase (provided by Ganache) to the starter code’s SAMPLE.env file. When the information has been added, rename the file .env.


### Step 2: Sign and Execute a Payment Transaction


* Fintech Finder customers will select a fintech professional from the application interface’s drop-down menu, and then input the amount of time for which they’ll hire the worker. 

## Results
Streamlit:
![Streamlit](https://user-images.githubusercontent.com/97059769/175784744-3ba44f7a-ff63-47f5-bef1-6a3a474194f1.png)

Ganache Balance:
![Ganache Balance](https://user-images.githubusercontent.com/97059769/175784710-e6714835-30aa-4ad9-a0c9-129c4d4732ec.png)

Ganache Transaction to Recipent:
![Ganache Transaction](https://user-images.githubusercontent.com/97059769/175784732-69d62776-e356-485b-b98e-5331eba7c945.png)

