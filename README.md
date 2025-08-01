# On Your Digital Website

## Overview
This is a professional, responsive website for "On Your Digital," showcasing the multiple businesses of entrepreneur Mary Anita Pandipilly John. The website includes five pages detailing different business aspects:

1. **Home Page**: Overview of all services
2. **School Uniforms**: Information about uniform and multi-brand shoes business
3. **Digital Marketing**: AI-powered digital marketing services for real estate and other industries
4. **Life Coaching**: Holistic healing and life coaching services
5. **Contact Page**: Contact information and inquiry form

## Features
- Fully responsive design that works on all devices (mobile, tablet, desktop)
- Modern, professional aesthetic with consistent branding
- Interactive elements including navigation menu, testimonial sliders, and accordions
- Contact form for customer inquiries
- Optimized for performance and user experience

## File Structure
```
OYD Website/
├── index.html              # Home page
├── uniform.html            # School uniforms page
├── digital.html            # Digital marketing page
├── coaching.html           # Life coaching page
├── contact.html            # Contact page
├── css/
│   └── style.css           # Main stylesheet
├── js/
│   └── script.js           # JavaScript functionality
├── images/                 # Image assets
│   ├── placeholder.svg     # Generic placeholder image
│   ├── hero-bg.svg         # Hero section background
│   ├── uniform-header.svg  # Uniform page header
│   ├── digital-header.svg  # Digital marketing page header
│   ├── coaching-header.svg # Life coaching page header
│   └── contact-header.svg  # Contact page header
└── README.md               # This documentation file
```

## Customization Guide

### Replacing Placeholder Images
The website currently uses SVG placeholders for images. To replace them with actual images:

1. Add your image files to the `images/` directory
2. Update the image paths in the HTML files or CSS where needed

### Updating Content
To update the website content:

1. Open the relevant HTML file in a code editor
2. Modify the text within the HTML tags
3. Save the file and refresh your browser to see changes

### Changing Colors
The website uses a consistent color scheme defined in CSS variables. To change the colors:

1. Open `css/style.css`
2. Locate the `:root` selector at the top of the file
3. Modify the color values as needed

```css
:root {
    --primary-color: #2ecc71;    /* Main brand color */
    --accent-color: #2ecc71;      /* Accent color for highlights */
    --accent-hover: #27ae60;      /* Hover state for accent elements */
    --dark-color: #333333;        /* Dark text color */
    --light-color: #f9f9f9;       /* Light background color */
    --box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1); /* Standard shadow */
    --transition: all 0.3s ease;  /* Standard transition */
}
```

### Adding New Pages
To add a new page to the website:

1. Copy one of the existing HTML files as a template
2. Rename the file appropriately
3. Update the content and page-specific styles
4. Add a link to the new page in the navigation menu of all HTML files

## Browser Compatibility
The website is compatible with all modern browsers including:
- Google Chrome
- Mozilla Firefox
- Safari
- Microsoft Edge

## Local Development
To work on this website locally:

1. Clone or download the repository
2. Open the files in your preferred code editor
3. Use a local development server for best results (e.g., Live Server extension for VS Code)

## Credits
- Fonts: Google Fonts (Poppins, Montserrat)
- Icons: Font Awesome

## License
This website is created for Mary Anita Pandipilly John and "On Your Digital" business. All rights reserved.