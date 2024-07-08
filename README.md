# Restaurant Menu Pricing System

This project implements a simple menu pricing system for a restaurant, allowing calculation of prices with or without tax and applying discounts based on the number of guests.

## Overview

The project consists of two main functions implemented in JavaScript:

- **getPrices(taxBoolean)**: getPrices(taxBoolean) Prints the menu items along with their prices. If taxBoolean is true, it calculates prices including tax; otherwise, it displays prices without tax.
- **getDiscount(taxBoolean, guests)**: getDiscount(taxBoolean, guests) Calls getPrices() and then calculates and displays discounts based on the number of guests. Discounts are applied as follows:
- **Tie Detection**: The game detects when there is a tie if all spots are filled without any player winning.
   - Less than 5 guests: 5% discount.
   - 5 or more guests: 10% discount.

