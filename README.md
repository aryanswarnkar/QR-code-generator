readme_content = """# QR Code Generator

A simple, interactive command-line application built with Node.js that takes a URL as input and instantly generates a QR code image. 

## Features
- Prompts the user to enter a URL via the terminal.
- Generates a QR code image (`qr_img.png`) for the provided link.
- Automatically saves the entered URL into a local text file (`URL.txt`) for reference.

## Prerequisites
Ensure you have [Node.js](https://nodejs.org/) installed on your machine.

## Installation

1. Clone the repository:git clone [https://github.com/aryanswarnkar/QR-code-generator.git](https://github.com/aryanswarnkar/QR-code-generator.git)
2. Navigate to the project directory: cd QR-code-generator
3. Install the required dependencies: npm install
4. Run the application using Node.js: node index.js

## Technologies Used
1. Node.js: JavaScript runtime environment.

2. Inquirer.js: For interactive command-line user prompts.

3. qr-image: To generate the PNG QR code from the provided string.

4. fs (File System): Native Node.js module used to save the user input to a text file.

## Author
1. Aryan Swarnkar

2. GitHub: @aryanswarnkar
