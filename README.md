# NYBOTECH Website

A modern, responsive website for NYBOTECH - a leading provider of innovative medical equipment and healthcare technology solutions.

## Features

- **Responsive Design**: Fully responsive layout that works on all devices (desktop, tablet, mobile)
- **Modern UI**: Clean, professional design with smooth animations and transitions
- **Smooth Scrolling**: Navigation links with smooth scroll behavior
- **Mobile Menu**: Hamburger menu for mobile devices
- **Contact Form**: Interactive contact form for inquiries
- **Multiple Sections**:
  - Hero/Homepage section with key features
  - Why Choose Us section highlighting benefits
  - Featured Products showcase
  - Innovation in Medical Technology section
  - Contact section with form and information

## File Structure

```
nybotech.com/
├── index.html      # Main HTML file
├── styles.css      # CSS stylesheet
├── script.js       # JavaScript for interactivity
├── package.json    # npm configuration
├── .gitignore      # Git ignore file
└── README.md       # This file
```

## Getting Started

### Using npm (Recommended)

1. **Install dependencies**:
   ```bash
   npm install
   ```

2. **Start development server**:
   ```bash
   npm run dev
   ```
   The website will be available at `http://localhost:5173` (or the port shown in the terminal)

3. **Build for production**:
   ```bash
   npm run build
   ```

4. **Preview production build**:
   ```bash
   npm run preview
   ```

### Alternative: Direct Browser

Simply open `index.html` in a web browser:
   - Double-click the file, or
   - Right-click and select "Open with" your preferred browser

## Customization

### Colors
Edit the CSS variables in `styles.css` to change the color scheme:
```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #10b981;
    /* ... other variables */
}
```

### Content
- Edit `index.html` to update text content, sections, and structure
- Modify `styles.css` to adjust styling, spacing, and layout
- Update `script.js` to add or modify interactive features

### Contact Form
The contact form currently shows an alert on submission. To connect it to a backend:
1. Update the form submission handler in `script.js`
2. Add your API endpoint
3. Handle form validation and submission

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript
- Google Fonts (Inter)
- Vite (Development server)

## License

This project is created for NYBOTECH. All rights reserved.

