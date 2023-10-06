# Cecilia and Hannah NASA Image Lookup
## An API-Backed React Web App
By: Cecilia Zaragoza and Hannah Holden

Welcome to NASA Image Lookup! Created using React, a JavaScript library, this webapp offers responsive sizing, utilizes flex and grid for design, and contains smooth transitions that allows users to find images of space from NASA.

### Features of Our Web App:
* Find our deployed app at: 
* We use the NASA Image and Video Library API (https://images.nasa.gov/docs/images.nasa.gov_api_docs.pdf) to display images from NASA based on user input in a grid-like fashion. 
* We call the search endpoint from the NASA Image and Video Library API with the query parameter, which is user-given, and the media_type parameter, where we specify that we want only images to display.
* If the user inputs information that does not return any images, we return a message that lets the user know there are no images for their request.
* We styled the images into cards and used grid for the overall layout as well as flex for each card so that the user can easily see the images that they request.
* The cards also transform to a larger size when you hover on them and have a transition for smooth movement.
* The site features responsive sizing that makes the two-column grid of NASA images becomes one column at 768px or smaller.
* We have a background image that displays in the hero, along with a gradient combined with an invert that goes across the hero and creates a cool effect.
* We imported two fonts, Space Mono and Pixelify Sans, from Google Fonts.
