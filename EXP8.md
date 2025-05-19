# Ex.No: 8  Test cases for Banking Application

### NAME: GOKULA PRIYA P                                                                            
### REGISTER NUMBER : 212222040044
### AIM: 
For Banking Applicationsystem study its system specifications and generate test cases.
### The characteristics of a Banking application are as follows: 
```
□ Multi-tier functionality to support thousands of concurrent user sessions 
□ Large scale Integration, typically a banking application integrates with 
numerous other applications such as Bill Pay utility and Trading accounts 
□ Complex Business workflows 
□ Real Time and Batch processing 
□ High rate of Transactions per seconds 
□ Secure Transactions 
□ Robust Reporting section to keep track of day-to-day transactions 
□ Strong Auditing to troubleshoot customer issues 
□ Massive storage system 
□ Disaster Management. 
 
The above listed ten points are the most important characteristics of a Banking 
application. 
 
Banking applications have multiple tiers involved in performing an operation. For Example, a 
banking application may have: 
1. Web Server to interact with end users via Browser 
2. Middle Tier to validate the input and output for web server 
3. Data Base to store data and procedures 
4. Transaction Processor which could be a large capacity Mainframe or any other 
Legacy system to carry out Trillions of transactions per second. 
 
 
If we talk about testing banking applications it requires an end-to-end testing methodology 
involving multiple software testing techniques to ensure: 
□ Total coverage of all banking workflows and Business Requirements 
□ Functional aspect of the application 
□ Security aspect of the application 
□ Data Integrity 
□ Concurrency 
□ User Experience 
 
 
Typical stages involved in testing Banking Applications are shown in below workflow 
which we will be discussing individually.
```
### Requirement Gathering: 
```
Requirement gathering phase involves documentation of requirements either as Functional 
Specifications or Use Cases. Requirements are gathered as per customer needs and documented 
by Banking Experts or Business Analyst. To write requirements on more than one subject 
expert are involved as banking itself has multiple sub domains and one full fledge banking 
application will be the integration of all. For Example: A banking application may have 
separate modules for Transfers, Credit Cards, Reports, Loan Accounts, Bill Payments, Trading 
Etc.
```
### Requirement Review: 
```
The deliverable of Requirement Gathering is reviewed by all the stakeholders such as QA 
Engineers, Development leads and Peer Business Analysts. They cross check that neither 
existing business workflows nor new workflows are violated.
```
### Business Scenario Preparations: 
```
In this stage QA Engineers derive Business Scenarios from the requirement documents 
(Functions Specs or Use Cases); Business Scenarios are derived in such a way that all 
Business Requirements are covered. Business Scenarios are high level scenarios without any 
detailed steps, further these Business Scenarios are reviewed by Business Analyst to ensure 
all of Business Requirements are met and its easier for BAs to review high level scenarios 
than reviewing low level detailed Test Cases.
```
### Test Case Preparation: 
```
In this stage Test Cases are derived from Business Scenarios, one Business Scenario leads to 
several positive test cases and negative test cases. Generally tools used during this stage are 
Microsoft Excel, Test Director or Quality Center.
```

### Test Case Review: 
```
Reviews by peer QA Engineers
```

### Test Case Execution: 
```
Test Case Execution could be either manual or automatic involving tools like QC, QTP or 
any other.
```

### Database Testing: 
```
Banking Application involves complex transaction which are performed both at UI level and 
Database level, Therefore Database testing is as important as functional testing. Database in 
itself is an entirely separate layer hence it is carried out by database specialists and it uses 
techniques like 
Data loading 
Database Migration 
Testing DB Schema and Data types 
Rules Testing 
Testing Stored Procedures and Functions 
Testing Triggers 
Data Integrity
```

### Security Testing: 
```
 Security Testing is usually the last stage in the testing cycle as completing functional and non 
functional are entry criteria to commence Security testing. Security testing is one of the major 
stages in the entire Application testing cycle as this stage ensures that application complies 
with Federal and Industry standards. Security testing cycle makes sure the application does not 
have any web vulnerability which may expose sensitive data to an intruder or an attacker and 
complies with standards like OWASP. 
In this stage the major task involves in the whole application scan which is carried out using 
tools like IBM Appscan or HP WebInspect (2 Most popular tools). 
Once the Scan is complete the Scan Report is published out of which False Positives are 
filtered out and rest of the vulnerability are reported to Development team for fixing 
depending on the Severity. 
Other Manual tools for Security Testing used are: Paros Proxy, Http Watch, Burp Suite, 
Fortify tools Etc. 
Apart from the above stages there might be different stages involved like Integration Testing 
and Performance Testing. 
In today’s scenario majority of Banking Projects are using: Agile/Scrum, RUP and 
Continuous Integration methodologies, and Tools packages like Microsoft’s VSTS and 
Rational Tools. As we mentioned RUP above, RUP stands for Rational Unified Process, 
which is an iterative software development methodology introduced by IBM which 
comprises of four phases in which development and testing activities are carried 
out. 
Inception 
Four phases are: 
i) 
ii)Collaboration 
iii)Construction and 
iii) Transition 
RUP widely involves IBM Rational tools. 
In this article we discussed how complex a Banking application could be and what are the 
typical phases involved in testing the application. Apart from that we also discussed current 
trends followed by IT industries including software development methodologies and tools. 
```


### Test cases for opening bank account:


### Input parameters checking: 
 ```
- Name -Date of Birth - Photo -Address Proof -Identity proof -Introducers (if applicable) - PAN card -Initial deposit -Whether checkbook / ATM card / Online banking facilities are needed or not -Customer signature
```

### Type of account: 
```
- Savings account -Salary account -Joint account - Current account - Secondary account -RD account -Account for a company
```

### Test cases: 
```
-Checking mandatory input parameters -Checking optional input parameters -Check whether able to create account entity. -Check whether you are able to deposit an amount in the newly created account (and thus updating 
the balance) -Check whether you are able to withdraw an amount in the newly created account (after 
deposit) (and thus updating the balance) -Check whether company name and its pan number and other details are provided in case ofsalary 
account -Check whether primary account number is provided in case of secondary account -Check whether company details are provided in cases of company's current account -Check whether proofs for joint account is provided in case of joint account -Check whether you are able deposit an account in the name of either of the person in a joint
```


### Result:
Thus, the Test cases for Banking Application is implemented and output is verified successfully. 
