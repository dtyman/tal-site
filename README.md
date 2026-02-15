# Tyman Auerbach Law - Website

Clean, bold, and direct. Built with Astro.

## Quick Start

### Local Development

1. Install dependencies:
```bash
npm install
```

2. Start the dev server:
```bash
npm run dev
```

3. Open your browser to `http://localhost:4321`

### Building for Production

```bash
npm run build
```

The built site will be in the `dist/` folder.

## Deploying to Netlify (Recommended - FREE)

### Option 1: Drag and Drop (Easiest)

1. Run `npm run build` locally
2. Go to https://app.netlify.com/drop
3. Drag your `dist` folder into the upload area
4. Done! You'll get a live URL immediately

### Option 2: Connect to GitHub (Best for ongoing work)

1. Push this project to GitHub
2. Go to https://app.netlify.com
3. Click "Add new site" → "Import an existing project"
4. Choose GitHub and select your repository
5. Build settings:
   - Build command: `npm run build`
   - Publish directory: `dist`
6. Click "Deploy"

Your site will be live at a URL like `yoursite.netlify.app`

### Custom Domain

Once deployed, you can point your actual domain (tyman-auerbach.com) to it:
1. In Netlify, go to Site settings → Domain management
2. Add your custom domain
3. Update your domain's DNS settings (Netlify will show you exactly what to do)

## Project Structure

```
/
├── public/
│   └── brand/
│       └── logo-red.png       # Your logo
├── src/
│   ├── layouts/
│   │   └── BaseLayout.astro   # Header, footer, meta tags
│   ├── pages/
│   │   ├── index.astro        # Homepage
│   │   ├── services.astro     # Services page (placeholder)
│   │   ├── about.astro        # About page (placeholder)
│   │   └── contact.astro      # Contact page (placeholder)
│   └── styles/
│       └── global.css         # Global styles and CSS variables
├── astro.config.mjs
└── package.json
```

## Design System

### Colors
- Red: `#D32F2F`
- Deep Red: `#B71C1C`
- Warm Black: `#1A1412`
- Charcoal: `#2C2624`
- Cream: `#F5F1E8`
- Warm White: `#FDFBF7`

### Fonts
- Display/Headings: Bebas Neue
- Serif/Emphasis: Crimson Pro
- Body: Work Sans

### Visual Language
- Bold, assertive red
- Textured, warm backgrounds
- Brutalist elements (heavy borders, physical shadows)
- Human, grounded feel

## Next Steps

1. Deploy to Netlify and get preview URL
2. Show your partner
3. Build out Services, About, and Contact pages
4. Add any additional content/sections
5. Point your actual domain once approved

## Notes

- Placeholder pages (Services, About, Contact) are ready to be filled in
- All navigation links work
- Design system is established and consistent
- Mobile responsive
- SEO-friendly structure

You've canceled Webflow, so you're saving $30/month. Netlify's free tier is more than enough for a law firm site.
