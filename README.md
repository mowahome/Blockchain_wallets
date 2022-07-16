# Blockchain_wallets
For this project, I imported several functions from the 'crypto_wallet.py' into the 'fintech_finder.py'. I added the mnemonic seed phrase from ganache to the .env file. For the streamlit sidebar, I created a variable named account by calling the generate_account function which creates the Fintech Finder customer's wallet and Ethereum account. Within the same section, i created a function to display the balance of the customer's account by calling the 'get_balance' function and passing it to the Ethereum 'account.address'.

## Sign and Execute a Payment Transaction
I wrote an equation to calculate the candidate's wage (hourly rate * hours) and wrote this variable on the sidebar. I sent a test transaction for candidate Lane usubg hourly rate of 0.2 eth for 150 hours by using the streamlit interface, and then looking up the resulting transation in Ganache. 
![ganache_transaction](ganache_transaction.png)
![transaction_tab](transaction_tab.png)