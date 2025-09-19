# Portfolio Website - frederictest52

A modern, responsive portfolio website showcasing my projects, skills, and professional experience.

## 🌟 Features

- **Responsive Design** - Optimized for all device sizes (desktop, tablet, mobile)
- **Modern UI/UX** - Clean, professional interface with smooth animations
- **Project Showcase** - Interactive gallery displaying my best work
- **Skills Section** - Comprehensive overview of technical expertise
- **Contact Form** - Functional contact form with validation
- **Dark/Light Mode** - Toggle between themes for better user experience
- **SEO Optimized** - Meta tags and structured data for better search visibility
- **Fast Loading** - Optimized images and efficient code for quick page loads

## 🛠️ Technologies Used

### Frontend
- **HTML5** - Semantic markup and accessibility features
- **CSS3** - Modern styling with Flexbox/Grid, animations, and responsive design
- **JavaScript (ES6+)** - Interactive functionality and DOM manipulation
- **Sass/SCSS** - CSS preprocessing for better organization

### Tools & Libraries
- **Bootstrap** - Responsive framework for faster development
- **Font Awesome** - Icon library for enhanced visual elements
- **AOS (Animate On Scroll)** - Smooth scroll animations
- **jQuery** - DOM manipulation and event handling
- **Lightbox** - Image gallery functionality

### Development Tools
- **Git** - Version control
- **GitHub Pages** - Hosting platform
- **VS Code** - Development environment
- **Live Server** - Local development server
- **Prettier** - Code formatting
- **ESLint** - Code linting

## 📁 Project Structure

```
frederictest52/
├── index.html              # Main HTML file
├── css/
│   ├── style.css          # Main stylesheet
│   ├── responsive.css     # Responsive design rules
│   └── themes.css         # Dark/light theme styles
├── js/
│   ├── main.js           # Main JavaScript file
│   ├── animations.js     # Animation controls
│   └── contact-form.js   # Contact form handling
├── images/
│   ├── projects/         # Project screenshots
│   ├── profile/          # Profile photos
│   └── icons/           # Custom icons
├── assets/
│   ├── resume.pdf       # Downloadable resume
│   └── favicon.ico      # Site favicon
├── README.md            # Project documentation
└── .gitignore          # Git ignore rules
```

## 🚀 Setup Instructions

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor or IDE (VS Code recommended)
- Git installed on your system
- Live Server extension (for local development)

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/fredericmirindi/frederictest52.git
   cd frederictest52
   ```

2. **Open in your preferred editor**
   ```bash
   code .  # For VS Code
   ```

3. **Start local development server**
   - Using VS Code Live Server: Right-click on `index.html` → "Open with Live Server"
   - Using Python: `python -m http.server 8000`
   - Using Node.js: `npx live-server`

4. **Open in browser**
   - Navigate to `http://localhost:3000` (Live Server)
   - Or `http://localhost:8000` (Python server)

### Deployment

This project is configured for GitHub Pages deployment:

1. **Enable GitHub Pages**
   - Go to repository Settings
   - Scroll to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/" (root) folder
   - Click "Save"

2. **Access your live site**
   - Visit: `https://fredericmirindi.github.io/frederictest52/`
   - Updates automatically deploy when pushing to main branch

## 🎨 Customization

### Colors & Themes
- Primary colors defined in `:root` CSS variables
- Easy theme switching in `themes.css`
- Customize brand colors by updating CSS custom properties

### Content Updates
- **Projects**: Update project data in `js/main.js`
- **Skills**: Modify skills section in `index.html`
- **About**: Edit personal information in HTML
- **Contact**: Update contact form endpoint in `contact-form.js`

### Adding New Sections
1. Add HTML structure in `index.html`
2. Style with CSS in appropriate stylesheet
3. Add JavaScript functionality if needed
4. Update navigation menu links

## 📱 Responsive Breakpoints

- **Mobile**: 320px - 768px
- **Tablet**: 769px - 1024px
- **Desktop**: 1025px and above
- **Large Desktop**: 1400px and above

## 🔧 Performance Optimizations

- **Image Optimization**: Compressed images with appropriate formats
- **CSS Minification**: Minified CSS for production
- **JavaScript Bundling**: Optimized JS loading
- **Lazy Loading**: Images load as user scrolls
- **Caching**: Proper cache headers for static assets

## 🧪 Testing

### Browser Compatibility
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

### Responsive Testing
- Test on various device sizes
- Use browser developer tools
- Validate on real devices when possible

### Performance Testing
- Lighthouse audit scores: 90+ recommended
- Page load time: < 3 seconds
- First contentful paint: < 1.5 seconds

## 📈 SEO Features

- Meta descriptions and keywords
- Open Graph tags for social sharing
- Structured data markup
- Semantic HTML5 elements
- Alt tags for all images
- Sitemap.xml (if applicable)

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

- **GitHub**: [@fredericmirindi](https://github.com/fredericmirindi)
- **Website**: [Portfolio Live Demo](https://fredericmirindi.github.io/frederictest52/)
- **Email**: Contact through the portfolio website

## 🔄 Version History

- **v1.0.0** - Initial release with basic portfolio structure
- **v1.1.0** - Added responsive design and animations
- **v1.2.0** - Implemented dark/light theme toggle
- **v1.3.0** - Enhanced SEO and performance optimizations

---

⭐ **Star this repository if you found it helpful!** ⭐

*Built with ❤️ by Frederic Mirindi*
