# VS-Code-Installation
To create and preview a "Hello World" program using Visual Studio Code (VS Code), follow these steps:

### 1. **Install Visual Studio Code**
   - Download and install VS Code from the [official website](https://code.visualstudio.com/).

### 2. **Install Necessary Extensions (Optional but Recommended)**
   - Depending on the programming language you want to use, install the relevant extensions:
     - **Python:** Install the Python extension.
     - **JavaScript/Node.js:** Install the JavaScript (ES6) or Node.js extension.
     - **HTML/CSS:** Install the Live Server extension for live preview.

### 3. **Create a New Project**
   - Open VS Code.
   - Go to **File > Open Folder** and create/select a folder for your project.
   - Create a new file by clicking **File > New File** or using the shortcut `Ctrl + N`.
   - Save the file with an appropriate extension based on the language you are using (e.g., `hello.py` for Python, `hello.js` for JavaScript, or `index.html` for HTML).

### 4. **Write a Simple "Hello World" Program**
   - Depending on the language you chose, enter the following code:

     **Python: `hello.py`**
     ```python
     print("Hello, World!")
     ```

     **JavaScript: `hello.js`**
     ```javascript
     console.log("Hello, World!");
     ```

     **HTML: `index.html`**
     ```html
     <!DOCTYPE html>
     <html>
     <head>
         <title>Hello World</title>
     </head>
     <body>
         <h1>Hello, World!</h1>
     </body>
     </html>
     ```

### 5. **Run/Preview the Program**

   - **Python (hello.py):**
     1. Open the integrated terminal in VS Code by pressing ``Ctrl + ` `` or going to **View > Terminal**.
     2. Run the script by typing:
        ```bash
        python hello.py
        ```
     3. You should see the output `Hello, World!` in the terminal.

   - **JavaScript (hello.js):**
     1. Open the terminal.
     2. Run the script by typing:
        ```bash
        node hello.js
        ```
     3. You should see the output `Hello, World!` in the terminal.

   - **HTML (index.html):**
     1. If you installed the Live Server extension, right-click on the `index.html` file in the Explorer and select **Open with Live Server**.
     2. This will open your default web browser and display the HTML page with the text "Hello, World!".
     3. Alternatively, you can open the file directly in your browser by double-clicking it in your file explorer.

### 6. **Preview the Output (for HTML)**
   - The browser will show the rendered HTML, and you should see "Hello, World!" displayed on the page.

### 7. **Debugging and Enhancements**
   - VS Code offers powerful debugging tools. You can set breakpoints, inspect variables, and step through your code using the debug pane.
   - For more advanced features like linting, auto-completion, and code formatting, ensure you have the relevant extensions and settings configured.

This basic setup should help you quickly create and preview "Hello World" programs in VS Code for various programming languages.