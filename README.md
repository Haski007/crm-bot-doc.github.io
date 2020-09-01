# TELEGRAM BOT (Pre-Alpha v.0.71) - crm for small business

Bot hosted on Google Cloud Platform. Database - mongoDB.

## Table of contents
* [To start](#to-start)
* [Types of product](#types-of-product)
* [Products](#products)
* [Purchases](#purchases)
* [Statistics](#statistics)
* [Cashbox](#cashbox)
* [For admins](#for-admins)

## To start
Here is a bot's link - https://t.me/pdemian

You need to be registered to use this bot, so if you don't have secret password - you just need to write your boss or author of bot https://t.me/pdemian

#### There are two types of users:
* users - hired workers. They can add to database new purchases and make changes in the stock.
* admins - founderds or cofounders of business. They can remove users, add new products. They receive statistics every day at 23:00 by Europe/Kiev.

## Fuctional

### Types of product
Add new type of products:  
<img src='/assets/images/add_type.gif' width="200">
  
To get all added types and remove one:  

<img src='/assets/images/remove_type.gif' width="200">   

### Products
To add new product type you should to set:
* Name of new product
* Choose type of product from the list
* Prime cost of product
* Price of product  
<img src='/assets/images/create_product.gif' width="200">   
  
To get all products and remove one:  
  
<img src='/assets/images/remove_product.git' width="200">   

### Purchases
To make purchase you should set amount of sold product:  
  
<img src='/assets/images/make_purchase.gif' width="200">   

To remove purchase you should enter object id of purchase:  
  
<img src='/assets/images/remove_purchase.gif' width="200">   

### Statistics:
You can get:
* history of purchases during the day
* statistics of day (sold amount of each product, total cash, total profit)
* statistics of any month.  
  
<img src='/assets/images/statistics.gif)  
 
### Stock
You can:
* Monitoring quantity of each product at stock
* Make new supplies  
<img src='/assets/images/stock.gif)  

### Cashbox
There is a general cashbox entinity, and to monitore your cash you can:
* add to cashbox (with your comment)
* get from cashbox (with your comment)
* get list of all transactions

You can also add a start day money (The money that you have in the your physical cashbox in the start of your duty)

Start money will be plused to total sum of cash fo whole day and you can enter how much money you want to leave in physical cashbox at the end of day.  

## For admins

Admins have much more permissions.
* `/users` to get list of users who are registered and belong to the same shop
* `/remove_users [user objectID]` - to remove user
* `/alert_all [message]` - send message to all users
* `/alert_admins [message]` - to send message only for admin
* All admins get day statistics everyday at 23 00.
