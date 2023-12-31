# Pete's Dairy

## Deployed Project
[Deployed project](https://app-milkman-1c8cec7719a8.herokuapp.com/ "Link to the site")

A basic site for a local dairy home delivery service
It is designed to be used on any device.

![Mockup images](/media/docs/Responsive-Screenshot.png)

## Table of Contents

- [User Experience UX](#user-experience-ux)
- [Design Strategy](#design-strategy)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Testing](#testing)
- [Future Development](#future-development)
- [Deployment](#deployment)
- [Credits](#credits)

## User Experience (UX)

* ### User Stories
  #### Viewing and navigation 
| # |As A/An| I want to    | So I Can  |
|---|---------|-------------| -----|
| 1 | Shopper | View a list of products | Select items to purchase|
| 2 | Shopper | View a  specific category of products |Quickly find a product I am interested in without searching through all products |
| 3 | Shopper | View product details| See price description, ingredients and allergens along with a other essential information |
| 4 | Shopper | Quickly see special offers and deals | Take advantage of special offers and deals |
| 5 | Shopper | See the total of my purchases | Keep a check on my spending |

#### Registration and user accounts
| # |As A/An| I want to    | So I Can  |
|---|---------|-------------| -----|
| 6 | Site User | Easily register for an account | Build a personal account and view my profile |
| 7 | Site User |Easily log in and out|Access my account information|
| 8 | Site User |Recover my password if I forget it|Recover access to my account|
| 9 | Site User |Receive an email confirmation after registering|Verify that my registration was successful|
| 10 | Site User |Have a personal profile|View my order history, order confirmations and save my payment information|

#### Sorting and searching
| # |As A/An| I want to    | So I Can  |
|---|---------|-------------| -----|
| 11 | Shopper | Sort the list of available products | Easily identify best rated, best priced and category sorted products |
| 12 | Shopper | Sort a category of products | Find the best rated or best priced product in a category or sort by product name |
| 13 | Shopper | Sort multiple categories simultaneously | Find the best rated or best priced product across broad categories such as "Dairy" or "Basics" |
| 14 | Shopper | Search for a product by name or description  | Find a specific product to purchase |
| 15 | Shopper | Easily see what I've searched for and the number of results | Quickly decide if the product I'm searching for is available |

#### Purchasing and checkout
| # |As A/An| I want to    | So I Can  |
|---|---------|-------------| -----|
| 16 | Shopper | Easily select the product and quantity I wish to purchase | Ensure I don't select the wrong quantity when ordering |
| 17 | Shopper | View items in my bag to be purchased | Identify the total cost of the order and what items I will receive |
| 18 | Shopper | Adjust the quantity of the items in my bag | Easily make changes to my purchase before checkout |
| 19 | Shopper | Choose a delivery day for my order | Know when my order will arrive |
| 20 | Shopper | Easily enter my payment information | Checkout quickly without any hassles |
| 21 | Shopper | Feel my personal and payment information is safe and secure | Confidently provide the needed information to make a purchase |
| 22 | Shopper | View an order confirmation after checkout | Verify that I haven't made any mistakes |
| 23 | Shopper | Receive an email confirmation after checkout | Keep the confirmation of what I've purchased for my records |

#### Admin and store management
| # |As A/An| I want to    | So I Can  |
|---|---------|-------------| -----|
| 24 | Shop Owner | Add a product | Add new items to my store |
| 25 | Shop Owner | Edit or update a product | Change product price, description, images and other criteria |
| 26 | Shop Owner | Delete a product | Remove items that are no longer available |

[Back to Index](#table-of-contents)

## Design Strategy
    
* Design Considerations
  - Colour Scheme
  
  The site uses a modified bootstrap scheme adapted to have white background, black text and black or white buttons.

  Messages will displayed using bootstrap toasts in a simple pop up

  There will be a colour coded bar above the toasts to signify their type using standard bootstrap colour coding.
  error - #dc3545 Red
  warning - #ffc107 Orange
  success - #28a745 Green
  information - #17a2b8 Cyan
  
  - Typography
    
    For simplicity, only one font style will be used. The Lato font is a clear sans-serif font which works well for all elements of the site. The fallback sans-serif is specified in case the Lato font fails to load.
    
  - Imagery
  
    Hero Image created using Photoshop and an image from Pexels [Photo by Klaus Hollederer:]( https://www.pexels.com/photo/brown-and-white-cow-54550/)

    The icons used are sourced from [Font Awesome](https://fontawesome.com/)
    
  - Wireframes

  #### Initial designs for the site. 
  All pages to be responsive.
  
  The wireframes can be viewed in a separate [Wireframes MD File](/wireframes.md)

[Back to Index](#table-of-contents)


### The strategy plane:
***What are you aiming to achieve in the first place and for whom?***

#### Users
Users should be able to use the site without needing additional instruction.

The interface should be simple and work on a variety of devices.

Users will be able to select and pay for items for delivery.

User will be able to select a delivery day

#### Admin
Store owners need to be able to manage the products in the store


### The scope plane:
**Which features, based on information from the strategy plane, do you want to include in your design?**

***Must Have***
#### Users

Users must be able to view all products

Users must be able to view products by category

Users must be able to view details of each product

Users must be able to see special offers and deals

Users must be able to see the total of their purchases

Users must be able to choose an item and select the quantity to buy

Users must be able to see a shopping bag of items before completing their purchase

Users must be able to change the quantity of items in the shopping bag before completing their purchase

Users must be able to easily enter payment information

Users must receive an email confirmation of their order

#### Admin
Store managers must be able to add new products

Store managers must be able to Edit or update the products

Store managers must be able to delete products

Store managers must be able to add product images to each product

***Should Have***
#### Users

Users should be able to use the site without needing additional instruction.

The interface should be simple and work on a variety of devices.

Users should be able to make a purchase with or without an account.

The site should allow users of the site to register and create a personal profile.

Users should be able to save their payment information

Users should be able to amend their profile information

Users should receive a confirmation email on account creation

Users should be able to easily log in and out

Users should feel confident that their purchase information is secure

Users should receive confirmation of their order once complete

#### Admin

Admins should be able to add images regardless of size

***Could Have***

#### Users ####

Users could be able to delete their profile and information

#### Admin ####

Store managers could be able to remove orphaned product images

***Future plans***

#### Users ####

A future version could allow users to select a delivery date instead of just a day of the week

A furture version could allow users to select a repeat order for regular delivery

#### Admin ####

Admins could be able to enter a quantity of available products to signify when a product is low or out of stock

**Usability**

Users are assumed to be accessing the site on a mobile device so the site should adopt a mobile first design.

Common Screen Resolutions for Mobile in 2023
|Resolution|Users
|---|---|
|360×800 |(11.01%)|
|390×844 |(7.92%)|
|414×896 |(5.55%)|
|393×873 |(5.26)|
|412×915 |(5%)|

[Source:](https://www.browserstack.com/guide/ideal-screen-sizes-for-responsive-design#:~:text=Book%20for%20More-,Common%20Screen%20Resolutions%20for%20Mobile%20in%202023,412%C3%97915%C2%A0%20%C2%A0%20%C2%A0%20(5%25),-Image%20Source)

The site will be designed to work on screens above 350px

Users should be able to navigate the site without instructions, so navigation should be intuitive.

For the initial build, this site will incorporate:
* The basic product pages
* Product detail page
* Basic navigation menu for All products, Dairy, Basics and Special Offers. With sub-menus to narrow the product category
* A User menu to access user registration, login and profile. with product management option for site admins
* Search option to find a product 
* Sort options by Price, Category, A-Z, Rating.
* Shopping bag page with options to edit quantity or delete item
* Checkout page to take payment
* Payment confirmation page
* Registration and login pages
* Profile page with options to edit
* Admin page to add product
* Admin page to edit product
* Admin option to delete product

**Future Development:**
* Add a stock control system to show low and out of stock items.
* Allow users to choose a delivery date and time
* Allow users to set up a regular (ie weekly) order for the same products


### The structure plane:
**How is the information structured and how is it logically grouped?**

The information should be grouped by;

* The landing page will show the welcome page and menus
* Products pages will show categories and search results
* Product details page will show all details of a selected product 
* Shopping bag page will show items added for purchase
* Checkout page will allow the user to enter delivery details and payment information
* Profile page will allow users to edit and save address details
* Product Management page will allow admins to add a product
* Edit product page will allow admins to edit product details
* Admin functions will only be available to the admin user

### The skeleton plane:
**How will our information be represented, and how will the user navigate to the information and the features?**

All main pages will contain a user menu which allows admins to login and access further pages. Users will be able to register and log in to see their profile information.

All main pages will contain a navigation menu which allows the user to select a product category or list all products by price or rating

A search function will allow the user to search for a product

### The surface plane:
**What will the finished product look like? What colors, typography, and design elements will we use?**

Wireframes for the site can be viewed in a separate [Wireframes MD File](/wireframes.md)

All pages to be responsive.

The pages will use the customised Bootstrap elements throughout.

Messages will be displayed using toasts to notify the user of the results of action such as adding a product to the bag or deleting a product.

[Back to Index](#table-of-contents)

## Features

### Responsive
The site must be designed to work on all devices from mobile to desktop.

### Intuitive
Navigation and use of the website must be intuitive allowing the user to be able to navigate the site without instructions

[Back to Index](#table-of-contents)

## Technologies Used

### Languages Used
[HTML5](https://en.wikipedia.org/wiki/HTML5)

[CSS3](https://en.wikipedia.org/wiki/CSS)

[JavaScript](https://en.wikipedia.org/wiki/JavaScript)

## Frameworks, Libraries & Programs Used

[Bootstrap 4.4](https://getbootstrap.com/docs/4.4/getting-started/introduction/)
Bootstrap was used to assist with the responsiveness and styling of the website.

[Google Fonts:](https://fonts.google.com/)
Google fonts were used to import the 'Lato' font into the style.css file which is used on all pages throughout the project.

[Fontawesome:](https://fontawesome.com/)
Fontawesome used for icons throughout the site.

[jQuery:](https://en.wikipedia.org/wiki/JQuery) is used for additional functions in Bootstrap.

[AllAuth](https://www.codingninjas.com/studio/library/django-allauth-setup-and-configuration) User management functions handled by AllAuth

[Stripe](https://stripe.com/) is used to handle all payments

[Git:](https://git-scm.com/) was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.

[GitHub:](https://github.com/) is used to store the projects code after being pushed from Git.

[Photoshop](https://www.adobe.com/uk/products/photoshop.html) was used to edit images for the site

## Image Credits

Hero Image created using Photoshop and an image from Pexels [Photo by Klaus Hollederer:]( https://www.pexels.com/photo/brown-and-white-cow-54550/)

All product images sourced from [Pexels]( https://www.pexels.com/)

Favicon.ico created at [Favicon.io](https://favicon.io/)

Sample product information sourced from [Asda](https://groceries.asda.com/)

[Back to Index](#table-of-contents)

## Testing

Full testing can be viewed in a separate [Testing MD File](/tests.md)

The W3C Markup Validator and W3C CSS Validator Services were used to validate the project to ensure there were no syntax errors in the project.

W3C Markup Validator - Results [link](https://validator.w3.org/nu/?doc=https%3A%2F%2Fapp-milkman-1c8cec7719a8.herokuapp.com%2F)

W3C CSS Validator - Results [link](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fapp-milkman-1c8cec7719a8.herokuapp.com%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

### Testing User Stories from User Experience (UX)

### User Stories

  #### Viewing and navigation 
| # | As A/An | I want to | So I Can | Satisfied by |
|---|---------|-------------| -----| ---------- |
| 1 | Shopper | View a list of products | Select items to purchase | Main products page lists all products |
| 2 | Shopper | View a specific category of products | Quickly find a product I am interested in without searching through all products | Main nav menu allows a user to select a category to view |
| 3 | Shopper | View product details | See price description, ingredients and allergens along with a other essential information | Selecting a product in the products page opens the product details page |
| 4 | Shopper | Quickly see special offers and deals | Take advantage of special offers and deals | The main nav menu has an offer option to select deals or clearance products |
| 5 | Shopper | See the total of my purchases | Keep a check on my spending | The shopping bag page displays a subtotal for each itam and a total for the bag |

#### Registration and usder accounts
| # | As A/An | I want to | So I Can | Satisfied by |
|---|---------|-------------| -----| ---------- |
| 6 | Site User | Easily register for an account | Build a personal account and view my profile | The user menu takes the user to the registration page to create their account |
| 7 | Site User | Easily log in and out | Access my account information | The nav menu takes the user to the login page |
| 8 | Site User | Recover my password if I forget it | Recover access to my account | The login page has a 'forgot password' option handled by AllAuth |
| 9 | Site User | Receive an email confirmation after registering | Verify that my registration was successful | Handled by AllAuth |
| 10 | Site User | Have a personal profile | View my order history, order confirmations and save my payment information | Profile page allows users to edit and save delivery information |

#### Sorting and searching
| # | As A/An | I want to | So I Can | Satisfied by |
|---|---------|-------------| -----| ---------- |
| 11 | Shopper | Sort the list of available products | Easily identify best rated, best priced and category sorted products | Main nav allows selection of categories. Products page allows filtering by Price, Rating, Name or Category |
| 12 | Shopper | Sort a category of products | Find the best rated or best priced product in a category or sort by product name | Main nav allows selection of categories. Products page allows filtering by Price, Rating, Name or Category |
| 13 | Shopper | Sort multiple categories simultaneously | Find the best rated or best priced product across broad categories such as "Dairy" or "Basics" | The main nav selects products across broad categories by selecting All Dairy or All Basics |
| 14 | Shopper | Search for a product by name or description  | Find a specific product to purchase | The search function allows users to find a search term in the product name or description |
| 15 | Shopper | Easily see what I've searched for and the number of results | Quickly decide if the product I'm searching for is available | The search results will be displayed on the products page |

#### Purchasing and checkout
| # | As A/An | I want to | So I Can | Satisfied by |
|---|---------|-------------| -----| ---------- |
| 16 | Shopper | Easily select the product and quantity I wish to purchase | Ensure I don't select the wrong quantity when ordering | The shopping bag allows the user to see and amend the quantity of each item |
| 17 | Shopper | View items in my bag to be purchased | Identify the total cost of the order and what items I will receive | The shopping bag displays all items selected for purchase |
| 18 | Shopper | Adjust the quantity of the items in my bag | Easily make changes to my purchase before checkout | The shopping bag allows the user to see and amend the quantity of each item |
| 19 | Shopper | Choose a delivery day for my order | Know when my order will arrive | User must choose a delivery day on the checkout page |
| 20 | Shopper | Easily enter my payment information | Checkout quickly without any hassles | Payments handled by Stripe |
| 21 | Shopper | Feel my personal and payment information is safe and secure | Confidently provide the needed information to make a purchase | Payments handled by Stripe |
| 22 | Shopper | View an order confirmation after checkout | Verify that I haven't made any mistakes | Order confirmation page shows all order details after processing by Stripe |
| 23 | Shopper | Receive an email confirmation after checkout | Keep the confirmation of what I've purchased for my records | Checkout success page emails the user with order confirmation information |

#### Admin and store management
| # | As A/An | I want to | So I Can | Satisfied by |
|---|---------|-------------| -----| ---------- |
| 24 | Shopper | Add a product | Add new items to my store | Product management page allows the admin to add a new product |
| 25 | Shopper | Edit or update a product | Change product price, description, images and other criteria | When logged in, an admin has the options to edit each product on the product and product detail pages |
| 26 | Shopper | Delete a product | Remove items that are no longer available | When logged in, an admin has the option to delete each product on the product and product detail pages  |
    
### Further Testing

#### Testing the register function for valid entries
While building the register function, I used conditional print statements to check that the inputs were valid before coding the functionality. eg

      `if terms != 'on':
        print ("Terms not accepted")`

      `if password1 != password2:
        print("Passwords don't match")`

      `if terms and (password1 == password2):
        print("Everything OK")`

#### Testing the user and admin options.

All of the nav links were tested from each page for functionality both while logged out and logged in to confirm that they funtion correctly and showed the correct options.

#### Layout tests

The Website was tested on Google Chrome on both a laptop, tablet and mobile phone for functionality and responsiveness

The responsivity of the website was checked on a variety of devices using [Responsive Design Checkers](https://responsivedesignchecker.com/checker.php) and [AmIResponsive](https://ui.dev/amiresponsive)

Friends and family members were asked to review the site and documentation to point out any spelling errors, bugs and/or user experience issues.

### Solved Bugs

Bug: noimage.png not loading for missing images

Cause: noimage.png not added to media folder

Solution: Upload noimage.png to media folder

-------------------------------------------------------

Bug: Images loading in their native size which means all images would need to be cropped to a standard size.

Cause: No css for product images assuming all images the same size when uploaded

Solution: Create new class of product-image with height: 200px and object-fit: contain; in base.css to override image defaults


-------------------------------------------------------

Bug: Order totals in order confirmation emails showing 14 decimal places

Cause: Missing formatting on variables

Solution: Added floatformat:2 to the variables


-------------------------------------------------------

Bug: Page headings not centered on some pages

Cause: Missing styling for headings on some pages

Solution: Ensure all headings contain text-center class

-------------------------------------------------------

Bug: Background image goes off screen on smaller displays

Cause: Large image overflows screen edge

Solution: Add new background image for smaller screens

-------------------------------------------------------

Bug: Headline text in index.html obscured by background image on smaller screens

Cause: Image and headline text similar colours with little contrast

Solution: Add 1px stroke to the headline text to give contrast against background

-------------------------------------------------------

Bug: Incorrect details in confirmation email subject

Cause: Incorrect site name in confirmation_email_subject.txt

Solution: Updated confirmation_email_subject.txt

-------------------------------------------------------

Bug: W3C CSS Validator found error in CSS

Cause: Missing minus sign in height attribute line 303

Solution: Added minus sign

-------------------------------------------------------

Bug: Error on checkout when user not logged in

Cause: Incorrect definition of bag_items in contexts.py

Solution: Corrected definition

-------------------------------------------------------

Bug: Page header (Pete's Dairy) not visible on smaller screens

Cause: Hidden by media query due to lack of space

Solution: Added to the hero image with new css to hide on larger screens

-------------------------------------------------------

### Linting Errors
./checkout/apps.py:8:9: F401 'checkout.signals' imported but unused
This shows as an error but is in fact used

Some auto generated files left in place in case of future development. Imports commented out.

[Back to Index](#table-of-contents)

## Future Development 

### Delivery Area
As this is a local delivery service, there should be a limit to the area that customers can order from. This could be managed by postcodes.
A delivery area map should also be included.

### Image Management
Currently, when a product image is added to a product which is later deleted, the image remains in the media folder.
An option should be included to remove this image if it is no longer required

### Delivery Dates
The user is able to select a delivery day (within the next seven days). An option should be added to allow customers to choose any future delivery date.

### Delete Profile
An option for users to delete their profile should be added.

### Stock Inventory
A stock level field could be added to the product database to manage available stock and only show products which are in stock 

### Add new product category
It is only possible to add new product categories in the database admin. If this were to be added, there would also need to be a way to add the new category to the relevant menu.
This will entail significant changes to the page navigation.
An extra field in the category table to signify which dropdown menu the category should be in.
The nav function would then have to read all categories for each dropdown to build it each time the page loads.

### Edit Category
At present, a category can only be edited in the database admin. As the menu is coded in main-nav.html, these changes will not be reflected in the menu items.
This could be addressed in a similar way to new product categories.

### Delete Category
If a category is deleted, it will still appear in the menu. This should be resolved in a similar way to new product categories.

### View Orders
The only way to view and process orders is through the database admin. A future addition should have a page for the admin to see outstanding orders and to be able to mark them as fulfilled

### Email Admin with new orders
A function to email the store owner with each new order should be included.

### Product Ratings
The site is able to display product ratings but as yet there is no system in place to allow users to rate products

[Back to Index](#table-of-contents)

## Deployment

### Forking the GitHub Repository

A fork is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project by using the following steps

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page) above the Settings Button on the menu, click the Fork Button.
3. Scroll down the page and click the Create Fork button to make a copy.
4. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/BackstagecrewIS/milkman)
2. Under the repository name, click the Code button next to the green Gitpod button.
3. To clone the repository using HTTPS, under the HTTPS tab, copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.

```
$ git clone https://github.com/BackstagecrewIS/milkman
```
7. Press Enter. Your local clone will be created.

Click [Here](https://docs.github.com/en/get-started/quickstart/fork-a-repo) for the Github tutorial.


[Back to Index](#table-of-contents)

### Deploying to Heroku

#### Set up a database on ElephantSQL

1. Navigate to ElephantSQL.com and click “Get a managed database today”

2. Select “Try now for FREE” in the TINY TURTLE database plan

3. Select “Log in with GitHub” and authorise ElephantSQL with your selected GitHub account

4. In the Create new team form:
  a. Add a team name (your own name is fine)
  b. Read and agree to the Terms of Service
  c. Select Yes for GDPR
  d. Provide your email address
  e. Click “Create Team”

5. Click “Create New Instance”

6. Set up your plan
  a. Give your plan a Name (this is commonly the name of the project)
  b. Select the Tiny Turtle (Free) plan
  c. You can leave the Tags field blank

7. Select “Select Region” (Select a data center near you)

8. Then click “Review”

9. Check your details are correct and then click “Create instance”

10. Return to the ElephantSQL dashboard and click on the database instance name for this project

11. In the URL section, clicking the copy icon will copy the database URL to your clipboard

12. Log into Heroku.com and click “New” and then “Create a new app”

13. Choose a unique name for your app, select the region closest to you and click “Create app”

14. Go to the Settings tab of your new app

15. Return to your ElephantSQL tab and copy your database URL

16. Back on Heroku, add a Config Var called DATABASE_URL and paste your ElephantSQL database URL in as the value. Make sure you click “Add”

17. Navigate to the “Deploy” tab of your app

18. In the Deployment method section, select “Connect to GitHub”

19. Search for your repo and click Connect
    Optional: You can click Enable Automatic Deploys in case you make any further changes to the project. This will trigger any time code is pushed to your GitHub repository

20. As we already have all our changes pushed to GitHub, we will use the Manual deploy section and click Deploy Branch. This will start the build process

21. Now, we have our project in place, and we have an empty database ready for use. We still need to add our tables to our database. To do this, we can click the “More” button and select “Run console”

22. Type python3 into the console and click Run

23. This opens the Python terminal. Now create the tables with the commands:

  `from milkman import db`

  `db.create_all()`

25. Exit the Python terminal, by typing exit() and hitting enter, and close the console. The Heroku database should now have the tables and columns created from the models.py file.

26. The app should be up and running now, so click the “Open app” button

[Back to Index](#table-of-contents)

### Create AWS Account and S3 bucket

Navigate to aws.amazon.com and click on create an AWS account.

Fill in your email address and a password, choose a username for your account, and select continue.

On the account type page, select personal and fill out the required information.

Click create account and continue.

Enter a credit card number which will be used for billing
if you go above the free usage limits.

After you answer the verification questions and confirm the required information your account will be created.

Once your account is created you can go back to aws.amazon.com and sign-in in the upper right by accessing the AWS management console under my account.

Once you've signed in search for S3 to create a new bucket to store files.

If you're asked to select a region select the one closest to you.

Uncheck block all public access and acknowledge that the bucket will be public.

Click create bucket.

[Back to Index](#table-of-contents)

### Set up AWS Bucket

On the properties tab, turn on static website hosting.

For the index and error document, just fill in some default values such as index.html and error.html.

Click save.

On the permissions tab 

Paste in the coors configuration

```
[
  {
      "AllowedHeaders": [
          "Authorization"
      ],
      "AllowedMethods": [
          "GET"
      ],
      "AllowedOrigins": [
          "*"
      ],
      "ExposeHeaders": []
  }
]
```

On the bucket policy tab.

Select, policy generator to create a security policy for the S3 bucket.

Allow all principals by using a star.

The action will be "get object".

Copy the Amazon Resource Name (ARN) from the previous tab.

Paste it into the ARN box here at the bottom.

Click Add statement.

Then generate policy.

Then copy this policy into the bucket policy editor.

Add a slash star here onto the end of the resource key to allow access to all resources in this bucket.

Click Save

On the Access Control List tab

Set the list objects permission for everyone under the Public Access section.

[Back to Index](#table-of-contents)

### Create User Access to S3 Bucket

On the services menu, open IAM.

Click groups then create a new group called manage-milkman-group.

Click next step, and then next step again, then create group.

Click policies and then create policy.

Go to the JSON tab and then select import managed policy 

Search for S3 and then import the S3 full access policy.

Paste in the ARN

Click review policy.

Give it a name and a description.

Click create policy.

Go to groups, click manage-milkman-group and click attach policy.

Search for the policy you just created and select it.

Click attach policy.

Create a user to put in the group.

On the user's page, click add user.

Create a user named milkman-staticfiles-user

Give it programmatic access and select next.

Click through to the end and then click create user.

Download the CSV file with this users access key and secret access key

[Back to Index](#table-of-contents)

### Connect Django to AWS Bucket and upload static files

In Heroku, add the AWS keys to the config variables.

Set USE_AWS key to true.

Set AWS_ACCESS_KEY_ID to the value from the credentials.csv file

Set AWS_SECRET_ACCESS_KEY to the value from the credentials.csv file


This will cause the collectstatic to search for and import all the static files into the S3 bucket.

Commit and push files which will trigger an automatic deployment to Heroku.

In S3, create a new folder called media.

Inside the folder, click upload and Add files.

Select all the product images

Click Next

Under manage public permissions, select grant public read access to these objects.

Click next through to the end and then click upload

[Back to Index](#table-of-contents)

### Create Stripe account

Go stripe.com and click start now.

Create an account using email address, name and set a password.

Click create to create the account.

Confirm the email address.

Get the test API key.

### Connect to Stripe and set Config Vars

In Stripe account.

Click developers.

Click Test Mode.

In the getting started panel, copy the publishable key and the secret key

Set these as the following config vars in Heroku

STRIPE_PUBLIC_KEY (Publishable Key)

STRIPE_SECRET_KEY (Secret Key)

Run the server to get the address of your site.

Copy that and then go to the stripe dashboard.

Click Developers

Select the Webhooks tab and select add endpoint.

Paste in the URL and add /checkout/wh onto the end.

Click receive all events and then click add endpoint.

Click to reveal the Signing Secret and copy.

In Heroku Config Vars, set STRIPE_WH_SECRET to this value

### Set up emails with Gmail

Go to gmail.com and create an account before starting

Go to your Google Account.

Select Security.

Under "Signing in to Google," select 2-Step Verification.

At the bottom of the page, select App passwords.

Enter a name that helps you remember where you’ll use the app password.

Select Generate.

To enter the app password, follow the instructions on your screen. 

The app password is the 16-character code that generates on your device.

Copy this password

Select Done.

Go to the Heroku app to enter it as a config variable called EMAIL_HOST_PASS. And paste in the password and click Add.

Set EMAIL_HOST_USER to your Gmail address

## Credits

Nav, Buttons, Cards, Modals Adapted from example code at [Bootstrap](https://getbootstrap.com/)


Hero Image from [Pexels](https://www.pexels.com/photo/brown-and-white-cow-54550/) and adapted using photoshop

Icons sourced from [Font Awesome](https://fontawesome.com/)

Heroku deployment sourced from [Code Institute](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+FSF_102+Q1_2020/courseware/4201818c00aa4ba3a0dae243725f6e32/d90bfac64e564b41a177b65c34a63502/)

Thanks go to my mentor Narender Singh for advice and guidance.

Thanks to Kieron and the Student Support team for their help and encouragement during my illness.

[Back to Index](#table-of-contents)
