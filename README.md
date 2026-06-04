# Nishi Solutions - Enterprise AI Website

This is a production-ready repository for the Nishi Solutions website, designed with a premium dark theme and interactive AI visuals.

## Features
- **Performance Optimized**: Lazy-loaded assets, cache-busting logic, and auto-minification ready.
- **SEO Ready**: Configured with `robots.txt`, `sitemap.xml`, Open Graph, Twitter Cards, and JSON-LD structured schema.
- **Security**: Form validation, Formsubmit integration (XSS/spam protected), and CSP headers.
- **Responsive Design**: Fluidly adapts across mobile, tablet, and desktop monitors.

## Folder Structure
```
/
├── index.html
├── assets/
│   ├── images/
│   │   └── logo.png
│   ├── css/
│   │   └── styles.css
│   ├── js/
│   │   └── app.js
│   └── icons/
├── sitemap.xml
├── robots.txt
├── favicon.ico
└── README.md
```

## Deployment Instructions (Vercel / Netlify)

This website requires **no build step** and is 100% ready for drag-and-drop deployment!

### Option 1: One-Click Deploy via Vercel
1. Create a GitHub repository and push this entire folder.
2. Go to [Vercel](https://vercel.com) and click **Add New Project**.
3. Import your GitHub repository.
4. Leave the Build Command and Output Directory blank.
5. Click **Deploy**. Your site will be live globally on Vercel's Edge Network with auto-minification enabled!

### Option 2: Drag and Drop via Netlify
1. Go to [Netlify Drop](https://app.netlify.com/drop).
2. Drag and drop this entire project folder into the upload box.
3. Your site will instantly go live!

## Contact Form Configuration
The contact forms in `index.html` use [Formsubmit](https://formsubmit.co) to securely forward inquiries to **info@nishisolutions.com**. 
- On your first test submission on the live site, Formsubmit will send an activation email to `info@nishisolutions.com`. Click "Activate Form" in that email to start receiving live inquiries.
