# Simple URL Shortener

## Overview
This project is a simple URL shortener built using HTML and JavaScript. It allows users to input a URL, shorten it, and manage cookie storage for the URLs. It features expiration times for cookies and provides the ability to view and remove cookies associated with a specific URL.

## Features
- Input a valid URL to shorten it.
- Choose cookie expiration time (1 minute to 72 hours).
- Automatically redirects to the most recently shortened URL.
- Confirmation dialog before redirection.
- Option to remove associated cookies if the user declines redirection.
- List all cookies currently stored in the browser.
- Remove specific cookies based on the URL provided.

## Usage
1. Clone the repository or download the project files.
2. Open the `index.html` file in your web browser.
3. Enter the URL you want to shorten in the input box.
4. Select an expiration time from the dropdown menu (1 minute to 72 hours).
5. Click the **Shorten URL** button.
6. A shortened URL will be displayed, and you will be prompted for redirection.
7. You can also click the link to visit the shortened URL directly.

### Managing Cookies
- **View All Cookies**: The bottom section of the page displays all cookies stored in the browser.
- **Remove Cookies**: To remove cookies associated with a specific URL:
  - Enter the URL in the input box.
  - Click the **Remove Cookies** button to delete all cookies that contain this URL.

## Development
- You can modify the HTML and JavaScript code according to your needs for additional functionality or UI enhancements.
- This project uses plain JavaScript; no external libraries or frameworks are required.

## Limitations
- Cookies are limited to the same-origin policy and may have restrictions based on your browser settings.
- The cookie removal feature works only for cookies set on the same path as the application.

## License
This project is open source and available under the MIT License. Feel free to use, modify, and distribute as per the license terms.
