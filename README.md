## Assignment 5

## Live URL
https://shaka3507.github.io/assignment5/index.html

## Assignment question
The most interesting thing from this week was learning the [] array syntax for creating associate arrays. I'm more familiar with {} notation, but was amazed to see that you can set for example person = [], person["age"] = 10 as a way to store information. I'm still wondering what the benefits are of that syntax versus person = {"age": 10}. I'm also surprised and excited to use destructuring to assign and reassign elements within an array.

## Requirements:
Part 1
- [x] Create a representation of the items and prices as an associative array of items
and prices (using array or object format)

Part 2
- [x] Display a menu of items on the page using the array

Part 3
- [x] A text input for the item name and a button labeled 'add to cart' is below menu
- [x] A div that define an area for a shopping cart is below the menu
- [x] an additional button below the cart, labeled checkout and below the menu is present
- [x] have an associative array to represent quantities in the cart, and keys should be the menu items and the values will be quantities. should start off as 0 for each

Part 4
- [x] a user can enter an item in text box and click 'add to cart' - if item is valid (case insensitive), add 1 to the quantity
- [x] display all items with quantity greater than 0 in cart area with quantity

Part 5
- [x] a user can click checkout and final cost of all items, tallied and a popup should display the quantity and total cost for each item if quantity is greater than 0, including total of order
- [x] a user that sees the popup, and clicks ok, should clear all the quantities in cart and see reflected in UI
