# His N Hers Mobile Detailing Website

A professional, responsive website for His N Hers Mobile Detailing - a mobile auto detailing service in Haslet, Texas.

## 🚀 Features

- **Responsive Design**: Mobile-first approach with perfect display on all devices
- **Professional Branding**: Custom color scheme and typography using Playfair Display & Inter fonts
- **SEO Optimized**: Meta tags, schema markup, sitemap, and keyword optimization for local search
- **Contact Forms**: Integrated with Formspree for easy form submissions
- **Online Booking**: Ready for Calendly or TidyCal widget integration
- **Performance Focused**: Optimized images, lazy loading, and minimal JavaScript
- **Accessibility**: WCAG compliant with proper contrast, focus states, and screen reader support

## 📁 File Structure

```
/
├── index.html          # Home page
├── about.html          # About page
├── services.html       # Services page
├── pricing.html        # Pricing page
├── contact.html        # Contact page
├── privacy.html        # Privacy Policy
├── terms.html          # Terms of Service
├── robots.txt          # Search engine directives
├── sitemap.xml         # XML sitemap
├── README.md           # This file
└── assets/             # Images and media (create this folder)
    ├── logo.png        # Company logo
    ├── about-photo.jpg # Team/owner photo
    └── ...             # Additional images
```

## 🎨 Brand Colors

- **Primary**: #1E40AF (Blue - trust/professionalism)
- **Secondary**: #0EA5E9 (Light Blue - freshness)
- **Accent**: #10B981 (Green - cleanliness)
- **Background**: #FFFFFF (White)
- **Text**: #0F172A (Dark)
- **Muted**: #F1F5F9 (Light Gray)

## ⚙️ Setup Instructions

### 1. Form Integration (Formspree)

1. Sign up at [Formspree.io](https://formspree.io)
2. Create a new form endpoint
3. Replace `XXXXXXXX` in the following files with your form ID:
   - `contact.html` (lines with `action="https://formspree.io/f/XXXXXXXX"`)

### 2. Calendar Booking Integration

Choose one of these options for online booking:

**Option A: Calendly**
1. Create a Calendly account and set up your availability
2. Get your Calendly embed code
3. Replace the placeholder in `contact.html` around line 290 with:
```html
<div class="calendly-inline-widget" data-url="https://calendly.com/your-link" style="min-width:320px;height:630px;"></div>
<script type="text/javascript" src="https://assets.calendly.com/assets/external/widget.js" async></script>
```

**Option B: TidyCal**
1. Create a TidyCal account
2. Replace the placeholder with:
```html
<iframe src="https://tidycal.com/your-link" width="100%" height="600"></iframe>
```

### 3. Google Analytics (Optional)

1. Create a Google Analytics 4 property
2. Uncomment and update the GA code in `index.html` (and other pages if desired)
3. Replace `GA_MEASUREMENT_ID` with your actual measurement ID

### 4. Images

Add these images to the `/assets/` folder:
- `logo.png` - Company logo (recommended: 200x80px)
- `about-photo.jpg` - Team or owner photo
- Additional service photos as desired

### 5. Social Media & Google Business

Update placeholder social media links in the footer:
- Replace `#` with actual Facebook, Instagram, and Google Business Profile URLs

## 🔧 Customization

### Business Hours
To change business hours, update in multiple locations:
- Footer contact info in all HTML files
- Schema.org markup in `index.html`
- Contact page content

### Service Areas
Update service areas in:
- `about.html` - Service Area section
- `contact.html` - Service Area map section
- Schema.org markup in `index.html`

### Pricing
Update prices in:
- `pricing.html` - Main pricing tables
- Service descriptions as needed

### Services
Modify services in:
- `services.html` - Main services content
- `index.html` - Services overview section
- `pricing.html` - Package descriptions

## 🚀 Deployment

### GitHub Pages
1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to Settings > Pages
4. Select source: Deploy from a branch
5. Choose main branch and / (root)
6. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Create a Netlify account
2. Drag and drop the entire folder to Netlify
3. Your site will get a random URL, which you can customize

### Custom Domain
For either platform:
1. Purchase a domain (recommended: something like `hisnhersmobiledetailing.com`)
2. Follow the platform's instructions to connect your custom domain
3. Update all absolute URLs in the code to match your domain

## 📱 Mobile Optimization

The site is built mobile-first and includes:
- Responsive navigation with mobile hamburger menu
- Sticky "Book Now" button on mobile
- Touch-friendly buttons and form elements
- Optimized images and fast loading times

## 🔍 SEO Features

- Local business schema markup
- Optimized meta titles and descriptions
- Keyword-rich content for "mobile detailing Haslet TX"
- XML sitemap and robots.txt
- Semantic HTML structure
- Image alt tags

## 📞 Contact Information

Current contact details (update as needed):
- **Phone**: (424) 209-5132
- **Email**: joshuacastro1@hotmail.com
- **Location**: Haslet, Texas
- **Hours**: Mon-Sat 8:00 AM - 6:00 PM

## 🛠️ Technical Stack

- **HTML5**: Semantic markup
- **CSS**: Tailwind CSS via CDN
- **JavaScript**: Vanilla JS (minimal, no frameworks)
- **Forms**: Formspree integration
- **Fonts**: Google Fonts (Playfair Display + Inter)
- **Icons**: SVG icons (no icon fonts)

## 📋 Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Mobile)
- Internet Explorer 11+ (with graceful degradation)

## 📄 Legal Pages

The site includes basic Privacy Policy and Terms of Service pages. **Important**: These are template documents and should be reviewed by a legal professional before use in a real business.

## 🎯 Performance

The site is optimized for:
- Google PageSpeed Insights scores 95+
- Fast loading times
- SEO best practices
- Accessibility standards

---

**Note**: This website is production-ready but remember to:
1. Add real business images
2. Configure form endpoints
3. Set up booking integration
4. Review legal documents with an attorney
5. Test all functionality before going live

For support or questions about this website, contact the development team.
