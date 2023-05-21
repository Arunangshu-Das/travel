# Responsive Navbar and Video Player

This code implements a responsive navbar and video player using HTML, CSS, and JavaScript. The navbar can be toggled by clicking a menu button, and it automatically collapses when scrolling. The video player allows the user to switch between different videos by clicking on control buttons.

## Navbar

The navbar functionality is implemented using JavaScript. The menu button with the ID `menu-btn` is assigned a click event listener. When the button is clicked, it toggles the `active` class on the `navbar` element. This class controls the visibility of the navbar when activated.

Additionally, the `window.onscroll` event listener is used to remove the `active` class from the `navbar` when the user scrolls the page. This ensures that the navbar collapses when the user interacts with the content.

## Video Player

The video player functionality is implemented using JavaScript. The control buttons within the `.about .video-container .controls` element are selected using `document.querySelectorAll()`. For each button, a click event listener is added.

When a control button is clicked, it retrieves the `data-src` attribute value, which represents the video source URL. The source of the video element within `.about .video-container` is then updated with the new URL. This allows the user to switch between different videos by clicking on the control buttons.

## HTML and CSS

The HTML structure and CSS styling are responsible for the layout and appearance of the navbar and video player. The navbar is typically located within the `.header` element and contains the menu button and navigation links. The video player is located within the `.about .video-container` element and consists of a video element and control buttons.

## Note

You can customize the HTML structure, CSS styles, and JavaScript code to fit your specific requirements. Feel free to modify the design, add additional functionality, or integrate it into your existing project.

---

Enjoy using the responsive navbar and video player!
