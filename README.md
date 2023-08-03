# Page_transition_withGSAP_animation
GSAP Animation: A captivating web showcase by a FullStack developer. Smooth animations using GSAP library, elegant Poppins font, and a seamless slide-out effect. Visually engaging, leaving a lasting impression.

# GSAP Animation Project Documentation

## Introduction
The GSAP Animation project is a web development endeavor that aims to create a visually appealing and engaging landing page with smooth animations using the GreenSock Animation Platform (GSAP) library. The project showcases the skills of a FullStack developer and highlights the journey from scratch to advanced development. This documentation provides an overview of the project, its components, and the animation effects implemented.

## Project Structure
The project consists of the following files:

1. `index.html`: The main HTML file that serves as the landing page for the animation project.
2. `style.css`: The CSS file containing the styles and layout for the project.
3. `dp.jpg`: An image used in the project to represent the hero section.
4. `app.js`: The JavaScript file that leverages GSAP to create animation effects.
5. External Libraries:
   - GSAP v3.12.2: A JavaScript animation library used for creating smooth animations.

## HTML Structure
The `index.html` file is structured as follows:

1. The `<!DOCTYPE html>` declaration specifies the document type and language.
2. The `<head>` section contains meta tags for character encoding, viewport settings, and the project title. It also includes a link to the external `style.css` file for styling.
3. The `<body>` section holds the main content of the landing page, organized into various sections.
4. The navigation bar (`<div class="nav">`) consists of a left and right section, displaying the project name and a user profile name, respectively.
5. The introduction section (`<div class="intro">`) contains a hero section (`<div class="hero">`) with a left and right division. The left division includes a header with a title, showcasing the skills of a FullStack developer, while the right division displays an image (`dp.jpg`) representing the developer.

## Styling (style.css)
The `style.css` file is responsible for the layout, design, and overall appearance of the landing page. Key styling points include:

1. The `Poppins` font from Google Fonts is imported to provide a modern and elegant typography style.
2. The global CSS reset sets default margin, padding, and box-sizing properties to maintain consistency.
3. The background color is set to black (`#000`), and the text color is set to white (`#fff`) for a high contrast look.
4. The `.wrapper` class defines the main container, spanning the full width and height of the viewport.
5. The `.nav` class formats the navigation bar with flexbox for responsiveness and space distribution.
6. The hero section's `.left-hero` and `.right-hero` divisions control the layout of the left and right content, respectively.
7. The `.slider` class creates a full-screen overlay with a semi-transparent background used for animation effects.

## Animation (app.js)
The `app.js` file utilizes the GSAP library to create impressive animation effects for the landing page. The `gsap.timeline` function is used to orchestrate the animations with default easing set to `power2.out`. The key animations implemented are as follows:

1. Slide-out Animation: The `.slider` div slides out from the bottom, revealing the content underneath. This animation duration is set to 1.2 seconds.
2. Hero Section Animation: The `.intro .hero` section slides up from the bottom, transitioning into view with a duration of 1.2 seconds.
3. Navigation Bar Fade-in: The `.nav` navigation bar fades in gradually with a duration of 0.1 seconds.

## Conclusion
The GSAP Animation project demonstrates the skills of a FullStack developer and presents an engaging landing page with eye-catching animations. By leveraging GSAP's powerful animation capabilities, the project achieves smooth and visually appealing effects. The use of the Poppins font, dark background, and careful layout enhances the overall aesthetic of the page. This documentation provides an overview of the project's structure, styling, and animation effects, showcasing the capabilities of the developer and the possibilities of GSAP in web development.
