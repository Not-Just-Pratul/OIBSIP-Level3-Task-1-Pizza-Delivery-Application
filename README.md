# Pizza-Deliciosa

[Not-Just-Pratul](https://github.com/not-just-pratul)

## Project Overview

Pizza-Deliciosa is a pizza delivery web application that helps customers build and order pizzas online. Users can choose pizza flavor, size, crust type, and toppings, then preview the order, add multiple pizzas, and submit delivery information.

## Live Deployment

- Production: https://pizza-deliciosa.netlify.app/

## Features

- Display of available pizza menu items
- Flavor selection for each pizza
- Size and crust customization
- Topping selection and order preview
- Add multiple pizzas to the cart
- Checkout workflow with delivery details
- Order confirmation message

## Installation / Setup Instructions

1. Open a terminal.
2. Navigate to the project folder:
   ```bash
   cd "Task 8/Pizza-Deliciosa"
   ```
3. Open `index.html` in a browser to run the application locally.

## Technologies Used

- HTML5
- CSS
- Bootstrap
- JavaScript

## Behaviour-Driven Development (BDD)

| Behaviour | Input | Output |
| :------------- | :----------: | -----------: |
| Select pizza flavor | Chicken Tikka | Selected flavor displayed |
| Select pizza size | Large, medium, small | Selected size displayed |
| Select crust | Crispy, stuffed, or gluten-free | Selected crust displayed |
| Select toppings | Choose available toppings | Toppings selected |
| Press Proceed | — | Selection summary and price displayed |
| Press Add Pizza | Pizza flavor, size, crust, toppings | Pizza added to the order |
| Press Checkout | — | Order total displayed |
| Press Home Delivery | Name, phone number, delivery location | Delivery details requested |
| Press Place Order | — | Order confirmed with delivery details |

## Known Issues

- All toppings currently use the same price regardless of pizza size.

## License

This project is licensed under the MIT License. See `Task 8/Pizza-Deliciosa/LICENSE` for details.

