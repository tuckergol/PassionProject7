# Geoestimator FRONTEND - README.md

## General Information (Introduction: what is Geoestimator?)

Geoestimator: a game that involves determining the geographical location of a country given through a silhouetted/general shape of said country.

This a educationally-originated project created for the purpose of fulfilling an assignment's requirements at Del Norte High School for AP Computer Science Principles. Our [the developers'] coding skills and the project itself are still growing and are not polished/completed to their fullest potential.

## Geoestimator - Code Documentation

NOTE: indexPlay.html (flags) and indexPlay2.html (country silhouettes) are nearly identical apart from image links.

- This README.md provides a comprehensive guide to understanding the structure and functionality of the HTML code for Geoestimator. It will help you navigate the code and grasp the intricacies of how different components work together.
- The HTML code in this repository comprises the frontend of Geoestimator. This document will guide you through the structure of the code and provide insights into its functionality.

### Structure: Applies to HTML Files
- index.html: The HTML file containing the main home page's information, which users will be greeted with.
    - Contains basic HTML, involving image links and code structures.
        - "<!DOCTYPE html>": This declaration specifies the document type and version of HTML being used.
            - HTML5 in this case.
        - "<html>": This tag marks the beginning of the HTML document. All other HTML elements are contained within it.- - "<head>": This section contains metadata about the HTML document, including the title, which is displayed in the browser's title bar or tab. In this case, the title is "Home."
        - "<title>": This tag sets the title of the HTML document, which is displayed in the browser's title bar or tab.
        - "<body>": This section contains the main content of the HTML document that is visible in the web browse
        - "<div>:" This tag is a container or division element that is often used to group and style other HTML elements. It doesn't have any specific visual impact on its own.
        - "<img>": This tag is used to embed an image in the HTML document. It has several attributes.
            - "images/": This directory houses flag images for various countries.
            - "README.md": The documentation you are currently reading.

## Key Components

### ADDITIONAL HTML Structure

- The HTML structure outlines the layout and content of Geoestimator.
    - <head> section: Contains the title and links to external stylesheets (none in this case).
    - <body> section: Defines the main content of Geoestimator, including:
    - A header with the title and a timer.
    - A container for displaying the flag image.
    - Input box for user guesses.
        - "Enter your guess"
    - "Check" and "New [Flag/Country]" buttons.
    - A section for displaying result messages.

### CSS Styles

- The CSS styles are embedded within the HTML file and define the visual appearance of Geoestimator.
    - Styling for the entire page, such as background color, font, and layout.
    - Styling for the flag image container, input box, buttons, and result messages.

### JavaScript Functions

- The JavaScript section of the code contains functions that manage Geoestimator's behavior. Primary functions listed below.
    - "startRound()": Selects a random country, displays its flag, and resets various game-related variables.
    - "checkGuess()": Compares the user's guess to the selected country and provides feedback on correctness.
    - "resetTimer()": Initiates the timer when a new round begins.
    - "stopTimer()": Halts the timer when the user guesses the correct country.
    - "updateTimer()": Updates the timer's display with the elapsed time.
    - "pad()": A helper function for formatting time components with leading zeros.

## Prerequisites

- Before working with this code, it is recommended to have a solid foundation in the following criteria listed below.
    - HTML, including document structure and tags.
    - JavaScript, as the code employs client-side scripting.
    - Possibly some familiarity with web development concepts and tools can be beneficial.

## Usage

- To use the code effectively, open the index.html file in a web browser or other application, such as VSCODE.

### Advanced Customization

- Geoestimator can be customized and extended in various ways through editing code in the HTML files. Possible (specific) ways of doing so are listed below.
    - Adding more countries and corresponding flag images to countryFlagImages in the JavaScript section.
    - Enhancing the user interface with additional CSS styles.
    - Implementing new game mechanics or features in the JavaScript functions.

### Additional Info

This is a school project made by four amateur computer science students. Therefore, the project should not expect to be extensively complicated.

As for licensing...anyone is free to adapt the project and its contents to their liking.