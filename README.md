# frontrunningbot
frontrunning sniper cross chain. When the contract owner attempts to add liquidity, this bot will auto buy before any other transactions, while the liquidy is pending

Installation
Download the repo with

git clone https://github.com/georgeunidev/frontrunningbot.git
cd my-project
Then edit env.json and save your changes
```json
{
    "RPC": "https://bsc-dataseed.binance.org/", 
    "CHAIN": 56, 
    "RECIPIENT": "0x00000000000000000000000000",  
    "PRIVATE_KEY": "xxxxxxxxxxxxxxxxxxxxxxxxxx",   
    "CONTRACT_TO_SNIPE": "0x000000000000000", 
    "MULTIPLIER": "1",
    "GAS_LIMIT": "1000000",
    "AMOUNT_TO_BUY": "0.5" ,
    "honeypotcheck":"true"
}
```

RECIPIENT = Your address to receive tokens at

PRIVATE_KEY = Your private key to sign the transaction



Run Powershell or a terminal

  cd my-project
  npm i
  node app.js
