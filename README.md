## smart-contract-joint-account
The purpose of this project is to create a joint savings account using a Solidarity smart contract which accepts two user addresses.  These two addresses will be able to control the account, including making deposits, withdrawls, checking balances, and the last account to withdrawl from the join account.  

## Usage
To use this program, download github repository clone in a local environment.  Then open your browser and go to (https://remix.ethereum.org/), select "open file" and load the joint_savings.sol file from the repo.  Select "compile" from the left menu and choose the compiler 0.50+commit.1d4f565a.  Hit the complie button and then once again on the left menu, under the compile button, select "deploy and run transactions."  Make sure the JointSavings contract is selected and hit deploy.  From there you should see this 
![menu](/images/1.png).  Click the arrow by set accounts to expland both accounts.  Copy and paste two of the dummy account address from the menu onto the set accounts fields and hit transact.  At this point, you'll only be able to use these two accounts.  On the top of the menu select how much you wish to deposit and which currency and then go down and hit the red despoit ![button](/images/2.png).  You can deposit in Ether, Wei, Gwei, or Finney.  ![menu](/images/3.png).  You can also make a ![withdrawl](/images/6.png) by selecting the amount you wish to withdrawl and copy and pasting one of your two chosen accounts.  The buttons "contract balance", "lastToWithdrawl", and "lastWithdrawl"  also display information when they are selected after a transaction. ![](/images/7.png) ![](/images/8.png)

## Technologies
This project was created with on with REMIX IDE with Solidarity.

[solidarity](https://soliditylang.org/) is a programming language designed for developing smart contracts that run on Ethereum..

[remix](https://remix-project.org/) is a GUI for developing smart contracts..




## Contributors
Created by Jeffrey Crabill  
jeffreycrabill@gmail.com  
[twitter](twitter.com/jeffcrabill)  
[linkedIn](linkedin.com/jeffreycrabill)  



## Licesne
GNU public lisence.