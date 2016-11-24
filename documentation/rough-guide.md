---
layout: default
title: Rough Guide
---

#Labtrac Team User Guide.





[NOTES For title sizes



1 ##

2 ###

3 ####

4 #####]





+ **[Welcome](#0)**



	- [Implementation](#0.1)

	

+ **[Getting Started](#1.0)**



	- [Access to Labtrac](#1.1)

	- [Data Build](#1.2)

		- [Things to Consider Before Getting Started](#1.2a)

			- [Price Lists](#1.2b)

			- [Dentist Codes](#1.2c)

			- [Product Codes](#1.2d)

	- [Adding Dentists](#1.4)

		- [Delivery Methods](#1.4b)

	- [Adding Products](#1.5)

	- [Adding Materials](#1.6)

		- [Attaching a Material to a Product](#1.6b)

	- [Adding a Job](#1.7)

		- [Entering a Job](#1.7b)

		- [Completing a Job](#1.7c)

		- [Stage Work](#1.7d)

		- [Sub Contracting](#1.7e)



	

+ **[System Settings](#2)**



	- [Lab Details](#2.1)

	- [System Options](#2.2)

	- [Sugeon Defaults](#2.3)

	- [Financial](#2.4)

	- [Order Enclosures](#2.5)

	- [Footnotes](#2.6)

	- [User Manager](#2.7)

	

+ **[Invoicing and Statements](#3)**



	- [Invoice List](#3.1)

	- [Invoice Manager](#3.2)

	- [Statement Manager](#3.3)

	- [Account Activity](#3.4)

	- [End of Month Guide](#3.5)



+ **[CRM Studio and Backup](#3.6)**

	

+ **[Payment Entry](#4)**



	- [Posting a Payment](#4.1)

	- [Reversing a Payment](#4.2)

	

+ **[Reports](#5)**



+ **[Financial Manager](#6)**



+ **[All Videos](#7)**





* * *



##<a name=0></a>Welcome to Labtrac



Thank you for choosing Labtrac and welcome to the Labtrac family of over 200 Laboratories in the UK who have run their systems successfully over the last 20 years.



This document is to give you a guide to the implementation process so you know the sequence of events and particularly what you will need to prepare for.



Some contact numbers that you will find useful;



**Labtrac Support/Sales - 03333 449970**

***(all calls charged at local rate)***





These Numbers are available during 9:00 to 5:30 Monday to Thursday and 9:00 to 5:00 on Fridays, excluding Bank Holidays.



If any issue is non-urgent then it is best to contact us using the **support@labtrac.com** email, explaining what the issue is and providing any details that you can, as well as Contact names etc. When we need to carry out any training or need to access your system to resolve any issues we have invested in the TeamViewer software package and this allows us to access your system with your permission.





###<a name=0.1></a>Installation of the Labtrac Software



* Firstly you need to install TeamViewer on all PC's which will have Labtrac on. To do this please follow these instructions.



+ Open an internet browser and go to labtrac.com



* Click on the tap in the top right corner called *Support*.



+ Now in this page you will see *Support* again in the middle of the page. Under this it will say *Labtrac Remote Support Client* click this link and it will start a download which you can say *Run* to.



* This will then open the *TeamViewer* Installer. The first thing you will need to enter in this page is *How do you want to use TeamViewer* to which you should select *Both of the above*.



+ Next it will ask you to agree to the tearms of the license.



+ Once you have agreed it will then ask for a password. This should be a password which you can tell the Labtrac Support team.



+ After you have entered the Password then change the name of the PC to your lab name **eg. Knutsford Dental-PC 1** and click *Finish*



* This Process will take 4 or 5 minutes for each PC.



* Once the TeamViewer link is available, the Labtrac Support Team can then proceed to install the latest Labtrac version on your PC and this will take around 20-30 minutes depending on broadband speeds and the modules that you have taken. Once this has been completed we can then start the Labtrac data build stage.



## Getting Started



###<a name=1.1></a name> Access to Labtrac



By clicking on the Labtrac icon on your desktop you will be presented with the Labtrac sign on screen. Key in the user name, press tab then enter the password. By default both these fields are set to ‘sys’.





![Adding a Dentist](C:\Users\dannysitunes\SharePoint\Home - Shared Documents\Support\Labtrac Manual\Media\Sign In.PNG)



***

- - -

***



###<a name=1.2></a>Data Build



####<a name=1.2a></a> Things to Consider Before Getting Started



Now you have Labtrac set up on your PC(s) you will need to enter all your data (Dentists, Product etc). Following is a step by step guide to do that.





#####<a name=1.2b></a>Price Lists



It is important that before you start entering any infomation that you have in mind your price lists that are used throughout your whole customer base. If you have 3 price lists then when you are entering dentists you will need to know which price list that dentist is on. Likewise when entering any products or material you will need to know every price for that product or material.



#####<a name=1.3></a>Dentist Codes



Every dentist in Labtrac needs a unique code. If you already have a coding system that you use then you can carry on with that system. If you dont we reccomend using the first 4 letters of the surname followed by 01 incase of duplicates.



+ Labtrac allows a dentist code of up to 10 characters, however, if you are planning on exporting your accounts, Sage will only allow up to 8 characters.



	- **WRIG01** - Owen Wright

	- **WRIG02** - Michael Wright



#####<a name=1.2b></a>Product Codes



When setting up product codes in Labtrac there are a few things you have to bear in mind;





+ There needs to be a product code for every standard of work that you do. Meaning if you do NHS,Independent and Private work you will need 3 codes for each product. In the example below we have suffixed the same *PBC* (for a Porcelain Bonded Crown) code with a N,I or P depending on the Standard.



	- **PBC-N** for (NHS) Porcelain Bonded Crown.

	- **PBC-I** for (Independent) Porcelain Bonded Crown.

	- **PBC-P** for (Private Porcelain) Bonded Crown.



***



- - -



***





 

###<a name=1.4b></a>Delivery Methods



* To set up our delivery methods (how the dentists recieve the work) you first need to double click on *Delivery Details* from the content bar.



* This then opens a new window which will be blank. To set up a delivery method click *Add* in the bottom left of the screen.



* Again, this will open a new window from here you need to select a few parameters. you need to select the *Run* number.



* Next you select the *Days* this is the amount of time you want to allow for the job to arrive in surgery after leaving the Lab.



* Now you will go down and write some details in the *Delivery Method* section(eg Postal, Courier, Hand Delivered etc)



* The *Rep* and *Sales Area* boxes are additional infomation you can add if you have/need it. It is not needed to set up a *Run*.



In our example we have created run number 1, allowed for 2 days and have named the method Postal. 



![Delivery Method Video](C:\Users\dannysitunes\SharePoint\Home - Shared Documents\Support\Labtrac Manual\Media\Delivery Method.PNG)





##<a name=1.4></a>Adding Dentists



* To add a dentist you need to click on *Dentist* in the contents bar.



* Now either click *Add* on the top or F2 to bring up the next screen.



* By now you should have have an idea for your dentist codes. Enter that into the *Dentist Code* section and then the full name under *Dentist Name*.



* Here you are met with a few different options. First off you can enter an address.



* Next you need to select the Dentsist as either a Principal (they handle their own payments and account) or an associate (they have a Principal who handles all payments and account infomation). If they are an associate you can select the principal, once they have been added to Labtrac, from the dropdown menu.



* Now we will look at the Invoicing section. The first box under the address box is *Invoiced*. If the Dentist is set as a principal then this box will always be selected. If it is an associate then you can choose whether or not they are invoiced. If you dont select this box all invoices will be sent to the Principal rather than this dentist.



* Next we have *Invoice on Delivery* if this box is checked then an invoice is sent with every job, and a Statement sent at the end of the month. If this box is not checked then there will be no invoice sent with the job, maybe a job ticket or delivery note instead, and a consolidated invoice sent at the end of the month detailing all jobs completed within that month.



* Next you will select the *Run*. This is the delivery method which you set up earlier. Click on the dropdown menu and select from your list.



* Next you can go to the *Contacts* tab here you can enter the contact name and contact number. This is just for your reference.



* Then click on the *Financial* tab and you need to enter a Invoice Address. If the Invoice address is the same as the one you entered on the Details screen you can click the button next to *Invoice Address* to copy it across.



* After entering the address you can go to the email tab. Here you can enter the Dentists email and select some in the preference menu which documents you would like to email.



* Now you can click *OK* and the surgeon is entered.



**Here is a video showing all the steps above...**



![Adding a Dentist](C:\Users\dannysitunes\SharePoint\Home - Shared Documents\Support\Labtrac Manual\Media\Adding a Dentist.mp4)





* * *

- - - 

* * *



##<a name=1.5></a>Products?????????





##<a name=1.5></a>Adding a Product



To add a product fist click on the *Master Products* section in the contents bar. Then click *Add* or F2 to bring up the *New Item* window.



Now you can enter a Product Code and Description and click *Add*. 



This brings up a new window with a few options. 



If this is the first time adding a product you need to set up our *Standard* and *Category*. This is something you will only need to do the first time. At the moment they will have a dropdown box which says *All*. To add to this do the following;



* First click the dotted box next to the dropdown for *Standard*. This will open a new window.



* Next you can type in the *Standard* you would like to set up, in the example we have used *NHS*, *Independent* and *Private*, then click *Add*.



Now you need to do the same for *Categories* 



* First click the dotted box next to the dropdown for *Categories*. This will open a new window.



* Next you need to type in the *Categories* you would like to set up, in the example you have used *Crown and Bridge*, *Prosthetics*, *Orthodontics* and *Misc*. Then click *Add*.



Now going back to the original *Add Product* window you can fill this out;



+ If you select tooth, stump or tooth mould shade required boxes Labtrac will then not allow you to enter a job without this infomation filled out.



+ Record Material is a section where you can attach a material to a product. Click [here](#1.3b) for more infomation.



* Choose your *Standard* and *Category*.



+ Next enter a price for every [Price List](#1.1.5) that you use, even if the price (for this particular product) doesnt change throughout. If you dont enter any infomation on one of your price lists yet you have a dentist set to that list the product will go onto a job with a value of £0.00.



* Click *OK* and the product has been entered.



**Here is a video showing all the steps above**



![Delivery Method Video](C:\Users\dannysitunes\SharePoint\Home - Shared Documents\Support\Labtrac Manual\Media\Adding a Product.mp4)





##<a name=1.6></a>Adding Materials



Now we are going to go through adding materials. In our example we are adding Gold Alloy.



* First go to Materials in the Contents bar.



* Click *Add* or F2 and this will bring up a new window.



* Enter a *Material Code* and *Description*, You may already have your own material code in the example, however, we have used *PGOLD60* for Private Gold Alloy 60%, then click *Add*.



This will have opened a new window where you can enter more details;



* We then move to *Standard* where in our cast we select *Private*.



* Then we have the prices which again go from 1 - 40. We have entered 3 different price structures.



* Click *OK* and the Material has been added.





####<a name=1.3b></a>Attaching a Material to a Product



In our example we have create a Full Gold Crown as a product. This product will always need our Material we then created, Gold Alloy. Now we will show you how to link the two together.



* Go into Master Products in the content bar and either select an existing product or create a new one.



* When we open the product you will see a unchecked box *Record Material* and a dropdown menu. Check the box and select from the dropdown the Material you want to add to the product.



* Click *OK* and that is now added.



Now when it comes to completing a job Labtrac will not allow you to do so without entering the amount, in our case grams, of material used.





* * *





###<a name=1.7></a>Adding a Job



####<a name=1.7b></a>Entering a Job



Now we will look at adding a job. To add a new job firstly click on 'Live Jobs' in the contents bar.



* To add a new job click this will then open a new window.



* The first thing to do in this new window is enter the patients details.



* Next, on the right hand side, we have the *Surgeon* details.



* Select the surgeon from the dropdown menu and the rest will fill in automatically.



* Next you need to enter your recieved and due dates. Labtrac assumes the date received is todays date. Then select the date the work is due in surgery by using the drop down menu and selecting from the calendar.



* We will then go to the *Product* button or *F7*. this will open a new window which will have all the products that we have set up. Select your product from the list, you can search through the list by typing the product code. Then click *OK*.



* Now the job is ready to *Launch* do this by clicking the Launch button or F11.



####Completing the Job<a name=1.7c></a>





Now we will work through completing the job.



* Open up a job that is ready to be completed.



*  Click on the *Task* button or F10.



* This is where you can change the status of a job in Labtrac to a few different things. Such as the work being *Out on Approval* (see [Stage Work](#1.7d)), *Surgeon Return* (see [Stage Work](#1.7d)), *Hold Job*, *Sub Contract* (see Sub Contracting) a job and *Complete Job*.



* Click *Complete Job* this will set the job as completed and produce an invoice and all relevant documents.



* Now in the window under quantity we can enter the amount you used, in our case it was per gram and in the example we have used 2.5g. That will then calculate the total cost and we can *Save* and *Continue* and the Job is complete.



####<a name=1.7d></a>Stage Work



Now we are going to go through staging a job.





* The first thing you need to do is to go into *Live Jobs* and click *Add* or F2 to open a new job.



* Go through all the normal steps for adding a job here.



* Launch the job.



* When the job is ready to be sent out to the dentist for approval you need to reopen the live job. Then you can click *Task* or F10. This will then bring up a dropdown menu. From this select *Send on Approval*. This now tells Labtrac that the job is out with the dentist and no longer in the lab.



* When we receive the work back from the dentist and you are ready to move onto the next stage you can open the job back up and again go to *Task* or F10 and select *Surgeon Return*. It will now prompt you to change the date the work is due back in surgery.



* Now you can **add the new stage** to do this we need to click on the *stage* tab (left of product button) or F5 this now brings up the products and from here you can select which ever may apply for the second stage.



* Now you are ready to send the work back into the lab which we do by clicking *Launch* or F11.



* Again once the work in the lab is complete and ready to be sent back to the dentist you have to reopen the job and select *Send on Approval*.



* When you receive the work back from the dentist you can go back into the job and into *Task* F10 and click *Surgeon return* then select *Stage* and choose from the product list.



* You can now launch this job and when work is complete in the lab you can then go through and complete the job as normal.



####<a name=1.7e></a>Sub Contracting



To Sub Contract a job in Labtrac first you need to set up a list of Subcontracters. 



+ Double click *Sub-Contracters* in the contents bar. This will open up a new window where you can enter all of the people you sub-contract work to.



+ Click *Add* and fill in the relevant infomation, making sure to add a *Run* then select *Save*.



+ Now you have your sub contracters set up you can go through and enter a job like normal, however, once you launch the job click on *Task* or F10 and select **Sub-Contract** then **Send Out** (This changes the Job Status to *Sub Contract* ). Now select the date that the work is due back to you. 



+ When you recieve the work back again go to **Sub Contract** and select **Recieve Back**.





* * * 

- - -

***



##<a name=2></a> System Settings



System settings is used to customise the way Labtrac will work for you. This section outlines the different settings that can be used and the effect they will have on the way Labtrac will work.



###<a name=2.1></a>Lab Details



+ **Lab Name** - Maximum of 50 characters - used on screens and optionally on external documents.



+ **Lab Address** - This is used on Delivery Notes and Invoices. When filling out this field remember to use **CTRL** and **ENTER** keys together to create a new line.



+ ***MHRA* Number** - The number provided by MHRA qualified labs. This appears on all documentation.



+ **Last Order Number** - This is a numeric or alpha/numeric field of up to 10 characters. The numeric part will be incremednted each time an order is processed. By default it will start at ***J00001***.



+ **Last Delivery Number** - This is a numeric or alpha/numeric field of up to 10 characters. The numeric part will be incremented each time a delivery note is produced. By Default it will start ***D00001***.



+ **Last Purchase Number** - This is a numeric or alpha/numeric field of up to 10 characters. The numeric part will be incremented each time a purchase order is produced. By Default it will start ***P00001***.







###<a name=2.2></a>System Options



+ Order

	- *Include Bin No* -  if checked Labtrac wont allow you to enter a job without entering a Bin Number (Pan Number).



	- *Check if Patient is Already on the System* -



	- *Price Final Stage Only* - 



	- *Job Ticket by Batch* -



	- *Disable Work Ticket Promt*





###<a name=2.3></a>Dentist



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



###<a name=2.4></a>Financial



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



###<a name=2.5></a>Order Enclosures



###<a name=2.6></a>Footnotes



###<a name=2.7></a>User Manager



User manager is the area within Labtrac in which you can set up individual log-ins for your users.



+ To add a new user double click on *User Manager* in the Contents Bar. That will open a new window in which you will see all the current users listed.



+ Click *Add* and this will bring up a *User Details* Page. Now all we have to do is fill the boxes with the correct infomation and click *OK*.



**NOTE: Security level is on a numerical scale from 1-9. **



+ 1 will only allow a user to input jobs. They wont be able to see prices for anything.



+ 5 allows a user to view and enter jobs, products and dentists as well as see any reports that a user with a higher security level allows. 



+ 9 is full acces.



##<a name=3></a>Invoicing and Statements



###<a name=3.1></a>Invoice List



Once you have clicked on the invoice list you will sere a coprehensive list of every invoice you have ever produced. To open any of these invoices up all you have to do is double click on the left hand side of any of the rows. This will then open the invoice report. From here you can reprint an invocie at any time by clicking on the print icon in the top left - this will send to your default printer.



###<a name=3.2></a>Invoice Manager







###<a name=3.3></a>Statement Manager



+ To produce your statments double click on *Statment Manager*. This will open a new window in the window select the type of statment you would like to run from the list in the left hand side. Next make sure the correct aged debt reference is set. Now click preview to view all of the statments and you can then print. 



	- Date filter - optional date filter to narrow down results.

	- Surgeon Filter - oprtional filter to  produce a statment for a particular dentist.



###<a name=3.4></a>Account Activity



The *Account Activity* section is the area of Labtrac in which you can see an overview and complete history of any account. 



###<a name=3.5></a>End Of Month Guide



Video



###<a name=3.6></a>CRM Studio and Backup Module 



**CRM Studio**  is for email and corporate invoicing. 



+ To set up your Dentists fo email please click [here](#1.1).



To Email Invoices, Statments, Patient Statments or Statments follow these instructions.



+ Open CRM Studio and click *Email*



+ This will then open a window which will list all dentists that are currently set up with email addresses in Labtrac.



+ Click on the appropriate tab for *Single Invoices* or *Patient Statments* click **Case Documents**.



+ For *Monthly Invoices* click **Monthly Invoices**.



+ For *Statements* click **Invoices**.



+ Then using the date filter in the top right select a date range. This will then show all documents that fall in this period. You can then select the documents you wish to send and click *send* in the bottom right.



+ This will then produce a report which should say *X invoices sent succesfully*.



**Backup** is a program that backs up all of your Data to Labtrac's secure Cloud Server at the click of a button.



+ Once the **Backup Module** has been installed on your PC all you need to do to back up your data is close labtrac down and click **YES** to the box asking if you would like to back up the Database. This will then run a Back up procedure the you should have a message in the dialog box saying *Upload Succesful*. This will then dissapear and the upload is complete.



##<a name=4></a>Payment Entry



###<a name=4.1></a>Posting a Payment



+ Once we are in Payment Entry find the dentist who you wish to post a payment against and double click on them. This will open a new window which will show all outstanding invoices for this Dentist. 



+ First we need to select what type of payment this is (BACS, Cheque, Credit Note or a Discount) from the list on the left hand side.



+ Next we can enter the *Amount*.



+ Then we can put in a *Reference* and/or *Details* these fields are not mandatory but can help keep track of payment infomation.



+ Next we can set the date the payment has been made.



+ Finally all we need to then do is select the relevant invoice the payment is against and click the check box on the left hand side of that.



+ Once we have all that we can click post in the top right and that is the payment posted.



![Delivery Method Video](C:\Users\dannysitunes\SharePoint\Home - Shared Documents\Support\Labtrac Manual\Media\Payment Entry.PNG)



###<a name=4.2></a>Reversing a Payment



If you find you have entered a payment incorrectly follow these steps to reverse the payment



+ Double click on *Reverse a Payment*. This will bring up a list of all the payments you have entered. Once you have found the relevant payment infomation double click on the left hand side of the row. This will then bring up another payment screen.



+ Once you have opened this you will see a list of all invoices included in the payment. What you need to do is select (by using the check box) the payment which you want to reverse.



**NOTE: You have to select every invoice that was in the original payment entry. You cannot partially reverse a payment.**



+ Now you have selected the relevant invoice numbers click *Update* in the top right which will then produce a message saying the details have been updated.



##<a name=5></a>Reports



Double click on *Reports* in the contents bar of Labtrac and you will see the Reports Package.



This is where you can view all financial or operational reports.



Please watch video for more infomation



VIDEO!



##<a name=6></a>Financial Manager (May have to change with new version of FM also add monthly invoice implications)



Financial Manager is a program that runs alongside Labtrac and allows you to ammend completed jobs Labtrac does not.



To open Financial Manager click **Support** in the very top left then **Financial Manager**.



You can then search for any job and change any infomation you want.



You wont find the job in the list if it is older than 3 months old or has had a payment posted against it. If the latter is the case please [Reverse Payments](1.2) against the invoice.



+ Use the search bar to find the relevant job/invoice. 



+ Once you have found the invoice double click to open the infomation screen.



+ In here you can change;



	- Order Status

		- To change the order status select from the dropdown menu the status you would like to set the job to and click *update* in the bottom right. (Note. Changing the status of a job will delete the previous invoice and create a new one)

	- Dentist

		-  Select the correct dentist from the dropdown menu and click *update*. (This will delete the old invoice and create a new one)

	- Order Details

		- To change a product select the product in the order details box and change it using the dropdown menu. Once the correct product is selected in the dropdown menu click the green tick and then *Update*.

	- Patient infomation

		- Change the patient name in the top box then click *Update Patient* then *Update*



##<a name=7></a>Videos





