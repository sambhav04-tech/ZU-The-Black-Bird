# ZÜ : The Black Bird - Premium Spirits PWA

A premium Progressive Web App (PWA) for ZÜ The Black Bird luxury beverages. Experience where darkness meets refinement.

## 🚀 Quick Start

1. Clone or download this repository
2. Add your app icons to the `icons/` folder (see Icon Setup below)
3. Update the product image in `images/zu-energy-drink.jpg`
4. Deploy to GitHub Pages or your preferred hosting service

## 📁 Project Structure

```
zu-blackbird-app/
├── index.html              # Main HTML file
├── manifest.json           # PWA manifest
├── browserconfig.xml       # Microsoft Tiles config
├── README.md              # This file
├── .gitignore             # Git ignore rules
├── images/
│   └── zu-energy-drink.jpg # Product image
├── icons/                 # App icons (you need to create these)
│   ├── favicon.ico
│   ├── favicon-16x16.png
│   ├── favicon-32x32.png
│   ├── apple-touch-icon.png
│   ├── icon-72x72.png
│   ├── icon-96x96.png
│   ├── icon-128x128.png
│   ├── icon-144x144.png
│   ├── icon-152x152.png
│   ├── icon-192x192.png
│   ├── icon-384x384.png
│   ├── icon-512x512.png
│   ├── maskable-icon-192x192.png
│   ├── maskable-icon-512x512.png
│   └── ...more icon sizes
└── screenshots/           # PWA screenshots (optional)
    ├── desktop-screenshot-1.png
    └── mobile-screenshot-1.png
```

## 🎨 Icon Setup Guide

### Method 1: Create Icons Manually

Create the following icon files in the `icons/` folder:

#### Required Sizes:
- **favicon.ico** - 16x16, 32x32, 48x48 (multi-size ICO)
- **favicon-16x16.png** - 16×16px
- **favicon-32x32.png** - 32×32px
- **apple-touch-icon.png** - 180×180px
- **icon-192x192.png** - 192×192px
- **icon-512x512.png** - 512×512px

#### Additional Recommended Sizes:
- **icon-72x72.png** - 72×72px
- **icon-96x96.png** - 96×96px
- **icon-128x128.png** - 128×128px
- **icon-144x144.png** - 144×144px
- **icon-152x152.png** - 152×152px
- **icon-384x384.png** - 384×384px

#### Maskable Icons (for Android):
- **maskable-icon-192x192.png** - 192×192px (with safe zone)
- **maskable-icon-512x512.png** - 512×512px (with safe zone)

#### Microsoft Tiles:
- **mstile-70x70.png** - 70×70px
- **mstile-150x150.png** - 150×150px
- **mstile-310x150.png** - 310×150px (wide)
- **mstile-310x310.png** - 310×310px

### Method 2: Online Icon Generators (Recommended)

Use these free online tools to generate all required icons from one source image:

1. **RealFaviconGenerator** - https://realfavicongenerator.net/
   - Upload your logo/image
   - Customize settings for each platform
   - Download complete icon package

2. **Favicon.io** - https://favicon.io/
   - Simple favicon generator
   - Supports text-to-icon generation

3. **PWA Builder** - https://www.pwabuilder.com/imageGenerator
   - Microsoft's PWA icon generator
   - Creates all PWA-required icons

### Method 3: Use Your Product Image

If you want to use your existing `zu-energy-drink.jpg`:

1. Use online tools to resize it to different icon sizes
2. Convert to PNG format for better transparency support
3. Ensure the image works well at small sizes (16x16, 32x32)

## 📱 Icon Design Guidelines

### Design Specifications:
- **Format**: PNG (recommended) or ICO for favicons
- **Background**: Should work on both light and dark backgrounds
- **Content**: Clear, recognizable ZÜ branding
- **Style**: Square format, system will apply appropriate rounding
- **Safe Zone**: For maskable icons, keep important content in center 80%

