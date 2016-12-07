---
layout: article
title: Getting Started
markdownpage: true
---
# Getting Started

## Access to Labtrac
Clicking the Labtrac icon on the desktop will bring up the sign on screen. Enter your username and password.
By default both these fields are set to ‘sys’.

![Adding a Dentist](C:\Users\dannysitunes\SharePoint\Home - Shared Documents\Support\Labtrac Manual\Media\Sign In.PNG)


<a class="offset" name="1.2"></a>

## Data Build

### Things to Consider Before Getting Started

Now you have Labtrac set up, you will need to enter all required data (Dentists, Product etc). 

#### Price Lists

It is important that before you start entering any infomation that you have in mind your price lists that are used throughout your whole customer base. If you have 3 price lists then when you are entering dentists you will need to know which price list that dentist is on. Likewise when entering any products or material you will need to know every price for that product or material.

#### Dentist Codes

Every dentist in Labtrac needs a unique code. If you already have a coding system that you use then you can carry on with that system. If you don't we recommend using the first 4 letters of the surname followed by 01 incase of duplicates.

+ Labtrac allows a dentist code of up to 10 characters, however, if you are planning on exporting your accounts, Sage will only allow up to 8 characters.


	- **WRIG01** - Owen Wright

	- **WRIG02** - Michael Wright



#### Product Codes

When setting up product codes in Labtrac there are a few things you have to bear in mind;

+ There needs to be a product code for every standard of work that you do. Meaning if you do NHS,Independent and Private work you will need 3 codes for each product. In the example below we have suffixed the same *PBC* (for a Porcelain Bonded Crown) code with a N,I or P depending on the Standard.



	- **PBC-N** for (NHS) Porcelain Bonded Crown.

	- **PBC-I** for (Independent) Porcelain Bonded Crown.

	- **PBC-P** for (Private Porcelain) Bonded Crown.



#### Delivery Methods


* To set up our delivery methods (how the dentists recieve the work) you first need to double click on *Delivery Details*, under *Dentist* from the content bar on the left side of the screen.


* This opens a new window which displays current delivery methods. To set up a delivery method click *Add* in the bottom left of the screen.


* This will open another new window, from here you need to enter some parameters. You need to select the *Run* number, which will identify this particular method of delivery.


* Next you select the *Days*. This is the amount of time you want to allow for the job to arrive in surgery after leaving the Lab.


* Enter some details in the *Delivery Method* section(eg Postal, Courier, Hand Delivered etc)


* The *Rep* and *Sales Area* boxes are optional additional infomation, it is not needed to set up a *Run*.

In our example we have created run number 1, allowed for 2 days and have named the method Postal. 



![Delivery Method Video](C:\Users\dannysitunes\SharePoint\Home - Shared Documents\Support\Labtrac Manual\Media\Delivery Method.PNG)


<a class="offset" name="1.4"></a>


## Adding Dentists


* To add a dentist, click on *Dentist* in the contents bar on the left.



* Now either click *Add* on the top or press the F2 key to bring up the next screen.


* Having established a system for your dentist codes (see above), enter the code into the *Dentist Code* section and then the full name under *Dentist Name*.


* Here you are met with a few different options. First off you can enter an address.


* Next you need to define the Dentist as either a *Principal* (they handle their own payments and account) by checking the box marked 'Principal', or as an *Associate* (they have a Principal who handles all payments and account infomation) by leaving the box unchecked and selecting their principal, once they have been added to Labtrac, from the dropdown menu.



* Now we will look at the Invoicing section. The first box under the address box is *Invoiced*. If the Dentist is set as a principal then this box will always be selected. If it is an associate then you can choose whether or not they are invoiced. If you don't select this box all invoices will be sent to the Principal rather than this dentist.


* Next we have *Invoice on Delivery*, if this box is checked then an invoice is sent with every job and a Statement is sent at the end of the month. If this box is not checked then there will be no invoice sent with the job (maybe a job ticket or delivery note instead) and a consolidated invoice will be sent at the end of the month detailing all jobs completed within that month.


* Next, select the *Run*. This is the delivery method which you set up earlier. Click on the dropdown menu and select from your list.


* Next, go to the *Contacts* tab where you can enter the contact name and contact number. This is just for your reference.


* Next, click on the *Financial* tab and enter an Invoice Address. If the Invoice address is the same as the one you entered on the Details screen you can click the button next to *Invoice Address* to copy it across.


* After entering the address you can go to the email tab. Here you can enter the Dentists email and select which documents will be included from the preferences menu. 

* Click *OK* and the surgeon is entered.
.

**Here is a video showing all the steps above...**



![Adding a Dentist](C:\Users\dannysitunes\SharePoint\Home - Shared Documents\Support\Labtrac Manual\Media\Adding a Dentist.mp4)





* * *

- - - 

* * *

<a class="offset" name="1.5"></a>

## Adding a Product



To add a product, click on the *Master Products* section in the contents bar. Then click *Add* or press the F2 key to bring up the *New Item* window.



Enter a Product Code and Description, then click *Add*. This brings up a new window with a few options. 



If this is the first time adding a product you need to set up your *Standard* and *Category*. This is something you will only need to do the first time. At the moment they will have a dropdown box which says *All*. To add to this do the following:



* First click the dotted box next to the dropdown for *Standard*. This will open a new window.



* Next you can type in the *Standard* you would like to set up, in the example we have used *NHS*, *Independent* and *Private*, then click *Add*.



Now you need to do the same for *Categories* 



