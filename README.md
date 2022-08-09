# ShoppingCart
React Shopping Cart that can be restocked using a Strapi API database

## What Is This?
This is a Shopping Cart app that allows the user to take stock out of a cart and create a shopping cart that provides a current total. The code is provided by MITxPro and we were tasked with refactoring the restock feature using the Strapi API with a database we created. In this database, we have a list of products and when we select `restock`, the app makes a call to the API to fetch the products list and restock the app with these products.

## What I Did
I created a Strapi database with products and practiced `GET` and `POST` using Postman. The app references this database and makes a call to it when we need to restock items. The items that are restocked are the current items in the database I created. The code was already provided for us so I didn't need to make any changes other than creating the database.
