# iPhone 17 Pro Max Landing Page

Complete standalone HTML landing page for iPhone 17 Pro Max rewards campaign.

## Folder Structure

```
final-html-site/
├── index.html
├── css/
│   └── styles.css
└── images/
    ├── screenshot-202026-01-05-20171917.png
    └── image.png
```

## Features

- Responsive design optimized for mobile and desktop
- Clean, simple layout matching DoorDash reference design
- Trustpilot rating display with 8.6 score and 2653 reviews
- Two step sections: How to Claim and How to Redeem
- Direct affiliate link to gloffers.org
- SEO optimized with meta tags
- Accessible HTML with ARIA labels

## How to Deploy

### Option 1: Traditional Web Host (cPanel, FTP)
1. Upload all files maintaining the folder structure
2. Ensure `index.html` is in the root directory
3. Keep `css/` and `images/` folders intact

### Option 2: Netlify
1. Drag and drop the entire `final-html-site` folder to Netlify
2. Site goes live immediately

### Option 3: Vercel
1. Run: `vercel --prod`
2. Or upload via Vercel dashboard

### Option 4: GitHub Pages
1. Create a new repository
2. Upload all files
3. Enable GitHub Pages in repository settings

## Testing Locally

Simply open `index.html` in your web browser. No server required.

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Updates

To update the affiliate link, edit line 83 in `index.html`:
```html
onclick="window.open('YOUR_NEW_LINK_HERE', '_blank', 'noopener,noreferrer')"
```

To update Trustpilot score, edit the HTML in the trustpilot section and adjust the star partial clip-path in CSS.
```
</md>
