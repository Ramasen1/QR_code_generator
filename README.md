# QR_code_generator
give Prompt to us and it will create a qr_image for your test

QR Code Generator
A Node.js project that prompts users for a URL and generates a QR code image for it. This project saves the QR code as an image and the entered URL as a text file locally.


Features :
Generate QR Codes from URLs entered by the user.
Save URL in a URL.txt file for record-keeping.
Output the QR code image as qr-image.png.


Prerequisites :
Make sure you have the following installed:

Node.js - Download and install it from here.
npm - Comes with Node.js; verify it by running npm -v in your terminal.


Installation :
1. Clone the repository to your local machine: https://github.com/Ramasen1/QR_code_generator/
2. Navigate to the project directory: cd <project-folder-name>
3. Install the required npm packages: npm install inquirer qr-image


Usages :
1. In the terminal, run the project with the following command: node index.js
2. You will be prompted to enter a URL. Type the URL you wish to convert into a QR code and press Enter.

3. The project will:
    Generate a QR code image as qr-image.png in the project directory.
    Save the entered URL in URL.txt in the project directory.
4. Open qr-image.png to view your generated QR code!



Example Output: 
After running the project, you should see the following files in your project directory:
qr-image.png - QR code image generated from your URL.
URL.txt - Text file containing the URL you entered.



Notes :
This project is designed to be run locally on Node.js.
Make sure you have internet connectivity to install required npm packages.



Troubleshooting :
If you encounter issues, make sure you have installed all dependencies correctly with npm install inquirer qr-image.
Verify Node.js and npm are installed by running node -v and npm -v



   
