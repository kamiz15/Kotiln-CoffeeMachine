# Coffee Machine Simulator ☕

This is a simple Kotlin console application that simulates a coffee machine. It tracks resources (water, milk, coffee beans, cups, money) and allows the user to perform actions like buying coffee, refilling resources, and collecting money.

## Features

- Make 3 types of coffee:
  - **Espresso** (250ml water, 16g beans, $4)
  - **Latte** (350ml water, 75ml milk, 20g beans, $7)
  - **Cappuccino** (200ml water, 100ml milk, 12g beans, $6)
- Track current machine resources
- Refill ingredients and cups
- Take out all collected money
- Exit the program anytime
- Supports multi-step actions with internal state handling

## How It Works

The machine listens for user input and changes its behavior based on the current state:

1. **buy** – Choose a coffee to buy.
2. **fill** – Refill water, milk, beans, and cups.
3. **take** – Withdraw all collected money.
4. **remaining** – Display current supply levels.
5. **exit** – Stop the machine.

## Example

