# Psychological Healing Center - Website Rebuild

A clean, modern rebuild of the Psychological Healing Center website featuring Mind Map Therapy.

## 🎯 What's New

- **Modern, clean design** with professional styling
- **Fully responsive** layout that works on all devices
- **Improved structure** with clear sections and navigation
- **Better typography** using Google Fonts (Inter + Playfair Display)
- **Smooth animations** and hover effects
- **Accessible** color scheme with good contrast
- **Fast loading** with optimized CSS

## 📁 File Structure

```
psychologicalhealingcenter.com/
├── index.html          # Main HTML file
├── styles.css          # All styling
├── README.md          # This file
└── images/            # All images from original site
    ├── logo.png       # Site logo
    ├── encoding-wound.gif
    ├── encoding-reactions.gif
    ├── encoding-core-beliefs.gif
    ├── decoding-chaos.gif
    ├── decoding-defenses.gif
    ├── decoding-breakthrough.gif
    ├── recoding-paradigm.gif
    ├── recoding-unity.gif
    └── recoding-future.gif
```

## 🎨 Design Features

### Color Palette
- **Primary**: Deep blue (#2C5F7F) - Professional, trustworthy
- **Accent**: Warm peach (#E8A87C) - Approachable, healing
- **Text**: Dark gray tones for readability
- **Backgrounds**: Light grays and whites for clean look

### Typography
- **Headings**: Playfair Display (serif) - elegant, authoritative
- **Body**: Inter (sans-serif) - modern, highly readable

### Sections
1. **Navigation** - Sticky header with smooth scroll links
2. **Hero** - Eye-catching intro with clear CTA buttons
3. **Mission** - Brief overview of purpose
4. **Process** - Three-phase journey (Encoding → Decoding → Recoding)
5. **Features** - Three key benefits with icons
6. **Free Assessment CTA** - Highlighted conversion point
7. **Courses** - Five course offerings in grid layout
8. **Testimonials** - Client success stories
9. **Final CTA** - Consultation booking
10. **Footer** - Links and copyright

## 🚀 Deployment

**Current Deployments:**
- **Vercel**: https://psychologicalhealingcenter-lewslnmhx.vercel.app
- **GitHub Pages**: https://mperlmutter83.github.io/psychological-healing-center/
- **Repository**: https://github.com/mperlmutter83/psychological-healing-center

### Other Hosting Options
You can also deploy to:
- **Netlify** (drag & drop)
- **Cloudflare Pages** (fast CDN)

### Option 2: Traditional Hosting
1. Upload both files to your web host via FTP/SFTP
2. Ensure `index.html` is in the root directory
3. `styles.css` should be in the same folder

### Option 3: Test Locally
```bash
# Simple Python server
python3 -m http.server 8000

# Or use Node.js
npx serve
```
Then visit `http://localhost:8000`

## 🔧 Customization Guide

### Change Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2C5F7F;    /* Main brand color */
    --accent-color: #E8A87C;     /* Accent/highlight color */
    --text-dark: #1A1A1A;        /* Main text */
}
```

### Update Content
All content is in `index.html`. Search for specific text and replace:
- Contact information
- Course descriptions
- Testimonials
- Assessment links

### Add Links
Replace `#` placeholders with actual URLs:
- Assessment download link
- Course enrollment pages
- Consultation booking link
- Social media links

### Add Images
To add images:
1. Create an `images/` folder
2. Add your images there
3. Update HTML with image tags:
```html
<img src="images/your-image.jpg" alt="Description">
```

## 📱 Mobile Responsive

The site is fully responsive with breakpoints at:
- Desktop: 1200px+
- Tablet: 768px - 1199px
- Mobile: < 768px

Test on different devices or use browser dev tools (F12 → Device toolbar).

## ✅ Next Steps

1. **Content Review**: Update all text to match current offerings
2. **Add Real Links**: Replace `#` with actual URLs
3. **Images**: Add professional photos/graphics
4. **Forms**: Integrate contact/assessment forms
5. **Analytics**: Add Google Analytics or similar
6. **SEO**: 
   - Add meta descriptions
   - Set up Open Graph tags
   - Create sitemap.xml
7. **Legal**: Add privacy policy and terms pages

## 🔗 Links to Configure

Before going live, update these:
- [ ] Free assessment download
- [ ] Course enrollment pages  
- [ ] Consultation booking system
- [ ] Contact form/email
- [ ] Social media profiles
- [ ] Privacy policy
- [ ] Terms of service

## 🎯 SEO Checklist

- [x] Semantic HTML structure
- [x] Descriptive page title
- [x] Meta description
- [ ] Open Graph tags
- [ ] Schema.org markup
- [ ] XML sitemap
- [ ] robots.txt
- [ ] Favicon
- [ ] Image alt tags (add when images added)

## 📞 Support

For questions about customization or deployment, refer to:
- HTML/CSS documentation: [MDN Web Docs](https://developer.mozilla.org/)
- Hosting platforms have detailed guides
- Web design communities for inspiration

---

**Built with**: HTML5, CSS3, Google Fonts  
**License**: All content rights reserved by Psychological Healing Center  
**Last Updated**: June 2024