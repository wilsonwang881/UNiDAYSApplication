# UNiDAYS Discount Calculator Application

## Link to the program specification: 

https://github.com/MyUNiDAYS/tech-placements-19-20

## Description:

The web interface includes two parts: one for selecting goods and adding them to the shopping cart, the other part for adding new goods and setting the prices and and discounts. Just click on the buttons on the left pane to switch. Note that once the prices, discounts or list of goods is changed, the shopping cart will be emptied and the user needs to re-select the goods.

## Implementation:

The application is implemented mainly using JavaScript and can be considered to be server-less. I am currently trying to integrate with Vue.js.

The jQuery, Bootstrap JavaScript and CSS are held in the repository instead of using links.

## Usage:

The user can change the number of each item either from the input field at the bottom, or from the small input fields below each item's price tag.

Once the user finishes entering items, click on the button on the right of the input field to generate the delivery cost, the total price and a summary.

The prices can be changed and saved through the 'Pricing Rules' page. The user will be prompted when the price is updated successfully.

The pricing policy can be changed also. Just follow the simple syntax:

1. none -> for no discount
2. x cost y -> if the buyer wants x same items, the buyer will pay for y pounds for x items
3. x free y -> the buyer gets extra y items for free if the buyer buys x items
3. x for y -> the buyer pays for the price of y items but will get x items

## Deployment:

Put the code into an online static website hosting service. Possible choices include but not limited to Amazon Web Services S3, GitHub repository web hosting (need to change the repository's settings) and Google Drive web hosting. Note some of the services are free of charge but some may incur additional charges.
