# How to Deploy Your Site to Netlify (5 Minutes)

## What You Need
- This project folder
- A free Netlify account (sign up at netlify.com)

## Fastest Way: Drag and Drop

1. **Build the site locally**
   - Open Terminal/Command Prompt
   - Navigate to this project folder
   - Run: `npm install` (first time only)
   - Run: `npm run build`
   - This creates a `dist` folder with your site

2. **Deploy to Netlify**
   - Go to: https://app.netlify.com/drop
   - Drag the entire `dist` folder onto the page
   - Wait 10 seconds
   - Done! You get a live URL like `random-name-12345.netlify.app`

3. **Share with your partner**
   - Copy the URL
   - Send it to Benjamin
   - He can view it on any device

## Better Way: Connect to GitHub (for ongoing updates)

If you put this on GitHub:

1. Push this project to GitHub
2. In Netlify, click "Add new site" → "Import from GitHub"
3. Select your repository
4. Build settings:
   - Build command: `npm run build`
   - Publish directory: `dist`
5. Click Deploy

Every time you push changes to GitHub, Netlify automatically rebuilds and deploys.

## Custom Domain (Later)

Once Benjamin approves and you want to use your real domain:

1. In Netlify: Site settings → Domain management
2. Click "Add custom domain"
3. Enter: tyman-auerbach.com
4. Netlify will show you DNS records to update
5. Update your domain's DNS (wherever you bought the domain)
6. Wait a few hours for DNS to propagate

Netlify handles SSL certificates (HTTPS) automatically.

## Troubleshooting

**"npm: command not found"**
- You need to install Node.js first
- Download from: https://nodejs.org
- Then try again

**Build fails**
- Make sure you ran `npm install` first
- Check that you're in the right folder

**Need help?**
- The README has more details
- Or just tell me what error you're seeing

## Cost

$0. Netlify's free tier is perfect for this site.

You just saved $30/month by canceling Webflow.
