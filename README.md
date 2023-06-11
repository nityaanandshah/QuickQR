# QuickQR

This project is a simple QR code generator built using Node.js. It utilizes the `inquirer`, `qr-image`, and `fs` npm packages to interact with the user, generate a QR code image from a user-entered URL, and save the URL in a text file.

## Description

The QR Code Generator is a Node.js application that allows users to generate QR codes for URLs. It provides a command-line interface (CLI) for a seamless user experience. The project uses the following npm packages:

- `inquirer`: A command-line user interface (CLI) utility that prompts the user for input and handles the response.
- `qr-image`: A package for generating QR code images from text or URLs.
- `fs`: The built-in Node.js module for interacting with the file system.

## Installation

1. Clone the repository or download the source code.
2. Navigate to the project directory.
3. Install the dependencies by running the following command:
    npm install

## Usage

1. Open a command-line interface (CLI) and navigate to the project directory.
2. Start the application by running the following command:
    node index.js    
3. Follow the prompts to enter the URL for which you want to generate a QR code.
4. Once you enter the URL, the application will generate a QR code image and save it as `qr_img.png`.
5. The entered URL will also be saved in a text file named `msg.txt`.
6. The application will display a success message once the files have been generated and saved.

## Contributing

Contributions are welcome! If you find any issues or want to add new features, please open an issue or submit a pull request on the GitHub repository.
