---
layout: article
title: System Settings
markdownpage: true
---
# System Settings

System settings is used to customise the way Labtrac will work for you. This section outlines the different settings that can be used and the effect they will have on the way Labtrac will work.


<a class="offset" name="2.1"></a>
## Lab Details

+ **Lab Name** - Maximum of 50 characters - used on screens and optionally on external documents.


+ **Lab Address** - This is used on Delivery Notes and Invoices. When filling out this field remember to use **CTRL** and **ENTER** keys together to create a new line.


+ ***MHRA* Number** - The number provided by MHRA qualified labs. This appears on all documentation.


+ **Last Order Number** - This is a numeric or alpha/numeric field of up to 10 characters. The numeric part will be incremednted each time an order is processed. By default it will start at ***J00001***.


+ **Last Delivery Number** - This is a numeric or alpha/numeric field of up to 10 characters. The numeric part will be incremented each time a delivery note is produced. By Default it will start ***D00001***.


+ **Last Purchase Number** - This is a numeric or alpha/numeric field of up to 10 characters. The numeric part will be incremented each time a purchase order is produced. By Default it will start ***P00001***.

<a class="offset" name="2.2"></a>
## System Options


+ Order

	- *Include Bin No* -  if checked Labtrac wont allow you to enter a job without entering a Bin Number (Pan Number).



	- *Check if Patient is Already on the System* -



	- *Price Final Stage Only* - 



	- *Job Ticket by Batch* -



	- *Disable Work Ticket Promt*




<a class="offset" name="2.3"></a>
## Dentist

+ **Invoice on Delivery** 

 	- If this is set to **YES** the system will produce a *Single Invoice* with every completed job.

 	- If this is set to **NO** then the completed job will be added to a Consolidated Invoice for preparing and printing at the month end.


+ **Copy of Invoice sent to Principal**



	- If this is set to **YES** this means that, for each Associate Dentist (non Principal) the designated Principal will recieve a copy of the Associate's invoice

	- If this is set to **NO** the system will not produce a copy of the Associate's invoice to be sent to the Principal.



+ **Discount Shown on Invoice** 



	- If this is set to **YES** then the value of of the discount offered will be shown on the invoice.

	- If this is set to **NO** the discount will not be shown on the invoice.



***NOTE***  *The value exported to an external accounts package will be the gross value.*



+ **Nominal Code**



	- This is the default nominal code in the external accounts package to which all sales values are assigned.



+ **Payment Details**



	- The default details entered in this section will be placed on any *new* 

Dentist record automatically. This can then be amended on an individual Dentist record if required.

**Days** - The days to be shown on the invoice by which the payment is due.

**Terms** - The payment terms to be shown on the invoice.



+ **Settlement Details** 



	- The default details entered in this section will be placed on any new Dentist record automatically. They can then be amended on the Dentist Details page as required.

**%** - Dicount percentage to apply if settlement made in the stipulated days.

**Days** - The number of days withinwhich the settlement discount will apply.

**Terms** - The settlement terms to be shown on the invoice.


<a class="offset" name="2.4"></a>
## Financial



The Laboratory's bank details can be added here but these details are **not used** by the system. These are purely for your reference.



+ **Bank Name** 



	- Name of Laboratory's bank - up to 50 characters



+ **Bank Address**

	- When entering the bank address details the **CTRL** and **Enter** keys need to be pressed together to start a new line.



+ **Sort Code** 

	- The banks sort code needs to be entered in the format **nn-nn-nn**.



+ **Account Number** 

	- The Labortatory's account number at the bank.



+ **Account Name**



	- The name of the Laboratory's bank accouny.



+ **Export Accounts To**

	- If you use an external accounts package (Sage etc) select from the dropdown list to select the system which the system invoice details are to be exported.



+ **Last Invoice Number**

	- Numeric or aplha/numeric field of up to 10 characters; the numeric part of which will be incremented each time an invoice is produced. **eg. I00001**



+ **Last Credit Number** 



	- Numeric or alpha/numeric field of up to 10 characters, the numeric part of which will be incremented each time a credit is raised. **eg. C00001**



+ **Last Transaction Number**



	- This field cannot be amended, it displays the last financial number.


<a class="offset" name="2.5"></a>
## Order Enclosures


<a class="offset" name="2.6"></a>
## Footnotes


<a class="offset" name="2.7"></a>
## User Manager



User manager is the area within Labtrac in which you can set up individual log-ins for your users.



+ To add a new user double click on *User Manager* in the Contents Bar. That will open a new window in which you will see all the current users listed.



+ Click *Add* and this will bring up a *User Details* Page. Now all we have to do is fill the boxes with the correct infomation and click *OK*.



**NOTE: Security level is on a numerical scale from 1-9. **



+ 1 will only allow a user to input jobs. They wont be able to see prices for anything.



+ 5 allows a user to view and enter jobs, products and dentists as well as see any reports that a user with a higher security level allows. 



+ 9 is full access.
