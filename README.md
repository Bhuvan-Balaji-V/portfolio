# Bhuvan Balaji V — Portfolio

A modern, responsive portfolio website showcasing projects, resume, and professional information for **Bhuvan Balaji V**, a Full Stack Developer & AI/ML Engineer.

## Features

- **Responsive Design** — Mobile-first approach with CSS Grid and Flexbox
- **Multiple Pages** — Home, Resume, and Bio-data pages
- **Clean UI** — Modern gradient header, card-based layout, smooth interactions
- **Accessibility** — Semantic HTML, meta descriptions, alt text support
- **Print Ready** — Optimized print stylesheet for resume printing
- **Fast Loading** — Minified CSS, jQuery for smooth navigation

## Pages

- **Home (`index.html`)** — Landing page with portfolio overview, key skills, and highlighted projects
- **Resume (`resume.html`)** — Detailed resume with education, skills, projects, experience, and achievements
- **Bio-data (`biodata.html`)** — Personal biographical information in a structured table format

## Technology Stack

- **Frontend:** HTML5, CSS3 (with CSS Variables), JavaScript (jQuery)
- **Design:** CSS Grid, Flexbox, Responsive Media Queries
- **Hosting:** GitHub Pages / Netlify

## Quick Start

### Local Development

1. Clone or download this repository
2. Open `index.html` in your browser, or use Live Server:
   ```bash
   # If using Live Server extension in VS Code
   Right-click index.html → Open with Live Server
   ```
3. Navigate between pages using the header navigation

### File Structure

```
portfolio/
├── index.html        (Home page)
├── resume.html       (Resume page)
├── biodata.html      (Bio-data page)
├── style.css         (Main stylesheet)
└── README.md         (This file)
```

## Deployment

### GitHub Pages (Free)

1. Create a GitHub repository: `https://github.com/<your-username>/<repo-name>`
2. Push this portfolio to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio commit"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. Enable GitHub Pages:
   - Go to Settings → Pages
   - Set Branch = `main`, Folder = `/root`
   - Your site will be live at: `https://<your-username>.github.io/<repo-name>/`

### Netlify (Drag & Drop)

1. Go to [Netlify](https://netlify.com)
2. Drag and drop the project folder into Netlify Deploy
3. Your site will be live with a unique URL

## Customization

### Colors

Edit the CSS variables in `style.css`:

```css
:root {
  --bg: #f4f7fb;
  --card: #ffffff;
  --accent: #0b63d6;
  --muted: #6b7280;
  --text: #0f1724;
  --radius: 12px;
}
```

### Content

- Update personal info in the HTML files
- Modify skills and projects in the respective sections
- Update social links and contact info

## Responsiveness

The portfolio is fully responsive and tested on:
- Desktop (1200px+)
- Tablet (768px - 1024px)
- Mobile (480px - 768px)
- Small Mobile (<480px)

## Accessibility

- ✅ Semantic HTML5 structure
- ✅ Meta descriptions for SEO
- ✅ Viewport meta tag for mobile optimization
- ✅ Proper heading hierarchy
- ✅ Color contrast compliance

## Print Styles

The resume page is optimized for printing:
```bash
Ctrl+P (Windows) or Cmd+P (Mac) → Print → Save as PDF
```

## Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Mobile)

## Contact

- **Email:** bhuvanbalajiv@outlook.com
- **GitHub:** [bhuvanbalajiv](https://github.com/bhuvanbalajiv)

## License

This portfolio is personal and open for learning purposes. Feel free to fork and customize for your own use.

---

**Last Updated:** December 2025
