# Fintech--python-blockchain

The pychain excersise was to build and validate a blockchain using the python programming language and display the key attributes of a blockchain using a streamlit web app.

## Pychain
The structure of the python blockchain was built using dataclasses to handle the blockchain functionality, instances of the classes then store and manipulate the data. Validation is done using the python haslib library and chain validation is done by checking the entire chain hash.

![example_ledger](images/pychain_ledger.png)


## Streamlit app
The streamlit app can inspct blocks, change hashing difficulty and add blocks (with data) to the blockchain. some basic error handling was implemented to stop invalid transaction amounts to be placed onto the blockchain.

![app_interface](images/pychain_app.png)