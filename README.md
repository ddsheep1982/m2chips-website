# M2chips Technologies - Company Website

A modern, responsive company website for M2chips Technologies, an enterprise Ethernet solutions provider.

## 📋 Overview

This website showcases M2chips Technologies' products, solutions, and company information based on their company presentation. The site features:

- **Company Profile**: About M2chips, management team, and deployment areas
- **Product Portfolio**: Ethernet controllers, network adapters, and detailed specifications
- **Solutions**: Cloud/Data Center, Network Security, and Industrial/Embedded solutions
- **Product Roadmap**: Technology evolution from 25GbE to 100GbE
- **Contact Form**: For business inquiries and technical support

## 🚀 Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Smooth scrolling, hover effects, fade-in animations
- **SEO-Friendly**: Semantic HTML5 structure
- **Fast Loading**: Optimized CSS and JavaScript

## 📁 File Structure

```
m2chips-website/
├── index.html          # Main HTML file
├── styles.css          # All styling and responsive design
├── script.js           # Interactive functionality
├── images/             # Company images from PPT
│   ├── image1.jpeg
│   ├── image2.png
│   ├── image3.png
│   ├── image4.wdp
│   └── image5.png
└── README.md          # This file
```

## 🎨 Design Elements

### Color Scheme
- **Primary Color**: #0B1F3B (Dark Blue)
- **Secondary Color**: #4F46E5 (Indigo)
- **Accent Color**: #C7D2FE (Light Blue)
- **Background**: #E8F0FF (Light Background)

### Typography
- **Headings**: Aptos Display
- **Body Text**: Aptos, Segoe UI

## 📦 Content Sections

### 1. Hero Section
- Company name and tagline
- Call-to-action buttons

### 2. About Company
- Core capabilities and focus areas
- Million-unit shipments highlight
- Deployment areas (4 key markets)

### 3. Management Team
- 4 key executives with backgrounds
- Team composition statistics
- R&D department breakdown

### 4. Product Portfolio
- **Ethernet Controllers**: MS5025, MS5040, MS6100 (planned)
- **Network Adapters**: FF5025, FF5040, FF6100 series
- Product spotlight on MS5025
- Technology roadmap table

### 5. Customer Expectations
- Throughput & Latency
- Security & Manageability
- Software Ecosystem
- Timing & Sync

### 6. Solutions & Use Cases
- Cloud / Data Center solutions
- Network Security applications
- Industrial / Embedded deployments

### 7. Why M2chips
- Architecture to Silicon to NIC approach
- Performance roadmap (25G/40G production, 100G planned)
- Security-ready features (SM2/SM3/SM4)

### 8. Contact
- Contact information
- Interactive contact form
- Email addresses for different departments

## 🌐 How to Use

### Option 1: Open Directly
Simply open `index.html` in any modern web browser:
```bash
open index.html
```

### Option 2: Use a Local Server
For better performance, use a local web server:

**Using Python:**
```bash
# Python 3
python -m http.server 8000

# Then visit: http://localhost:8000
```

**Using Node.js (http-server):**
```bash
npx http-server -p 8000
```

**Using PHP:**
```bash
php -S localhost:8000
```

## 🔧 Customization

### Updating Content
- Edit `index.html` to modify text content
- Update sections by changing the HTML structure

### Changing Colors
- Modify CSS variables in `styles.css`:
```css
:root {
    --primary-color: #0B1F3B;
    --secondary-color: #4F46E5;
    /* ... more variables */
}
```

### Adding Images
- Place images in the `images/` folder
- Reference them in HTML: `<img src="images/your-image.jpg">`

### Modifying Layout
- Grid layouts can be adjusted in `styles.css`
- Most sections use CSS Grid for responsive design

## 📱 Responsive Breakpoints

- **Desktop**: > 768px
- **Tablet**: 481px - 768px
- **Mobile**: < 480px

## ✨ Interactive Features

1. **Smooth Scrolling**: Navigation links scroll smoothly to sections
2. **Fade-in Animations**: Elements fade in as you scroll
3. **Hover Effects**: Cards and buttons have interactive hover states
4. **Active Navigation**: Current section is highlighted in navigation
5. **Counter Animation**: Statistics animate when scrolling into view
6. **Parallax Hero**: Hero section has subtle parallax effect

## 🔍 SEO Considerations

- Semantic HTML5 tags
- Proper heading hierarchy (h1, h2, h3)
- Meta tags included
- Alt text for images (when added)
- Fast loading times

## 📄 Source Information

Content sourced from M2chips Technologies internal materials and public reference pages (February 2026).

## 🚀 Deployment

To deploy this website:

1. **Static Hosting** (GitHub Pages, Netlify, Vercel):
   - Push to Git repository
   - Connect to hosting service
   - Deploy automatically

2. **Traditional Hosting**:
   - Upload all files via FTP
   - Ensure directory structure is maintained
   - Set index.html as default document

3. **CDN Deployment**:
   - Upload to S3/Cloud Storage
   - Configure CloudFront/CDN
   - Set appropriate cache headers

## 📞 Contact Form Integration

The contact form currently shows an alert. To make it functional:

1. Add a backend API endpoint
2. Update the form submission handler in `script.js`
3. Consider using services like:
   - FormSpree
   - Netlify Forms
   - EmailJS
   - Custom backend API

Example integration:
```javascript
contactForm.addEventListener('submit', async (e) => {
    e.preventDefault();
    const formData = new FormData(contactForm);

    await fetch('YOUR_API_ENDPOINT', {
        method: 'POST',
        body: JSON.stringify(Object.fromEntries(formData)),
        headers: { 'Content-Type': 'application/json' }
    });
});
```

## 🎯 Future Enhancements

- [ ] Add actual company logo image
- [ ] Integrate real team photos
- [ ] Add product images/diagrams
- [ ] Implement backend for contact form
- [ ] Add language switcher (English/Chinese)
- [ ] Create blog/news section
- [ ] Add case studies/testimonials
- [ ] Implement analytics tracking
- [ ] Add live chat support
- [ ] Create downloadable product datasheets

## 📝 License

Copyright © 2026 M2chips Technologies. All rights reserved.

## 🤝 Support

For technical support or inquiries:
- Email: support@m2chips.com
- Sales: sales@m2chips.com
- General: info@m2chips.com
