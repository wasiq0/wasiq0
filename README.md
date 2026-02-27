# Wasiq Nabi Bakhsh - Data Science Portfolio

A modern, responsive portfolio website showcasing data science and machine learning projects.

## 🚀 Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Dark theme with animated backgrounds and smooth transitions
- **Interactive Elements**: Hover effects, scroll animations, and parallax effects
- **Project Showcase**: Highlighting key ML, NLP, and data science projects
- **Technical Skills**: Visual representation of technical competencies
- **Contact Section**: Multiple ways to get in touch

## 📋 Sections

1. **Hero** - Introduction with name, title, and navigation
2. **Projects** - Featured data science and ML projects
3. **Skills** - Technical skills organized by category
4. **About** - Background, experience, and statistics
5. **Contact** - Contact information and career interests

## 🛠️ Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript
- Google Fonts (IBM Plex Mono, Spectral)

## 📦 Deployment to GitHub Pages

Follow these steps to deploy your portfolio to GitHub Pages:

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right and select "New repository"
3. Name your repository: `your-username.github.io` (replace `your-username` with your GitHub username)
   - Example: `wasiq0.github.io`
4. Set it to **Public**
5. Click "Create repository"

### Step 2: Upload Your Files

**Option A: Using GitHub Web Interface**

1. In your new repository, click "uploading an existing file"
2. Drag and drop the `index.html` file
3. Scroll down and click "Commit changes"

**Option B: Using Git Command Line**

```bash
# Navigate to where you downloaded the portfolio file
cd /path/to/your/portfolio

# Initialize git repository
git init

# Add the file
git add index.html

# Commit the file
git commit -m "Initial commit: Add portfolio website"

# Add your GitHub repository as remote
git remote add origin https://github.com/your-username/your-username.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings" (in the repository menu)
3. Scroll down to "Pages" section in the left sidebar
4. Under "Source", select "main" branch
5. Click "Save"

### Step 4: Access Your Website

Your portfolio will be live at: `https://your-username.github.io`

It may take a few minutes for GitHub Pages to build and deploy your site.

## 🎨 Customization

### Updating Project Links

In the `index.html` file, update the project links from the placeholder `https://github.com/wasiq0` to your actual project repository URLs:

```html
<a href="https://github.com/your-username/your-project-repo" class="project-link">View Project →</a>
```

### Changing Colors

The color scheme is defined in CSS variables at the top of the file:

```css
:root {
    --bg-primary: #0a0e17;
    --accent-primary: #00d9ff;
    --accent-secondary: #7c3aed;
    /* etc. */
}
```

### Adding More Projects

Copy a project card `<div class="project-card reveal">...</div>` and modify the content:

```html
<div class="project-card reveal">
    <div class="project-icon">🎯</div>
    <div class="project-tags">
        <span class="tag">Your Tag</span>
    </div>
    <h3 class="project-title">Your Project Title</h3>
    <p class="project-description">Your project description</p>
    <div class="project-meta">
        <span>📊 Metric 1</span>
        <span>🎯 Metric 2</span>
    </div>
    <a href="your-link" class="project-link">View Project →</a>
</div>
```

## 📱 Mobile Responsive

The portfolio is fully responsive with breakpoints at:
- Desktop: 1200px+
- Tablet: 968px - 1199px
- Mobile: < 968px

## 🔗 Links

- **GitHub**: [github.com/wasiq0](https://github.com/wasiq0)
- **LinkedIn**: [linkedin.com/in/wasiqbakhsh](https://linkedin.com/in/wasiqbakhsh)
- **Email**: Wasiqcyber@gmail.com

## 📄 License

This portfolio template is free to use and modify for personal use.

## 🤝 Contributing

Feel free to fork this repository and customize it for your own portfolio!

---

Built with ❤️ by Wasiq Nabi Bakhsh
