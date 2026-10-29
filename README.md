# Week 2: CSS Styling & Layout - Portfolio

## Author
- **Name:** Precious Ndegwa
- **GitHub:** [@preciousndegwa48](https://github.com/preciousndegwa48)
- **Date:** October 28, 2026

## Project Description
Portfolio website built for IYF Week 2 assignment focusing on CSS fundamentals - Reset, Box Model, Typography System, Color Scheme, Flexbox, Grid, and Mobile-first Responsive Design. Includes box model exercises and polished interactive effects.

## Technologies Used
- HTML5
- CSS3
- CSS Variables (Custom Properties)
- Flexbox
- CSS Grid
- Google Fonts (Poppins, Inter)

## Features
- Reset and Base Typography System with CSS variables
- Box Model Mastery - 4 demo boxes, broken/fixed 340px debug, 300px card component
- Color Scheme with primary, secondary, background, text, muted
- Flexbox Navigation and Card Row layout
- Grid Gallery (3 columns), Magazine Layout with grid areas, Projects Grid responsive
- Mobile-first responsive design (320px, 768px, 1024px, 1280px, 1440px)
- Polish effects - hover transform, box-shadow, transitions, focus states

## How to Run
1. Clone this repository: `git clone https://github.com/preciousndegwa48/iyf-s12-week-02-preciousndegwa48.git`
2. Open `index.html` in your browser
3. Also open `box-model-practice.html` for box model exercises

## Lessons Learned
- How `box-sizing: border-box` fixes overflow by including padding/border inside width, making card exactly 300px total even with 20px padding
- Grid is best for 2D layouts (gallery, magazine), Flexbox for 1D layouts (nav, card row)
- Mobile-first with min-width media queries works better than desktop-first
- Using CSS variables for typography and colors makes theming consistent
- `max-width: 100%` on images prevents horizontal scroll

## Challenges Faced
- **Box model overflow:** My broken-box became 340px instead of 300px because padding added to width. Fixed by using `box-sizing: border-box`.
- **Flexbox vs Grid confusion:** Was unsure when to use flex vs grid. Solved: flex for nav and card row (1D), grid for gallery and magazine (2D).
- **Mobile nav stacking:** Nav overflow on mobile. Fixed with `flex-direction: column` at max-width 600px.
- **Horizontal scroll:** Images overflowing. Fixed with `img { max-width: 100% }` and `object-fit: cover` for gallery.

## Screenshots (optional)
![Portfolio Screenshot](https://placehold.co/800x400?text=Portfolio+Week+2)

## Live Demo (if deployed)
[View Live Demo](https://preciousndegwa48.github.io/iyf-s12-week-02-preciousndegwa48/)
