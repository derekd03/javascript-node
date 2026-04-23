Microsoft Dev Container Template Example
========================================

This example tutorializes how to set up and run Microsoft's standard Node.js & JavaScript Dev Container Template
(mcr.microsoft.com/devcontainers/javascript-node) on your own machine.

# Prerequisites

Installed
---------

WSL
Docker
Visual Studio Code

# Steps

1. Access Visual Studio Code's Command Palette (Ctrl+Shift+P) or the top search bar and enter ">"
2. Enter "Dev Containers: New Dev Containers..."
3. Enter "Node.js & Javascript", you'll find a matching template by devcontainers (verified) from GitHub
4. Uncomment "forwardPorts": [], add 3000 or your desired port(s) within the square brackets
5. Enter "Dev Containers: Rebuild" into the Command Palette
6. Add app.js to the root of the project with just a simple console.log("Hello, World!") statement
7. Access "Run and Debug" through the icon on the left-hand sidebar and click "Run and Debug",
   OR enter "node app.js" in the project's bash terminal through View > Terminal in the top bar to test the application
