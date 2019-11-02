# password_generator

Random password generator created with HTML, CSS, and JavaScript.

The purpose of this generator is so that someone with access to sensitive data can randomly generate a password that meets certain critera so a strong password is created. This provides greater security for the sensitive data. 

The generator utilizes 4 variables that contain strings of uppercase letters, lowercase letters, symbols, and numbers. When a user pushes the "generate" button on the web page, a function runs that prompts the user to specify the number of characters they would ike in their password. 

The user is then prompted to confirm if they would like symbols, uppercase letters, lowercase letters, symbols, and numbers in their password or not. Based on this user input, a new string is generated containing all specified characters. This string is then randomized by running through a for loop that utilizes the length specified by the user in the inital prompt, Math.floor function, and Math.random function.

The resulting random string is the final password. This password is then printed to the text area on the index page and can be copied to the clipboard by pushing the "copy to clipboard" button. This was achieved by assigning functions to be run when the buttons are clicked. 

