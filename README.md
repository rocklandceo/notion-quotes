# Rockland Digital Daily Inspo

## Overview
Rockland Digital Daily Inspo is a web application designed to inspire users with daily quotes. It displays motivational quotes along with their authors, adjusting the display for both desktop and mobile viewers. The application randomly selects a quote from a predefined list each time the page is loaded or refreshed.

## Features
- **Responsive Design**: Utilizes Bootstrap classes for responsiveness, ensuring the application is accessible on devices of various sizes.
- **Dynamic Quote Generation**: Randomly selects a quote and its author from an array and displays it on the page.
- **Mobile and Desktop Compatibility**: Different layouts for mobile and desktop users to enhance readability.
- **Social Sharing**: Includes functionality (though not fully implemented in the provided code snippet) for sharing quotes on social media platforms like Twitter.

## How to Use
To use the Rockland Digital Daily Inspo, simply load the webpage in your browser. The application will automatically display a new inspirational quote each time the page is refreshed.

### HTML Structure
- The HTML is structured into two main sections for displaying quotes: one optimized for desktop (`quoteDesktop`) and the other for mobile devices (`quoteMobile`).
- Quotes and authors are displayed within `<h1>` and `<h3>` tags for desktops, and `<h3>` and `<h5>` tags for mobile devices, respectively.

### JavaScript Functionality
- The `quote()` function is the core of the application, responsible for randomly selecting a quote and its author from arrays and updating the HTML elements with these values.
- The `randomNumber()` function generates a random index to select a unique quote from the array, ensuring it is different from the last selected quote.
- The application initializes by calling the `quote()` function when the window loads, displaying a new quote and author.

### Styling
- The CSS styles define the appearance of the quote text and authors, setting the font style, weight, color, and sizes. It also sets a background color for the entire page.
- Media queries (via Bootstrap classes) are used to adjust the layout and font sizes for different screen sizes.

## Technologies Used
- HTML5
- CSS3
- JavaScript
- Bootstrap (for responsive design)

## Setup
1. Copy the provided HTML, CSS, and JavaScript code into respective files within your project directory (`index.html`, `styles.css`, `script.js`).
2. Ensure the Bootstrap framework is accessible, either by including a link to the Bootstrap CDN in your HTML or by installing Bootstrap in your project.
3. Open `index.html` in a web browser to view the application.

## Contribution
Contributions to the Rockland Digital Daily Inspo are welcome. Please fork the repository, make your changes, and submit a pull request for review.

## License
This project is open-source and available under the MIT License. See the LICENSE file for more details.