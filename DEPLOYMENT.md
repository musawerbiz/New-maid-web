# MAiD Infographic - Static HTML Deployment Guide

## GitHub Pages Deployment

This folder contains a fully static, production-ready build of your MAiD ethics infographic.

### Files Included
- `index.html` - Complete infographic with all styles and scripts embedded
- `assets/` - CSS and JavaScript bundles
- `.nojekyll` - Tells GitHub Pages to serve the site as-is (no Jekyll processing)
- `DEPLOYMENT.md` - This file

### Deployment Steps

#### Option 1: GitHub Pages (Recommended)
1. Create a new GitHub repository (e.g., `maid-infographic`)
2. Clone the repository locally
3. Copy all files from this folder into the repository root
4. Commit and push:
   ```bash
   git add .
   git commit -m "Add MAiD infographic static build"
   git push origin main
   ```
5. Go to repository Settings → Pages
6. Under "Build and deployment", select:
   - Source: Deploy from a branch
   - Branch: main / root
7. Your site will be live at `https://yourusername.github.io/maid-infographic`

#### Option 2: Any Static Web Host
- **Netlify**: Drag and drop this folder
- **Vercel**: Import the GitHub repository
- **AWS S3 + CloudFront**: Upload to S3 bucket with static website hosting enabled
- **Any web server**: Copy files to web root directory

### Features Included
✓ Interactive guided tour with warm voice narration
✓ Sticky navigation bar with 9 section links
✓ Progress bar showing scroll completion
✓ Back-to-top button
✓ Hover tooltips for key terms
✓ Interactive reflection section
✓ Smooth scroll-to-section navigation
✓ Responsive design (mobile, tablet, desktop)
✓ All academic citations and references
✓ Speaker buttons for individual section narration

### Browser Support
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Mobile)

### Notes
- All external resources (fonts, images) are loaded from CDN
- No backend server required
- Fully self-contained and offline-capable
- All interactive features work without any API calls

### File Sizes
- index.html: ~360 KB (minified)
- assets/: ~736 KB (CSS + JS bundles)
- Total: ~1.1 MB (gzipped: ~130 KB)

### Quick Start
1. Download this entire folder
2. Push to GitHub or upload to your hosting provider
3. Your site is live!

For questions or issues, refer to the original Manus project documentation.
