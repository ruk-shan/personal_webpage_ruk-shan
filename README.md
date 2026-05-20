# Ruk Shan - Personal Portfolio Website

Welcome to my personal portfolio website, hosted on GitHub Pages at [ruk-shan.com](https://ruk-shan.com).

## Features

- 🎨 **Modern & Responsive Design** - Clean, minimalist aesthetic with a dark theme
- 📱 **Mobile First** - Fully responsive on all devices
- ⚡ **Fast Loading** - Optimized static HTML/CSS/JS
- 🔗 **GitHub Pages Compatible** - Ready to deploy directly from GitHub
- ♿ **Accessible** - Semantic HTML and WCAG compliant

## Project Structure

```
ruk-shan/
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # JavaScript for interactivity
├── README.md           # This file
└── CNAME              # Custom domain configuration (optional)
```

## Sections

1. **Navigation Bar** - Sticky navigation with mobile menu toggle
2. **Hero Section** - Eye-catching introduction with call-to-action buttons
3. **About Section** - Personal introduction and skills showcase
4. **Projects Section** - Featured project cards with descriptions
5. **Contact Section** - Contact information and social links
6. **Footer** - Copyright and footer information

## Customization

### Update Personal Information

Edit `index.html` to customize:
- Your name and subtitle
- About section text
- Project details (titles, descriptions, links)
- Social media links and email
- Contact information

### Customize Colors

Edit the CSS variables at the top of `styles.css`:
```css
:root {
    --primary-color: #0f172a;
    --secondary-color: #1e293b;
    --accent-color: #3b82f6;
    /* ... more variables ... */
}
```

### Add More Projects

In the Projects section, duplicate a `.project-card` element and update:
- Project title
- Description
- Technology tags
- Project link

## Deployment to GitHub Pages

### Option 1: Using GitHub Pages with Custom Domain

1. Push this repository to GitHub with the name `ruk-shan.github.io`
2. Go to repository Settings → Pages
3. Set Source to "Deploy from a branch" with main branch
4. Add a `CNAME` file with your domain: `ruk-shan.com`
5. In your domain registrar, point your domain to GitHub's nameservers

### Option 2: Using GitHub Pages with Repository

1. Push to a regular repository (e.g., `website`)
2. Go to Settings → Pages
3. Set Source to "Deploy from a branch"
4. Your site will be available at `https://yourusername.github.io/website`

### Option 3: Deploy Manually

Simply push the files to your GitHub repository. GitHub Pages will automatically serve the `index.html` file.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Tips

- Keep images optimized and under 100KB
- Use modern image formats (WebP)
- Leverage browser caching
- Minimize CSS and JS if needed

## License

© 2026 Ruk Shan. All rights reserved.

## Questions?

If you need help customizing this template or deploying to GitHub Pages, feel free to reach out!
