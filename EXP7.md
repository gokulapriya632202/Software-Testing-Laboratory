# Ex.No: 7  ATM Applicationn
### NAME : GOKULA PRIYA P                                                                            
### REGISTER NUMBER : 212222040044
### AIM: 
For ATM system study its system specifications and report various bugs
# Purpose: 
This document describes the software requirements and specification (SRS) for an automated 
teller machine (ATM) network. The document is intended for the customer and the developer 
(designers, testers, maintainers). The reader is assumed to have basic knowledge of banking 
accounts and account services. Knowledge and understanding of Unified Modeling Language 
(UML) diagrams is also required. 
# Scope: 
The software supports a computerized banking network called ‗Bank24„. The network 
enables customers to complete simple bank account services via automated teller machines 
(ATMs) that may be located off premise and that need not be owned and operated by the 
customer’s bank. The ATM identifies a customer by a cash card and password. It collects 
information about a simple account transaction (e.g., deposit, withdrawal, transfer, bill 
payment), communicates the transaction information to the customer’s bank, and dispenses 
cash to the customer. The banks provide their own software for their own computers. The 
‗Bank24„ software requires appropriate record keeping and security provisions. The 
Software must handle concurrent accesses to the same account correctly. 
# Intended Audience: 
The intended audience of this SRS consists of: 
□ Software designers 
□ Systems engineers 
□ /Software developers 
□ Software testers 
□ Customers 
The actors of the system are: 
1. User 
2. ATM Machine 
3. Bank 
# Product Perspective: 
An automated teller machine (ATM) is a computerized telecommunications device that 
provides the customers of a financial institution with access to financial transactions in a 
public space without the need for a human clerk or bank teller. On most modern ATMs, the 
customer is identified by inserting a plastic ATM card with a magnetic stripe or a plastic 
smartcard with a chip, that contains a unique card number and some security information, 
such as an expiration date or CVC (CVV). Security is provided by the customer entering a 
personal identification number (PIN). 
Take ATM system and study its system specifications and report various bugs
Exp.N/O: 08 
Date:18/03/2024
# Product functions: 
Using an ATM, customers can access their bank accounts in order to make cash withdrawals 
(or credit 
card cash advances) and check their account balances. The functions of the system are: 
1. Login 
2. Get Balance Information 
3. Withdraw Cash 
4. Transfer Funds 
# Operating Environments: 
The hardware, software and technology used should have following specifications: 
□ Ability to read the ATM card. 
□ Ability to count the currency notes. 
□ Touch screen for convenience. 
□ Keypad(in case touchpad fails) 
□ Continuous power supply. 
□ Ability to connect to bank’s network. 
□ Ability to validate user. 
Design/implementation constraints: 
# Login: 
Validate Bank Card 
□ Validate for Card Expiration Date 
□ Validate that the card's expiration date is later than today's date 
□ If card is expired, prompt error message "Card is expired" 
Validate for Stolen or Lost Card 
□ Validate that the card is not reported lost or stolen 
□ If card is lost, prompt error message, "Card has been reported lost" 
□ If card is stolen, prompt error message, "Card has been reported stolen" 
Validate for Disabled Card 
□ Validate that the card is not disabled 
□ If card is disabled, prompt error message, "Card has been disabled as of 
<expiration date>" 
Validate for Locked Account Validate 
that the account is not locked 
□ If account is locked, prompt error message "Account is locked" 
Validate PIN 
□ Validate that the password is not blank 
□ If PIN is blank, prompt error message "Please provide PIN" 
□ Validate that the password entered matches the password on file 
□ If password does not match, prompt error message "Password is Incorrect" 
Lock Account 
□ If number of consecutive unsuccessful logins exceeds three attempts, lock account. 
Maintain Consecutive Unsuccessful Login Counter 
Increment Login Counter 
For every consecutive Login attempt, increment logic counter by 1. 
Reset login counter to 0 after login is successful. 
Get Balance Information 
Withdraw Cash 
Transfer Funds 
# Assumptions and Dependencies: 
□ Hardware never fails 
□ ATM casing is impenetrable 
□ Limited number of transactions per day (sufficient paper for receipts) 
□ Limited amount of money withdrawn per day (sufficient money) 
External Interface Requirements 
User interfaces 
The customer user interface should be intuitive, such that 99.9% of all new ATM users are able to 
complete their banking transactions without any assistance. 
Hardware interfaces 
# The hardware should have following specifications: 
□ Ability to read the ATM card 
□ Ability to count the currency notes 
□ Touch screen for convenience 
□ Keypad (in case touchpad fails) 
□ Continuous power supply 
□ Ability to connect to bank’s network 
□ Ability to take input from user 
□ Ability to validate user 
Software interfaces 
The software interfaces are specific to the target banking software systems. At present, two known 
banking systems will participate in the ATM network. 
□ State Bank 
□ Indian Overseas Bank 

# Safety requirements: 
Must be safe kept in physical aspects, say in a cabin 
□ Must be bolted to floor to prevent any kind of theft 
□ Must have an emergency phone outside the cabin 
□ There must be an emergency phone just outside the cabin 
□ The cabin door must have an ATM card swipe slot 
□ The cabin door will always be locked, which will open only when user swipes his/her 
ATM card in the slot & is validated as genuine 

# Security requirements: 

□ Users accessibility is censured in all the ways 
□ Users are advised to change their PIN on first use 
□ Users are advised not to tell their PIN to anyone 
□ The maximum number of attempts to enter PIN will be three 
Some of the possible Bugs on ATM machine? 
1. Successful insertion of ATM card
2. Unsuccessful operation due to insert card in wrong angle
3. Unsuccessful operation due to invalid account Ex: other bank card or time expired card
4. successful entry of PIN number
5. un successful operation due to enter wrong PIN number 3times
6. successful selection of language
7. successful selection of account type
8. unsuccessful operation due to invalid account type
9. successful selection of withdraw operation
10. successful selection of amount to be withdrawal
11. successful withdraw operation
12. unsuccessful withdraw operation due to wrong denominations 
13. unsuccessful withdraw operation due to amount is greater than day limit 
14. unsuccessful withdraw operation due to lack of money in ATM 
15. unsuccessful withdraw operation due to amount is greater than possible balance 
16. unsuccessful withdraw operation due to transactions is greater than day limit 
17. unsuccessful withdraw operation due to click cancel after insert card 
18. unsuccessful withdraw operation due to click cancel after insert card & pin number 
19. unsuccessful withdraw operation due to click cancel after insert card, pin number & language 
20. unsuccessful withdraw operation due to click cancel after insert card, pin number, language 
&account type 
21. unsuccessful withdrawal operation due to click cancel after insert card, pin number, language, 
account type & withdrawal operation 
22. unsuccessful withdrawal operation due to click cancel after insert card, pin number, language, 
account type, withdrawal operation &amount to be withdraw

# Result: 
Thus, the ATM system specifications and reporting the various bugs is implemented and output 
is verified successfully.
### Result:
Thus, the ATM system specifications and reporting the various bugs is implemented and output was verified successfully

