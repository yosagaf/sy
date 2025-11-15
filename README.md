# Portfolio Website - Sagaf Youssouf

A modern, minimalist portfolio website showcasing expertise in Computer Vision, MLOps, and Edge AI. Built with vanilla HTML, CSS, and JavaScript for optimal performance and simplicity.

## 🚀 Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Modern UI**: Clean, elegant design with smooth animations
- **Performance Optimized**: Fast loading times and optimized assets
- **SEO Friendly**: Proper meta tags and semantic HTML
- **Accessible**: Follows accessibility best practices

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles
├── script.js           # JavaScript for interactivity
└── README.md          # This file
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid and Flexbox
- **JavaScript (Vanilla)**: No frameworks, pure JavaScript for performance
- **Google Fonts**: Inter font family

## 📦 Deployment on GitHub Pages

GitHub Pages is the recommended hosting solution - it's free, simple, and perfect for static websites.

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Name it `portfolio` (or any name you prefer)
5. Make it **Public** (required for free GitHub Pages)
6. Click "Create repository"

### Step 2: Upload Your Files

**Option A: Using GitHub Web Interface**

1. In your new repository, click "uploading an existing file"
2. Drag and drop all files from the `portfolio` folder:
   - `index.html`
   - `styles.css`
   - `script.js`
3. Add a commit message (e.g., "Initial portfolio commit")
4. Click "Commit changes"

**Option B: Using Git Command Line**

```bash
# Navigate to your portfolio directory
cd portfolio

# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial portfolio commit"

# Add your GitHub repository as remote (replace YOUR_USERNAME)
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings** (top menu)
3. Scroll down to **Pages** (left sidebar)
4. Under **Source**, select:
   - Branch: `main` (or `master`)
   - Folder: `/ (root)`
5. Click **Save**
6. GitHub will provide you with a URL like: `https://YOUR_USERNAME.github.io/portfolio/`

### Step 4: Custom Domain (Optional)

If you have a custom domain:

1. In the Pages settings, add your domain under "Custom domain"
2. Update your DNS records:
   - Add a CNAME record pointing to `YOUR_USERNAME.github.io`
   - Or add A records pointing to GitHub Pages IPs:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153

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

After making changes:

1. **If using Git:**
   ```bash
   git add .
   git commit -m "Update portfolio content"
   git push
   ```

2. **If using GitHub web interface:**
   - Edit files directly on GitHub
   - Or upload new versions

Changes will be live on GitHub Pages within a few minutes.

## 🌐 Alternative Hosting Options

### Google Sites
- **Pros**: Very simple, no code needed
- **Cons**: Limited customization, not ideal for developer portfolios
- **Verdict**: Not recommended for this portfolio

### Netlify
- **Pros**: Free, automatic deployments from Git, custom domains
- **Cons**: Slightly more complex setup
- **How**: Connect your GitHub repo to Netlify

### Vercel
- **Pros**: Free, excellent performance, easy Git integration
- **Cons**: More suited for React/Next.js projects
- **How**: Import your GitHub repository

### GitHub Pages (Recommended)
- **Pros**: Free, simple, perfect for static sites, integrated with Git
- **Cons**: None for this use case
- **Verdict**: ✅ Best choice

## 📧 Contact

- **Email**: sagafysf@gmail.com
- **Phone**: +33 783929127
- **LinkedIn**: [linkedin.com/in/yosagaf](https://www.linkedin.com/in/yosagaf/)

## 📄 License

This portfolio template is free to use and modify for personal or commercial projects.

---

**Built with ❤️ by Sagaf Youssouf**

