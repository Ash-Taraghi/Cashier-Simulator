# Cash Register Project 📠

## Overview

The Cash Register Project is a simple web application that simulates a cash register. The application allows users to input the amount of cash they have, compare it with the price of an item, and determine the correct change to return, if any. It also displays the status of the cash register based on the transaction.

## Features

- Calculate and display the change due for a purchase.
- Display the status of the cash register (OPEN, CLOSED, INSUFFICIENT_FUNDS).
- Show the amount of cash remaining in the register after a transaction.
- Responsive design suitable for various screen sizes.

## Files

- **index.html**: The main HTML file that structures the web page.
- **styles.css**: The CSS file that styles the web page.
- **script.js**: The JavaScript file that contains the logic for the cash register calculations.

## Usage

1. Open the `index.html` file in a web browser.
2. Enter the cash amount in the input field provided.
3. Click the "Purchase" button or press "Enter" to execute the transaction.
4. The application will display the price, change due, and the status of the cash register.

## How It Works

- **Input Field**: Users input the amount of cash they have.
- **Purchase Button**: Clicking this button triggers the calculation of the change.
- **Change Calculation**: The JavaScript logic calculates the change due and determines whether the register has enough cash to complete the transaction.
- **Status Display**: The status is updated based on the transaction, showing whether the register is OPEN, CLOSED, or if there are INSUFFICIENT_FUNDS.

## CSS Styling

The project uses a simple, clean layout with a centered container. The design is responsive, ensuring a good user experience on both desktop and mobile devices.

## JavaScript Functionality

The JavaScript code:
- Retrieves the cash input by the user.
- Compares it to the item price.
- Determines the change to be returned.
- Updates the status of the cash register and the cash in the drawer.

## Requirements

- A web browser to run the application.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

