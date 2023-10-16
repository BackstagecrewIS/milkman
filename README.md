# Pete's Dairy

[Not yet deployed](# "Link to the site")

A basic site for a local dairy home delivery service
It is designed to be used on any device.

[Mockup images](https://ui.dev/amiresponsive?url=https://8000-backstagecrewis-milkman-gv8e3vmyqxk.ws-eu105.gitpod.io/)

## Table of Contents

- [User Experience UX](#user-experience-ux)
- [Design Strategy](#design-strategy)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Testing](#testing)
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

#### Registration and usder accounts
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
| 19 | Shopper | Easily enter my payment information | Checkout quickly without any hassles |
| 20 | Shopper | Feel my personal and payment information is safe and secure | Confidently provide the needed information to make a purchase |
| 21 | Shopper | View an order confirmation after checkout | Verify that I haven't made any mistakes |
| 22 | Shopper | Receive an email confirmation after checkout | Keep the confirmation of what I've purchased for my records |

#### Admin and store management
| # |As A/An| I want to    | So I Can  |
|---|---------|-------------| -----|
| 23 | Shopper | Add a product | Add new items to my store |
| 24 | Shopper | Edit or update a product | Change product price, description, images and other criteria |
| 25 | Shopper | Delete a product | Remove items that are no longer available |


## Design Strategy
    
* Design Considerations
  - Colour Scheme
  
  The colour scheme is the standard bootstrap colour scheme adapted to have white background, black text and black or white buttons.

  Messages will displayed using bootstrap toasts in a simple pop up

  There will be a colour coded bar above the toasts to signify their type using standard bootstrap colour coding.
  error - #dc3545 Red
  warning - #ffc107 Orange
  success - #28a745 Green
  information - #17a2b8 Cyan
  
  - Typography
    
    For simplicity, only one font style will be used. The Lato font is a clear sans-serif font which works well for all elements of the site. The fallback sans-serif is specified in case the Lato font fails to load.
    
  - Imagery
  
    Hero Images created using Photoshop and an image from Pexels [Photo by Klaus Hollederer:]( https://www.pexels.com/photo/brown-and-white-cow-54550/)

    The icons used are sourced from [Font Awesome](https://fontawesome.com/)
    
  - Wireframes

  Initial designs for the site. All pages to be responsive.
  
  The wireframes can be viewed in a separate [Wireframes File](/wireframes.md)

[Back to Index](#table-of-contents)


### The strategy plane:
***What are you aiming to achieve in the first place and for whom?***

#### Users
Users should be able to use the site without needing additional instruction.

The interface should be simple and work on a variety of devices.

Users will be able to select and pay for items for delivery the next day

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

Users must be able to change the quantity of items in the shopping bag before conpleting their purchase

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

A future version could allow users to select a delivery date

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

The site will be designed to work on screens above 300px

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
* Admin functions will only be visible to the admin user

### The skeleton plane:
**How will our information be represented, and how will the user navigate to the information and the features?**

All main pages will contain a user menu which allows admins to login and access further pages. Users will be able to register and log in to see their profile information.

All main pages will contain a navigation menu which allows the user to select a product category or list all products by price or rating

A search function will allow the user to search for a product

### The surface plane:
**What will the finished product look like? What colors, typography, and design elements will we use?**

Wireframes for the site can be viewed in a separate [Wireframes File](/wireframes.md)

All pages to be responsive.

The pages will use the customised Bootstrap elements throughout.

Messages will be displayed using toasts to notify the user of the results of action such as adding a product to the bag or deleting a product.

[Back to Index](#table-of-contents)

## Features

### Responsive
The site must be designed to work on on all devices from mobile to desktop.

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

[jQuery:](https://en.wikipedia.org/wiki/JQuery) is used for additional functions in Bootstrap function.

[AllAuth](https://www.codingninjas.com/studio/library/django-allauth-setup-and-configuration) User management functions handled by AllAuth

[Stripe](https://stripe.com/) is used to handle all payments

[Git:](https://git-scm.com/) was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.

[GitHub:](https://github.com/) is used to store the projects code after being pushed from Git.

## Image Credits

Hero Image created using Photoshop and an image from Pexels [Photo by Klaus Hollederer:]( https://www.pexels.com/photo/brown-and-white-cow-54550/)

All product images sourced from [Pexels]( https://www.pexels.com/)

[Back to Index](#table-of-contents)

## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate the project to ensure there were no syntax errors in the project.

W3C Markup Validator - Results [link](https://validator.w3.org/nu/?doc=https%3A%2F%2Fapp-faq.herokuapp.com%2F)

W3C CSS Validator - Results [link](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fapp-faq.herokuapp.com&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#errors)

## Testing User Stories from User Experience (UX) Section

* ### User Stories
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
| 19 | Shopper | Easily enter my payment information | Checkout quickly without any hassles | Payments handled by Stripe |
| 20 | Shopper | Feel my personal and payment information is safe and secure | Confidently provide the needed information to make a purchase | Payments handled by Stripe |
| 21 | Shopper | View an order confirmation after checkout | Verify that I haven't made any mistakes | Order confirmation page shows all order details after processing by Stripe |
| 22 | Shopper | Receive an email confirmation after checkout | Keep the confirmation of what I've purchased for my records | Checkout success page emails the user with order confirmation information |

#### Admin and store management
| # | As A/An | I want to | So I Can | Satisfied by |
|---|---------|-------------| -----| ---------- |
| 23 | Shopper | Add a product | Add new items to my store | Product management page allows the admin to add a new product |
| 24 | Shopper | Edit or update a product | Change product price, description, images and other criteria | When logged in, an admin has the options to edit each product on the product and product detail pages |
| 25 | Shopper | Delete a product | Remove items that are no longer available | When logged in, an admin has the option to delete each product on the product and product detail pages  |

    
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

All of the nav links were tested from each page for functionality both while logged out and logged in to confirm that they funtion correctly.


#### Layout tests

The Website was tested on Google Chrome on both a laptop, tablet and mobile phone for functionality and responsiveness

The responsivity of the website was checked on a variety of devices using [Responsive Design Checkers](https://responsivedesignchecker.com/checker.php?url=https%3A%2F%2F8000-backstagecrewis-milkman-gv8e3vmyqxk.ws-eu105.gitpod.io%2F&width=1500&height=1200) and [AmIResponsive](https://ui.dev/amiresponsive?url=https://8000-backstagecrewis-milkman-gv8e3vmyqxk.ws-eu105.gitpod.io/)

Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

### Solved Bugs

Bug: noimage.png not loading for missing images

Cause: noimage.png not added to media folder

Solution: Upload noimage.png to media folder

------------------------------------------------------------

Bug: Images loading in their native size which means all images would need to be cropped to a standard size.

Cause: No css for product images assuming all images the same size when uploaded

Solution: Create new class of product-image with height: 200px and object-fit: contain; in base.css to over-ride image defaults


------------------------------------------------------------

Bug: Order totals in order confirmation emails showing 14 decimal places

Cause: Missing formatting on variables

Solution: Added floatformat:2 to the variables


------------------------------------------------------------

Bug: Page headings not centered on some pages

Cause: Missing styling for headings on some pages

Solution: Ensure all headings contain text-center class

------------------------------------------------------------

Bug: Background image goes off screen on smaller displays

Cause: Large image overflows screen edge

Solution: Add new background image for smaller screens

------------------------------------------------------------

Bug: Headline text in index.html obscured by background image on smaller screens

Cause: Image and headline text similar colours with little contrast

Solution: Add 1px stroke to the headline text to give contrast against background

------------------------------------------------------------

Bug: Incorrect details in confirmation email subject

Cause: Incorrect site name in confirmation_email_subject.txt

Solution: Updated confirmation_email_subject.txt

------------------------------------------------------------

Bug: 

Cause: 

Solution: 

------------------------------------------------------------

Bug: 

Cause: 

Solution: 

------------------------------------------------------------

Bug: 

Cause: 

Solution: 

------------------------------------------------------------

Bug: 

Cause: 

Solution: 

------------------------------------------------------------

Bug: 

Cause: 

Solution: 

------------------------------------------------------------

Bug: 

Cause: 

Solution: 


[Back to Index](#table-of-contents)

## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/BackstagecrewIS)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section on the left column.
4. Under "Source", select 'Deploy from Branch then click the dropdown called "None" and select "Main".
5. Click Save to confirm the choice.
6. Scroll back to the top of the page to locate the link to the published site in the "GitHub Pages" section.

[Back to Index](#table-of-contents)


### Forking the GitHub Repository

A fork is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project by using the following steps

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page) above the Settings Button on the menu, click the Fork Button.
3. Scroll down the page and click the Create Fork button to make a copy.
4. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. Under the repository name, click the Code button next to the green Gitpod button.
3. To clone the repository using HTTPS, under the HTTPS tab, copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```
7. Press Enter. Your local clone will be created.

Click [Here](https://docs.github.com/en/get-started/quickstart/fork-a-repo) for the Github tutorial.

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

  `from taskmanager import db`

  `db.create_all()`

25. Exit the Python terminal, by typing exit() and hitting enter, and close the console. The Heroku database should now have the tables and columns created from the models.py file.

26. The app should be up and running now, so click the “Open app” button

## Credits

Nav, Buttons, Cards, Modals Adapted from example code at [Bootstrap](https://getbootstrap.com/)

Hero image CSS adapted from [](https://www.w3schools.com/howto/howto_css_hero_image.asp)

Hero Image from [Backstagecrew](https://backstagecrew.com)

Icons sourced from [Font Awesome](https://fontawesome.com/)

Heroku deplyment sourced from [Code Institute](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+DIWADRDB+2022_Q3/courseware/c0c31790fcf540539fd2bd3678b12406/6e44128b0b37416ab40c1a87ef2cb32a/)

Thanks go to my mentor Narender Singh for advice and guidance.

[Back to Index](#table-of-contents)
