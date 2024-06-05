# responsive-website-uifry-

This is a modern, responsive website built using HTML and CSS.
[live website](https://responsive-website-uifry.vercel.app/)

## Table of Contents

- [Instructions to Run Locally](#instructions-to-run-locally)
- [Design Choices](#design-choices)
- [Libraries Used](#libraries-used)

## Instructions to Run Locally

To run this project on your local machine, follow these steps:

1. **Clone the repository**:

   ```sh
   git clone https://github.com/Ramanakunam16/responsive-website-uifry-.git
   ```

2. **Navigate to the project directory**:

   ```sh
   cd responsive-website-uifry-
   ```

3. **Open the index.html file in your browser**:
   - You can simply double-click on the `index.html` file located in the project directory, or
   - You can use a local server setup like [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in Visual Studio Code for live reloading.

## Design Choices

- **Typography System**:

  - Font sizes range from 10px to 98px for various headings and body text.
  - Default font weight is set to 400, with headings using a bolder weight of 700.
  - Line heights and letter spacing are used to ensure readability and aesthetic spacing.

- **Color Palette**:

  - Primary color: `#FF5555`
  - Tint: `#ff6666`
  - Grey shades: `#555`, `#000`
  - These colors were chosen to provide a vibrant yet professional look.

- **Layout**:

  - A grid system is used for layout, with predefined column configurations for responsive design.
  - Media queries ensure the design is responsive across various screen sizes, from desktop to mobile.

- **Components**:
  - Reusable CSS classes are created for buttons, headings, and other UI components to maintain consistency across the site.

## Libraries Used

- **Google Fonts**:
  - Font: [Rubik](https://fonts.google.com/specimen/Rubik)
  - Importing the font via a CDN for easy usage.
  - `@import url("https://fonts.googleapis.com/css2?family=Rubik:ital,wght@0,300..900;1,300..900&display=swap");`
