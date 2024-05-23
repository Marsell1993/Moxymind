Overview
This project includes automated tests written in Cypress. The following instructions will guide you on how to set up and run these tests locally using Visual Studio Code (VSC).

Prerequisites
Before you can run the tests, ensure you have the following installed on your local machine:

Node.js: Download and install Node.js v20.11.1. (which includes npm).
Visual Studio Code (VSC): Download and install VSC 1.89.1 .
Git: Download and install Git Git-2.45.1-64-bit
Setup
Follow these steps to set up the project on your local machine:

Clone the Repository:

Open a terminal and run the following command to clone the repository:

bash
Kopírovať kód
--git clone https://github.com/Marsell1993/MoxymindRepo.git
Navigate into the project directory:

bash:

--cd your-repository
Install Dependencies:

Run the following command to install the project dependencies:

bash:

--npm install
Running Tests
You can run the Cypress tests in two ways: via the Cypress Test Runner (GUI) or in headless mode. Here are the instructions for both methods:

Running Tests via Cypress Test Runner (GUI):

Open Cypress Test Runner using the following command:

bash:

--npx cypress open
This will open the Cypress Test Runner window. From here, you can select and run the tests.

Running Tests in Headless Mode:

To run the tests in headless mode (without the GUI), use the following command:

bash:

--npx cypress run
Running Tests in Visual Studio Code (VSC)
To run tests directly within VSC, you can use the integrated terminal:

Open the Integrated Terminal:

Open VSC and navigate to your project. Open the integrated terminal by pressing Ctrl + ` or by selecting View > Terminal from the menu.

Run the Tests:

Use the commands mentioned above (npx cypress open or npx cypress run) directly in the integrated terminal to run your tests.
