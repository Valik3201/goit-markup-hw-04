# Web Studio - HTML, CSS, and Icon Styling

Welcome to the continued development of the Web Studio project! In this part of the project, the focus will be on enhancing the graphic design and layout of the web pages. The key additions to the project will include the integration of HTML tags and the styling of icons, along with decorative effects. The details of what this portion of the project contains are as follows:

## Project Contents

### HTML Markup

- All HTML pages have been updated to include icons using vector graphics in SVG format.
- All vector icons are collected in an SVG sprite named `icons.svg`, which is located in the `images` folder.
- The SVG sprite `icons.svg` contains all the optimized vector icons used in the project.

### Icon Styling

- Icons in the SVG sprite are correctly exported, selecting the "group" rather than the individual vector during the export process.
- Icons from the SVG sprite are added to the HTML using the `<svg>` and `<use>` tags.
- Icons have been strategically added to various sections of the website:
  - In the "Our assets" section.
  - In the "Our Team" section for social media links.
  - In the "Customers" section for company icons.
  - In the footer for social media icons.

## Styling Guidelines

### Background and Effects

- A large background image with a darkening effect is applied below the header. The darkening effect is achieved using a multi-layered gradient background.
- The background image below the header does not stretch wider than its original size of 1440px.
- Cards in the "Our Team" section have a persistent shadow effect.
- Cards on the Portfolio page have a shadow effect upon hovering over any part of the card.
- The filter (button list) on the Portfolio page has a shadow effect upon hovering over or focusing on the buttons.

### Icon Styling

- Icons should become active (e.g., change color) when hovered over or focused on if indicated in the layout.

## SVG Sprites and Optimization

- Vector icons are optimized and stored in the SVG sprite `icons.svg` to ensure efficient use and fast loading times.
- The `icons.svg` sprite is generated using the Icomoon service.
- The generated `icons.svg` sprite is further optimized using the svgomg service for minimal file size and optimal performance.

## Conclusion

This part of the Web Studio project focuses on enhancing the graphic design and layout of the web pages by incorporating vector icons and applying various visual effects and styles.
