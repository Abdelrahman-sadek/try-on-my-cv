# Abdelrahman Sadek - Professional Portfolio Website

A modern, dark-themed personal portfolio website showcasing Abdelrahman Sadek's professional profile. The site features a sleek, futuristic design with interactive elements, smooth animations, and responsive layout.

![Portfolio Preview](assets/images/portfolio-preview.jpg)

## Features

- **Dark Futuristic Theme** - Modern dark mode with neon accents and glassmorphism effects
- **Interactive UI** - Custom cursor effects, hover animations, and smooth transitions
- **Responsive Design** - Fully optimized for all devices (desktop, tablet, mobile)
- **Animated Sections** - Scroll-triggered animations and elegant entry effects
- **Interactive Elements** - Animated skill bars, project filtering, and timeline
- **Performance Optimized** - Fast loading times with minimal dependencies
- **Accessibility Focused** - Semantic HTML and proper ARIA attributes

## Technologies Used

- **HTML5** - Semantic structure for better accessibility and SEO
- **CSS3** - Custom properties, flexbox, grid, and animations
- **JavaScript** - Vanilla JS for interactive elements and animations
- **Particles.js** - For the interactive background particles effect
- **ScrollReveal** - For scroll-triggered animations
- **Typed.js** - For the typing animation in the hero section

## Project Structure

```
portfolio-website/
├── index.html              # Main HTML file
├── site.webmanifest        # Web app manifest for PWA support
├── assets/
│   ├── css/
│   │   └── styles.css      # Main stylesheet
│   ├── js/
│   │   └── main.js         # Main JavaScript file
│   ├── images/             # Image assets
│   │   ├── profile.jpg     # Profile picture
│   │   ├── project-*.jpg   # Project thumbnails
│   │   ├── favicon-*.png   # Favicon files
│   │   └── ...
│   └── fonts/              # Custom fonts (if any)
└── README.md               # Project documentation
```

## Setup and Installation

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/portfolio-website.git
   ```

2. Navigate to the project directory:
   ```bash
   cd portfolio-website
   ```

3. Open the project in your code editor

4. Launch the site using a local server:
   - You can use the Live Server extension in VS Code
   - Or use Python's built-in server: `python -m http.server`
   - Or any other local development server

### Customization

1. **Personal Information**:
   - Update personal details in `index.html`
   - Replace profile image in `assets/images/profile.jpg`
   - Update project images and descriptions

2. **Color Scheme**:
   - Modify CSS variables in `assets/css/styles.css` to change the color scheme
   - Main colors are defined at the top of the CSS file

3. **Content Sections**:
   - Add or remove sections as needed in `index.html`
   - Update the navigation links accordingly

4. **Animations**:
   - Adjust animation parameters in `assets/js/main.js`
   - Modify ScrollReveal configurations for different animation effects

## Deployment

### GitHub Pages

1. Create a GitHub repository for your portfolio

2. Push your code to the repository:
   ```bash
   git remote add origin https://github.com/yourusername/portfolio-website.git
   git branch -M main
   git push -u origin main
   ```

3. Go to repository Settings > Pages
   - Set source to "main" branch
   - Save the settings

4. Your site will be published at `https://yourusername.github.io/portfolio-website/`

### Other Hosting Options

The website can be deployed on any static site hosting service:

- Netlify
- Vercel
- Firebase Hosting
- Amazon S3

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## Performance Optimization

- Optimized images for faster loading
- Minified CSS and JavaScript files
- Lazy loading for images
- Efficient animations using CSS transforms and opacity
- Limited use of external libraries

## Credits

- Fonts: Google Fonts (Inter, Space Grotesk, Orbitron, Fira Mono)
- Icons: Font Awesome
- Particles Background: Particles.js
- Typing Animation: Typed.js
- Scroll Animations: ScrollReveal.js

## License

This project is available for personal use.

---

Designed and developed with ❤️ for Abdelrahman Sadek