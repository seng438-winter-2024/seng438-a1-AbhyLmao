# MFT: Incorrect total balance after deposit in account 1 (v1.0)

[SCRUM-1](https://ucalgary-seng438.atlassian.net/browse/SCRUM-1) Created: 1/28/24 Updated: 1/29/24

**Description:** Account 1 originally has $1000 in savings. After depositing $50, the receipt shows total balance of $1040 instead of $1050

**Steps to Reproduce:**

* Turn on system
* Enter 10 for number of $20 bills
* Click to insert card
* Enter 1 for the card number
* Enter 42 as PIN.
* Make a deposit of $50 into the savings account

**Expected behaviour:**

* Receipt should show balance of $1050

**Actual behaviour:**

* Receipt is showing balance of $1040