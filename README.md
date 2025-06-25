# Mudit's Portfolio

A modern, responsive portfolio website built with HTML, CSS, and JavaScript featuring a beautiful metallic greyscale design.

## Features

- 🎨 **Metallic Greyscale Design** - Elegant color scheme with metallic gradients
- 📱 **Fully Responsive** - Works perfectly on all devices
- ⚡ **Smooth Animations** - Scroll animations and hover effects
- 🧭 **Smooth Navigation** - One-page design with smooth scrolling
- 📝 **Contact Form** - Functional contact form (requires backend setup)
- 🎯 **Modern UI/UX** - Clean and professional design

## Sections

1. **Hero Section** - Introduction and call-to-action
2. **About** - Personal information and statistics
3. **Experience** - Work history timeline
4. **Projects** - Featured projects with descriptions
5. **Skills** - Technical skills organized by category
6. **Contact** - Contact information and form

## Customization

### Personal Information
Update the following in `index.html`:

- **Name**: Replace "Mudit" with your name
- **Title**: Update the hero subtitle
- **Description**: Modify the about section text
- **Contact Details**: Update email, phone, and location
- **Social Links**: Add your social media profiles

### Experience Section
Replace the placeholder experience items with your actual work history:

```html
<div class="timeline-item">
    <div class="timeline-content">
        <h3>Your Job Title</h3>
        <h4>Company Name</h4>
        <p class="timeline-date">2023 - Present</p>
        <ul>
            <li>Your achievement 1</li>
            <li>Your achievement 2</li>
            <li>Your achievement 3</li>
        </ul>
    </div>
</div>
```

### Projects Section
Update the project cards with your actual projects:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-brain"></i> <!-- Change icon as needed -->
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>Project description</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="your-github-link" class="project-link"><i class="fab fa-github"></i> Code</a>
            <a href="your-live-link" class="project-link"><i class="fas fa-external-link-alt"></i> Live</a>
        </div>
    </div>
</div>
```

### Skills Section
Update the skills in each category to match your expertise.

## Deployment to GitHub Pages

### Method 1: Automatic Deployment

1. **Create a new repository** on GitHub
2. **Upload all files** to the repository:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `README.md`
3. **Go to Settings** → **Pages**
4. **Select Source**: "Deploy from a branch"
5. **Select Branch**: "main" (or "master")
6. **Select Folder**: "/ (root)"
7. **Click Save**
8. Your site will be available at: `https://yourusername.github.io/repository-name`

### Method 2: Using GitHub Pages Branch

1. Create a new branch called `gh-pages`
2. Upload all files to this branch
3. Go to Settings → Pages
4. Select "Deploy from a branch"
5. Select "gh-pages" branch
6. Click Save

## Custom Domain (Optional)

1. **Purchase a domain** from a domain registrar
2. **Add CNAME file** to your repository:
   ```
   yourdomain.com
   ```
3. **Configure DNS** with your domain provider:
   - Add CNAME record pointing to `yourusername.github.io`
4. **Update GitHub Pages settings**:
   - Go to Settings → Pages
   - Enter your custom domain
   - Check "Enforce HTTPS"

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── README.md           # This file
└── Mudit-Resume-AI.pdf # Your resume (optional)
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Tips

- Optimize images before uploading
- Minimize CSS and JavaScript files for production
- Use a CDN for external resources
- Enable GZIP compression on your server

## Contributing

Feel free to fork this project and customize it for your own portfolio!

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you have any questions or need help with customization, please open an issue on GitHub.

---

**Note**: Remember to update all placeholder content with your actual information before deploying! 