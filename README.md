# WallStreetClash Website

A modern, responsive landing page for WallStreetClash - the ultimate stock trading battle arena.

## Files

- `index.html` - Main HTML structure
- `styles.css` - All styling and responsive design
- `script.js` - Interactive features and animations

## Features

✅ **Modern Design**
- Dark theme with financial/trading aesthetic
- Gradient accents and smooth animations
- Professional typography using Inter font

✅ **Fully Responsive**
- Mobile-first design
- Works on all screen sizes (mobile, tablet, desktop)
- Touch-friendly navigation

✅ **Interactive Elements**
- Smooth scroll navigation
- Fade-in animations on scroll
- Hover effects on cards
- Parallax effects

✅ **Sections Included**
- Hero section with call-to-action
- Features showcase
- How It Works step-by-step guide
- Ranking system display
- Download/App Store section
- Footer with links

## Deployment Options

### Option 1: GitHub Pages (Free & Easy)

1. Create a new repository on GitHub (or use existing)
2. Upload the `website` folder contents to the repository
3. Go to Settings → Pages
4. Select the branch and folder (`/root` or `/docs`)
5. Your site will be live at `https://yourusername.github.io/repository-name`

### Option 2: Netlify (Free & Recommended)

1. Go to [netlify.com](https://netlify.com) and sign up
2. Drag and drop the `website` folder
3. Your site will be live instantly
4. Add custom domain: Site settings → Domain management → Add custom domain → `wallstreetclash.com`

### Option 3: Vercel (Free)

1. Go to [vercel.com](https://vercel.com) and sign up
2. Import your GitHub repository or upload the `website` folder
3. Deploy automatically
4. Add custom domain in project settings

### Option 4: Traditional Web Hosting

1. Upload all files in the `website` folder to your web hosting via FTP/SFTP
2. Point your domain `wallstreetclash.com` to your hosting
3. Ensure `index.html` is in the root directory

## Domain Setup

To connect `wallstreetclash.com` to your hosting:

1. **Get DNS access** from your domain registrar
2. **Add DNS records**:
   - For GitHub Pages: Add CNAME record pointing to `yourusername.github.io`
   - For Netlify: Add A record or CNAME as instructed by Netlify
   - For Vercel: Add A/CNAME records as instructed by Vercel
   - For traditional hosting: Add A record pointing to your server IP

3. **Wait for DNS propagation** (can take up to 48 hours, usually much faster)

## Customization

### Update App Store Link
In `index.html`, find the App Store button and update the `href` attribute with your actual App Store URL when available.

### Update Contact Information
Edit the footer section in `index.html` to add your actual:
- Support email
- Social media links (Twitter, Discord, etc.)
- Privacy Policy and Terms of Service URLs

### Change Colors
Edit CSS variables in `styles.css` at the top (`:root` section) to customize:
- Primary colors
- Gradients
- Background colors
- Text colors

### Add Analytics
Add Google Analytics or other tracking by inserting the script tag in the `<head>` section of `index.html`.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Optimized CSS with minimal dependencies
- No external JavaScript libraries (vanilla JS)
- Fast loading times
- Smooth animations with CSS transforms

## Next Steps

1. **Add App Store URL** - Update the download button when your app is live
2. **Add Privacy Policy** - Create and link your privacy policy
3. **Add Terms of Service** - Create and link your terms
4. **Add Analytics** - Set up Google Analytics or similar
5. **Add SEO Meta Tags** - Enhance meta tags for better search visibility
6. **Add Favicon** - Create and add a favicon for your site
7. **Add Social Media Preview** - Add Open Graph tags for better social sharing

## Support

For questions or issues, contact support@wallstreetclash.com
