# John Borgia Professional Website

Three-time award-winning composer and strategic concept developer.

## 🚀 Quick Setup

This website is designed to be hosted on **GitHub Pages** (100% FREE).

### Step 1: Upload Your Photos

You need to add your photos to the `/images` folder:

1. **Primary photo** (blue blazer by pool): Save as `john-borgia-primary.jpg`
2. **Secondary photo** (dark suit): Save as `john-borgia-secondary.jpg`

**Photo requirements:**
- Format: JPG or PNG
- Recommended size: 800-1200px wide
- Keep file sizes under 500KB for fast loading

### Step 2: Create GitHub Repository

1. Go to [GitHub.com](https://github.com) and create free account (if you don't have one)
2. Create a new repository named `johnborgia` (or any name you want)
3. Upload all files from this folder to the repository

### Step 3: Enable GitHub Pages

1. In your repository, go to **Settings**
2. Scroll to **Pages** section (left sidebar)
3. Under "Source", select **main** branch
4. Click **Save**
5. GitHub will give you a URL like: `https://yourusername.github.io/johnborgia`

### Step 4: Connect Your Domain (johnborgia.com)

1. In GitHub Pages settings, add your custom domain: `johnborgia.com`
2. In GoDaddy:
   - Go to DNS settings for johnborgia.com
   - Add these records:

   **A Records** (point to GitHub):
   ```
   185.199.108.153
   185.199.109.153
   185.199.110.153
   185.199.111.153
   ```

   **CNAME Record**:
   ```
   www → yourusername.github.io
   ```

3. Wait 24-48 hours for DNS to propagate
4. Enable HTTPS in GitHub Pages settings

## 📁 File Structure

```
johnborgia-website/
├── index.html          # Homepage
├── about.html          # About page with full timeline
├── music.html          # Music portfolio
├── concepts.html       # Innovation concepts
├── blog.html           # Blog (coming soon)
├── contact.html        # Contact page
├── style.css           # All styles
├── images/             # Your photos go here
│   ├── john-borgia-primary.jpg
│   └── john-borgia-secondary.jpg
└── README.md           # This file
```

## 🎨 Customization

### Update LinkedIn (when you create it):

Find this line in all HTML files:
```html
<li><a href="#" target="_blank">LinkedIn</a></li>
```

Replace `#` with your LinkedIn URL.

### Add More Photos:

Just add photos to `/images` folder and reference them:
```html
<img src="images/your-photo.jpg" alt="Description">
```

## ✅ What's Included

- ✅ Professional homepage
- ✅ Complete about page with timeline (1974-2025)
- ✅ Music portfolio with YouTube embeds
- ✅ Concepts showcase (MICS, NO AI CERTIFIED, etc.)
- ✅ Blog framework (ready for content)
- ✅ Contact page
- ✅ Fully responsive (mobile-friendly)
- ✅ Modern, clean design
- ✅ Fast loading
- ✅ SEO optimized

## 🔧 Technical Details

- **Hosting**: GitHub Pages (FREE)
- **Tech**: Pure HTML/CSS (no JavaScript frameworks)
- **Speed**: Lightweight, fast loading
- **Mobile**: Fully responsive
- **Browser**: Works on all modern browsers

## 📧 Need Help?

If you need assistance:
1. Check GitHub Pages documentation: https://pages.github.com
2. YouTube tutorials: Search "GitHub Pages custom domain"

## 🎯 Next Steps After Launch

1. **Create LinkedIn profile** (use content from About page)
2. **Start blog posts** (6 topics outlined in blog.html)
3. **Add more music** (upload to YouTube, embed here)
4. **Update regularly** (shows you're active)

---

**Built December 2025**  
**Ready to make you visible as a credible founder**
