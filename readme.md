# Keling Studio - Digital Transformation Agency Website

**Version 2.0** - Optimized & Enhanced

## 🚀 About Keling Studio

Keling Studio is a digital transformation agency based in Yogyakarta, Indonesia, specializing in:
- **Web Development** (Company Profiles, E-Commerce, Landing Pages, Custom Applications)
- **Branding & Design** (Logo Design, Brand Guidelines, Social Media Design, Marketing Collateral)
- **Digital Marketing** (Social Media Management, SEO, Digital Advertising, Email Marketing)

**Mission**: *"Bridging the Gap: Transforming Your Business to Digital Success"*

---

## ✨ Features

- ✅ Fully responsive design (mobile-first)
- ✅ SEO optimized with Open Graph and Twitter Cards
- ✅ Lazy loading images for better performance
- ✅ Integrated pricing packages section
- ✅ Newsletter subscription with FormSubmit.co
- ✅ Google Analytics ready
- ✅ Accessibility-focused (ARIA labels, keyboard navigation)
- ✅ Smooth scrolling navigation
- ✅ Client testimonials slider
- ✅ WhatsApp integration for direct contact
- ✅ Progressive Web App (PWA) ready

---

## 📁 Project Structure

```
kelingstudio/
├── index.html              # Main homepage
├── thank-you.html          # Thank you page (newsletter)
├── styles.html             # Style guide (if needed)
├── readme.md               # This file
├── CONFIGURATION.md        # Detailed configuration guide
├── site.webmanifest        # PWA manifest
├── css/
│   ├── styles.css         # Custom styles (4989 lines)
│   └── vendor.css         # Third-party CSS (Swiper, GLightbox)
├── js/
│   ├── main.js            # Custom JavaScript (702 lines)
│   └── plugins.js         # Third-party JS (Swiper, GLightbox)
└── images/
    ├── avatars/           # Testimonial avatars
    ├── gallery/           # Gallery images
    │   └── large/
    └── icons/             # Icon assets
```

---

## 🛠️ Quick Setup

### 1. Clone or Download

```bash
git clone https://github.com/yourusername/kelingstudio.git
cd kelingstudio
```

### 2. Configure Essential Settings

**a) Update Google Analytics** ([index.html](index.html)):
- Replace `GA_MEASUREMENT_ID` with your actual Google Analytics ID

**b) Update Email for Newsletter** ([index.html](index.html)):
- Find the form: `<form id="mc-form" ...>`
- Replace `kelingstudio@gmail.com` with your email
- Verify email on first submission to FormSubmit.co

**c) Update Social Media Links** ([index.html](index.html)):
- Find all social media URLs and update with your handles:
  - Facebook: `https://www.facebook.com/keling.studio`
  - Instagram: `https://www.instagram.com/keling.studio/`
  - Twitter, LinkedIn, Pinterest, etc.

**d) Update Contact Information**:
- WhatsApp number: `6285142965211`
- Email: `kelingstudio@gmail.com`
- Business address (footer section)

**e) Update Meta Tags** ([index.html](index.html)):
- `<meta property="og:url" content="https://kelingstudio.com/">` - Change to your domain
- `<meta property="og:image" ...>` - Upload and link your social sharing image (1200x630px)

### 3. Test Locally

Simply open `index.html` in a web browser or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

Navigate to `http://localhost:8000` in your browser.

### 4. Deploy

**Options:**
- **Netlify**: Drag & drop folder or connect Git repo
- **Vercel**: Connect Git repo for automatic deployment
- **GitHub Pages**: Enable in repository settings
- **Traditional Hosting**: Upload via FTP

---

## 📋 Configuration Guide

For detailed configuration instructions, see [CONFIGURATION.md](CONFIGURATION.md)

**Key sections:**
- SEO setup and optimization
- Google Analytics integration
- Newsletter form configuration
- Social media links
- Pricing section customization
- Performance optimization tips
- Security recommendations

---

## 🎨 Customization

### Colors
Primary color scheme defined in CSS variables:
- Gold: `#d4af37`
- Dark: `#151515`
- Light gray: `#f8f8f8`

### Fonts
- **Headings**: Playfair Display (Serif)
- **Body**: Roboto Flex (Sans-Serif)

### Pricing Packages
Located in `index.html` - Pricing section:
- **Starter**: Starting at $500
- **Professional**: Starting at $1,500 (Popular)
- **Enterprise**: Custom quote

Edit the HTML to update prices, features, and package details.

---

## 📱 Contact Information

