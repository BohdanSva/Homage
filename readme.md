# The Homage Project

## This project intends to replicate the substantive elements of the website located at URL https://brightwoodlp.com/, but solely using CSS and HTML. 

---

## Project Documentation

Included in the project folder are:

- [x] Assets
    - Favicons
    - Images
- [x] Fonts
    - To the extent not replicated by Google Fonts, one local WOFF file is used to exactly replicate webpage icons.
- [x] Stylesheets
    - Best practice CSS to apply across the page [Styles.css]
    - Desktop-applicable CSS [styles_-_desktop.css]
    - The SCSS file used to pre-process the desktop CSS [styles_-_desktop.scss]
    - Mobile-applicable CSS [styles_-_mobile.css]
    - The SCSS file used to pre-process the mobile CSS [styles_-_mobile.scss]
- [x] HTML
    - Index.html
- [x] This project documentation Markdown file

---

## Viewport Breakpoints

The page is currently using two viewport breakpoints, and namely:
- Desktop view for a minimum width of 768 pixels; and
- Mobilie view for a screen width between 375 and 767 pixels. 

The breakpoints are implemented directly in the < head > section of the HTML using links to two distinct CSS files (styles-desktop.css and styles-mobile.css), in order to ensure consistent application of the code for each viewport width range.

The mobile version has been optimised for iPhone 12 Pro.

---

## Scope of Functionalities

### Features
- [x] Menu fixed to the viewport's top end with links to each section of the webpage. 
- [x] Mobile "hamburger" menu which slides onto the screen from the left upon clicking the "hamburger" SVG icon. 
- [x] Image carousel rendering a 15-second animation that complements a text box to its left that changes text description in the same 5-second interval for each paragraph/image. 
- [x] Three buttons indicating by white fill (dark blue fill in mobile view) which image/paragraph is currently displayed in the above sequence. 
- [x] Complex SVG icons drawn on a PNG logo canvas to explain the company's main verticals and business model. 
- [x] Image carousel with 4 images to provide additional backround on the company's experienced team. 
- [x] Image carousel with 3 images to show the company's office locations in the contact section. 

### Improvements to be implemented
- [_] Initial JavaScript animation when the logo on blue background fades away but SVG curve remains to act as a mask for an image carousel.
- [_] JavaScript to link each of the colour-changing button under the "Why Brightwood" section to one of the three images in the carousel.
- [_] Smoother scroll snap with a better animation.
- [_] Complex SVG graphics drawn using the < canvas > element to describe the company's five business verticals.
- [_] Form elements to replicate fully the people section.
- [_] Carousel of mp4 video files, changing the background video in the contact section every 5 seconds. It is currently unclear whether this functionality requires JavaScript or could be replicated CSS only. 
- [_] Resize the mobile menu so that it covers the whole height of the webpage (not just the viewport).
- [_] Translate on the X axis by 40% the whole body of the page, so that on clicking the hamburger the page moves to the left and its place on the right is filled with the mobile menu. Unclear whether CSS suffices. 
- [_] Use JavaScript to change the font colour for the sections in the desktop menu depending on which < section > of the website is currently displayed by the viewport. Unclear whether CSS suffices. 

---

## Code structure

### HTML
- The HTML code follows standard HTML structure. 
- Indentation and comments are used throughout to explain the code. 

### SCSS / CSS
- Both SCSS files (to pre-process CSS for both desktop and mobile screens) have ca. 600 lines of code each and follow the following structure: 
1. Colour format control
    - Global SASS variables are used to define RGB colours.
2. Text format control
    - Standardizes text formatting for titles and paragraphs.
3. Page-level grid control
    - Defines grid display for the < body > of the webpage.
4. Page-level grid items
    - Defines header, navigation, < main >, < sections > and footer grids, together will styles for all elements within.  
    - Styling of each element or function is preceded by a comment to label the code.












