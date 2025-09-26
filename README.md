# AQDesk - Personal Portfolio Website

A clean, responsive personal portfolio website showcasing AQDesk's expertise in Digital Information Technology, E-Learning, and Information Security.

## About AQDesk

At AQDesk, we focus on Digital Information Technology, E-Learning, and Information Security to empower learners and professionals. We provide practical digital skills, flexible online learning solutions, and security awareness to help individuals and organizations succeed in today's connected and secure world.

## Features

- **Responsive Design**: Mobile-friendly layout that works on all devices
- **Modern UI**: Clean design with modern fonts, colors, and smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, and dynamic content
- **Contact Form**: Functional contact form with validation
- **Grid Layout**: Organized project showcase with filtering capabilities
- **Accessible**: Built with accessibility best practices

## Sections

- **Hero**: Eye-catching introduction with call-to-action
- **Bio**: About section with expertise and skills
- **Projects**: Grid layout showcasing key projects and solutions
- **Contact**: Contact form and information
- **Footer**: Additional links and information

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: Interactive functionality and form handling
- **Google Fonts**: Inter font family for modern typography

## Getting Started

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/aqdesk/teadqdesk.git
   cd teadqdesk
   ```

2. Open `index.html` in your web browser or use a local server:
   ```bash
   # Using Python (if installed)
   python -m http.server 8000
   
   # Using Node.js (if installed)
   npx http-server
   
   # Using PHP (if installed)
   php -S localhost:8000
   ```

3. Navigate to `http://localhost:8000` in your browser

### GitHub Pages Deployment

This website is configured for easy deployment on GitHub Pages:

1. **Enable GitHub Pages**:
   - Go to your repository settings
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

2. **Access Your Site**:
   - Your site will be available at: `https://aqdesk.github.io/teadqdesk/`
   - It may take a few minutes for the site to be available after enabling Pages

3. **Custom Domain** (Optional):
   - Add a `CNAME` file with your custom domain
   - Configure DNS settings with your domain provider
   - Update repository settings to use custom domain

### Automatic Deployment

GitHub Pages will automatically rebuild and deploy your site when you push changes to the main branch.

## Customization

### Content
- Edit `index.html` to update text content, projects, and contact information
- Modify the projects section to showcase your own work
- Update the bio section with your personal information

### Styling
- Customize colors, fonts, and layouts in `styles.css`
- The CSS uses CSS custom properties (variables) for easy theming
- Responsive breakpoints are configured for mobile, tablet, and desktop

### Functionality
- Extend `script.js` to add more interactive features
- The contact form currently shows a success message (integrate with a backend service for real functionality)

## File Structure

```
teadqdesk/
├── index.html          # Main HTML file
├── styles.css          # Stylesheet
├── script.js           # JavaScript functionality
├── README.md           # This file
├── LICENSE             # CC0 License
└── .gitignore          # Git ignore rules
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Optimized for fast loading
- Uses system fonts fallback
- Minimal external dependencies
- Responsive images and media queries

## License

This project is licensed under CC0 1.0 Universal - see the [LICENSE](LICENSE) file for details. This means you can freely use, modify, and distribute this code without any restrictions.

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Support

For questions or support, please open an issue in this repository or contact us through the website's contact form.

---

**Live Demo**: [View on GitHub Pages](https://aqdesk.github.io/teadqdesk/) (once deployed)