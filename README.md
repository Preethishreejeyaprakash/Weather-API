## Weather-API
# HTML Structure

Features
Search Box: Allows users to enter a location.
Weather Display: Shows current temperature, weather description, humidity, and wind speed.
Error Handling: Displays an error message if the location is not found.
Icons: Utilizes Font Awesome for weather icons and search button icon.

Files
index.html: The main HTML file containing the structure of the app.
style.css: The CSS file for styling the app.
script.js: The JavaScript file that handles fetching and displaying weather data.
404.png: Image displayed when the location is not found.
cloud.png: Default weather image displayed.

How to Use
Clone the repository.
Open index.html in a web browser.
Enter a location in the search box and press the search button.
The app will display the weather information for the entered location

# Css Structure

Styling Details
General
Global Reset: Sets margins, padding, and box-sizing for all elements to ensure consistent styling. Removes borders and outlines, and sets the default font to sans-serif.
Body
Background and Centering: The body is styled to cover the entire viewport height, with flexbox centering for the content. A background image is applied
Container
Main Container: The main container for the app, with a semi-transparent white background, rounded corners, and padding.
Search Box
Layout and Styling: The search box is styled to contain an input field and a search button, with a flexbox layout for alignment.
Weather Body
Weather Display: Initially hidden, this section shows the weather image, temperature, description, humidity, and wind speed once data is available.Weather Box
Temperature and Description: Center-aligned text showing the temperature and weather description with specified font sizes and weights.

# Javascript Structure

API Key: Ensure the API key is valid and replace it if necessary.
Image Paths: Ensure the paths for the weather images (cloud.png, clear.png, rain.png, mist.png, snow.png) are correct.
Run the App: Open the HTML file in a web browser, enter a location in the input field, and click the search button to see the weather information.
