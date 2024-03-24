# QR-Code_Generator
This project is a simple command-line tool that allows users to generate QR codes from URLs entered via user input. It utilizes the inquirer npm package for getting user input, the qr-image npm package to convert user-entered URLs into QR code images, and the native fs node module to save the user input and generated QR code image to files.

Features:

User Input: Utilizes the inquirer npm package to prompt users to enter a URL.

QR Code Generation: Converts the user-entered URL into a QR code image using the qr-image npm package.

File Saving: Saves the user-entered URL and the generated QR code image to files using the native fs node module. The URL is saved in a .txt file, and the QR code image is saved as a .png file.

Technologies Used:

Node.js
inquirer npm package
qr-image npm package
fs native node module
Contributing:

Contributions to this project are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.
