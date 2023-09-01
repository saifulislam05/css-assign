# Netflix Landing Page

### Hosted Link: https://saifulislam05.github.io/css-assign/
### Header Section
![image](https://github.com/saifulislam05/css-assign/assets/73392705/13dd32ce-754f-4162-a15c-3523e79f3fd7)

The header section contains the logo and buttons for signing in and registering. The `display: flex;` property is used to align these elements horizontally. The logo image is resized using `width` and `height` properties. The buttons have a red background color, bold font, and rounded corners due to the use of `background`, `color`, and `border-radius` properties.

### Hero Section
![Screenshot 2023-08-29 063101](https://github.com/saifulislam05/css-assign/assets/73392705/9af68062-19af-4186-a0e3-4c584e6100bf)

The hero section displays a heading and two paragraphs centered vertically and horizontally using `display: flex;`. The text is styled with various font sizes for emphasis. The background image is set using `background` property in the `body` element's CSS. The background has a slight transparency with `rgba()` to give a darker overlay effect.

## Explanation of some Tags and Properties
![image](https://github.com/saifulislam05/css-assign/assets/73392705/4e75bcb0-bf4f-4af1-b44f-96e76dec67ea)

### `<link>` Tag
The `<link>` Tag is use to connect external CSS file with HTML file using its attribute `href="style.css`.

## Explanation of CSS Styles and properties

### Global Styles
- `*`: Resets margin and padding for all elements to 0, ensuring consistent spacing.

### `body` Selector
- `height: 100vh;`: Sets the body height to cover the full viewport.
- `background`: Sets a background image for the body.

### `#container` Selector
- `height: inherit;`: Inherits height from the parent element `body`, covering the full viewport.
- `background: rgba(0, 0, 0, 0.7);`: Adds a semi-transparent overlay to the container.

### Header Section (`#nav`, `#logo`, `#buttons`)
- `#nav`:
  - `width: 90%;`: Sets the navigation width to 90%.
  - `margin: auto;`: Centers the navigation horizontally using auto margins.
  - `display: flex;`: Uses flex layout for child elements.
  - `padding: 20px 0;`: Adds 20px top and bottom padding.

- `#logo`:
  - `width: 40%;`: Sets the logo container width.

- `#logo img`:
  - `width`: Sets the logo image width.
  - `height`: Sets the logo image height.

- `#buttons`:
  - `width: 60%;`: Sets the buttons container width.
  - `text-align: right;`: Aligns text to the right.
  - `display: flex;`: Uses flex layout for child elements.
  - `justify-content: end;`: Aligns content to the end (right).
  - `align-items: center;`: Aligns items vertically to the center.

- `.btn`:
  - `background: red;`: Sets button background color.
  - `padding: 8px 14px;`: Adds padding to buttons.
  - `border: none;`: Removes button border.
  - `color: white;`: Sets text color.
  - `font-size: 15px;`: Sets font size.
  - `border-radius: 5px;`: Rounds button corners.
  - `font-weight: bold;`: Sets font weight.
  - `margin-left: 10px;`: Adds left margin.

### Hero Section (`#hero`, `h1`, `p`, `#p1`, `#p2`)
- `#hero`:
  - `display: flex;`: Uses flex layout.
  - `flex-direction: column;`: Stacks items vertically.
  - `justify-content: center;`: Centers content vertically.
  - `align-items: center;`: Centers items horizontally.
  - `color: white;`: Sets text color.
  - `height: 80%;`: Sets section height.

- `h1`:
  - `font-size: 55px;`: Sets font size.

- `p`:
  - `margin: 13px;`: Adds margin.
  - `font-weight: 400;`: Sets font weight.

- `#p1` and `#p2`:
  - `font-size`: Sets specific font sizes for paragraphs.
