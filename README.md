# Portfolio Website - Sagaf Youssouf

A modern, high-tech portfolio website showcasing expertise in Computer Vision, MLOps, and Edge AI. Built with vanilla HTML, CSS, and JavaScript for optimal performance and simplicity.

## 🚀 Features

- **Modern High-Tech Design**: Dark theme with blue glow effects, animated borders, and luminous elements
- **Responsive Design**: Fully responsive layout that works on all devices
- **Bilingual Support**: English and French language switching
- **Performance Optimized**: Fast loading times with vanilla JavaScript (no frameworks)
- **SEO Friendly**: Proper meta tags and semantic HTML
- **Accessible**: Follows accessibility best practices
- **CI/CD**: Automatic deployment to GitHub Pages on every push

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles with modern glow effects
├── script.js           # JavaScript for interactivity and i18n
├── translations.js     # Bilingual content (EN/FR)
├── favicon.svg         # Portfolio favicon
├── .nojekyll          # Disable Jekyll processing
├── _config.yml        # Jekyll config (disabled)
├── .github/
│   └── workflows/
│       └── deploy.yml  # CI/CD workflow for GitHub Pages
└── README.md          # This file
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid, Flexbox, and advanced animations
- **JavaScript (Vanilla)**: No frameworks, pure JavaScript for performance
- **Google Fonts**: Inter and JetBrains Mono font families
- **GitHub Actions**: CI/CD for automatic deployment
- **GitHub Pages**: Free hosting

## 📦 Deployment

This portfolio uses **GitHub Pages** with **GitHub Actions** for automatic deployment.

### Automatic Deployment (CI/CD)

The repository includes a GitHub Actions workflow that automatically deploys the site to GitHub Pages whenever you push changes to the `main` branch.

**Setup:**

1. **Create a GitHub Repository**
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
   git push -u origin main
   ```

2. **Configure GitHub Pages**
   - Go to your repository → **Settings** → **Pages**
   - Under **Source**, select **"GitHub Actions"** (not "Deploy from a branch")
   - Save

3. **That's it!** Every time you push changes, the site will automatically deploy.

**Live URL:** `https://yosagaf.github.io/sy/`

### Manual Deployment

If you prefer manual deployment:

1. Go to repository **Settings** → **Pages**
2. Select **"Deploy from a branch"**
3. Choose branch: `main`, folder: `/ (root)`
4. Save

### Custom Domain (Optional)

1. In Pages settings, add your domain under "Custom domain"
2. Update DNS records:
   - **CNAME**: Point to `YOUR_USERNAME.github.io`
   - Or **A records**: Point to GitHub Pages IPs (185.199.108.153, etc.)

## 🔧 Local Development

To view the website locally:

1. Simply open `index.html` in your web browser
2. Or use a local server:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## 🎨 Customization

### Colors

Edit CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2563eb;      /* Main brand color */
    --secondary-color: #10b981;     /* Accent color */
    --text-primary: #1f2937;        /* Main text color */
    /* ... */
}
```

### Content

- Edit `index.html` to update your information
- Modify sections, projects, and experience entries
- Update contact information and social links

### Styling

- All styles are in `styles.css`
- Responsive breakpoints are defined in media queries
- Animations can be adjusted in the CSS transitions

## 📝 Updating Your Portfolio

After making changes, simply push to GitHub:

```bash
git add .
git commit -m "Update portfolio content"
git push
```

The GitHub Actions workflow will automatically deploy your changes to GitHub Pages within 1-2 minutes.

## 🎨 Design Features

- **Modern High-Tech Aesthetic**: Blue glow effects (`#00d4ff`) with animated borders
- **Smooth Animations**: Fade-in effects, hover transitions, and pulse animations
- **Luminous Elements**: Glowing timeline markers, borders, and text shadows
- **Dark Theme**: Professional dark background with subtle grid patterns
- **Interactive Cards**: Hover effects with gradient borders and shadows

## 🌐 Alternative Hosting Options

### Netlify
- **Pros**: Free, automatic deployments from Git, custom domains, drag & drop
- **How**: Connect your GitHub repo or drag & drop files

### Vercel
- **Pros**: Free, excellent performance, easy Git integration
- **How**: Import your GitHub repository

### Cloudflare Pages
- **Pros**: Free, fast CDN, automatic deployments
- **How**: Connect your GitHub repository

### GitHub Pages (Current)
- **Pros**: Free, integrated with Git, CI/CD included
- **Status**: ✅ Currently deployed

## 📧 Contact

- **Email**: sagafysf@gmail.com
- **Phone**: +33 783929127
- **LinkedIn**: [linkedin.com/in/yosagaf](https://www.linkedin.com/in/yosagaf/)

## 📄 License

This portfolio template is free to use and modify for personal or commercial projects.

---

**Built with ❤️ by Sagaf Youssouf**

