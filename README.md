# Daman Mavi - Personal Portfolio

INFR3120 Assignment 1: a four-page portfolio site built with HTML5 and CSS3.

- Live site: https://ogballah.github.io/portfolio/
- Repository: https://github.com/ogballah/portfolio

## Pages

- `index.html`: Home page with navigation
- `about.html`: Photo, introduction and embedded video
- `projects.html`: Five projects from previous semesters
- `contact.html`: Contact form with HTML5 validation

## Viewport sizes

The site uses fluid design (percentage widths) and media queries, with a separate CSS file for each screen size. Flexbox is not used.

- `full.css`: 961px and wider, for laptops and desktops. The page is 90% wide (max 1100px) and shows three project boxes per row.
- `tablet.css`: 481px to 960px, for tablets and small laptops. The page is 94% wide and shows two project boxes per row.
- `phone.css`: 480px and narrower, for most phones. Everything stacks in one column and the nav buttons form two per row.

The ranges do not overlap, so only one stylesheet loads at a time. I chose each size at the point where the layout stops fitting comfortably.

## Gradients

- Header (all four pages): `linear-gradient(to right, #0A2A66, #1565C0)`, a left-to-right gradient from navy to blue.
- Footer (all four pages): `linear-gradient(135deg, #1565C0, #0A2A66)`, an angled gradient from blue to navy.

## Colour scheme

Palette from Adobe Color: PASTE YOUR ADOBE COLOR LINK HERE

- Navy `#0A2A66`: header background and gradients, footer gradient
- Blue `#1565C0`: footer background, header and footer gradients
- Light blue `#4FA3FF`: headings, links and accents
- Dark grey `#222222`: project boxes
- Black `#000000` and white `#FFFFFF`: page background, nav buttons and text

## Testing

- HTML: checked with the W3C Markup Validator
- CSS: checked with the W3C CSS Validator
- Links: checked with the W3C Link Checker
- Accessibility: checked with WAVE
- Spelling: checked with the Code Spell Checker extension in VS Code

## Credits

- All code, the photo and the video are my own work.