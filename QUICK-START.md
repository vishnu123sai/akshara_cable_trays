# 🚀 QUICK START GUIDE - Akshara Cable Trays Website

## Welcome! 👋

Your complete Akshara Cable Trays website is ready to go. This guide will help you get started quickly.

---

## 📁 What You Have

A fully functional, responsive static website with:

### **11 Files Total:**
```
✅ index.html                    - Main homepage
✅ ladder-tray.html             - Ladder Cable Trays product page
✅ perforated-tray.html         - Perforated Cable Trays product page
✅ raceway.html                 - Cable Raceway Systems product page
✅ junction-box.html            - Cable Junction Boxes product page
✅ supports.html                - Tray Supports & Brackets product page
✅ style.css                    - Complete styling
✅ script.js                    - Interactive features
✅ README.md                    - Main documentation
✅ PRODUCT-CATALOG.md           - Complete product information
✅ TECHNICAL-SPECIFICATIONS.md  - Detailed technical specs
```

---

## 🎯 5 Products Included

### 1. **Ladder Cable Trays** 📊
- Heavy-duty with rung supports
- Load capacity: Up to 500kg/m
- Best for: Industrial, high-load applications
- Page: `ladder-tray.html`

### 2. **Perforated Cable Trays** 🔲
- Superior ventilation and drainage
- Load capacity: Up to 300kg/m
- Best for: Outdoor, wet environments
- Page: `perforated-tray.html`

### 3. **Cable Raceway Systems** 📦
- Fully enclosed cable management
- For: Professional indoor use
- Best for: Offices, data centers, retail
- Page: `raceway.html`

### 4. **Cable Junction Boxes** 🔳
- Secure cable connections and branching
- Sizes: Small to Extra Large + Custom
- Best for: Cable distribution and transitions
- Page: `junction-box.html`

### 5. **Tray Supports & Brackets** 🏗️
- Heavy-duty mounting systems
- Load capacity: 500kg - 1500kg per point
- Best for: Structural support and installation
- Page: `supports.html`

---

## 🚀 How to Use

### **Option 1: View Locally**
1. Double-click `index.html` to open in your browser
2. Click on product links to view detailed pages
3. Try the mobile menu on smaller screens
4. Test the contact form

### **Option 2: Upload to Web Hosting**
1. Create an FTP connection to your web server
2. Upload all files to your public_html folder
3. Visit your domain to access the website

### **Option 3: Deploy to Free Services**

#### **GitHub Pages (Free)**
```bash
1. Create GitHub account (if needed)
2. Create new repository: "akshara-cable-trays"
3. Upload all files
4. Enable GitHub Pages in settings
5. Access at: username.github.io/akshara-cable-trays
```

#### **Vercel (Free)**
```bash
1. Sign up at vercel.com
2. Connect your GitHub repository
3. Deploy automatically
4. Get custom domain option
```

#### **Netlify (Free)**
```bash
1. Sign up at netlify.com
2. Drag & drop your files, or connect GitHub
3. Website goes live instantly
4. Custom domain available
```

---

## ✏️ Quick Customization

### **Update Company Information**
Open `index.html` and find & replace:
- `+91 9133883496 / +91 9392408589` → Your phone numbers
- `info@akshara.com` → Your email address
- `Akshara Cable Trays` → Your company name (if different)

### **Change Colors**
In `index.html` and product pages, replace:
- `from-blue-600 to-blue-800` → Your primary color
- `text-blue-600` → Your accent color

**Popular color combinations:**
- Professional Blue: `from-blue-600 to-blue-800`
- Modern Purple: `from-purple-600 to-purple-800`
- Corporate Gray: `from-gray-700 to-gray-900`

### **Add Product Images**
Each product page has a placeholder:
```html
<img src="https://via.placeholder.com/400x300?text=Product+Name">
```

Replace with your images:
```html
<img src="images/product-name.jpg" alt="Product Name">
```

### **Update Contact Form**
The form currently shows an alert. To send actual emails:

> **WhatsApp button:** a green WhatsApp icon is fixed at the bottom‑right of every page. It links to `https://wa.me/1234567890` by default; update the number in each HTML file to your own international phone number before deployment.


**Using Formspree (Free):**
1. Go to formspree.io
2. Sign up and create a form
3. Copy the form ID
4. In `index.html`, update the form:
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

---

## 📱 Features Included

