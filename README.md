# UNiDAYS Discount Calculator Application

## Pricing Rules

(Quoted from https://github.com/MyUNiDAYS/tech-placements-19-20 above about the program specification)

| Item | Price  | Discount |
| ---- | ------ | -------- |
| A    | £8.00  | None |
| B    | £12.00 | 2 for £20.00 |
| C    | £4.00  | 3 for £10.00 |
| D    | £7.00  | Buy 1 get 1 free |
| E    | £5.00  | 3 for the price of 2 |

## Delivery Charges

(Quoted from https://github.com/MyUNiDAYS/tech-placements-19-20 above about the program specification)

Delivery charge £7.00

Free delivery on orders over £50.00 (inclusive)

## Description:

You can access the application at https://wilsonwang881.github.io/UNiDAYSApplication/

The web interface includes two parts: one for selecting goods and adding them to the shopping cart, one for setting the prices and and discounts. Just click on the buttons on the left pane to switch. Note that once the prices, discounts or list of goods is changed, the shopping cart will be emptied and the user needs to re-select the goods.

## Implementation:

The application can be considered to be server-less. The functions, i.e. selecting goods, change pricing policies, are implemented using JavaScript.

The jQuery, Bootstrap JavaScript and CSS, Popper.js are held in this repository instead of using links.

## Usage:

The user can change the number of each item either from the input field at the bottom, or from the small input fields below each item's price tag.

Once the user finishes entering items, click on the button on the right of the input field to generate the delivery cost, the total price and a summary.

The prices can be changed and saved through the 'Pricing Rules' page. The user will be prompted when the price is updated successfully.

The pricing policy can be changed also. Just follow the simple syntax:

1. none -> for no discount
2. x cost y -> if the buyer wants x same items, the buyer will pay for y pounds for x items
3. x free y -> the buyer gets extra y items for free if the buyer buys x items
3. x for y -> the buyer pays for the price of y items but will get x items

When validating the new pricing policy, the white space before and after the whole text will be removed. Also, please leave one space between elements in the policy.

## Deployment:

Put the code into an online static website hosting service. Possible choices include but not limited to Amazon Web Services S3, GitHub repository web hosting (need to change the repository's settings) and Google Drive web hosting. Note some of the services are free of charge but some may incur additional charges.

keep the file structure, i.e. put the files in the corresponding folders. If the file structure is changed, remember to change the head part of the index.html file in order to ensure correct reference.

To host the application locally, simply open the index.html in any modern browser and you are good to go!
