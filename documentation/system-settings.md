---
layout: article
title: System Settings
markdownpage: true
---
# Settings & More

<a name="SystemSettings"></a>
## System Settings

System settings are used to customise the way Labtrac will work for you. This section outlines the different settings that can be used and the effect they will have on the way Labtrac will work. These can be accessed by double clicking System Settings in the content bar.

In the new window there will be 7 tabs.

[Lab Details](#LabDetails), [System Options](#SystemOptions), [Dentist](#Dentist), [Financial](#Financial), [Order Enclosures](#OrderEnclosures), [Footnotes](#Footnotes), [Custom Reports](#CustomReports).

- - -

<a class="offset" name="2.1"></a>
<a name="LabDetails></a>
### Lab Details

**Lab Details** will hold all the Lab information. The **Name**, **Address**, **Phone Number**, and **MHRA Number**. 

It will also show the **Last Order Number** and **Last Delivery Number**. You can change these if necessary.

- - -

<a class="offset" name="2.2"></a>
<a name="SystemOptions"></a>
### System Options

#### Order 

Using the Order section you can set your default options for when you are entering a job.

The options are;

- *Include Pan No* -  if checked Labtrac won't allow you to enter a job without entering a **Pan Number**.

- *Check if Patient is Already on the System* - If the patient name, that you are entering, is already on the system for the same Dentist **Labtrac** will prompt you to view the previous case before you **Launch** the job. 

- *Price Final Stage Only* - If this is selected when entering [Stage Work](#StageWork) **Labtrac** will ignore the prices on all but the last stage.

- *Job Ticket by Batch* - NEED TO ENTER

- *Disable Work Ticket Prompt* - Disables the prompt to print a work ticket when you **Launch** a job.

#### Invoicing

Using the Invoicing section you can set your default invoicing options.

The options are;

- *Apply Discount to Jobs* - With this selected any volume discounts entered will be applied on your jobs.

- *Print Prices on Delivery Notes* - Using this you can select wether or not prices are shown on the **Delivery Notes**

- *Print Delivery Note on A5 Paper* - Using this you can to print on A5 paper rather than the default A4.

- *Print Invoice on A5 Paper* - Using this you can to print on A5 paper rather than the default A4

- *Export to External Accounts* - Select here if you wish to export your invoices to an external accounts package. (Sage, Xero and Quickbooks Online are currently supported, if you have another accounts system that you would like integrated please contact [Labtrac Support](#LabtracSupport)


<a class="offset" name="2.3"></a>
<a name="Dentist"></a>
## Dentist

+ **Invoice on Delivery** 

	- If this is set to **YES** the system will produce a *Single Invoice* with every completed job.

	- If this is set to **NO** then the completed job will be added to a Consolidated Invoice for preparing and printing at the month end.


+ **Copy of Invoice sent to Principal**

	- If this is set to **YES** this means that, for each Associate Dentist (non Principal) the designated Principal will receive a copy of the Associate's invoice.

	- If this is set to **NO** the system will not produce a copy of the Associate's invoice to be sent to the Principal.

+ **Discount Shown on Invoice** 

	- If this is set to **YES** then the value of of the discount offered will be shown on the invoice.

	- If this is set to **NO** the discount will not be shown on the invoice.

***NOTE:***  *The value exported to an external accounts package will be the gross value.*

+ **Nominal Code**

	- This is the default nominal code in the external accounts package to which all sales values are assigned.

+ **Payment Details**

	- The default details entered in this section will be placed on any *new* Dentist record automatically. This can then be amended on an individual Dentist record if required.

	- **Days** - The days to be shown on the invoice by which the payment is due.

	- **Terms** - The payment terms to be shown on the invoice.

+ **Settlement Details** 

	- The default details entered in this section will be placed on any new Dentist record automatically. They can then be amended on the Dentist Details page as required.

	- **Days** - The number of days withinwhich the settlement discount will apply.

	- **Terms** - The settlement terms to be shown on the invoice.


<a class="offset" name="2.4"></a>

## Financial

The Laboratory's bank details can be added here but these details are **not used** by the system. These are purely for your reference.

+ **Bank Name** 

	- Name of Laboratory's bank - up to 50 characters.

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

	- Numeric or aplha/numeric field of up to 10 characters; the numeric part of which will be incremented each time an invoice is produced. **eg. I00001**.

+ **Last Credit Number** 

	- Numeric or alpha/numeric field of up to 10 characters, the numeric part of which will be incremented each time a credit is raised. **eg. C00001**.

+ **Last Transaction Number**

	- This field cannot be amended, it displays the last financial number.

<a class="offset" name="2.5"></a>

## Order Enclosures
{content pending}


<a class="offset" name="2.6"></a>

## Footnotes
{content pending}

<a class="offset" name="2.7"></a>

## User Manager

The User Manager is used to set up and manage individual log-ins for users of Labtrac. 

+ To add a new user, double-click on *User Manager* in the contents bar. That will open a new window in which you will see all the current users listed.

+ Click *Add* to bring up a *User Details* Page. Fill the boxes with the correct infomation and click *OK*.

**NOTE: Security level is on a numerical scale from 1-9.**

+ 1 will only allow a user to input jobs. They wont be able to see prices for anything.

+ 5 allows a user to view and enter jobs, products and dentists as well as see any reports that a user with a higher security level allows. 

+ 9 is full access.
