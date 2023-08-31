![alt=“”](Images/20-5-challenge-image.png)
# Joint Savings on ETH

This repository contains a Solidity smart contract that allows two users to manage a joint savings account on the Ethereum blockchain. The contract uses ether management functions to implement the financial features of the joint savings account, such as depositing and withdrawing funds.

## The repository includes the following files:

joint_savings.sol: This is the Solidity smart contract that defines the joint savings account.
README.md: This file provides instructions on how to develop, compile, and deploy the contract.

To develop the contract, you can follow these steps:

1. Open the joint_savings.sol file in a Solidity IDE, such as Remix.
Make sure that the contract is compatible with the Ethereum Virtual Machine (EVM) version that you are using.
2. Compile the contract by clicking the "Compile" button in Remix.
3. Deploy the contract by clicking the "Deploy" button in Remix.
Once the contract is deployed, you can interact with it using a web3 wallet, such as MetaMask. To deposit funds into the joint savings account, you can send ether to the contract address. To withdraw funds from the account, you can call the withdraw function in the contract.

The contract is open source and available for anyone to use. It can be used by fintech startups to provide their customers with a secure and reliable way to manage joint savings accounts.

To interact with the deployed smart contract, the following steps were taken:

1. The setAccounts function was used to define the two Ethereum addresses that will be authorized to withdraw funds from the contract.

   The setAccounts function takes two arguments: the first argument is the address of the    first authorized user, and the second argument is the address of the second authorized    user.

3. The deposit function was used to deposit ether into the contract.

   The deposit function takes one argument: the amount of ether to deposit.

5. The withdraw function was used to withdraw ether from the contract.

   The withdraw function takes two arguments: the first argument is the amount of ether      to withdraw, and the second argument is the address of the recipient.

Step-by-step
1. Deployed the contract
  <img width="436" alt="1_Joint_Savings_Deployed" src="https://github.com/dxmolnar/Joint_Savings/assets/127795314/e71f33af-72c9-47f3-a253-1dce25cdf3b0">

2. Set AccountOne and AccountTwo
<img width="877" alt="2_Joint_Savings_SetAccounts" src="https://github.com/dxmolnar/Joint_Savings/assets/127795314/255a531e-56f0-4429-8b2d-ee33c3b800c3">

3. Deposited 1 ETH of Wei
<img width="913" alt="3_Joint_Savings_Deposited1eth" src="https://github.com/dxmolnar/Joint_Savings/assets/127795314/29e85ff4-32f1-460b-932a-be4f31b216f8">

4. Deposited 10 ETH of Wei
<img width="934" alt="4_Joint_Savings_Deposited10eth" src="https://github.com/dxmolnar/Joint_Savings/assets/127795314/6ef4e1d3-b181-4914-84b6-647a0806c937">

5. Deposited 5 ETH of Wei
<img width="906" alt="5_Joint_Savings_Deposited5eth" src="https://github.com/dxmolnar/Joint_Savings/assets/127795314/4221a5b9-63d5-45aa-8cb2-7741a8449467">

6. Withdrew 5 ETH
<img width="874" alt="6_Joint_Savings_Withdraw5eth" src="https://github.com/dxmolnar/Joint_Savings/assets/127795314/119c6511-b8df-4c84-bb82-dd276c61f9c8">

7. Withdrew 10 ETH
<img width="941" alt="7_Joint_Savings_Withdraw10eth" src="https://github.com/dxmolnar/Joint_Savings/assets/127795314/330669c2-79b7-4376-b8c8-ea4cbf13eb71">

8. Shows LastToWithdraw amount and address for last txn (10 ETH)
<img width="950" alt="8_Joint_Savings_LastToWithdraw10eth" src="https://github.com/dxmolnar/Joint_Savings/assets/127795314/49202680-63f0-40a7-8464-b9fed0cfe0e4">

