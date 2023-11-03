# Testing

## Pages

|Feature|Test|Result|
|----|----|----|
|base.html|base.html renders correctly|Working correctly|
|index.html|Loads end extends base.html|Working correctly|
|products.html|Loads and displays selected products|Working correctly|
|Product sorting|Sorting of product by appropriate fields|Working correctly|
|product_details.html|Displays details of selected product|Working correctly|
|Product images|Product images load in product pages|Working correctly|
|Search results|Displays the result of a search|Working correctly|
|Bag total|Shows bag total including delivery in header|Working correctly|
|Add product to bag|Add selected product to the bag|Working correctly|
|Add correct quantity to bag|Add the correct quantity of the selected item|Working correctly|
|Increment quantity|Adds 1 and limited to 99|Working correctly|
|Decrement quantity|Subtracts 1 and limited to 1|Working correctly|
|bag.html|displays correct products and quantities|Working correctly|
|Increment quantity|Adds 1 and limited to 99|Working correctly|
|Decrement quantity|Subtracts 1 and limited to 1|Working correctly|
|Update link|Updates value to changed quantity|Working correctly|
|Remove from bag link|Removes item from shopping bag|Working correctly|
|Item subtotals|Subtotal displays correct information|Working correctly|
|Bag total|Total displays correct information|Working correctly|
|Delivery cost|Delivery cost correct and added as appropriate|Working correctly|
|Empty search|Displays error message in toast|Working correctly|
|Checkout success|Displays correct order information|Working correctly|

## Navigation

|Feature|Test|Result|
|----|----|----|
|Nav menu|All menu items link to the correct url|Working correctly|
|User Menu|All menu items link to the correct url|Working correctly|
|Main page Shop Now button|Direct to All products page|Working correctly|
|main-nav.html|Included on large screens|Working correctly|
|mobile-top-header|Included on smaller screens|Working correctly|
|Search box (main-nav)|Navigates to search function and passes argument|Working correctly|
|Search box (mobile-top-header)|Navigates to search function and passes argument|Working correctly|

## User Profile

|Feature|Test|Result|
|----|----|----|
|Create|User can create login|Working Correctly|
|Read|User can view profile|Working Correctly|
|Update|User can make changes to profile and save|Working Correctly|
|Delete|User can delete profile|This can only be done through the database admin functions. Future development will address this issue|

## Security

|Feature|Test|Result|
|----|----|----|
|Admin functions only show to admin users|Checked when logged out and with admin and non-admin account|Working correctly|
|Non admin users denied access to admin links|Non admin users shown a denial and redirected to log in again|Working correctly|
|Login logout toggles on login|Login showed to users not logged in and logout shown when logged in|Working correctly|

## Free Delivery

|Feature|Test|Result|
|----|----|----|
|Banner appears|Free delivery banner appears below threshold|Working correctly|
|Banner Hidden|Banner not visible over threshold|Working correctly|
|Show threshold amount|Banner shows correct amount|Working correctly|
|Delivery cost added|5% delivery charge added below £10|Working correctly|
|Free delivery option|No delivery charge on bags £10 and over|Working correctly|

## Toasts

|Feature|Test|Result|
|----|----|----|
|Error|Displays a toast with the correct colour for the message level|Working correctly|
|Info|Displays a toast with the correct colour for the message level|Working correctly|
|Warning|Displays a toast with the correct colour for the message level|Working correctly|
|Success|Displays a toast with the correct colour for the message level|Working correctly|
|Add to bag toast|Displays when product added to bag with correct information|Working correctly|
|Remove from bag|Displays when product removed from bag with correct information|Working correctly|
|Update bag quantity|Displays when item quantity updated in the bag with correct information|Working correctly|
|Error messages|Displays error message with details|Working correctly|
|Bag details displaying|Displays correct items and prices|Working correctly|
|Show delivery info|Shows when delivery threshold not reached|Working correctly|
|Checkout link|Links to secure checkout|Working correctly|
|Log in / out|Displays to confirm log in or log out|Working correctly|
|Checkout success|Confirms order correctly created|Working correctly|

## Database

|Feature|Test|Result|
|----|----|----|
|User model|Has correct fields|Working correctly|
|Create user|New users can sign up and create an account|Working correctly|
|Read user|View user information in profile and checkout|Working correctly|
|Update user|Update user information|Working correctly|
|Delete user|Delete user account|Users cannot yet delete their profile. Future development will address this issue|
|Product model|Has correct fields|Working correctly|
|Create product|Add a product|Working correctly|
|Add product image|Upload an image for the product|Working correctly|
|Delete product image|Remove the image from the product|Deletes the link from the database but leaves image file in media folder. Future development will address this issue|
|Read product|Display products|Working correctly|
|Update product|Change product info|Working correctly|
|Delete product|Delete product|Deletes from database but leaves image file in media folder. Also needs confirmation pop up Future development will address this issue|
|Category model|Has correct fields|Working correctly|
|Create category|Admin user can create category|This can only be done through the database admin functions. Future development will address this issue|
|Read category|Categories are read in with product information|Working correctly|
|Update category|Admin user can change a category|This can only be done through the database admin functions. Future development will address this issue|
|Delete category|Admin can delete a category|This can only be done through the database admin functions. Future development will address this issue|
|Order created|Order created when payment complete|Working correctly|
|Order created by payment intent|Creates order if user closes browser|Working correctly|

## Stripe

|Feature|Test|Result|
|----|----|----|
|Payment intent|Payment intent reaches Stripe|Working correctly|
|Payment success|Payment reaches Stripe|Working correctly|
|Further Authentication|Authentication popup appears over loading overlay|Working correctly|
|Webhooks|Receives and responds to webhooks|Working correctly|

## Database Admin

|Feature|Test|Result|
|----|----|----|
|Admin login|Check access to database|Working correctly|

## Responsive Elements

|Feature|Test|Result|
|----|----|----|
|Nav menu|Visible on large screens|Working Correctly|
|Nav menu collapse|Visible on smaller screens|Working Correctly|
|Products layout|Adjusts number of columns based on device width|Working Correctly|

## Emails

|Feature|Test|Result|
|----|----|----|
|User authentication email sent|Email sent to user on account creation|Working correctly|
|User authentication email works|Clicking email link verifies user email|Working correctly|
|Order confirmation email sent|Email sent to user on order completion contains correct information|Working correctly|

## Other Functionality

|Feature|Test|Result|
|----|----|----|
|Users can view products without log in|All functions work for non logged in users|Working correctly|
|Users can make a purchase without account|Anonymous users can make a purchase without an account|Working correctly|
