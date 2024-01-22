# Typing Animation

![Screenshot_4](https://github.com/Cosaslearning/typing-animation/assets/100014446/eec1a3dc-728c-4a30-8825-983f6b53331f)

This HTML, CSS, and JavaScript code combination creates a captivating webpage titled "Jai Shri Ram" under the Cosas Learning project. The webpage features a visually appealing container with a dynamic image and a unique typing animation showcasing significant phrases related to "Jai Shri Ram" in the Devanagari script. Leveraging Google Fonts for an elegant typeface and incorporating the Typed.js library for the typing animation, this project aims to provide an engaging and aesthetically pleasing user experience.

**HTML File (index.html):**

The HTML structure comprises essential elements, including meta tags for character set and viewport settings. The CSS file is linked to the HTML document to handle styling, and the JavaScript files for the Typing Animation library are also imported. The container is divided into two sections: an image and a text area.

- The HTML file defines the structure of a webpage with the document type declaration, head, and body sections.
- It includes meta tags for character set, viewport settings, and the title of the webpage.
- The CSS file is imported into the HTML document using a `<link>` tag.
- The body contains a container (`<div class="container">`) with two main divisions: one for an image (`<div class="image">`) and another for text (`<div class="text">`).
- The image division has a background image that changes on hover, and the text division contains an h1 heading with a span element having the class "input."

**CSS File (style.css):**

CSS styling defines a cohesive visual identity for the webpage. The container is set to occupy the full viewport height, and the image section features a dynamic background transition on hover. Colors are defined using CSS variables, contributing to a harmonious color scheme. The styling enhances the overall aesthetics, making the content visually appealing.

- Google Fonts are imported to use the "PT Serif" font throughout the webpage.
- CSS variables are declared in the `:root` selector to define colors used in the styling.
- The general styling includes setting up the base styles for all elements, such as box-sizing, margin, padding, font-family, and text color.
- The container is styled to have a height of 100% viewport height, center its content, and have a background color of a specific orange shade.
- The image division is styled with a fixed width and height, a background image that transitions over 3 seconds on hover, and a border-radius for rounded corners.
- When hovered over, the image background changes to another image.

**JavaScript File (script.js):**

The JavaScript file utilizes the Typed.js library to create a captivating typing animation within the "text" division. The phrases related to "Jai Shri Ram" are presented in a loop, enhancing the overall thematic experience. The background image transition on hover is also facilitated by JavaScript, adding an interactive element to the user interface.

- The JavaScript file includes the Typed.js library from a CDN to create a typing animation effect.
- An instance of the Typed class is created, targeting the element with the class "input."
- The Typed instance is configured to display a series of strings with a specific typing and backspacing speed. The loop property is set to true, ensuring continuous looping of the animation.

In conclusion, the "Jai Shri Ram" webpage seamlessly blends HTML, CSS, and JavaScript to deliver an immersive user experience. The combination of visual elements, dynamic transitions, and the culturally significant typing animation contributes to a well-rounded project. Users can explore and appreciate the aesthetics while engaging with the spiritually enriched content related to "Jai Shri Ram." Feel free to customize and integrate this code into your projects to enhance user engagement further.
