# Coffee Machine

This is a Python project for a coffee machine. It allows users to select various coffee options and handles the process of making the coffee, deducting resources, and handling payments.

## Features

- Offers three types of coffee: espresso, latte, and cappuccino.
- Keeps track of available resources such as water, milk, and coffee.
- Calculates the cost of each coffee option.
- Accepts user input for selecting a coffee or performing other actions.
- Processes coin inputs for payment.
- Verifies if there are sufficient resources to make the selected coffee.
- Handles transactions and returns change if necessary.
- Keeps track of the machine's profit.
- Provides a report of available resources and profit.

## Getting Started

To run the coffee machine, follow these steps:

1. Make sure you have Python installed on your system.
2. Clone the repository or download the project files.
3. Open the terminal or command prompt and navigate to the project directory.
4. Run the `main.py` file using the following command:

```
python main.py
```

5. Follow the instructions in the console to interact with the coffee machine.

## Dependencies

This project has no external dependencies. It only requires Python 3.x to be installed on your system.

## Usage

Once you run the `main.py` file, you will be prompted to select a coffee or perform other actions. Available commands are:

- `expresso`: Selects the espresso coffee option.
- `latte`: Selects the latte coffee option.
- `cappuccino`: Selects the cappuccino coffee option.
- `report`: Displays a report of available resources and profit.
- `off`: Turns off the coffee machine.

When selecting a coffee option, you will be asked to insert coins for payment. The program will calculate the total based on the number of quarters, dimes, nickels, and pennies you enter. If the payment is sufficient, the coffee will be made, and any change will be returned.

## Examples

Here are some examples of how to interact with the coffee machine:

1. Selecting a coffee:

```
What would you like? (expresso/latte/cappuccino): latte
Please insert coins.
how many quarters?: 2
how many dimes?: 0
how many nickles?: 1
how many pennies?: 0
Here is $0.75 in change.
Here is your latte ☕️. Enjoy!
```

2. Checking the report:

```
What would you like? (expresso/latte/cappuccino): report
Resources:
 Water: 250ml
 Milk: 50ml
 Coffee: 76g
 Money: R2.5
```

3. Turning off the machine:

```
What would you like? (expresso/latte/cappuccino): off
Turning off the machine.
Goodbye.
```

## License

This project is licensed under the MIT License. You can find more details in the [LICENSE](LICENSE) file.

Feel free to modify and adapt this project to suit your needs.

## Acknowledgments

This project is based on a Python course exercise.