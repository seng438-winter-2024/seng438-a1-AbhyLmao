# MFT: Incorrect amount added to account after valid deposit (v1.0)

[SCRUM-6](https://ucalgary-seng438.atlassian.net/browse/SCRUM-6) Created: 1/29/24 Updated: 1/29/24

**Description:** When making a deposit into any card, the amount added to the account is $10 less than the amount of cash deposited.

**Steps to Reproduce:**

* Enter any card
* Enter correct PIN
* Select Deposit
* Enter an amount greater than $10
* Finish the deposit

**Expected behaviour:**

* The correct amount of cash deposited will be added to the account

**Actual behaviour:**

* An amount of $10 less will be added to the account