**Keling Studio**
- 📧 Email: kelingstudio@gmail.com
- 📱 WhatsApp: +62 851-4296-5211
- 📍 Location: Jl. Kaswari no 84, Yogyakarta, Indonesia
- 🌐 Website: [kelingstudio.com](https://kelingstudio.com)

**Social Media:**
- Instagram: [@keling.studio](https://www.instagram.com/keling.studio/)
- Facebook: [Keling Studio](https://www.facebook.com/keling.studio)
- LinkedIn: [Keling Studio](https://www.linkedin.com/company/keling-studio)

---

## 🧪 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

**Note**: Lazy loading images requires modern browsers. Older browsers will load images normally.

---

## 📊 Performance

### Optimization Features:
- Lazy loading images
- Minification ready (CSS/JS)
- Efficient JavaScript (vanilla JS, no heavy frameworks)
- Optimized animations and transitions
- Responsive images with srcset

### Lighthouse Score Goals:
- Performance: 90+
- Accessibility: 95+
- Best Practices: 95+
- SEO: 95+

---

## 🔐 Security

### Current Implementation:
- HTTPS ready (configure on server)
- Form validation
- FormSubmit.co spam protection

### Recommended Additions:
- Content Security Policy (CSP)
- Rate limiting on forms
- Regular security updates

---

## 🐛 Known Issues & Fixes

### Issue: Newsletter form doesn't send
**Fix**: Verify email with FormSubmit.co (check spam folder for verification email)

### Issue: Google Analytics not tracking
**Fix**: Replace `GA_MEASUREMENT_ID` with actual tracking ID

### Issue: Images not loading
**Fix**: Check image paths are relative to index.html

---

## 🚀 Deployment Checklist

Before going live:

- [ ] Update all placeholder content
- [ ] Configure Google Analytics
- [ ] Verify FormSubmit.co email
- [ ] Update all social media links
- [ ] Test newsletter form submission
- [ ] Test all WhatsApp links
- [ ] Optimize and compress images
- [ ] Add favicon files
- [ ] Test mobile responsiveness
- [ ] Check all internal links
- [ ] Verify SEO meta tags
- [ ] Test on multiple browsers
- [ ] Enable HTTPS
- [ ] Submit sitemap to Google Search Console

---

## 📈 Future Enhancements

Planned features (see CONFIGURATION.md for details):
1. Portfolio/Case Studies section
2. Blog for content marketing
3. Online booking system
4. Multi-language support (EN/ID)
5. Live chat integration
6. Client portal

---

## 📚 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS Grid and Flexbox
- **Vanilla JavaScript** - No framework dependencies
- **Swiper.js** - Testimonial slider
- **GLightbox** - Image gallery lightbox
- **FormSubmit.co** - Newsletter form handling
- **Google Analytics** - Website analytics
- **Font Awesome** - Icon library (SVG)

---

## 🎓 Credits

- **Original Design**: [StyleShout](https://styleshout.com/) - Lounge Template
- **Distributed by**: [ThemeWagon](https://themewagon.com)
- **Customization & Optimization**: Keling Studio Team (2026)

---

## 📄 License

- Design and Code: Copyright © [StyleShout](https://styleshout.com/)
- Licensed under [MIT License](https://opensource.org/licenses/MIT)
- Free for personal and commercial use

---

## 🤝 Contributing

Found a bug or want to contribute? Feel free to:
1. Fork the repository
2. Create a feature branch
3. Submit a pull request

Or contact us directly:
- Email: kelingstudio@gmail.com
- WhatsApp: +62 851-4296-5211

---

## 📝 Changelog

### Version 2.0 (February 2026)
- ✅ Added SEO optimization (Open Graph, Twitter Cards)
- ✅ Integrated Google Analytics
- ✅ Updated all social media links
- ✅ Replaced MailChimp with FormSubmit.co
- ✅ Added image lazy loading
- ✅ Improved accessibility (alt texts, ARIA labels)
- ✅ Added pricing/packages section
- ✅ Enhanced CTAs throughout the site
- ✅ Created thank-you page
- ✅ Updated navigation menu
- ✅ Comprehensive documentation added

### Version 1.0 (Original)
- Basic company profile website
- Service listings
- Contact information
- Testimonials slider

---

## 📞 Support

Need help with setup or customization?

**Contact Keling Studio:**
- 📧 kelingstudio@gmail.com
- 💬 WhatsApp: +62 851-4296-5211
- 🌐 [www.kelingstudio.com](https://kelingstudio.com)

---

**Built with ❤️ by Keling Studio**

*Empowering businesses through digital technology*


