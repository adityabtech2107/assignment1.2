Here is a complete, step-by-step guide to setting up your web development environment and completing Assignment 1.2.

Step 1: Install Visual Studio Code
Go to the official website: code.visualstudio.com

Download the installer for your operating system (Windows, macOS, or Linux).

Run the installer and follow the on-screen instructions. Make sure to check options like "Add to PATH" so you can easily open it from the terminal.

Step 2: Install Node.js (LTS Version)
Go to the official website: nodejs.org

Download the LTS (Long Term Support) version, as it is the most stable and recommended for development.

Run the installer and complete the setup wizard (keep the default settings).

Step 3: Install VS Code Extensions
Open Visual Studio Code.

Click on the Extensions icon on the left sidebar (or press Ctrl+Shift+X on Windows/Linux or Cmd+Shift+X on Mac).

Search for and install:

Live Server (by Ritwick Dey) — allows you to run a local development server with live reload.

Prettier - Code formatter (by Prettier) — automatically formats your code for clean styling.

Step 4: Create the Project Folder
Open your computer's file explorer and create a new folder named:web-development-practice

Open VS Code, click on File > Open Folder..., and select the web-development-practice folder you just created.

Step 5: Create the Required Files
Inside your web-development-practice folder in VS Code, create three files:

index.html

style.css

script.js

You can add some basic starter code to test them out:

index.html


HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Development Practice</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Hello, World! My environment is set up successfully.</h1>
    <script src="script.js"></script>
</body>
</html>

style.css


CSS

body {
    font-family: Arial, sans-serif;
    text-align: center;
    margin-top: 50px;
    background-color: #f4f4f9;
    color: #333;
}

script.js


JavaScript

console.log("JavaScript is working correctly!");


Step 6: Run the HTML File Using Live Server
Open index.html in VS Code.

Look at the bottom-right corner of the VS Code window and click the "Go Live" button.

Your default web browser will automatically open and display your web page running locally.

Step 7: Verify Node.js and npm Installation
In VS Code, open the integrated terminal by pressing Ctrl + ` (Windows/Linux) or Cmd + ` (Mac), or go to Terminal > New Terminal.

Run the following commands to check the versions:


Bash

node -v
npm -v

You should see version numbers appear in the terminal (e.g., v20.x.x for Node and 10.x.x for npm).