### Color Recommendations:
- **Primary**: Black/Dark theme to match ZÜ branding
- **Accent**: White or gold accents
- **Background**: Transparent or solid black

## 🛠 Setup Instructions

### Step 1: Create Icons
1. Create an `icons/` folder in your project root
2. Generate icons using one of the methods above
3. Save all icon files in the `icons/` folder

### Step 2: Upload to GitHub
```bash
# Add all files to git
git add .

# Commit changes
git commit -m "Add app icons and PWA manifest"

# Push to GitHub
git push origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll to "Pages" section
4. Select source: "Deploy from a branch"
5. Choose branch: "main" and folder: "/ (root)"
6. Click "Save"

### Step 4: Test Your PWA
1. Visit your GitHub Pages URL: `https://yourusername.github.io/zu-blackbird-app/`
2. Test PWA installation on different devices
3. Verify icons appear correctly in browser tabs and home screen

## 🔧 Customization

### Update URLs
In `index.html`, replace `yourusername` with your actual GitHub username:
```html
<meta property="og:url" content="https://yourusername.github.io/zu-blackbird-app/">
```

### Modify Content
- Update product descriptions in the HTML
- Change contact email in footer
- Modify color scheme in CSS
- Add your own product images

### PWA Configuration
Edit `manifest.json` to customize:
- App name and description
- Theme colors
- Start URL
- Display mode
- Orientation

## 📊 Features

### ✨ Premium Features:
- **Progressive Web App** - Installable on all devices
- **Responsive Design** - Perfect on mobile, tablet, and desktop
- **Offline Support** - Works without internet connection
- **Fast Loading** - Optimized performance
- **Touch Gestures** - Mobile-optimized interactions
- **Dark Theme** - Premium dark aesthetic
- **Animations** - Smooth, elegant transitions
- **SEO Optimized** - Search engine friendly

### 🛡 Technical Features:
- Service Worker for offline functionality
- Web App Manifest for PWA installation
- Lazy loading for optimal performance
- Error handling and analytics ready
- Accessibility features
- Cross-browser compatibility

## 🎯 Browser Support

### PWA Installation Support:
- ✅ Chrome/Edge (Android & Desktop)
- ✅ Safari (iOS - Add to Home Screen)
- ✅ Firefox (Android)
- ✅ Samsung Internet
- ✅ Opera

### General Compatibility:
- All modern browsers
- iOS Safari 11.1+
- Android Chrome 40+
- Desktop browsers (Chrome, Firefox, Safari, Edge)

## 📈 Performance

### Optimization Features:
- Minified and optimized code
- Compressed images
- Efficient animations
- Lazy loading
- Service worker caching
- Preload critical resources

### Lighthouse Scores Target:
- Performance: 90+
- Accessibility: 95+
- Best Practices: 95+
- SEO: 95+
- PWA: 100

## 🚨 Troubleshooting

### Common Issues:

#### Icons Not Showing:
1. Verify all icon files exist in `icons/` folder
2. Check file names match exactly in HTML and manifest
3. Ensure PNG files are properly formatted
4. Clear browser cache and test again

#### PWA Not Installing:
1. Check HTTPS requirement (GitHub Pages provides HTTPS)
2. Verify manifest.json is valid JSON
3. Ensure service worker is registered
4. Test on different browsers/devices

#### Images Not Loading:
1. Check image paths are correct
2. Verify images exist in `images/` folder
3. Test image file format compatibility
4. Check file names for typos

### Debugging Tools:
- Chrome DevTools → Application → Manifest
- Chrome DevTools → Application → Service Workers
- Chrome DevTools → Lighthouse audit
- PWA testing: https://web.dev/measure/

## 📞 Support

For issues or questions:
- **Email**: zutheblackbird@gmail.com
- **GitHub Issues**: Create an issue in this repository

## 📄 License

© 2025 ZÜ : The Black Bird. All rights reserved.

---

**Enjoy responsibly. Experience the premium difference with ZÜ : The Black Bird.**
