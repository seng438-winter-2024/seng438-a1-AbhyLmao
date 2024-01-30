# MFT: Incorrect amount of cash dispensed and logged during withdrawal (v1.0)

[SCRUM-2](https://ucalgary-seng438.atlassian.net/browse/SCRUM-2) Created: 1/28/24 Updated: 1/29/24

**Description:** When choosing to withdraw $20. ATM dispensed $40 and deducted $40 from account.

**Steps to Reproduce:**

* Insert card 1, enter correct PIN
* Withdraw $20 from checking account.

**Expected behaviour:**

* ATM dispenses $20
* ATM deducts $20 from checking account

**Actual behaviour:**

* ATM dispenses $40
* ATM deducts $40 from checking account