# RAG Chatbot Landing Page

Professional landing page for RAG Chatbot WordPress plugin.

## Files

- `index.html` - Main HTML file
- `styles.css` - All styles
- `script.js` - JavaScript functionality
- `README.md` - This file

## Deployment to GitHub Pages

### Option 1: Using GitHub Web Interface

1. Create a new repository on GitHub
2. Upload all files from this folder
3. Go to repository Settings → Pages
4. Select source: "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click Save
7. Your site will be live at: `https://yourusername.github.io/repository-name/`

### Option 2: Using Git Command Line

```bash
cd rag-chatbot-landing
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/yourusername/your-repo-name.git
git push -u origin main
```

Then enable GitHub Pages in repository settings.

## Customization

### Update Checkout Link

The checkout link is set to:
`https://checkout.freemius.com/plugin/22674/plan/38023/`

To change it, search for this URL in `index.html` and replace with your actual checkout URL.

### Colors

Edit CSS variables in `styles.css`:

```css
:root {
    --primary: #111827;
    --primary-hover: #1f2937;
    /* ... other colors ... */
}
```

### Content

Edit text content directly in `index.html`.

## Features

- ✅ Fully responsive design
- ✅ Smooth scrolling navigation
- ✅ Animated elements on scroll
- ✅ Modern, professional design
- ✅ Mobile-friendly
- ✅ Fast loading
- ✅ SEO-friendly structure

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## License

This landing page is for RAG Chatbot plugin promotion.

