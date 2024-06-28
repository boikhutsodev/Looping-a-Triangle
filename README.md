# Looping a Triangle in JavaScript

This project demonstrates how to create a simple JavaScript program that outputs a right-aligned triangle using a loop. The triangle will have seven rows, with each row containing an increasing number of hash (`#`) characters.

## Objective

Write a loop that makes seven calls to `console.log` to output the following triangle:

## Prerequisites

- Visual Studio Code (VS Code)
- Node.js

## Instructions

### 1. Install VS Code

If you haven't already, download and install Visual Studio Code from [here](https://code.visualstudio.com/).

### 2. Install Node.js

Ensure you have Node.js installed on your machine. You can download it from [here](https://nodejs.org/).

### 3. Create a New Project Folder

1. Open VS Code.
2. Create a new folder for your project. You can do this directly in the file explorer of your operating system.
3. Open this folder in VS Code by going to `File > Open Folder` and selecting your newly created folder.

### 4. Create a New JavaScript File

1. Inside your project folder, create a new file by going to `File > New File` or by right-clicking in the Explorer pane and selecting `New File`.
2. Name this file `triangle.js`.

### 5. Write the Code

1. Open `triangle.js` and write the following code:

   ```javascript
   for (let i = 1; i <= 7; i++) {
     let line = "#".repeat(i);
     console.log(line);
   }
   ```

### 6. Run the Code

1. Open a terminal in VS Code by going to `Terminal > New Terminal` or by pressing `` Ctrl+` ``.
2. Ensure you are in the directory where your `triangle.js` file is located. You can navigate to the correct directory using the `cd` command. For example:
   ```sh
   cd path/to/your/project/folder
   ```
