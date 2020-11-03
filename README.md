# Solidity Contracts for Payroll

![](Pictures/digital_shaking_hands.jpeg)

## Contracts

[General Payroll Contract](Code/AssociateProfitSplitter.sol)

- Contract using solidity for basic payroll purposes. Within this contract, you are assuming all three employees will be paid the same. Simply enter the total amount for all three employees and the contract will divide it evenly.

[Tiered Payroll Contract](Code/TieredProfitSplitter.sol)

- Contract using solidity for payroll based on level of employee. Here we have three different levels, with Bob being the king. You can adjust levels within line 25, 30 and 34 for employee 1, employee 2 and employee 3, respectively. 

[Deferred Equity Plan Contract](Code/DeferredEquityPlan.sol)

- Contract using solidity for a stock option plan with vesting. A simple contract that vests 250 shares annually for 4 years. Vests on the same day, year over year. 

## Motivation

With the trend in incorporating technology within finance, we created 3 easy to use contracts on the Ethereum Kovan Test network. Depending on how you wish to pay your employees, we have a contract suited to you. 