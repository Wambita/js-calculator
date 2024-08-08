# Simple Calculator

This is a simple calculator application built with HTML, CSS, and JavaScript. It provides basic arithmetic operations like addition, subtraction, multiplication, and division.

## Table of Contents
- [Demo](#demo)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Demo

You can view a live demo of the calculator [here](https://wambita.github.io/js-calculator/).

## Features

- Addition, subtraction, multiplication, and division operations
- Responsive design for various screen sizes
- User-friendly interface
- Light mode and dark mode

## Installation

To get a local copy up and running, follow these simple steps:

1. Clone the repository
    ```sh
    git clone https://github.com/Wambita/js-calculator.git
    ```
2. Open the `index.html` file in your favorite browser.

## Usage

1. Open the `index.html` file in a web browser.
2. Use the calculator buttons to perform calculations.

## Technologies Used

- HTML
- CSS
- JavaScript

## CSS Breakdown

The CSS file includes styles for the calculator's layout and appearance. Media queries are used to ensure the calculator is responsive on screens below 550px width.

### Key CSS Classes and IDs

- `body`: Styles for the overall page, including flexbox layout and background color.
- `h2`: Styles for the header, including font size, color, and decoration.
- `#calculator`: Styles for the calculator container, including background color and border radius.
- `#display`: Styles for the display area of the calculator, including padding, font size, and background color.
- `#keys`: Styles for the grid layout of the calculator buttons.
- `button`: Styles for the buttons, including size, color, and hover/active states.
- `.operator-btn`: Additional styles for operator buttons.

### Javascript 
Has 3 functions:
 + `appendToDisplay()` it displays the numbers that have been input and operand to the display so as to view the equation.

 + `clearDisplay()` - it clears the display so that a new equation can be added

 + `calculte()` - does the calculation of the problem using `eval` function and also has error handling to catch errors

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.
