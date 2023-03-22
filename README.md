# Blockchain_Joint_Automation
---
## Description

This is a [Solidity](https://soliditylang.org/) file which is to be run in [Remix](https://remix.ethereum.org/). We have created a Joint Savings Account. We have created a contract which holds the funds and provided two addresses which jointly own the account.

We can compile the contract then use [Remix MX (Merge)](https://remix-ide.readthedocs.io/en/latest/run.html#environment), formerly known as Javascript MX, to test the code with some mock transactions. Please see screenshots below.

Initial Balance
![](/Execution_Results/1proof_of_first_deployment.png)
![](/Execution_Results/2beginning_balance.png)

Set mock account addresses
![](/Execution_Results/3set_accounts.png)

Test 1: Deposit 1 Ether as Wei
![](/Execution_Results/4deposit_1.png)
![](/Execution_Results/5contractBalance_1.png)

Test 2: Deposit 10 Ether as Wei
![](/Execution_Results/6deposit_2.png)
![](/Execution_Results/7contractBalance_2.png)

Test 3: Deposit 5 Ether 
![](/Execution_Results/8deposit_3.png)
![](/Execution_Results/9contractBalance_3.png)

Test 4: Withdraw 5 Ether and send to Account #1
![](/Execution_Results/10withdrawal_1.png)
![](/Execution_Results/11contractBalance_4.png)

Test 5: Withdraw 10 Ether and send to Account #2
![](/Execution_Results/12withdrawal_2.png)
![](/Execution_Results/13contractBalance_5.png)


---
## 1. Installation

You may download this repository to your local machine by using your termainal to designate a folder on your machine and typing `git clone https://github.com/rachelannhodson/Blockchain_Joint_Account`.
There are no other required installations for this file.

---
## 2. Usage

Please navigate to [Remix](https://remix.ethereum.org/) and use the [Solidity](https://soliditylang.org/) plugin to begin using this file. From there, you can upload the `joint_savings.sol` file. Navigate to the "Deploy & run transactions" icon on the left side menu. Input your account numbers in the "setAccounts" section. Now you can make deposits and withdrawls.

---
## Contributors

[Rachel Ann Hodson](https://www.linkedin.com/in/rachelannhodson/)
rachelannhodson@gmail.com

---
## License

MIT