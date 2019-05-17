## Banking terms

#### _ACH (Automated Clearing House)_

It's a funds transfer system run by NACHA (National Automated Clearing House Association). Its generally used by depository institutions such as banks. When you send money from one account to another, you can do it via bank wire or ACH. Think of ACH as an electronic payment from one bank account to another. The transaction is initiated by a business to debit an account by submitting an ACH file. This file contains the bank’s ABA (American Bankers Association®) number and the account number(s) to debit, along with the amount(s). This file is submitted for processing nightly and passes through networks controlled by the Federal Reserve. ACH payments are not guaranteed; that is, they must clear, much like a check. ACH is useful as an alternative to accepting a credit card.

#### _Demand Deposit_, _Term Deposit_

These are funds held in an account that can be withdrawn at any time by the depositor. Ex: Savings account, checking account. A term deposit or time deposits are made for a predetermined amount of time at a certain rate. Demand Deposits have high liquidity, lower interest rates Vs term deposits have lower liquidity but higher interest rates. The most common form of a term deposit is called a CD (certificate of Deposit)

#### _Despository Institutions_

A depository institution is colloquiallyc called as "finanical institution" in US such as savings bank, commercial banks, loan associations, credit unions that is legally allowed to accept monetary deposits from consumers

#### _ABA Routing Number_

This is a 9 digit routing number that appears on all checks along with bank account number. This is also called Transit Routing Number. This number identifies which bank the account is from.

#### _Capture_

The process of acquiring account information required for processing a payment.

#### _GL_

General Ledger or GL is a complete record of financial transactions over the life of a company

#### _Nostro Acount_

A nostro account refers to an account that a bank holds in a foreign currency in another bank. Nostros, a term derived from the Latin word for "ours," are frequently used to facilitate foreign exchange and trade transactions.

#### _NDM file_

Connect:Direct—originally named Network Data Mover (NDM)— is a computer software product that transfers files between mainframe computers and/or midrange computers. It was developed for mainframes, with other platforms being added as the product grew. NDM was renamed to Connect:Direct in 1993.

#### _BIC_

Bank Identifier Code is often referred to as SWIFT Code as SWIFT owns and administers the BIC system

#### _SWIFT Code_

A SWIFT code is an international bank code that identifies particular banks worldwide. A SWIFT code consists of 8 to 11 characters. Commercial banks use SWIFT code to send moneys to overseas banks. An example of a BIC/SWIFT code is CTBAAU2S

- First 4 chars are the bank code
- Next two are country code
- Last 2 are the location code

#### _Boleto_

Boleto is a payment method in Brazil regulated by Brazilian Federation Bank. Boleto in english means Ticket. A boleto can be paid at ATMs, branch facilities and internet banking of any Bank, Post Office, Lottery Agent and some supermarkets until its due date. After the due date it can only be paid at the issuer bank facilities.

![Boleto Sample](./img/boleto.png)

#### _DDA_

DDAs, or demand deposit accounts, are offered by banks and credit unions. These accounts are primarily used for frequent transactions, such as checking accounts. However, the term "DDA account" refers to any bank account that you can deposit to and withdraw from immediately, on demand. DDA accounts may or may not pay interest. When they do, the rate is typically less than the rate found on certificates of deposit and other accounts. Most DDAs let you withdraw your money without advance notice, but the term also includes accounts that require six days or less of advance notice. DDA accounts permit joint account holders. Each holder can deposit and withdraw part or all of the balance at any time. Either can sign checks or make ATM withdrawals without the permission or knowledge of the other party. While both parties must submit signature cards to the bank to open DDA accounts, only one account owner is needed to close out the account. It's wise to open joint DDA accounts only with someone you trust.

#### _Transaction Accounts_

The term DDA is most often used to refer to transaction accounts, also called checking accounts. DDA accounts offer offer checks, ATM or debit cards and overdraft protection, if the account owner wishes. There are no restrictions on the number of withdrawals and deposits a user can have in given period. To attract more depositors, some banks offer interest for their DDA accounts, but many financial institutions still do not. For instance, Northeast Missouri State Bank offers some such accounts that pay interest, while the Bank of Ireland offers ones that do not.

#### _NOW and MMA Accounts_

NOW (negotiable order of withdrawal) accounts are essentially checking accounts where you earn interest on the money you have deposited. With a NOW account, the bank or credit union has the right to require at least seven days written notice of a withdrawal, though this is rarely done. Although NOW and MMA (money market accounts) allow deposits and withdrawals on a demand basis, they are not legally DDA accounts. These accounts typically pay market interest rates. MMA withdrawals are limited to six per month. Some banks might also limit your total MMA transactions to six per month, whether withdrawals, transfers or deposits. Bank fees apply if you exceed the transaction limits. The difference between a DDA (or checking account) and a negotiable order of withdrawal account is the amount of notice you need to give to the bank or credit union before making a withdrawal.

#### _WIRE transfer Vs ACH_

- :airplane: Wire transfers are guaranteed funds that occur on the same day provided the instructions are given to the originating bank before the cutoff time and sent by the originating bank to the Federal Reserve and received and processed by the receiving institution before close of their business day. Wires are not real time, they are normally same day.
- :moneybag: Wires cost the bank $0.35 per wire and the bank typically retails them to customers for $6 in high volume to \$30 in very low volume. This covers the costs of labor, technology and compliance.

