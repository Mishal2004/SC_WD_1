Interactive Navigation Menu

This project demonstrates how to create an interactive navigation menu using HTML, CSS, and JavaScript. The menu has a fixed position, changes color when the page is scrolled, and includes hover effects for each menu item.

Features

Fixed Position: The navigation menu stays at the top of the page as you scroll.
Scroll Effect: The background color of the navigation menu changes when the page is scrolled.
Hover Effect: Menu items change color and background when hovered over.
Files

index.html: The main HTML file containing the structure of the webpage.
styles.css: The CSS file that styles the navigation menu and the webpage.
script.js: The JavaScript file that adds the scroll effect to the navigation menu.
Installation

To run this project locally:

Clone or download this repository to your local machine.
bash
Copy code
git clone <repository_url>
Navigate to the project folder.
bash
Copy code
cd InteractiveMenu
Open the index.html file in a web browser.
You can do this by double-clicking the index.html file, or by right-clicking it and selecting "Open with" followed by your preferred web browser.
Usage

Open the index.html file in your browser to view the interactive navigation menu.
Scroll down the page to see the menu's background color change.
Hover over the navigation links to see the hover effects.
Customization

Change Colors
Modify the colors in styles.css to customize the appearance of the navigation menu and the hover effects.
Add More Links
To add more items to the navigation menu, add additional <li> elements inside the <ul> in the index.html file.
Adjust Scroll Threshold
The scroll effect threshold (50 pixels) can be adjusted in script.js by changing the value in the if condition:
javascript
Copy code
if (window.pageYOffset > 50) {
License

This project is open-source and free to use. You can modify and distribute it as per your needs.
