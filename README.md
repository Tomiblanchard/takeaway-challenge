[![Build Status](https://travis-ci.org/makersacademy/takeaway-challenge.svg?branch=master)](https://travis-ci.org/makersacademy/takeaway-challenge)
[![Coverage Status](https://coveralls.io/repos/makersacademy/takeaway-challenge/badge.png)](https://coveralls.io/r/makersacademy/takeaway-challenge)

Takeaway Challenge
==================

Task
-----

We were given the following user stories to guide development of a simple command line takeaway menu + ordering system.

```sh
As a customer
So that I can check if I want to order something
I would like to see a list of dishes with prices

As a customer
So that I can order the meal I want
I would like to be able to select some number of several available dishes

As a customer
So that I can verify that my order is correct
I would like to check that the total I have been given matches the sum of the various dishes in my order

As a customer
So that I am reassured that my order will be delivered on time
I would like to receive a text such as "Thank you! Your order was placed and will be delivered before 18:52" after I have ordered
```

Features included:

* A list of dishes with prices
* Ability to assemble a list of items to order
* Ability to place an order by calling the appropriate method.
* Will receive a text stating that the order was received and that it will be there in 1 hour.

Largely unit/feature tested (aside from Twilio calls etc.)

# Installation

Clone this repo and run ```bundle``` and then ```rspec```. To use the twilio functionality, you will need to create your own twilio account and enter your account details in the appropriate places.
