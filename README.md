# Figma Design 33 - Responsive Webpage

## Overview

This project is a responsive webpage implementation based on a Figma design, developed as part of the Fullstack Developer Bootcamp at [Mwenaro Academy](https://academy.mwenaro.com). The goal of this project is to demonstrate proficiency in HTML, CSS, and responsive design principles by translating a static design into a functional, mobile-friendly webpage.

### Original Design

The design was sourced from the Figma community. You can view the original Figma design here:
- **[Figma Design Link](https://www.figma.com/design/3EO3gS5FJAXmZsobOArP9B/50--Landing-page-designs--Community-?node-id=832-1583&t=ABXJ9J4xbbtZzzc3-0)**
- A reference image of the original design is included in the project as `Original-reference-image.png`

## Features

- **Responsive Design**: The layout adapts seamlessly across different screen sizes, from mobile phones to desktops.
- **Mobile-First Approach**: Designed with mobile devices in mind, using progressive enhancement for larger screens.
- **Clean Layout**: Two-column layout on larger screens, stacking vertically on mobile devices.
- **Interactive Elements**: Hover effects on buttons and proper semantic HTML structure.
- **Image Optimization**: Uses appropriate image formats and responsive image handling.

## Technologies Used

- **HTML5**: Semantic markup for structure and accessibility.
- **CSS3**: Flexbox for layout, media queries for responsiveness, and modern CSS features.
- **Figma**: Design source for the webpage layout and styling.

## Project Structure

```
figma-design33/
├── index.html          # Main HTML file
├── README.md           # Project documentation
├── images/             # Image assets
│   ├── Circle1.png
│   ├── Circle2.png
│   ├── Circle3.png
│   ├── Frame1.png
│   ├── Frame2.png
│   ├── Frame3.png
│   ├── Frame4.png
│   └── Original-reference-image.png
└── styles/
    ├── main.css        # Main stylesheet
    └── main copy.css   # Backup stylesheet
```

## Live Demo

You can view the live deployed project here: **[https://mustafajeilan.github.io/figma-design33](https://mustafajeilan.github.io/figma-design33)**

## Setup and Installation

Since this is a static webpage project, no complex installation is required:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/mustafajeilan/figma-design33.git
   cd figma-design33
   ```

2. **Open the webpage**:
   - Open `index.html` in your preferred web browser.
   - Alternatively, serve the files using a local server for better development experience.
   - Or visit the live demo link above to see it deployed.

## Usage

The webpage displays a promotional section with:
- A headline and description text
- A call-to-action button
- Three circular icons
- Two list items with titles and descriptions
- Four frame images arranged in a grid layout

The design responds to screen size changes:
- **Mobile (< 768px)**: Single column layout with stacked elements
- **Tablet/Desktop (≥ 768px)**: Two-column layout with side-by-side content and images

## Responsive Breakpoints

- **Base**: Mobile-first design (default styles)
- **480px+**: Enhanced spacing for smaller tablets and large phones
- **768px+**: Desktop layout with horizontal flex direction and adjusted image positioning

## Design Implementation

The implementation faithfully recreates the Figma design using:
- Flexbox for flexible layouts
- CSS custom properties for consistent theming
- Media queries for responsive behavior
- Proper image sizing and positioning
- Color scheme matching the original design

## Learning Outcomes

This project demonstrates:
- Converting design mockups to code
- Implementing responsive web design
- Using modern CSS layout techniques
- Semantic HTML practices
- Cross-device compatibility

## Credits

- **Mwenaro Academy**: For providing the bootcamp curriculum and project guidelines
- **Figma**: For the design tool used to create the original mockup

## License

This project is part of a learning exercise and is not licensed for commercial use.