Folder for CS 396 Web Development files:

Week 4 Lab---Implementing Two Interactive Elements

1: Hamburger Menu that disables itself when JS is not enabled.
2: Builder/Configurator Image Zoom

1: Expected behavior
The expected behavior for the Hamburger Menu is as follows:
- When JS is enabled, if the page is more than ~750 px wide, the website will display the 4 navigation links separately.
    - Should the page width become lower than ~750 px, the four navigation links will collapse into a single hamburger menu.
    - This hamburger menu icon is selectable via keyboard.
    - The hamburger menu, when activated, shows the four navigation links in a drop down.
- When JS is disabled, the hamburger menu will never activate, and the links will stack on top of each other
    - This is not ideal as it makes them harder to click individually, but the page is still operable.

2: Expected behavior
When the user hovers over the output of the configurator (or the current image placeholder), the image will zoom in.
- The image is constrained to its original size.
- The image will zoom out when the user no longer hovers over the image.
- While the user is hovering over the image, it will continually stay zoomed in.