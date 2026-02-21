# Kimberly Jane Reyes - Portfolio

A professional portfolio website showcasing my experience as a Software Developer.

## 🚀 Deploy to GitHub Pages

### Step 1: Create a GitHub Account
1. Go to [github.com](https://github.com)
2. Click "Sign up" and create your account
3. Verify your email address

### Step 2: Create a New Repository
1. Click the "+" icon in the top right corner
2. Select "New repository"
3. Name it: `yourusername.github.io` (replace `yourusername` with your actual GitHub username)
   - Example: If your username is `kimreyes`, name it `kimreyes.github.io`
4. Make it **Public**
5. Click "Create repository"

### Step 3: Upload Your Files
You have two options:

#### Option A: Upload via Web Interface (Easiest)
1. On your repository page, click "uploading an existing file"
2. Drag and drop these files:
   - `index.html`
   - `styles.css`
   - `script.js`
3. Scroll down and click "Commit changes"

#### Option B: Using Git (If you have Git installed)
```bash
# Navigate to your portfolio folder
cd path/to/your/portfolio

# Initialize git
git init

# Add all files
git add .

# Commit files
git commit -m "Initial portfolio commit"

# Add remote repository (replace with your URL)
git remote add origin https://github.com/yourusername/yourusername.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 4: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "main" branch
5. Click "Save"
6. Wait 1-2 minutes for deployment

### Step 5: View Your Live Site
Your portfolio will be live at: `https://yourusername.github.io`

## 🎨 Customization

### Update Your Information
- Edit `index.html` to update your projects, experience, or contact info
- Modify `styles.css` to change colors or styling
- Update `script.js` for interactive features

### Change Colors
The color palette is defined in `styles.css` under `:root`:
```css
:root {
    --primary-color: #ff7f6a;
    --secondary-color: #ff6b54;
    --accent-color: #ffa894;
}
```

## 📱 Features
- Responsive design (mobile, tablet, desktop)
- Smooth scrolling navigation
- Animated sections on scroll
- Professional timeline for work experience
- Project showcase with technology tags
- Contact section with multiple methods

## 🔧 Technologies Used
- HTML5
- CSS3
- JavaScript (Vanilla)
- Font Awesome Icons

## 📝 License
© 2025 Kimberly Jane Reyes. All rights reserved.

## 🆘 Troubleshooting

**Site not showing up?**
- Wait 2-3 minutes after enabling Pages
- Check that your repository name is exactly `yourusername.github.io`
- Ensure the repository is Public
- Make sure `index.html` is in the root folder

**Need to update your site?**
- Just upload new files or push changes via Git
- GitHub Pages will automatically rebuild (takes 1-2 minutes)

**Want a custom domain?**
- Buy a domain from any registrar (Namecheap, GoDaddy, etc.)
- In GitHub Pages settings, add your custom domain
- Update your domain's DNS settings to point to GitHub
