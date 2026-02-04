# Personal Portfolio Website

A beautiful, modern portfolio website ready to deploy on GitHub Pages.

## 🚀 Quick Start - Host on GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in (or create an account)
2. Click the **+** icon in the top right and select **New repository**
3. Name your repository `yourusername.github.io` (replace `yourusername` with your actual GitHub username)
   - For example, if your username is `johndoe`, name it `johndoe.github.io`
4. Make sure it's set to **Public**
5. Click **Create repository**

### Step 2: Upload Your Website

**Option A: Using GitHub Web Interface (Easiest)**

1. In your new repository, click **uploading an existing file**
2. Drag and drop the `index.html` file
3. Scroll down and click **Commit changes**

**Option B: Using Git Command Line**

```bash
# Navigate to your project folder
cd path/to/your/website

# Initialize git
git init

# Add your files
git add index.html

# Commit your files
git commit -m "Initial commit - Add portfolio website"

# Connect to your GitHub repository
git remote add origin https://github.com/yourusername/yourusername.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (top right)
3. Click **Pages** in the left sidebar
4. Under **Source**, select **main** branch
5. Click **Save**

### Step 4: View Your Website

After a few minutes, your website will be live at:
```
https://yourusername.github.io
```

## ✏️ Customizing Your Website

Open `index.html` in any text editor and update:

1. **Your Name**: Replace "YourName" and "Your Name" throughout
2. **Title & Description**: Update the hero section text
3. **About Section**: Customize the about cards with your skills
4. **Projects**: Update project titles, descriptions, and tags
5. **Contact Info**: 
   - Replace `your.email@example.com` with your email
   - Update social media links (GitHub, LinkedIn, Twitter)
6. **Colors**: Modify CSS variables at the top if you want different colors:
   ```css
   :root {
       --cream: #F5F1E8;
       --charcoal: #2C2C2C;
       --rust: #B85C38;
       --sage: #7A9B76;
       --slate: #4A5568;
   }
   ```

## 🎨 Design Features

- Modern, distinctive design with serif headers and clean sans-serif body text
- Smooth animations and hover effects
- Fully responsive (looks great on mobile, tablet, and desktop)
- Smooth scrolling navigation
- Professional color palette

## 📱 Adding More Pages

To add more pages:

1. Create new HTML files (e.g., `blog.html`, `resume.html`)
2. Upload them to your repository
3. Link to them from your main page: `<a href="blog.html">Blog</a>`

## 🔄 Updating Your Site

Whenever you want to update your website:

1. Make changes to your HTML file
2. Upload the new version to GitHub (replace the old file)
3. Or use git commands:
   ```bash
   git add .
   git commit -m "Update website"
   git push
   ```

Your changes will appear on your live site within a few minutes!

## 💡 Tips

- Keep your `index.html` as the main page (GitHub Pages looks for this)
- Test your website locally by opening `index.html` in your browser before uploading
- Use your repository to version control your website
- Consider adding a custom domain later through GitHub Pages settings

## 🆘 Troubleshooting

**Website not showing up?**
- Wait 5-10 minutes after pushing changes
- Check that your repository is named correctly (`yourusername.github.io`)
- Ensure GitHub Pages is enabled in Settings > Pages
- Make sure the file is named exactly `index.html`

**Need help?**
- Check [GitHub Pages documentation](https://docs.github.com/en/pages)
- Visit [GitHub Community](https://github.community)

---

Enjoy your new website! 🎉
