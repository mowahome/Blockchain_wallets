# Blockchain_wallets
For this project, I imported several functions from the 'crypto_wallet.py' into the 'fintech_finder.py'. I added the mnemonic seed phrase from ganache to the .env file. For the streamlit sidebar, I created a variable named account by calling the generate_account function which creates the Fintech Finder customer's wallet and Ethereum account. Within the same section, i created a function to display the balance of the customer's account by calling the 'get_balance' function and passing it to the Ethereum 'account.address'.

## Sign and Execute a Payment Transaction
I wrote an equation to calculate the candidate's wage (hourly rate * hours) and wrote this variable on the sidebar. I sent a test transaction for candidate Lane usubg hourly rate of 0.2 eth for 150 hours by using the streamlit interface, and then looking up the resulting transation in Ganache. 
![image](https://user-images.githubusercontent.com/98926434/179368605-9a516f84-4c57-4e40-8e8f-8873ef4d1ba1.png)
![image](https://user-images.githubusercontent.com/98926434/179368618-ceb92e91-3ae3-4db7-8cff-73eb917d257c.png)
