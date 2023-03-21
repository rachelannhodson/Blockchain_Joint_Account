# Blockchain_Joint_Automation
---
## Description

This is a [Solidity](https://soliditylang.org/) file which is to be run in [Remix](https://remix.ethereum.org/). We have created a Joint Savings Account. We have created a contract which holds the funds and provided two addresses which jointly own the account.

We can compile the contract then use [Remix MX (Merge)](https://remix-ide.readthedocs.io/en/latest/run.html#environment), formerly known as Javascript MX, to test the code with some mock transactions. Please see screenshots below.

![initial contract](Execution_Results/initial_balance.png)

We can see above that our balance is 0 Ether. Below the balance, we've provided two accounts (our joint accounts) that will be able to withdraw from the contract address.  We can see that our function to set accounts works accordingly by verifying via the logs, which can be seen below.

Initial Balance

Test 1: Deposit 1 Ether as Wei

Test 2: Deposit 10 Ether as Wei

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