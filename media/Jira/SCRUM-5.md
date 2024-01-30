# MFT: Savings account balance displayed when prompted money market account from card 1 (v1.0)

[SCRUM-5](https://ucalgary-seng438.atlassian.net/browse/SCRUM-5) Created: 1/29/24 Updated: 1/29/24

**Description:** When performing a balance inquiry for money market account on card 1, the balance of the savings account is printed on the receipt instead.

**Steps to Reproduce:**

* Insert Card 1 and enter correct PIN
* Select Balance Inquiry
* Select Money Market Account

**Expected behaviour:** Error message should display since card 1 does NOT have a money market account

**Actual behaviour:** Balance of savings account is displayed & the receipt prints Card number 2 instead of Card number 1.