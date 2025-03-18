# Simple Calculator

## Introduction
This project is a **Simple Calculator** that performs basic arithmetic operations such as addition, subtraction, multiplication, and division. It is built using **HTML, CSS, and JavaScript** to create an interactive and responsive calculator interface.

## Technologies Used
- **HTML** - For structuring the calculator interface.
- **CSS** - For styling and layout.
- **JavaScript** - For handling user input and performing calculations.

## Features
- Perform basic arithmetic operations: `+`, `-`, `*`, `/`.
- Supports parentheses `(`, `)` for order of operations.
- Includes a **clear button (C)** to reset the display.
- **Delete button (DEL)** to remove the last entered character.
- Decimal point `.` support for floating-point calculations.
- Error handling for invalid expressions.

## Project Structure
```
calculator/
│── index.html      # Main HTML structure
│── style.css       # Styles for the calculator
│── script.js       # JavaScript for calculator functionality
```

## Setup Instructions
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/simple-calculator.git
   cd simple-calculator
   ```
2. Open `index.html` in a web browser.
3. Use the calculator interface to perform calculations.

## How It Works
- **appendToDisplay(value):** Adds the clicked button value to the display.
- **clearDisplay():** Clears the entire input field.
- **deleteLastCharacter():** Removes the last entered character.
- **calculate():** Evaluates the mathematical expression entered in the display.

## Future Enhancements
- Implement keyboard support.
- Improve UI design with animations.
- Add more advanced mathematical functions like square root, exponentiation, etc.

## License
This project is licensed under the **MIT License**.
