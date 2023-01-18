# README

## This is a Follow Along For Agile Web Development with Rails 6
I would like to use this as a resource for anyone learning to use rails or
if I ever have to teach Rails again this will be a repo I can leverage.

I also want to hone in my methodology and process. How do I stay organized.
How do I document my progress, dependencies, code, etc.

---
# Iteration G1: Capturing An Order

## 1.17.23 (11:22 PM)
### In this Commit:
- Generated a scaffold for Order model
- Added a Order foreign key to line_item
- Worked with enums and forms
- Fixed the action cable from previous chapter
---
# Iteration F5: Broadcasting Updates With Action Cable

## 1.16.23 (4:32 PM)
### In this Commit:
- I'm having issues identifying action cable working
 
---
# Iteration F4: Hiding An Empty Cart With A Custom Helper

## 1.16.23 (3:39 PM)
### In this Commit:
- Using a helper to hide cart

---
# Iteration F3: Highlighting Changes

## 1.16.23 (3:00 PM)
### In this Commit:
- Use Keyframes to highlight changes

---
# Iteration F2: Creating An AJAX Based Cart

## 1.15.23 (7:00 AM)
### In this Commit:
- Ajaxify the cart

---
# Iteration F1: Moving The Cart

## 1.15.23 (6:00 AM)
### In this Commit:
- Moved the cart to prepare for ajax.

---
# Iteration E3: Finshing The Cart

## 1.15.23 (4:00 AM)
### In this Commit:
- We added the ability to destroy a cart
- We changed the formatting of the cart
- Created a couple methods to find the total of the line items & total of cart

---
# Iteration E2: Handling Errors

## 1.15.23 (4:00 AM)
### In this Commit:
- Created a rescue hook for invalid carts
- updated line_items_controller_test

---
# Iteration E1: Creating A Smarter Cart

## 1.15.23 (3:30 AM)
### In this Commit:
- Created a migration to add quantity to line item
- Created a migration to update already exisiting line_items

---
# Iteration D3: Adding a Button

## 1.14.23 (7:30 PM)
### In this Commit:
- Created Cart object
- Familiarize with session objects
- Created a private method and placed it in a concern making it accessible to all of our controllers
- Created relationships between carts and line items and line items and products
- Added a button that causes a product to be posted to a cart, causing a new line item to be created

---
# Iteration D1: Finding A Cart & Iteration D2: Connecticting Products to Carts

## 1.13.23 (3:02 PM)
### In this Commit:
- Scaffold the cart
- Scaffold the line_item
  - understand belongs_to and active record associations.
- Modified ProductsControllerTest

Next Steps: Create a branch for Iteration D3: Adding A button
---
# Iteration C5: Caching Of Partial Results

## 1.12.23 (11:31 PM)
### In this Commit:
- Familiarize with caching (should look more into this in the future)

---
# Iteration C4: Function Testing Of Controllers

## 1.12.23 (10:36 PM)
### In this Commit:
- Add tests to store_controller

---
# Iteration C3: Using A Helper To Format The Price

## 1.12.23 (10:45 PM)
### In this Commit:
- Use number_to_currency helper

---
# Iteration C2: Adding Page Layout

## 1.12.23 (10:30 PM)
### In this Commit:
- Added a common page layout

---
# Iteration C1: Creating the Catalog Listing

## 1.12.23 (9:19 PM)
### In this Commit:
- Created store controller
- Assign root
- View for Pragmatic Catalog Store

---
# Iteration B2: Unit Tests

## 1.12.23 (12:45 PM)
### In this Commit:
- Created simple unit tests for the Product Model and Controller
- Fixtures

---
# Iteration B1: Validations

## 1.12.23 (10:54 AM)
### In this Commit: 
- Created simple validations for Product

---
# Iteration A2: Making Prettier Listings

## 1.12.23 (10:30 AM)
### In this Commit: 
- Added Seed Data
- We styled the Products page


---
#  Iteration A1: Creating The Product Maintenance App

## 1.10.23 (8:56 PM)

### In this Commit: 
- Ran Migration
- Updated the form for Product
- Finished Iteration A1: Creating the Product Maintenance Application

---
## 1.10.23 (8:22 PM)

### In this Commit:
- Generated Scaffold For Product
- Ran Migration For Product

---
## 1.9.23

### In this Commit:
- The first commit
- Generated brand new rails application

---

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
