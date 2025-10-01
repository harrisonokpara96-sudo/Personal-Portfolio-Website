# Personal Portfolio Website

This is my personal portfolio website built with HTML5 and CSS3. The website showcases my skills, projects, and provides a way for visitors to contact me.

## Project Structure

- index.html - Home page with navigation and introduction
- about.html - About me page with profile information and introduction video
- projects.html - Projects page showcasing my work
- contact.html - Contact form page with validation
- css/style.css - Main stylesheet
- css/mobile.css - Mobile-specific styles
- css/tablet.css - Tablet-specific styles
- images/ - Directory for image assets
- video/ - Directory for video assets

## Responsive Design

The website is fully responsive and uses fluid design with media queries for different screen sizes:

- *Mobile*: Up to 768px - Stacked navigation, centered content, single-column layout
- *Tablet*: 769px to 1024px - Adjusted font sizes and image dimensions for medium screens
- *Desktop*: 1025px and above - Full layout with side-by-side elements where appropriate

### Why These Breakpoints Were Chosen:
- 768px is a common breakpoint for mobile devices as it covers most smartphones in both portrait and landscape orientations
- 1024px is a standard breakpoint for tablets as it covers most tablet devices in portrait orientation
- These breakpoints provide a good balance between device coverage and development efficiency

## CSS Features Used

### Linear Gradients
- Used in the header navigation background: linear-gradient(135deg, #667eea 0%, #764ba2 100%)
- Used in button backgrounds: linear-gradient(135deg, #667eea 0%, #764ba2 100%)
- Used in hero section background: linear-gradient(45deg, #f3f4f6, #e5e7eb)

### Color Scheme
The color scheme was created using Adobe Color and features:
- Primary: #667eea (Light blue)
- Secondary: #764ba2 (Purple)
- Neutral: #f9f9f9 (Light gray background)
- Text: #333 (Dark gray)

## Form Validation

The contact form includes the following validation:
- Name field: Required
- Email field: Required with email format validation
- Phone field: Optional but follows pattern validation (###-###-####)
- Comments field: Required

## External Code Usage

No external code was used in this project. All HTML, CSS, and JavaScript was written from scratch.

## Testing and Validation

- HTML validated using W3C Markup Validation Service
- CSS validated using W3C CSS Validation Service
- Links checked using W3C Link Checker
- Spelling checked using online spell check tools
- Accessibility tested using WAVE Web Accessibility Evaluation Tool

## GitHub Repository

The repository is structured with clear commit history showing the development process:
- Initial setup and basic structure
- Home page implementation
- About page with image and video
- Projects page with project listings
- Contact page with form validation
- Responsive design implementation
- Final testing and deployment

## Deployment

The site is deployed on GitHub Pages at: [(https://github.com/harrisonokpara96-sudo/portfolio-website)]

## Copyright

© 2025 Harrison Okpara. All rights reserved.