### **Mobile Responsive** ✓
- Works on phones, tablets, and desktops
- Hamburger menu for mobile
- Touch-friendly buttons

### **Interactive Elements** ✓
- Smooth scrolling navigation
- Hover effects on cards and buttons
- Mobile menu toggle
- Scroll animations
- Contact form validation

### **Professional Design** ✓
- Modern gradient backgrounds
- Color-coded product sections
- Clean typography
- Proper spacing and layout

### **SEO Ready** ✓
- Semantic HTML structure
- Meta tags included
- Organized heading hierarchy
- Alt text for images

### **Fast Loading** ✓
- Static HTML (no server-side processing)
- Optimized CSS and JavaScript
- Uses CDN for fonts and icons
- Minimal dependencies

---

## 📊 Website Structure

```
Homepage (index.html)
├── Navigation (all pages)
├── Hero Section
├── Features Section
├── Products Grid (links to detail pages)
├── About Section
├── Contact Section
└── Footer

Product Pages (5 pages)
├── Navigation
├── Breadcrumb
├── Product Hero
├── Key Features
├── Specifications & Dimensions
├── Applications
├── [Additional sections vary by product]
└── Footer
```

---

## 🎨 Customization Tips

### **Styling Changes**
- All styling is in `style.css`
- Most colors are in `index.html` as Tailwind classes
- Gradients can be easily changed
- Fonts are system fonts (no external download needed)

### **Content Updates**
- Product descriptions in each HTML file
- Specifications in tables (easy to update)
- Contact information in footer
- Company stats in about section

### **Add New Sections**
1. Copy an existing section from `index.html`
2. Modify the content
3. Update links in navigation
4. Style using Tailwind classes

---

## 🔧 Maintenance

### **Regular Updates**
- Update contact information quarterly
- Refresh product images seasonally
- Update testimonials/case studies
- Monitor and fix broken links

### **Performance**
- Optimize image files (compress)
- Test on different browsers
- Check mobile responsiveness
- Verify contact form functionality

### **Backup**
- Keep a backup of all files
- Version control (GitHub recommended)
- Document any custom changes

---

## 📚 Documentation Files

1. **README.md** - General project information
2. **PRODUCT-CATALOG.md** - Detailed product catalog with all specifications
3. **TECHNICAL-SPECIFICATIONS.md** - Engineering specs and standards
4. **QUICK-START.md** - This file

---

## 🆘 Common Issues & Solutions

### **Images Not Showing**
- Ensure image file paths are correct
- Use relative paths: `images/product.jpg`
- Check file extensions (.jpg, .png, .webp)
- Verify file sizes aren't too large

### **Links Not Working**
- Check filename spelling (case-sensitive on some servers)
- Ensure all files are in same directory
- Use correct relative paths
- Test on live server after upload

### **Form Not Sending Emails**
- By default, form shows alert message only
- Integrate Formspree, Netlify Forms, or EmailJS
- Check backend compatibility with your hosting

### **Website Looks Different on Mobile**
- Website is fully responsive
- Test on actual devices
- Check browser developer tools
- Verify viewport meta tag in HTML

---

## 🚀 Next Steps

1. ✅ **Customize content** with your company information
2. ✅ **Add real product images** replacing placeholders
3. ✅ **Set up email form** using Formspree or Netlify Forms
4. ✅ **Test thoroughly** on mobile and desktop
5. ✅ **Deploy to web hosting** or free services
6. ✅ **Set up analytics** (Google Analytics)
7. ✅ **Get custom domain** (if using Vercel/Netlify)

---

## 📞 Support

### **Get Help With:**
- Hosting & deployment questions
- Custom modifications
- Technical specifications
- Website optimization
- SEO improvements

### **Resources:**
- Tailwind CSS Documentation: tailwindcss.com
- Free Hosting: vercel.com, netlify.com
- Email Service: formspree.io
- Analytics: analytics.google.com

---

## 🎉 You're All Set!

Your Akshara Cable Trays website is complete and ready to:
- ✓ Showcase your products professionally
- ✓ Reach potential customers worldwide
- ✓ Provide detailed product information
- ✓ Capture leads through contact forms
- ✓ Build your brand online

**Start by opening `index.html` in your browser and exploring!**

---

**Made with ❤️ for Akshara Cable Trays**  
**© 2026 Akshara Cable Trays. All rights reserved.**
