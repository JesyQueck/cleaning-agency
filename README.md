# WeCleanIt - Professional Cleaning Services Website

A modern, responsive website for WeCleanIt, a professional cleaning service company based in Lagos, Nigeria. This website showcases their services, gallery, and provides a way for potential customers to get in touch.

## Features

- **Fully Responsive Design**: Works on all devices (desktop, tablet, mobile)
- **Modern UI/UX**: Clean and professional design with smooth animations
- **Interactive Elements**:
  - Mobile-friendly navigation menu
  - Image gallery with lightbox functionality
  - Contact form with validation
  - Newsletter subscription
  - Smooth scrolling navigation
- **Performance Optimized**: Fast loading times and optimized assets
- **SEO Friendly**: Properly structured with semantic HTML and meta tags

## Technologies Used

- **Frontend**:
  - HTML5
  - CSS3 (with CSS Variables for theming)
  - JavaScript (Vanilla JS - no jQuery)
  - Font Awesome Icons
  - Google Fonts (Poppins)

## File Structure

```
cleaning-agency/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # Main stylesheet
├── js/
│   └── script.js       # Main JavaScript file
└── images/             # Directory for all images
    └── gallery/        # Gallery images
```

## Setup and Installation

1. **Clone the repository** or download the source code
2. **Open `index.html` in your web browser** to view the website locally
3. **For development**, you can use a local server like Live Server in VS Code

## Customization

### Colors
You can easily customize the color scheme by modifying the CSS variables in the `:root` selector in `css/style.css`:

```css
:root {
    --primary-color: #2c7be5;      /* Main brand color */
    --secondary-color: #00d97e;    /* Secondary accent color */
    --dark-color: #2d3748;         /* Dark text/background */
    --text-color: #4a5568;         /* Main text color */
    --text-light: #718096;         /* Lighter text color */
}
```

### Content
- Update the company information in the contact section
- Replace placeholder images in the `images/` directory with your own
- Modify the services, about, and other content in `index.html`

## Form Submission

The contact form and newsletter subscription form are set up with basic client-side validation. To make them fully functional, you'll need to:

1. Set up a server-side script to handle form submissions
2. Update the form actions in `index.html` to point to your server endpoint
3. Add any additional form fields as needed

## Browser Support

The website is tested and works on all modern browsers including:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available under the [MIT License](LICENSE).

## Credits

- [Font Awesome](https://fontawesome.com/) for icons
- [Google Fonts](https://fonts.google.com/) for the Poppins font
- [Unsplash](https://unsplash.com/) for placeholder images (replace with your own)

## Contact

For any questions or support, please contact WeCleanIt at info@wecleanit.ng

---

© 2023 WeCleanIt. All rights reserved.
