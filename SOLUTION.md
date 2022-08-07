## What are the smart contracts 
- **UnstoppableLender.sol ---> smart contract for give flashloans** 
- **ReceiverUnstoppable.sol ---> recivers smart contract for execute FlashLoan** 
- **DamnValuableToken.sol ---> just an ERC20 Token** 


## What is our mission
There's a lending pool with a million DVT tokens in balance, offering flash loans for free.
We are trying to stop the pool from offering flash loans...

## Solution 


**1. Here reciver triggers flashloan**
 ![s1](pictures/s1.png) 


**2. Here is the flashloan funtion**
  ![s2](pictures/s2.png) 


**3. The break point is in line 8**
  ![s3](pictures/s3.png) 

The contracts check if that **poolBalance** equal to **balanceBefore**
![s4](pictures/s4.png) 
