# PyChain Ledger

The purpose of this project is to create a ledger that allows partner banks to conduct financial transactions to verify the integrity of the data in the ledger.

The project uses Python Version 3.7 and dependancies for this project are:

- `streamlit`
- `hashlib`
- `pandas`

The project demonstrates dataclaseses in python and the the sha256 hashing algorithm to return a hexidecimal string.

## Running the app

0. Clone the repository to your local drive
1. Navigate to the folder with pychain.py
2. Run application by typing `streamlit run pychain.py` into the terminal
3. Web app should open automatically @ http://localhost:8501/ (in the app, you can change the nonce difficulty, add sender, reciever, and amount, and also validate transactions)
4. To shut down the app, navigate to terminal ant type `ctrl + c`

## App Demo

![](/Resources/APP_Demo.gif)
