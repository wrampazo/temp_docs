# Welcome to Bazaar!
*A web application made to simplify your point of sale*

Readme Document

## Read me
**Introduction**
*"Bazaar"* was created as a final project for Harvard CS50 course and to support a non-profitable organization from Brazil, called "Amigos do Bem", ([https://www.amigosdobem.org/en/main/](https://www.amigosdobem.org/en/main/)). It is a simple web application developed to control stock/inventory and sell products such as Books, CDs, DVDs, Statues, Crafts, etc. to support their activities during fairs or other events (such as a bazaar!). It would be like a point of sale, providing basically features. In fact, it was created to replace a excel sheet. Which is what folks have been using at Amigos do Bem. We all know how powerful and amazing Excel is. However, it is not the best tool to handle orders in a point of sale, and it is really easy to have many failures and mistakes. The sheet used has only a list of products and prices, with another sheet to register orders - everything is manual. Bazaar app has also an easy way to query and report sales, product stock, and balance. 

**For more detailed technical information, please, read the design document. It also contains important information about Server and Client Requirements, besides supported platforms.**


### Installing the Application on Server Side

This application has never been installed in another environment besides CS50 IDE environment. While we do have plans to deploy in single server box, it has never been done before and this document hasn't had detail steps on how to do it yet.

**Getting Started - Steps:**
- Login and Open your CS50 IDE;
- Open a new Terminal window and type:
$ mkdir ~/workspace/bazaar/
$ cd ~/workspace/bazaar.
- Download application files from the repository where it was submitted and copy all files to the new folder:
$ ~/workspace/bazaar
- Then, to run the application, start Flask's built-in web server:
$ flask run



## Using the Application

As soon as flask run is executed, it will display you an URL similar to:
*("wrampazo" is the alias I used, you should see the alias you have chosen)*

~/workspace/project/bazaar/ $ flask run
* Serving Flask app "application"
* Running on ==http://ide50-wrampazo.cs50.io:8080/== (Press CTRL+C to quit)
* Restarting with stat

Navigate to that page and browser should load web page requesting for "username" and "password".

![Login](https://lh3.googleusercontent.com/6ME6tKkw9pAIJEYC7bm3p1iExgul7FId9WC_8ImOogaV38zaaBfeS_hqBifeK8WQ1__aMP7usfE "Login")

For user, type: admin
Password, type: admin1
Click "Log in", if login was successfully done, you're in the application main page, or index.html.

![Index](https://lh3.googleusercontent.com/mU4Ze5QAvi48OFGbr3bMF0l0QDdljxZLAkmcvlzQUrfP2C4BoEHcdcVcIcB-WX9DsBKcm5AMQ40 "Index.html")

Now, **"Bazaar - Orders"** is available for use. As you can see the menu has a few options:

| Menu | Description | 
| ----- | ------- |
| [Admin] | To manage users, add, delete, or change password. |
| [Stock/Inventory] | To manage stock, add products in stock, check product balance, and check inventory balance. |
| [Products] | To manage products such as add, edit, delete, list. |
| [Orders] | To manage orders, such as new, cancel, list, and order reports |
| [Logout] | To logout application used logged. |

There is no specific navigation you should follow, you can use anyone of these options to perform actions. Let's follow a few scenarios below to get familiar with Bazaar.
