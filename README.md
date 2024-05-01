﻿# CapstoneOne_AccountingLedger

#### This is a command line Accounting Ledger application. It is used to track and filter through financial transactions.

##### Features:

Add Deposit: User can add a deposit with date, time, description, vendor, and amount.

![image](https://github.com/ninjakid56810/CapstoneOne_AccountingLedger/assets/70558570/7a1ad0f9-2ac8-4b7f-aca6-3d9cba03a7f4)

Make Payment: User can make a payment with date, time, description, vendor, and amount.

![image](https://github.com/ninjakid56810/CapstoneOne_AccountingLedger/assets/70558570/747214df-a542-48a0-86a5-a10288fa4f52)

Ledger: User can view all entries (transactions), only deposits, only payments, or filter based on date or vendor witihn the reports screen.

![image](https://github.com/ninjakid56810/CapstoneOne_AccountingLedger/assets/70558570/6ba039ab-f336-4614-bbe9-462cb309a458)

One interesting piece of code from this project:

One of our prompts was that "All entries should show the newest entry first" when displaying entries to the screen.
The transactions.txt file appended to the top of the file, however in an ArrayList it appended to the end of the list.
To display newest entries first, I reversed the array list, printed it, and reveresed it back to its original state.





