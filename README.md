# Restaurant Menu Display

## Explanation of the Code

### HTML File (index.html):
- Defines the basic structure of the webpage.
- Includes meta tags for character set and viewport settings.
- Links to external CSS (style.css) and Font Awesome for icons.
- Contains a section for the menu display, including a title, filter buttons, and menu items.
- Uses placeholders ({}) to be dynamically filled with data from JavaScript.

### JavaScript File (app.js):
- Defines an array `menu` containing objects representing menu items.
- Uses `querySelector` to select the container elements for menu items and filter buttons.
- Defines functions to display menu items (`displayMenuItems`) and filter items (`displayMenuButtons`).
- Listens for the `DOMContentLoaded` event to populate the menu items and filter buttons when the page loads.
- Uses event delegation to handle click events on filter buttons and filter the menu items accordingly.

### CSS File (style.css):
- Defines variables for colors, fonts, spacing, and other common styles.
- Applies global styles to elements like body, h1, p, and a.
- Defines specific styles for the menu section, including layout, typography, and button styles.
- Uses media queries to adjust the layout for different screen sizes.

The code creates a responsive restaurant menu display with filter functionality using HTML, CSS, and JavaScript.

![menu4](https://github.com/Hafsajillani/menu/assets/103882246/ebbf93ce-dd01-4db5-a390-a73751b6d5ba)
