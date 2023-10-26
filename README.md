# Geoestimator - README
## General Information (Introduction: what is Geoestimator?)

Geoestimator: a game that involves determining the geographical location of a country given through a silhouetted/general shape of said country.

This a educationally-originated project created for the purpose of fulfilling an assignment's requirements at Del Norte High School for AP Computer Science Principles. Our [the developers'] coding skills and the project itself are still growing and are not polished/completed to their fullest potential.

## Main "Play" Functionality

### Code Structure

- The code for Geoestimator is divided into HTML and JavaScript sections
    - Here's a brief overview of each part:
        - HTML (<head> and <body>): The HTML structure defines the game's layout, including the title, input box, buttons, and result display.
        - CSS (<style>): The CSS styles define the appearance and layout of the game elements, making it visually appealing.
        - JavaScript (<script>): The JavaScript section contains the game's logic. It randomly selects a country, calculates the direction and distance of guesses, and provides feedback to players.

### Technical Details

- Random country slection: game randomly selects a country from a predefined list
    - Relates to visuals
        - Ex: flags, images, etc.
- Guess comparison: player guesses are compared to the selected country, and feedback is provided based on a distance and direction
- Direction calculation: the direction of guesses is calculated using an angle and mapped to cardinal directions (ex: north, east, etc.)
- Distance calculation: distance of guesses is calculated for feedback