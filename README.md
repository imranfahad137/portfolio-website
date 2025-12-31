# Professional Portfolio Website

A modern, responsive portfolio website for Computer Engineering PhD students, built with HTML, CSS, and JavaScript.

## Features

- 🎨 Modern and clean design
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Smooth animations and transitions
- 🧭 Easy navigation with smooth scrolling
- 🎯 Sections: About, Research, Publications, Projects, Contact
- 🔍 SEO-friendly structure
- 🚀 Optimized for GitHub Pages hosting

## Getting Started

### Local Development

1. Clone or download this repository
2. Open `index.html` in your web browser
3. For a better development experience, use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (http-server)
   npx http-server
   ```

### Customization

1. **Personal Information**: Edit `index.html` and replace:
   - "Your Name" with your actual name
   - Email addresses in the contact section
   - Social media links (GitHub, LinkedIn, Google Scholar)
   - Research interests and descriptions
   - Publications and projects

2. **Styling**: Modify `styles.css` to customize:
   - Colors (update CSS variables in `:root`)
   - Fonts (change Google Fonts import in HTML)
   - Spacing and layout
   - Animations

3. **Functionality**: Enhance `script.js` to add:
   - Contact form handling
   - Additional interactive features
   - Analytics integration

## Deploying to GitHub Pages

### Method 1: Using GitHub Web Interface

1. Create a new repository on GitHub (or use an existing one)
2. Upload all files to the repository
3. Go to **Settings** → **Pages**
4. Under **Source**, select the branch containing your files (usually `main` or `master`)
5. Select the root folder (`/`)
6. Click **Save**
7. Your site will be available at `https://yourusername.github.io/repository-name`

### Method 2: Using Git Command Line

```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit: Portfolio website"

# Add remote repository (replace with your repository URL)
git remote add origin https://github.com/yourusername/your-repo-name.git

# Push to GitHub
git branch -M main
git push -u origin main
```

Then follow steps 3-7 from Method 1.

### Custom Domain (Optional)

1. Add a `CNAME` file in the root directory with your domain name
2. Configure DNS settings with your domain provider
3. Update GitHub Pages settings to use your custom domain

## File Structure

```
portfolio-website/
│
├── index.html          # Main HTML file
├── styles.css          # Stylesheet
├── script.js           # JavaScript functionality
├── README.md           # This file
└── .gitignore          # Git ignore file (optional)
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Tips

- Optimize images before adding them to the site
- Consider using a CDN for external resources
- Minify CSS and JavaScript for production
- Use lazy loading for images if you add many

## License

This project is open source and available under the MIT License. Feel free to use it for your own portfolio!

## Credits

- Font: [Inter](https://fonts.google.com/specimen/Inter) by Google Fonts
- Icons: Emoji (native support)

## Support

If you encounter any issues or have questions, please open an issue on GitHub.

---

**Note**: Remember to update all placeholder content (especially email addresses, links, and personal information) before deploying your site publicly.
