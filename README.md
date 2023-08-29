# Netflix Landing Page


### Header Section
![image](https://github.com/saifulislam05/css-assign/assets/73392705/13dd32ce-754f-4162-a15c-3523e79f3fd7)

The header section contains the logo and buttons for signing in and registering. The `display: flex;` property is used to align these elements horizontally. The logo image is resized using `width` and `height` properties. The buttons have a red background color, bold font, and rounded corners due to the use of `background`, `color`, and `border-radius` properties.

### Hero Section
![Screenshot 2023-08-29 063101](https://github.com/saifulislam05/css-assign/assets/73392705/9af68062-19af-4186-a0e3-4c584e6100bf)

The hero section displays a heading and two paragraphs centered vertically and horizontally using `display: flex;`. The text is styled with various font sizes for emphasis. The background image is set using `background` property in the `body` element's CSS. The background has a slight transparency with `rgba()` to give a darker overlay effect.

## Explanation of Tags and Properties
![image](https://github.com/saifulislam05/css-assign/assets/73392705/4e75bcb0-bf4f-4af1-b44f-96e76dec67ea)

### `<link>` Tag
The `<link>` Tag is use to connect external CSS file with HTML file using its attribute `href="style.css`.
### `<img>` Tag
The `<img>` tag is used to display the Netflix logo. The `src` attribute points to the logo image's URL. This tag is used within the `#logo` div to showcase the logo.

### `<button>` Tag
The `<button>` tag is used for the "Sign In" and "Register" buttons. They have a red background color, white text color, bold font, and rounded corners. This is achieved through the `background`, `color`, `font-weight`, and `border-radius` properties.

### `background` Property
The `background` property is applied to both the `body` and `#container` elements. It sets the background image of the page. In the `#container`, it adds a slight background overlay to improve readability of content.

### `display: flex;` Property
The `display: flex;` property is used in the `#nav` and `#hero` sections to create a flexible layout. It aligns elements horizontally (in the navigation) and both horizontally and vertically (in the hero section).

### Font Styling
Various text elements use different font sizes and weights to create visual hierarchy and emphasize important information. For example, the `<h1>` tag has a large font size to grab attention, while paragraphs have smaller sizes for better readability.

### CSS Selectors
Classes like `.btn`, IDs like `#nav`, and tag selectors like `h1` are used to target specific elements and apply styles. These selectors help organize and customize the appearance of different parts of the page.

### `margin` and `padding` Properties
The `margin` property is used to control the space outside elements, while the `padding` property is used to control the space inside elements. These properties are used throughout the CSS to create spacing between and within elements.
