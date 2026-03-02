# Akshara Cable Trays - Static Website

A beautiful, responsive static website for Akshara Cable Trays - Premium Cable Management Solutions.

## Features

✨ **Modern Design**
- Clean and professional UI with gradient accents
- Fully responsive design (mobile, tablet, desktop)
- Smooth animations and transitions
- Professional color scheme

## Contact Details

- **Phone:** +91 9133883496 / +91 9392408589
- **Email:** aksharacabletrays@gmail.com / sahithakshara@gmail.com
- **Office:** Plot No: 382,382, S.V.C.I.A, SVGIE, Hyderabad, Medchal‑500055


📱 **Mobile Friendly**
- Mobile-first responsive design
- Hamburger menu for mobile navigation
- Touch-friendly buttons and links
- Optimized viewport settings

🎨 **Interactive Elements**
- Smooth scrolling navigation
- Mobile menu toggle
- Contact form with validation
- Hover effects and animations
- Scroll animations for sections

🚀 **Performance**
- Static HTML - super fast loading
- No dependencies (uses Tailwind CDN)
- Optimized CSS and JavaScript
- Minimal file sizes

## Project Structure

```
├── index.html              # Main website homepage
├── ladder-tray.html        # Ladder Cable Trays product page
├── perforated-tray.html    # Perforated Cable Trays product page
├── raceway.html            # Cable Raceway Systems product page
├── junction-box.html       # Cable Junction Boxes product page
├── supports.html           # Tray Supports & Brackets product page
├── style.css               # Custom styles and animations
├── script.js               # Interactive functionality
├── PRODUCT-CATALOG.md      # Complete product catalog with specifications
└── README.md               # This file
```

## Website Pages

### Homepage (index.html)
- **Navigation** - Fixed header with mobile menu
- **Hero Section** - Eye-catching introduction with CTAs
- **Features** - Why choose Akshara Cable Trays
- **Products** - Quick links to all 5 product pages
- **About** - Company information and statistics
- **Contact** - Contact details and inquiry form
- **Footer** - Links and copyright information

### Product Pages
Each product has a dedicated page with:

1. **Ladder Cable Trays** (`ladder-tray.html`)
   - Heavy-duty ladder design with rung supports
   - Specifications and load ratings
   - Available sizes (Compact, Standard, Heavy Duty)
   - Industrial applications

2. **Perforated Cable Trays** (`perforated-tray.html`)
   - Superior ventilation and drainage design
   - Multiple perforation options (6mm, 8mm, 10mm)
   - Outdoor and wet environment suitability
   - IP65 weather protection

3. **Cable Raceway Systems** (`raceway.html`)
   - Enclosed cable management solutions
   - Material options (Steel, Aluminum, PVC)
   - Professional appearance for indoor use
   - EMI shielding available

4. **Cable Junction Boxes** (`junction-box.html`)
   - Secure cable connections and branching
   - Multiple sizes and types (Straight, Corner, Distribution)
   - Material comparison chart
   - IP rated protection options

5. **Tray Supports & Brackets** (`supports.html`)
   - Heavy-duty mounting systems
   - Load capacity ratings (500kg - 1500kg)
   - Multiple support types and angles
   - Fastening options and installation guides

## Files Included

### index.html
The main HTML file containing:
- Semantic HTML5 structure
- Tailwind CSS classes (via CDN)
- Complete page layout with all sections
- Accessibility considerations

### style.css
Custom CSS styles including:
- Navigation animations
- Card hover effects
- Form focus states
- Responsive media queries
- Accessibility preferences
- Print styles

### script.js
JavaScript functionality for:
- Mobile menu toggle
- Smooth scrolling
- Form handling
- Scroll animations
- Active navigation highlighting
- Card hover effects

## How to Use

### Quick Start
1. Open `index.html` in your web browser
2. The website will load immediately

### Customization

#### Update Company Information
Edit these sections in `index.html`:
- Company name and logo (navigation)
- Contact information (footer & contact section)
- Phone number and email (contact section)
- Company description and statistics (about section)

#### Change Colors
The website uses Tailwind CSS classes. Key colors:
- Primary: `blue-600` (used throughout)
- Gradients: `from-blue-600 to-blue-800`

To change colors, replace all instances of color classes in `index.html`

#### Add Product Images
Currently, all product pages use placeholder images from placeholder.com service. To add real product images:

1. **Replace placeholder images** in each HTML file:
   - Find: `<img src="https://via.placeholder.com/400x300?text=...">`
   - Replace with: `<img src="path/to/your/image.jpg">`

2. **Recommended image locations:**
   - Create an `images/` folder in the root directory
   - Organize images by product: `images/ladder-tray/`, `images/perforated/`, etc.

3. **Recommended image specifications:**
   - **Product hero images:** 400×300px or larger
   - **Format:** JPG (photos) or PNG (graphics)
   - **File size:** Optimize to under 100KB for fast loading

4. **Example directory structure:**
```
├── images/
│   ├── ladder-tray/
│   │   ├── main.jpg
│   │   └── specifications.jpg
│   ├── perforated-tray/
│   │   ├── main.jpg
│   │   └── outdoor-install.jpg
│   ├── raceway/
│   ├── junction-box/
│   └── supports/
```

#### Update Product Information
Modify the product cards in the "Products" section:
- Change product names
- Update descriptions
- Add new products by duplicating a card

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Responsive Breakpoints

- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

## Accessibility Features

- Semantic HTML structure
- ARIA-compatible
- Keyboard navigation support
- Color contrast compliance
- Focus indicators on interactive elements
- Prefers-reduced-motion support

## Performance Tips

1. Add images: Place images in an `images/` folder
2. Optimize images: Use JPEG for photos, PNG for graphics
3. Compress files: Use minifiers for production
4. Add analytics: Include tracking code in the footer
5. SEO: Update meta tags in the `<head>` section

## Hosting Options

This static website can be hosted on:
- GitHub Pages (free)
- Vercel (free)
- Netlify (free)
- AWS S3 + CloudFront
- Traditional web hosting
- Any static file hosting service

## Deployment Steps

1. Push files to GitHub repository
2. Connect to Vercel/Netlify
3. Deploy automatically on push

Or simply:
1. Upload files to your web hosting
2. Ensure files are in the public directory
3. Access via your domain

## Contact Form

The contact form is functional but currently shows an alert. To integrate with email:

### WhatsApp Shortcut 📱
A floating WhatsApp icon appears at the bottom‑right of every page. It uses `images/whatsapp.png` for the icon and links to `https://wa.me/919133883496?text=Hi` by default; **update the phone number and text if needed** in each HTML file to route chats to your account. You can replace the image with your own file if desired.

The link snippet you need is:
```html
<a href="https://wa.me/YOUR_NUMBER" target="_blank" class="fixed bottom-4 right-4 bg-green-500 hover:bg-green-600 text-white p-3 rounded-full shadow-lg z-50" aria-label="Chat on WhatsApp">
    <!-- SVG icon included in HTML files -->
</a>
```


### Option 1: Using Formspree
1. Go to formspree.io
2. Create an account
3. Update form action in HTML:
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

### Option 2: Using Netlify Forms
1. Deploy on Netlify
2. Add `netlify` attribute to form
3. Submissions go to Netlify dashboard

## Future Enhancements

- Add product detail pages
- Integrate email notifications
- Add image gallery/lightbox
- Implement blog section
- Add customer testimonials
- Integrate payment system
- Add live chat support
- Implement dark mode

## Support

For questions or customization help, contact your web developer.

## License

© 2026 Akshara Cable Trays. All rights reserved.
