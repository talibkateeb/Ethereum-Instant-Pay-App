# Ethereum-Instant-Pay-App

An Ethereum based application that can send funds to FinTech candidates using their Ethereum account address. The user can use this application to find the FinTech professionals, choose the number of hours they want to hire them for, and pay them by sending an ETH transaction. The transactions can be viewed on [Etherscan](https://etherscan.io/).

---

## Watch how it works

A short video showing a transaction to Kendall from the list of FinTech professionals (DISCLAIMER: I had to change the wage that Kendall takes for the demo because I did not have enough ETH and the Kovan Faucet website is down):

![](https://github.com/talibkateeb/Ethereum-Instant-Pay-App/blob/main/README-Resources/transaction-recording.gif)

A picture of the user's account's transaction history:

![](https://github.com/talibkateeb/Ethereum-Instant-Pay-App/blob/main/README-Resources/sender-transaction-history.png)

A picture of the transaction details:

![](https://github.com/talibkateeb/Ethereum-Instant-Pay-App/blob/main/README-Resources/transaction-details.png)

A picture of the receiver's (Kendall) account's transaction history

![](https://github.com/talibkateeb/Ethereum-Instant-Pay-App/blob/main/README-Resources/receiver-transaction-history.png)

---

## Technologies

* [Python](https://www.python.org/) 

* [Streamlit](https://streamlit.io/) 

* [bip44](https://pypi.org/project/bip44/)

* [Web3.py](https://web3py.readthedocs.io/en/stable/overview.html)

* [Infura API](https://infura.io/)
---

## Installation Guide

Open the terminal or command line and install the following before running streamlit:

    pip install streamlit

    pip install web3==5.17

    pip install bip44

[Register an account with Infura](https://infura.io/register)

Navigate to the folder containing the python file and run the following command:

    streamlit run fintech_finder.py

---

## Contributors

*  Talib Kateeb

---

## License

[Click Here To View](https://github.com/talibkateeb/Ethereum-Instant-Pay-App/blob/main/LICENSE)