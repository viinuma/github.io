---
layout: essay
type: essay
title: "Checkpoint Assignment 3"
# All dates must be YYYY-MM-DD format!
date: 2023-05-02
published: true
labels:
  - Learning
  - Assignment
---
[Click here for screencast presentation covering the areas below] (https://www.dropbox.com/s/6gh0tycdk9bv1ga/Checkpoint%20Assignment%203.mov?dl=0)

### 1.	Show what each page will look like. The pages do not have to be “functional” but the design should clear.
![image](https://user-images.githubusercontent.com/85478391/235381166-a173a485-6a1a-4b17-b8ae-e5899343107b.png)<br>

### 2.	Describe your design for your site’s shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart!<br>
Before the user is logged in, the user can view the products and other pages, including the shopping cart. As the user adds products to the shopping cart, the cart counter will go up. The cart counter will be in the navigation bar that will be included on every page. The shopping cart page will be a separate page and accessible by clicking on the cart in the navigation bar. The page will allow the user to edit the quantity of each item and remove items from the cart, but the quantity will be limited to the inventory available. The page will also display the taxes and shipping costs. However, a purchase cannot be made unless the user is logged in. If the user is not logged in when selecting purchase, then the user will be directed to the login page.
 
### 3.	Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their objects) you will use to manage the shopping cart data and how they will be used in a session!<br>
Sessions will be used to manage quantity selected for the products in the shopping cart. The shopping cart data that will be stored in the session will include the product name, price, and quantity. The data will be stored as an array of objects. 
Here's an example of the product array and the objects stored in the array for the data: "point & shoot" [{"name": "Canon IXUS 50", "price": 50.00, "quantity": 1}]; 
The cart array will be stored in the session so that the user can move between pages and the session data will be stored in the memory of the server. 

### 4.	How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address? <br>
Access will be limited to logged in users (or registered for new account). By using cookies, only successfully logged in users will be able to access their invoice. If the user is not logged in then the user will not be able to access the invoice page after completing their purchase in the shopping cart. 

### 5.	Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary)<br>
Considering personalization in the navbar or on every page beneath the nav bar once the user is logged in. The text might say, "Aloha, Mr. Name." The name will also be displayed on the invoice, "Thank you for your purchase, Mr. Name!" Personalization will also be required to email the user the completed invoice for the transaction. 

### 6.	If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when?<br>
I'm not working with partners.

### 7.	How are you approaching Assignment 3 differently than Assignment 2? <br>
Start as early as possible, but think through how to set up the webpages, including how I want to the pages to behave before jumping into coding. I need to focus on organizing my thoughts and approach to carrying out the requirements first. 
