# St Anne's Prep Website - Demo

A complete static school website with WhatsApp integration and Google Maps.

## 📁 Files Included

- `index.html` - Homepage
- `about.html` - About the School page
- `academics.html` - Academic programs page
- `student-life.html` - Student activities page
- `gallery.html` - Photo gallery page
- `contact.html` - Contact page with form and map
- `styles.css` - All styling
- `script.js` - JavaScript for navigation and WhatsApp form
- `README.md` - This file

## 🚀 Quick Start

1. Extract all files to a folder
2. Open `index.html` in a web browser
3. The website works offline - no server needed!

## ✏️ How to Customize

### Change School Name and Details

1. **School Name**: Search for "St Anne's Prep" in all HTML files and replace with your school name
2. **Phone Number**: Replace `254743942030` with your WhatsApp number (format: country code + number, no + or spaces)
3. **Email**: Replace `info@stannesprep.ac.ke` with your email
4. **Location**: Replace "Githunguri, Machakos County, Kenya" with your address

### Update WhatsApp Number

The WhatsApp number appears in:
- Floating button on all pages
- Contact form submission (in `script.js`)
- Hero section links
- Footer links

Search for `254743942030` and replace everywhere.

### Update Colors (Optional)

Edit `styles.css` at the top (CSS Variables):
```css
:root {
    --primary-color: #1a5f7a;  /* Main color */
    --secondary-color: #d4a373; /* Secondary color */
    --accent-color: #e67e22;    /* Button color */
}
```

### Add Real Images

Replace the placeholder SVG images in `gallery.html` with actual images:

```html
<!-- Replace this: -->
<svg width="100%" height="100%" viewBox="0 0 400 300" fill="none">
    <rect width="400" height="300" fill="#e8f4f8"/>
    <text x="50%" y="50%" text-anchor="middle">Campus Image</text>
</svg>

<!-- With this: -->
<img src="images/campus.jpg" alt="Campus Image">
```

Create an `images` folder and add your photos.

### Update Google Maps

In `contact.html`, replace the map embed URL with your school's location:

1. Go to Google Maps
2. Search for your school address
3. Click "Share" → "Embed a map"
4. Copy the iframe code
5. Replace the existing iframe in `contact.html`

Or use this format:
```html
<iframe 
    src="https://www.google.com/maps/embed?pb=YOUR_EMBED_CODE_HERE"
    allowfullscreen="" 
    loading="lazy">
</iframe>
```

### Update Content

Edit the text in any HTML file:
- About page: Add your school's history, mission, values
- Academics: Describe your curriculum and programs
- Student Life: List your clubs, sports, activities
- Gallery: Add real images and update captions

## 📱 WhatsApp Integration

### How it Works

1. **Floating Button**: Always visible, links directly to WhatsApp
2. **Contact Form**: Collects info, formats it, and opens WhatsApp with pre-filled message
3. **CTA Buttons**: Throughout site link to WhatsApp with context-specific messages

### Customize WhatsApp Messages

In HTML files, find WhatsApp links like:
```html
https://wa.me/254743942030?text=Hello%20Sunrise%20Academy...
```

The text after `text=` is the pre-filled message (URL encoded). Customize as needed.

## 🗺️ Google Maps Setup

### Get Your Map Coordinates

1. Open Google Maps
2. Search for your school
3. Right-click on the location → "What's here?"
4. Note the coordinates (e.g., -1.100000, 36.950000)

### Update Map Link

In `contact.html` and footer links, update:
```html
<a href="https://www.google.com/maps/search/?api=1&query=YOUR_SCHOOL_NAME+YOUR_LOCATION">
```

## 📱 Mobile Responsive

The website automatically adjusts for:
- Desktop computers
- Tablets
- Mobile phones

Test on different devices to ensure everything looks good.

## 🎨 Design Features

- Clean, professional design
- WhatsApp floating button on all pages
- Smooth animations and transitions
- Mobile-friendly navigation
- Fast loading (no heavy frameworks)
- SEO-friendly structure

## 📋 Content Guidelines

When updating content:
- Keep paragraphs short (2-4 sentences)
- Use bullet points for lists
- Write in simple, clear language
- Avoid jargon or technical terms
- Be honest and specific (no exaggerations)

## 🔧 Technical Notes

- **No backend required**: Pure HTML/CSS/JS
- **No database**: All content in HTML files
- **Works offline**: Can be opened locally
- **Fast**: Optimized for quick loading
- **Compatible**: Works in all modern browsers

## 📞 Support

To update the website:
1. Edit HTML files for content changes
2. Edit `styles.css` for design changes
3. Edit `script.js` for functionality changes

No coding experience needed for basic text updates!

## 🚀 Deployment

To put online:
1. Choose a web hosting service (e.g., Netlify, Vercel, GitHub Pages - all have free options)
2. Upload all files
3. Your website will be live!

For custom domain (www.yourschool.com):
- Purchase domain from registrar
- Point domain to your hosting
- Follow hosting provider's instructions

## ✅ Checklist Before Going Live

- [ ] Replace all "St Anne's Prep" references
- [ ] Update WhatsApp number everywhere
- [ ] Update email address
- [ ] Update physical address
- [ ] Add real school images
- [ ] Update Google Maps location
- [ ] Test contact form
- [ ] Test all links
- [ ] Test on mobile devices
- [ ] Review all content for accuracy

---

**Note**: This is a demo website. Customize it with your actual school information before publishing online.