* First click the dotted box next to the dropdown for *Categories*. This will open a new window.



* Next you need to type in the *Categories* you would like to set up, in the example we have used *Crown and Bridge*, *Prosthetics*, *Orthodontics* and *Misc*. Then click *Add*.



Now going back to the original *Add Product* window you can fill this out:



+ If you select tooth, stump or tooth mould shade required boxes Labtrac will then not allow you to enter a job without this infomation filled out.



+ Record Material is a section where you can attach a material to a product. Click [here](#1.3b) for more infomation.



* Choose your *Standard* and *Category*.



+ Next enter a price for every [Price List](#1.1.5) that you use, even if the price (for this particular product) doesn't change throughout. If you don't enter any information on one of your price lists yet you have a dentist set to that list the product will go onto a job with a value of £0.00.



* Click *OK* and the product has been entered.



**Here is a video showing all the steps above**



![Delivery Method Video](C:\Users\dannysitunes\SharePoint\Home - Shared Documents\Support\Labtrac Manual\Media\Adding a Product.mp4)

<a class="offset" name="1.6"></a>

## Adding Materials


Now we are going to go through adding materials. In our example we are adding Gold Alloy.

* First go to Materials in the Contents bar.

* Click *Add* or press the F2 key, this will bring up a new window.

* Enter a *Material Code* and *Description*. You may already have your own material code in the example, however, we have used *PGOLD60* for Private Gold Alloy 60%, then click *Add*.



This will have opened a new window where you can enter more details:

* We then move to *Standard* where *Private* is selected in cast.

* Then we have the prices which again go from 1 - 40. We have entered 3 different price structures.

* Click *OK* and the Material has been added.


### Attaching a Material to a Product


In our example we have create a Full Gold Crown as a product. This product will always need the Material we created, Gold Alloy. Now we will show you how to link the two together.

* Go into Master Products in the content bar and either select an existing product or create a new one.

* When we open the product details window you will see a unchecked box *Record Material* and a dropdown menu. Check the box and select from the dropdown the Material you want to add to the product.

* Click *OK* to add the material to the product.

When completing a job Labtrac will not allow you to do so without entering the amount, in this case grams, of material used.


<a class="offset" name="1.7"></a>

## Adding a Job

Now we will look at adding a job. To add a new job, click on 'Live Jobs' in the contents bar.


* To add a new job click add at the top or press the F2 key to open the order details window.


* The first thing to do is enter the patients details.


* Next, on the right hand side, we have the *Surgeon* details.


* Select the surgeon from the dropdown menu and the rest will fill in automatically.


* Next you need to enter your received and due dates. Labtrac assumes the date received is today's date. Then select the date the work is due in surgery by using the drop down menu and selecting from the calendar.


* We will then go to the *Product* button or the *F7* key. This will open a new window which will show all the products that we have set up. Select your product from the list; you can search through the list by typing the product code. Then click *OK*.


* Now the job is ready to *Launch*. Do this by clicking the Launch button or by pressing the F11 key.


### Completing the Job


Now we will work through completing the job.

* Open up a job that is ready to be completed.

* Click on the *Task* button or press the F10 key.

* This is where you can change the status of a job in Labtrac to a few different things. Such as the work being *Out on Approval* , *Surgeon Return* (see next section - Stage Work), *Hold Job*, *Sub Contract* (see Sub Contracting) a job and *Complete Job*.

* Click *Complete Job*. This will set the job as completed and produce an invoice and all relevant documents.

* Now in the window under quantity we can enter the amount you used, in our case it was per gram and in the example we have used 2.5g. That will then calculate the total cost and we can *Save* and *Continue* and the job is complete.


### Stage Work

Now we are going to go through staging a job.

* The first thing you need to do is to go into *Live Jobs* and click *Add* or press the F2 key to open a new job.

* Go through all the normal steps for adding a job.

* Launch the job.

* When the job is ready to be sent out to the dentist for approval, you need to reopen the live job. Then you can click *Task* or press the F10 key. This will then show a dropdown menu. From this select *Send on Approval*. This now tells Labtrac that the job is out with the dentist and no longer in the lab.

* When we receive the work back from the dentist and are ready to move onto the next stage, open the job back up and again go to *Task* or press the F10 key and select *Surgeon Return*. It will now prompt you to change the date the work is due back in surgery.

* To **add the new stage**, click on the *stage* tab (left of product button) or press the F5 key which brings up the products. Select which ever may apply for the second stage.

* Now you are ready to send the work back into the lab, click *Launch* or press the F11 key.

* Again once the work in the lab is complete and ready to be sent back to the dentist, reopen the job and select *Send on Approval*.

* When you receive the work back from the dentist, go back into the job and into *Task* press F10 and click *Surgeon return* then select *Stage* and choose from the product list.

* You can now launch this job and when work is complete in the lab you can then go through and complete the job as normal.


### Sub Contracting

To Sub Contract a job, first you need to set up a list of *Sub-contracters*. 

+ Double click *Sub-Contracters* in the contents bar. This will open up a new window where you can enter all of the people you sub-contract work to.

+ Click *Add* and fill in the relevant infomation, making sure to add a *Run* then select *Save*.

+ Now you have your sub-contracters set up you can go through and enter a job like normal, however, once you launch the job click on *Task* or press the F10 key, select **Sub-Contract** then **Send Out** (This changes the Job Status to *Sub Contract* ). Now select the date that the work is due back to you. 

+ When you recieve the work back again go to **Sub Contract** and select **Receive Back**.