- :truck: ACH is not same day, it is next (or can be future) day settlement. Transactions are entered with a date to settle which is normally the next day. At the opening of business banks receive files from the day before and process them, offsetting their general ledger with customer accounts. However because ACH debits are not guaranteed, the corresponding credit can be held. ACH credits are guaranteed and must be settled on the settlement day by the NACHA Rules.
- :dollar: ACH cost banks $0.035 per transaction or $0.025 per transaction in bulk (>1k transactions). They usually retail to customers for between $0.10 and $2.50, depending on volume. ACH by definition is meant to be automated, and meant to be delayed settlement, thus the lower cost associated. There is a push for real-time and same-day ACH service but large banks are fighting the push.

#### _Global ACH_

A global ACH system expands the use of certain electronic payments beyond the North American region. Doing so makes it easier and less costly to transfer funds to other countries. Electronic payments using the ACH (Automated Clearing House) system are only possible within the United States and Canada. However, similar types of transaction processing systems are available in other countries or regions, such as Australia, China, Europe, Hong Kong, India, Japan, New Zealand, Singapore, and South Korea.

In order to initiate an ACH payment that crosses borders into the electronic payment system of another country, a business must enter its payment information into a portal (usually maintained by a bank) that links to the other country’s payment system. This may require the entry of different types of data, in order to comply with the message formatting requirements of the other system. Many of these systems do not allow for the inclusion of remittance information along with a payment, so the payer will need to supply this information to the payee separately, perhaps as part of an e-mail message.

In those parts of the world that do not have systems similar to the ACH system, it may be necessary to pay by the more expensive wire transfer method. A wire transfer is expensive not only for the sender, but also for the recipient, who is charged a lifting fee by the receiving bank to process the payment.

When the much higher cost of a wire transfer is compared to the cost of an ACH transfer, it is apparent that global ACH is a much more cost-effective solution, despite the issues with transferring information into the ACH formats required for different regions.

#### _MT103_
This is a Swift payment format used for cash transfer specifically for cross-border wire transfer. MT101 messages were designed for Corporates for bulk transfer. MT103 relate to single transfer and is predominantly used between bank to bank. So MT101, is a message that gets sent to a bank to deduct the money from an account  - the payment instruction. This message can contain 1 or more lines. This means there can be a sinle instruction stating to debit 100$ from account X and out of that, 50$ should go to Account A, 20 to B and 30 to C.  When the bank receives this message, it will forward those single lines to bank where the money needs to be added to that account. This could be the same bank or another bank. Thus, MT101 is the actual payment instruction that gets sent and MT103 is the internal single lines messages used within the bank. Following are the fields in a MT013 message:

|Field|Value|
|:-----:|:-----:|
|:20| Transaction Reference Number|
|:23B| Bank Operation Code |
|:32A| Value date/Currency/Interbank Settled|
|:33B| Currency/Original Ordered Amount|
|:50A, F or K| Ordering Customer (Payer)|
|:52A or D| Ordering institution (Payer's Bank)|
|:53A, B or D| Senders Correspondent (Bank)|
|:54A, B or D| Receivers Correspondent (Bank)|
|:56A, C or D| Intermediary (Bank)|
|:57A, B, C or D| Account with Institution (Beneficiary Bank)|
|:59 or 59A| Beneficiary|
|:70 | Remittance information (Payment reference)|
|:71A | Details of Charges (BEN/OUR/SHA)|
|:72 | Sender to receiver information|
|:77B | Regulatory Reporting|

#### _BAI2_
BAI2 format is a specialized set of codes used for cash management by Bank Administration Institute (BAI). BAI2 files come to an account holder from a BANK. The account holder imports the file into a book keeping application to reconcile bank statements. Reconciliation is a process whereby the bank statements are compared to an book keeping application's  data and differences are resolved. If you have to choose between BAI2 and MT940 then you need to consider where the client location is. If client location and Banks are in USA , BAI2 is good and you will find lot of documentations on the config. If you do business with International Banks and your client location is not in US don't think of BAI2, since BAI is not most used format for banks around the world. Switch to MT940.

#### _BookTransfer_ _GIRO_
A book transfer is a transfer of legal right of ownership of an asset from old owner to new without physically shifting the asset. In banking terms, it means transfer of funds from one deposit account to another at the same financial institution. This results in fast transfer of funds so that payee can use the funds immediately. Book transfers eliminates check clearing float.

A GIRO (General Interbank Recurring Order) is also a method to directly transfer funds from one bank account to another without the use of physical checks. A GIRO is generally cheaper ($0.5 per transfer). A GIRO usually takes about a day or two to clear. The funds will leave the payor's account on day zero. GIRO transfers are predominantly used in European countries.

#### _Float_
A float in financial terms is a money within the banking system that is briefly counted twice due to the time gaps between registering it as a deposit or a withdrawal. The delay happens usually due to processing of paper cheques. The bank credits a customer account as soon as the cheque is deposited, but it takes some time to receive the money from payers bank and record it. Until that happens, the amount is written as "exists" both in the source and target accounts in both the payers and recipients account. The float enables the payer bank to earn extra interest on those funds before they get cleared.

#### _Lock Box_
A service offered by banks to companies in which the company receives payments by mail to a post office box and the bank picks up the payments several times a day, deposits them into the company's account, and notifies the company of the deposit. This enables the company to put the money to work as soon as it's received, but the amounts must be large in order for the value obtained to exceed the cost of the service.

#### _Non Operating Balance/Assets_
Non operating assets/funds/balance are redundant assets that do not contribute to the core operations of the company. These are the assets that a company may keep around but not use it. These assets may still generate income or provide a ROI. Non operating assets are listed in the company's balance sheet along with operating assets/balance. Common non operating assets are unallocated cash, marketable securities, loans receivable, idle equipments and vacant land.
