# Dark VPS Hosting - Website Setup

## Files Required:
1. `index.html` - Main website file
2. `sw.js` - Service worker file
3. `logo.jpg` - Your logo image (upload separately)
4. `IMG-20250829-WA0006.jpg` - Your QR code image (upload separately)

## Deployment Steps:

### 1. Prepare Files:
- Save `index.html` as your main HTML file
- Save `sw.js` as service worker file
- Prepare your `logo.jpg` (50x50 to 200x200 pixels recommended)
- Prepare your `IMG-20250829-WA0006.jpg` QR code image

### 2. Upload to GitHub:
Repository Structure:
├── index.html
├── sw.js
├── logo.jpg
└── IMG-20250829-WA0006.jpg
### 3. Deploy on Render:
1. Go to https://render.com
2. Sign up/login with GitHub
3. Click "New +" → "Static Site"
4. Connect your GitHub repository
5. Configure:
   - Name: darkvps-hosting
   - Branch: main/master
   - Build Command: (leave empty)
   - Publish Directory: (leave empty)
6. Click "Create Static Site"

### 4. Configure Custom Domain (Optional):
1. In Render dashboard, go to your static site
2. Click "Settings"
3. Scroll to "Custom Domains"
4. Add your domain: `darkvps.in`
5. Follow DNS configuration instructions

## Features Included:
✅ Dark VPS Hosting branding
✅ Logo image support (logo.jpg)
✅ UPI payment system
✅ QR code payment
✅ Monetag ads integration
✅ Analytics tracking
✅ Service worker for performance
✅ Mobile responsive design
✅ Contact forms
✅ Pricing plans
✅ Testimonials
✅ FAQ section

## Logo Requirements:
- File name must be: `logo.jpg`
- Supported formats: JPG, PNG, WebP
- Recommended size: 100×100 pixels
- Transparent background preferred

## Testing:
1. Open your deployed website
2. Check logo appears in header
3. Test order form
4. Verify payment details
5. Check mobile responsiveness

## Support:
For issues, contact: support@darkvps.in
