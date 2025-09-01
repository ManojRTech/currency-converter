# currency-converter

Project Overview

This is a Currency Converter Web Application that allows users to convert an amount from one currency to another using live exchange rates from an external API. It also dynamically updates flags based on selected currencies to enhance user experience.


Features

Live Currency Conversion: Converts any amount between multiple currencies using the Open Exchange Rates API.


Dynamic Dropdowns: Automatically populates dropdowns with all supported currency codes.

Flag Display: Updates the flag of the selected currency dynamically.

Input Validation: Ensures the amount entered is valid and defaults to 1 if empty or invalid.

Responsive UI: Works well on both desktop and mobile devices.


Tech Stack

HTML: Provides the structure of the application including forms, buttons, and containers.

CSS: Handles styling, layout, and responsive design using internal styles.

JavaScript:

DOM manipulation (document.querySelector, createElement)

Event handling (click, change, load)

API fetching (fetch) for live currency rates

Dynamic updates for exchange results and flags


How to Use

Open index.html in a modern web browser.

Select the source currency and target currency from the dropdowns.

Enter the amount to convert in the input box.

Click “Convert” to see the converted amount.

The flags of the selected currencies are displayed for visual clarity.


Future Improvements

Add historical exchange rates and chart visualization.

Allow automatic detection of the user’s local currency.

Enhance UI with animations and better mobile responsiveness.

Add offline support with cached exchange rates.


GitHub Repository

View Code on GitHub
