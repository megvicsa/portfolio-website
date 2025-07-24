# Personal Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Features a clean design, smooth animations, and mobile-first approach.

## 🚀 Features

- **Responsive Design**: Works perfectly on all devices
- **Modern UI/UX**: Clean and professional design
- **Smooth Animations**: CSS animations and JavaScript interactions
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Contact Form**: Functional contact form with validation
- **SEO Optimized**: Proper meta tags and semantic HTML
- **Fast Loading**: Optimized for performance
- **Cross-browser Compatible**: Works on all modern browsers

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🛠️ Setup Instructions

1. **Clone or Download**: Download all files to your local machine
2. **Open in Browser**: Simply open `index.html` in your web browser
3. **Local Development**: Use a local server for better development experience

### Using a Local Server (Recommended)

If you have Python installed:
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

If you have Node.js installed:
```bash
# Install a simple server globally
npm install -g live-server

# Run the server
live-server
```

Then visit `http://localhost:8000` in your browser.

## 🎨 Customization Guide

### 1. Personal Information

Edit the following in `index.html`:

- **Name**: Replace "Your Name" with your actual name
- **Title**: Change "Full Stack Developer" to your profession
- **Description**: Update the hero description
- **About Me**: Modify the about section content
- **Contact Information**: Update email, phone, and location

### 2. Skills & Technologies

In the skills section, you can:
- Add/remove skill categories (Frontend, Backend, Tools)
- Change skill items and their icons
- Modify the layout by editing the CSS grid

### 3. Projects

Update the projects section with your own projects:
- Project titles and descriptions
- Technologies used
- Links to live demos and GitHub repositories
- Project images (replace placeholder icons)

### 4. Experience

Modify the experience timeline:
- Job titles and companies
- Dates and durations
- Job descriptions and achievements

### 5. Styling

Customize the appearance in `styles.css`:

#### Colors
```css
:root {
    --primary-color: #2563eb;      /* Main brand color */
    --secondary-color: #fbbf24;    /* Accent color */
    --text-color: #333;            /* Main text color */
    --bg-color: #f8fafc;           /* Background color */
}
```

#### Fonts
Replace the Google Fonts link in `index.html`:
```html
<link href="https://fonts.googleapis.com/css2?family=Your+Font:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

### 6. Images

Replace placeholder elements with your own images:
- Profile picture in the hero section
- About section image
- Project screenshots
- Company logos

## 🌐 Deployment Options

### 1. GitHub Pages (Free)

1. Create a new GitHub repository
2. Upload your files
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your site will be available at `https://username.github.io/repository-name`

### 2. Netlify (Free)

1. Sign up for Netlify
2. Drag and drop your project folder
3. Your site will be deployed instantly
4. Get a custom domain or use the provided subdomain

### 3. Vercel (Free)

1. Sign up for Vercel
2. Connect your GitHub repository
3. Deploy automatically on every push
4. Get a custom domain

### 4. Traditional Web Hosting

Upload files to any web hosting service:
- cPanel hosting
- AWS S3
- Google Cloud Storage
- Any FTP-enabled hosting

## 📱 Mobile Optimization

The website is already optimized for mobile devices with:
- Responsive design
- Touch-friendly navigation
- Optimized images
- Fast loading times

## 🔧 Advanced Customization

### Adding New Sections

1. Add HTML structure in `index.html`
2. Add corresponding CSS in `styles.css`
3. Add navigation link if needed
4. Add JavaScript functionality if required

### Custom Animations

Add new CSS animations:
```css
@keyframes yourAnimation {
    from { /* starting state */ }
    to { /* ending state */ }
}

.your-element {
    animation: yourAnimation 1s ease-out;
}
```

### Form Integration

To make the contact form functional:

1. **EmailJS** (Client-side):
   ```html
   <script src="https://cdn.jsdelivr.net/npm/@emailjs/browser@3/dist/email.min.js"></script>
   ```

2. **Netlify Forms** (Serverless):
   Add `netlify` attribute to the form:
   ```html
   <form class="contact-form" netlify>
   ```

3. **Custom Backend**: Replace the form handling in `script.js`

## 🎯 SEO Optimization

The website includes:
- Proper meta tags
- Semantic HTML structure
- Alt text for images
- Open Graph tags
- Schema markup (can be added)

## 🔍 Performance Tips

1. **Optimize Images**: Compress images before uploading
2. **Minify CSS/JS**: Use tools to minify files for production
3. **Use CDN**: Consider using CDN for external resources
4. **Lazy Loading**: Implement lazy loading for images
5. **Caching**: Set up proper caching headers

## 🐛 Troubleshooting

### Common Issues

1. **Fonts not loading**: Check internet connection and Google Fonts availability
2. **Icons not showing**: Ensure Font Awesome CDN is accessible
3. **Animations not working**: Check if JavaScript is enabled
4. **Mobile menu not working**: Verify JavaScript file is loaded

### Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your needs. If you find any bugs or have suggestions, please open an issue.

## 📞 Support

If you need help customizing or deploying your portfolio, feel free to reach out!

---

**Happy coding! 🚀** 