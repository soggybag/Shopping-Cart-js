# Shopping-Cart-js

This example is the completed project that is covered in this series of videos. The video tutorials cover the process of 
building the shopping cart from beginning to end. The process covers many of the basic features of JavaScript. It also 
builds the shopping cart system in many itereations explaing problems, and their solutions along the way. Hopefully this 
explains why methods and approaches were used better than starting with the final version. 

[Shopping Car Tutorial Playlist](https://www.youtube.com/watch?v=1Q74A6ZQxdY&list=PLoN_ejT35AEhzNoPStBzAkpqAu3YQwPj7)

## Goals

The real goal of these videos and this example is to teach basic JavaScript through a practical real world, and interesting 
example that wide range of people can relate to. Who hasn't used an online shopping cart? Here you can make your own, and 
see what is happening behind the scenes. You can apply your everyday experiences into learning the basics of JavaScript and
see ho they translate into code. 

While a large heavily trafficed site would use a complex framework, the ideas here are still very applicable. I feel 
understand the ideas here will give you a foundational understaning of JavaScript. 

Speaking of frameworks, this project does use jQuery. This is an industry standard framework, that makes many basic tasks 
easier to accomplish. 

## Features

The shopping cart covered in these vides is built with JavaScript, it also uses jQuery. 

The shopping cart, in it's finsihed form will be able to: 

*Add items to the cart
*Remove Items from the cart
*Clear all items from the cart
*Display the count of each item
*Total cost for each particular item
*Display the total number of items in the cart
*Display the total cost of all items in the cart
*Save the cart to local storage, persisting the cart between browsing sessions

## JavaScript Concepts covered

* Where to put the script tag, and why
* Varaibles and values
* Objects and Object Oriented Programming
* Funcitions, Arguments, and Parameters
* Arrays
* For loop 
* If statements
* Local Storage
* JSON
* The Module programming pattern
* The DOM (Document Object Model)
* jQuery
  * Selecting elements with jQuery
  * Using Events
  * Handling Forms
  * Writing to the DOM
  

*What the cart does not do*

This example is really focussed on frontend. The cart will not make purchases, or pull products off of existing e-commerce 
web sites. You could use this is as a starting point to building something larger, but features presented here are focussed
only on the frontend functionality of the cart. 

## API 

Creates a single variable shoppingCart and all methods are accessed from this. 

`addItemToCart(name, price, count)` 

Adds an item to the cart. If this item name already exists it increases the count that amount. 

`setCountForItem(name, count)` 

Sets the count for item of name in cart.

`removeItemFromCart(name)`

Removes 1 item of name from cart. 

`removeItemFromCartAll(name)` 

Removes all items of name from cart. 

`clearCart()`

Removes items from cart, empties the cart. 

`countCart()` 

returns the count of the cart. 

`totalCart()`

Returns the total cost of all items in the cart. 

`listCart()` 

Returns an array containing all items in the cart. Each item in the array contains the following properties: 

* name
* price
* count
* total
