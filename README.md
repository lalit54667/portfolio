# Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. This website showcases your skills, projects, and provides a way for potential clients or employers to contact you.

## 🚀 Features

- **Modern Design**: Clean, professional design with gradient accents and smooth animations
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Interactive Elements**: Hover effects, scroll animations, and smooth transitions
- **Contact Form**: Functional contact form with validation
- **Navigation**: Sticky navigation with smooth scrolling and active link highlighting
- **Performance Optimized**: Debounced scroll events and optimized animations
- **SEO Friendly**: Semantic HTML5 structure
- **Accessible**: Proper ARIA labels and keyboard navigation support

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and modern structure
- **CSS3**: Modern styling with CSS Grid, Flexbox, and animations
- **JavaScript (ES6+)**: Interactive features and form handling
- **Google Fonts**: Inter font family for typography
- **Font Awesome**: Icon library for social links and UI elements

## 📋 Setup Instructions

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A code editor (VS Code, Sublime Text, etc.) - optional
- A local web server (optional, for development)

### Getting Started

1. **Clone or Download** the project files to your local machine

2. **Open the project folder** in your code editor or file explorer

3. **Launch the website**:
   - **Simple Method**: Double-click `index.html` to open it in your default browser
   - **Development Method**: Use a local web server for better development experience

### Using a Local Web Server

#### Option 1: Using Python (if installed)
```bash
# Navigate to the project directory
cd portfolio

# Start a local server (Python 3)
python -m http.server 8000

# For Python 2
python -m SimpleHTTPServer 8000
```

#### Option 2: Using Node.js (if installed)
```bash
# Install http-server globally
npm install -g http-server

# Navigate to the project directory
cd portfolio

# Start the server
http-server
```

#### Option 3: Using VS Code Live Server Extension
1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

4. **Open your browser** and navigate to:
   - `http://localhost:8000` (if using Python)
   - `http://localhost:8080` (if using http-server)
   - Or the URL provided by your local server

## 🎨 Customization Guide

### Personal Information

Update the following sections in `index.html`:

1. **Hero Section** (lines 44-52):
   ```html
   <h1 class="hero-title">Hi, I'm <span class="highlight">Lalit Kumar</span></h1>
   <p class="hero-subtitle">Your Professional Title</p>
   ```

2. **About Section** (lines 75-85):
   ```html
   <p>Your personal description...</p>
   ```

3. **Contact Information** (lines 180-190):
   ```html
   <span>your.email@example.com</span>
   <span>+1 234 567 8900</span>
   <span>Your City, Country</span>
   ```

### Skills Section

Modify the skills in `index.html` (lines 107-143):
- Update skill titles and descriptions
- Change Font Awesome icons as needed
- Add or remove skill cards

### Projects Section

Update projects in `index.html` (lines 150-210):
- Replace placeholder content with your actual projects
- Update project titles, descriptions, and technologies
- Add real links to live demos and GitHub repositories

### Social Links

Update social media links in `index.html` (lines 195-202):
```html
<a href="https://github.com/lalit54667" class="social-link">
    <i class="fab fa-github"></i>
</a>
```

### Color Scheme

Customize colors in `styles.css` (lines 8-16):
```css
:root {
    --primary-color: #667eea;    /* Primary accent color */
    --secondary-color: #764ba2;  /* Secondary accent color */
    --text-dark: #2d3748;        /* Main text color */
    --text-light: #718096;       /* Secondary text color */
    --bg-light: #f7fafc;         /* Light background */
    --bg-white: #ffffff;          /* White background */
}
```

### Typography

Change fonts by updating the Google Fonts link in `index.html` (line 7):
```html
<link href="https://fonts.googleapis.com/css2?family=Your+Font:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

And update the font-family in `styles.css` (line 25):
```css
body {
    font-family: 'Your Font', sans-serif;
}
```

## 📱 Responsive Design

The website is fully responsive and includes:

- **Mobile-first approach** with breakpoints at 768px and 480px
- **Hamburger menu** for mobile navigation
- **Flexible grid layouts** that adapt to screen size
- **Touch-friendly** buttons and links
- **Optimized images** and media queries


## 🐛 Troubleshooting

### Common Issues

1. **Styles not loading**: Ensure `styles.css` is in the same directory as `index.html`
2. **JavaScript not working**: Check browser console for errors and ensure `script.js` is linked correctly
3. **Local server issues**: Try a different port or use a different local server method
4. **Font Awesome icons not showing**: Check internet connection for CDN access

### Browser Compatibility

This website works on all modern browsers:
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## 📞 Support

If you need help customizing or deploying your portfolio, feel free to reach out.

---

**Happy Coding! 🎉**
