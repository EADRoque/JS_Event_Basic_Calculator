# # Setting Up the Basic Calculator Project

This document outlines the steps to set up the basic calculator project from a GitHub repository on your local machine using VS Code.

## Prerequisites

* **Git:** You need Git installed on your machine. If you don't have it, download and install it from [git-scm.com](https://git-scm.com/downloads).
* **VS Code:** You need Visual Studio Code installed. If you don't have it, download and install it from [code.visualstudio.com](https://code.visualstudio.com/).
* **GitHub Account (Optional):** While not strictly required for cloning, having a GitHub account makes it easier to fork and contribute back to the repository.

## Step 1: Cloning the Repository

1.  **Navigate to the GitHub Repository:**
    * Go to the GitHub repository containing the HTML, CSS, and JavaScript files for the calculator. (For this example, let's assume the repo URL is `https://github.com/yourusername/basic-calculator.git`. Replace `yourusername` with the actual username.)
2.  **Copy the Repository URL:**
    * Click the green "Code" button and copy the HTTPS URL of the repository.
3.  **Open a Terminal or Command Prompt:**
    * Open your terminal or command prompt on your local machine.
4.  **Navigate to the Directory:**
    * Navigate to the directory where you want to clone the repository. For example:
        ```bash
        cd Documents/Projects
        ```
5.  **Clone the Repository:**
    * Use the `git clone` command followed by the repository URL:
        ```bash
        git clone [https://github.com/yourusername/basic-calculator.git](https://github.com/yourusername/basic-calculator.git)
        ```
    * This will create a new directory named `basic-calculator` in your current directory and download the repository files into it.
6.  **Navigate into the Cloned Directory:**
    * Change your current directory to the newly cloned `basic-calculator` directory:
        ```bash
        cd basic-calculator
        ```

## Step 2: Opening the Project in VS Code

1.  **Open VS Code:**
    * Launch Visual Studio Code.
2.  **Open the Project Folder:**
    * Go to `File` > `Open Folder...`
    * Navigate to the `basic-calculator` directory you cloned in the previous step and click "Select Folder".
    * Alternatively, you can open a terminal and navigate to the project directory, then type `code .` to open VS code in that directory.
3.  **Explore the Project Files:**
    * In the VS Code Explorer (the sidebar on the left), you will see the project files: `index.html`, `style.css`, and `script.js`.
4.  **Open the Files:**
    * Click on each file to open it in the editor.

## Step 3: Running the Calculator

1.  **Open `index.html` in a Browser:**
    * Right-click on the `index.html` file in the VS Code Explorer.
    * Select "Open with Live Server" (if you have the Live Server extension installed) or "Reveal in File Explorer" (or "Reveal in Finder" on macOS) and then double-click the `index.html` file to open it in your default browser.
    * If you do not have the live server extension, you will have to manually refresh the browser each time you make a change.
2.  **Interact with the Calculator:**
    * The calculator should now be running in your browser. You can use the buttons to perform calculations.
3.  **Make Changes and Test:**
    * You can now make changes to the HTML, CSS, or JavaScript files in VS Code and see the changes reflected in your browser (if using Live Server, the changes will happen automatically).

## Optional: Installing Live Server (VS Code Extension)

The Live Server extension for VS Code allows you to automatically refresh your browser when you make changes to your files.

1.  **Open the Extensions View:**
    * Click the Extensions icon in the VS Code Activity Bar (the sidebar on the left).
2.  **Search for "Live Server":**
    * Type "Live Server" in the search bar.
3.  **Install the Extension:**
    * Click the "Install" button next to the "Live Server" extension by Ritwick Dey.
4.  **Use Live Server:**
    * As described in Step 3, right click the HTML file and select "Open with Live Server".

Enjoy working with your basic calculator project!