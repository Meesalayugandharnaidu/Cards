#Profile-Cards 

This project creates a set of three interactive profile cards using HTML and CSS. The design is modern and visually engaging, featuring a dynamic, animated gradient background. Each card displays a person's profile picture, name, occupation, social media links, and a star rating. The cards also include "About Me" and "Hire Me" buttons that change color on hover. The use of Font Awesome icons and clever CSS styling makes the design both functional and aesthetically pleasing.

Key Features
HTML Structure (index.html): The HTML file organizes the content into a main container and three separate card divs. Each card contains a profile image, social media icons, a heading with a name and a profession, a star-based rating, and two call-to-action buttons.

Animated Background (body): The body element uses a linear gradient with an animation named anima to create a smooth, color-shifting background. The @keyframes rule for anima transitions the background position, giving it a subtle, continuous motion.

Card Styling (.card): Each card has a semi-transparent black background, a cyan border, and a shadow, giving it a sleek, modern look. A creative ::before pseudo-element adds a dynamic, partially transparent cyan circle to the top left of each card, which is an eye-catching design element.

Profile Image and Icons (.imgBox, .icons-f): The profile images are perfectly circular due to border-radius: 50% and have a cyan border and a subtle shadow. The social media icons are styled to have their own unique, brand-color backgrounds, and they are positioned vertically on the side of the card.

Interactive Buttons (.btns): The "About Me" and "Hire Me" buttons have a solid cyan background and black text. A transition effect is used to make the hover state feel smooth as the buttons change to a vibrant green.

Responsiveness: The layout uses a flexbox on the .container to arrange the cards, which helps them adapt to different screen sizes, though the design is primarily focused on a desktop view.
