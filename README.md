# heart-trail-animation
i made a first web page animation using HTML, CSS, JAVASCRIPT .It is giving me  enthusisam of learning a web development.

Creating a heart trail animation using HTML5, CSS3, and vanilla JavaScript involves making a series of hearts follow the cursor as it moves around the screen. This effect is achieved by dynamically creating heart elements and animating them along the path of the cursor. Below is a step-by-step description and the code to implement this effect.

Description:
HTML Structure:

A basic HTML structure with a container where the hearts will appear. You can have an empty div as a container, or you can directly append hearts to the body.
CSS Styling:

Styling for the hearts, using CSS to shape them with the ::before and ::after pseudo-elements.
Each heart is made of two overlapping circles that form a heart shape when combined.
Additional CSS is used to animate the opacity and position of the hearts as they follow the cursor.
JavaScript Logic:

Use JavaScript to detect the cursor's position.
Create heart elements at the cursor's position each time the mouse moves.
Set a timeout to remove each heart after a short duration to create a fading trail events.
