# Infinite Scroll

## Introduction
**Infinite Scroll** is a simple web application that fetches and displays posts dynamically as the user scrolls. The posts are retrieved from an external API, providing an endless scrolling experience similar to social media platforms.

## Features
- Infinite scrolling functionality
- Fetches posts from `https://jsonplaceholder.typicode.com/posts`
- Smooth loading animation
- Debounced scrolling to optimize performance
- Clean and responsive UI

## Installation
To run the project locally, follow these steps:

1. Clone the repository:
   git clone https://github.com/singhalaadi/infinite-scroll.git

2. Navigate to the project directory:
   cd infinite-scroll
   
3. Open index.html in your browser.

## Usage
1. Open index.html in any modern web browser.
2. Scroll down to load more posts dynamically.
3. Posts will be fetched in batches of 5 from the API.
4. The loader animation appears when new posts are being loaded.

## Project Structure
infinite-scroll/

│── index.html        # Main HTML file

│── style.css         # Stylesheet for the application

│── script.js         # JavaScript file handling data fetching & infinite scroll

│── README.md         # Project documentation

## Configuration
- The API request limits posts to 5 per request.
- A debounce function is implemented to optimize scroll events.
- The loader animation appears during API calls.

## Dependencies
- This project relies on:
- JavaScript Fetch API: To fetch posts from the API.
- CSS Animations: For the loading spinner effect.

## Contributors
Aaditya Singhal

## License
This project is licensed under the MIT License.

