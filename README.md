# project2
Responsive image slider
Overview

This project is a responsive image slider built using HTML, CSS, and JavaScript. The slider features smooth transitions, navigation buttons, and an auto-slide functionality to enhance user experience.

Features

Responsive Design: Adapts to different screen sizes.

Smooth Transitions: Uses CSS transitions for a fluid sliding effect.

Navigation Buttons: Allows users to manually navigate through images.

Auto Slide: Automatically moves to the next image every 3 seconds.

Hover Effects: Button background changes on hover.

Technologies Used

HTML: Structure of the webpage.

CSS: Styling and responsive design.

JavaScript: Functionality for navigation and auto-sliding.

Installation & Usage

Download or Clone the Repository

git clone https://github.com/your-username/responsive-image-slider.git

Navigate to the Project Folder

cd responsive-image-slider

Open the index.html File in a Browser
Simply double-click the file or open it with a browser.

File Structure

responsive-image-slider/
│-- index.html
│-- styles.css (if extracted separately)
│-- script.js (if extracted separately)
│-- images/
    │-- Machu Picchu.jpg
    │-- Mountains.jpg
    │-- Beach.webp
    │-- Forest.jfif
    │-- Desert.webp

How It Works

The JavaScript controls the slider functionality by updating the transform property of the .slides container.

The Next (›) and Previous (‹) buttons allow manual navigation.

The setInterval() function automatically moves the slider every 3 seconds.

The CSS media queries ensure buttons resize properly on smaller screens.

Customization

Replace the images inside the <div class="slides"> container with your own images.

Adjust the transition speed in the CSS (transition: transform 0.5s ease-in-out;).

Modify the auto-slide duration in JavaScript (setInterval() in milliseconds).

License

This project is open-source and free to use under the MIT License.

Author

[sonu panchal] - [Your GitHub Profile]

