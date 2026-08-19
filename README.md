# ChinaPatchFactory - Custom Patches Manufacturer

A professional, SEO-friendly website for custom patches wholesale business. Built with pure HTML, CSS, and JavaScript - no frameworks required. Perfect for GitHub Pages hosting.

![ChinaPatchFactory Screenshot](screenshot.png)

## Features

- **SEO Optimized**: Complete meta tags, structured data, Open Graph, Twitter Cards
- **Responsive Design**: Mobile-first approach, works on all devices
- **Fast Loading**: No heavy frameworks, optimized images with lazy loading
- **Interactive**: Smooth scroll, animations, FAQ accordion, tabs, product filters
- **Quote Form**: Ready-to-use contact form with validation
- **Multi-language Ready**: Currently in English, easy to add more languages
- **Blog System**: Full blog with categories, featured posts, and article pages
- **Product Catalog**: Product listing with filters and detailed product pages

## Website Structure

### Main Pages

1. **Home Page** (`index.html`)
   - Hero Section with CTA
   - Products showcase (8 types)
   - Size Guide with interactive tabs
   - Backing Options (6 types)
   - Why Choose Us
   - Process explanation
   - Testimonials
   - FAQ accordion
   - Quote Form
   - Contact information

2. **Products Page** (`product.html`)
   - Filter by category (Embroidered, Woven, PVC, Leather, Specialty)
   - Sort by price/name
   - 8 product cards with details
   - Quick quote buttons

3. **Blog Page** (`blog.html`)
   - Category filters
   - Featured article
   - Article grid with pagination
   - Newsletter subscription

### Detail Pages

4. **Product Detail** (`product/Embroidered-Patches/Embroidered-Patches-Demo.html`)
   - Image gallery with thumbnails
   - Product specifications
   - Pricing tables
   - Customer reviews
   - FAQ section
   - Related products

5. **Blog Article** (`blog/blog-1.html`)
   - Full article content
   - Table of contents sidebar
   - Related articles
   - Social sharing
   - Author information

## SEO Features

- Semantic HTML5 structure
- Meta descriptions and keywords
- Open Graph tags for social sharing
- Twitter Card support
- Structured data (Schema.org):
  - Organization
  - Product
  - BlogPosting
  - BreadcrumbList
  - AggregateRating
- Canonical URLs
- Alt text for all images
- Semantic heading hierarchy
- Breadcrumb navigation
- Fast page load speed
- Mobile-friendly design

## File Structure

```
patchhub/
├── index.html                              # Home page
├── product.html                            # Products listing page
├── blog.html                               # Blog listing page
├── product/
│   └── Embroidered-Patches/
│       └── Embroidered-Patches-Demo.html   # Product detail example
├── blog/
│   └── blog-1.html                         # Blog article example
├── css/
│   └── style.css                           # All styles (3000+ lines)
├── js/
│   └── main.js                             # All JavaScript
├── .github/
│   └── workflows/
│       └── deploy.yml                      # GitHub Actions auto-deploy
├── README.md                               # This file
└── CNAME                                   # Custom domain (optional)
```

## Getting Started

### Local Development

Simply open `index.html` in your browser:

```bash
# Using Python's simple server
python -m http.server 8000

# Or using Node.js http-server
npx http-server

# Or using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000`

### Deploy to GitHub Pages

1. **Create a new repository** on GitHub
2. **Upload these files** to your repository
3. **Enable GitHub Pages**:
   - Go to repository Settings
   - Scroll to "Pages" section
   - Select source: "Deploy from a branch"
   - Select branch: "main"
   - Select folder: "/ (root)"
   - Click Save
4. **Your site will be live** at `https://yourusername.github.io/repository-name`

### Custom Domain (Optional)

1. Add a `CNAME` file with your domain name
2. Configure DNS settings with your domain provider
3. Update the canonical URL in all HTML files

## Customization

### Update Contact Information

Edit these sections in all HTML files:
- Email: `cocohan520@gmail.com`
- Phone: `+86 138-XXXX-XXXX`
- Address: `KunShan, China`
- Social media links

### Update Pricing

Modify prices in the Products section:
```html
<span class="price-value">$0.17</span>
```

### Update Images

Replace Unsplash URLs with your own images:
```html
<img src="your-image-url.jpg" alt="Description">
```

### Update Colors

Edit CSS variables in `css/style.css`:
```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #f59e0b;
    --accent-color: #10b981;
}
```

### Add New Products

1. Copy `product/Embroidered-Patches/Embroidered-Patches-Demo.html`
2. Rename folder and file appropriately
3. Update content, images, and pricing
4. Add link in `product.html`

### Add New Blog Posts

1. Copy `blog/blog-1.html`
2. Rename file (e.g., `blog-2.html`)
3. Update article content
4. Add to `blog.html` grid

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- 100/100 PageSpeed Insights (estimated)
- < 1s First Contentful Paint
- Optimized for Core Web Vitals
- Lazy loading images
- Minified CSS and JS ready
- Mobile-optimized

## License

MIT License - feel free to use for your business!

## Support

Need help customizing? Contact us at cocohan520@gmail.com

---

**Made with ❤️ for patch manufacturers worldwide**
