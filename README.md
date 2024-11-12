# Clock

HTML Structure

Document Metadata:

The document is defined as HTML5.

Metadata includes the character set (UTF-8) and viewport settings for responsive design.

Title:

The title of the webpage is set to "Clock".

Stylesheet:

Links to an external CSS file, style.css, for styling the clock.

Body:

Clock Container: A div with the class clock acts as the container for the clock.

Clock Face: Inside the clock container, another div with the class clock-face represents the face of the clock.

Clock Hands: Three div elements with classes hand, hour-hand, min-hand, and second-hand represent the hour, minute, and second hands of the clock.

Script:

Links to an external JavaScript file, script.js, which will handle the functionality of the clock.

CSS Styling (style.css)
Background:

Sets a background image for the html element with background-size: cover.

Body:

Removes default margins and padding.

Clock Container:

Styles the clock with a white border, fixed dimensions, rounded corners, and centered alignment.

Clock Face:

Ensures the clock face fills the container and is positioned relative to the container.

Clock Hands:

Styles the hands of the clock with a fixed width and height, centered positioning, and black color.

Adds a transformation origin and transition for smooth movement of the hands.

hands of the clock.

JavaScript Functionality (script.js)

Select Clock Hands:

Uses document.querySelector to select the hour, minute, and second hands of the clock.

Set Date Function:

Purpose: Updates the positions of the clock hands to reflect the current time.

Implementation:

Gets the current time using new Date().

Calculates the degree of rotation for each hand based on the current seconds, minutes, and hours.

Sets the transform style of each hand to rotate it to the correct position.

Interval:

Uses setInterval to call the setDate function every second (1000 milliseconds) to update the clock.

Overall Functionality

This setup creates a functional analog clock with a stylish appearance and smoothly moving hands that update every second to show the current time.

The CSS ensures the clock looks visually appealing, and the JavaScript keeps it in sync with real-world time.
