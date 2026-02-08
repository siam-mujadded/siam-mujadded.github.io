# Siam Al Mujadded - Portfolio Website

A modern, responsive portfolio website showcasing my professional experience, research work, projects, and skills.

## 🌐 Live Website

Once deployed, your portfolio will be available at:
**https://siam-mujadded.github.io** (or your GitHub username)

## 📋 Features

- **Modern Design**: Clean, professional, and visually appealing interface
- **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Animations**: Engaging user experience with smooth scrolling and fade-in effects
- **Comprehensive Sections**:
  - Hero section with introduction
  - About me
  - Skills showcase
  - Work experience (detailed achievements)
  - Research publications
  - Projects portfolio
  - Education background
  - Contact information

## 🚀 Deployment Guide

Follow these steps to deploy your portfolio to GitHub Pages:

### Step 1: Create a New Repository

1. Go to [GitHub](https://github.com) and sign in to your account
2. Click the **"+"** icon in the top right corner and select **"New repository"**
3. Name your repository: **`siam-mujadded.github.io`** (must match your GitHub username exactly)
4. Make it **Public**
5. **DO NOT** initialize with README, .gitignore, or license (we already have these files)
6. Click **"Create repository"**

### Step 2: Initialize Git and Push Files

Open your terminal/command prompt in the project directory and run:

```bash
# Initialize git repository (if not already initialized)
git init

# Add all files to staging
git add .

# Commit the files
git commit -m "Initial commit: Portfolio website"

# Add your GitHub repository as remote (replace with your username if different)
git remote add origin https://github.com/siam-mujadded/siam-mujadded.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

**Note**: If you already have a repository initialized, you can skip `git init` and just run the other commands.

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub: `https://github.com/siam-mujadded/siam-mujadded.github.io`
2. Click on **"Settings"** tab (at the top of the repository)
3. Scroll down to **"Pages"** in the left sidebar
4. Under **"Source"**, select **"Deploy from a branch"**
5. Choose **"main"** branch and **"/ (root)"** folder
6. Click **"Save"**

### Step 4: Wait for Deployment

- GitHub Pages will take a few minutes to build and deploy your site
- You'll see a message: "Your site is live at https://siam-mujadded.github.io"
- It may take up to 10-15 minutes for the site to be fully accessible

### Step 5: Verify Your Site

1. Visit `https://siam-mujadded.github.io` in your browser
2. Check that all sections are displaying correctly
3. Test the navigation and links

## 📝 Customization

### Update Personal Information

1. **Contact Information**: Edit the contact section in `index.html`
2. **Social Links**: Update LinkedIn and other social media links in the hero section
3. **GitHub Links**: Update project links to point to your actual repositories

### Update Project Links

In `index.html`, find the project cards and update the GitHub links:

```html
<a href="https://github.com/siam-mujadded/your-repo-name" target="_blank" class="project-link">
```

### Change Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2563eb;    /* Main brand color */
    --accent-color: #f59e0b;     /* Accent/highlight color */
    /* ... other colors */
}
```

### Add More Projects

Copy a project card in `index.html` and modify it with your project details.

## 🔄 Updating Your Portfolio

Whenever you make changes:

```bash
# Add changed files
git add .

# Commit changes
git commit -m "Update: Description of changes"

# Push to GitHub
git push origin main
```

GitHub Pages will automatically rebuild your site with the updates (usually within 1-2 minutes).

## 📁 File Structure

```
siam-mujadded/
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # JavaScript for interactivity
├── README.md           # This file
└── .gitignore          # Git ignore file
```

## 🛠️ Technologies Used

- **HTML5**: Structure and content
- **CSS3**: Styling and responsive design
- **JavaScript**: Interactive features and animations
- **Font Awesome**: Icons
- **GitHub Pages**: Hosting

## 📧 Contact

- **Email**: mujadded1998@gmail.com
- **Phone**: +880 1907 791862
- **GitHub**: [siam-mujadded](https://github.com/siam-mujadded)
- **Location**: Dhaka, Bangladesh

## 📄 License

This portfolio is open source and available under the MIT License.

---

**Note**: Make sure to update all GitHub repository links in the HTML file to point to your actual repositories. Currently, they point to your main GitHub profile.

