# Code Explanation

This project is a simple web application that displays a random quote when a button is clicked.

## Files

- `index.html`: The main HTML file that defines the structure of the web page.
- `style.css`: The CSS file that styles the web page.
- `game.js`: The JavaScript file that contains the logic for displaying random quotes.

## HTML Structure (`index.html`)

The HTML file consists of a container with a button and a paragraph element. The button is used to trigger the display of a new quote, and the paragraph element is where the quote is displayed. The file also includes a footer with social media links.

## CSS Styling (`style.css`)

The CSS file styles the elements of the web page. It sets a gradient background, centers the content, and defines the styles for the button, quote display, and footer. The most important styles are:

- `body, html`: Sets the basic styles for the page, including the background gradient and font color.
- `#quote-btn`: Styles the button with a background color, rounded corners, and a box shadow.
- `#quote-display`: Styles the text of the quote, including font size and style.
- `.social-icons a`: Styles the social media icons in the footer.

## JavaScript Logic (`game.js`)

The JavaScript file contains an array of quotes and an event listener for the button. When the button is clicked, a random quote is selected from the array and displayed in the `quote-display` paragraph element. The `hidden` class is removed from the paragraph to make it visible.