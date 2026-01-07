# 15627 Sudsbury Circle - Real Estate Listing Website

A modern, professional real estate listing website for a premium vacant lot in Truckee, CA.

## Property Overview
- **Address:** 15627 Sudsbury Circle, Truckee, CA 96161
- **Price:** $345,000
- **Size:** 0.47 acres
- **Type:** Vacant Land - Residential Lot

## Website Structure

The site consists of 4 main pages:

1. **index.html** - Listing home page with hero section, quick stats, and property overview
2. **plans.html** - Architectural plan detail page showcasing the included home design
3. **gallery.html** - Photo gallery with lightbox functionality
4. **details.html** - Complete property details and specifications

## Features

- Modern, clean design with professional aesthetics
- Fully responsive layout for all devices
- Interactive photo gallery with lightbox
- Comprehensive property information display
- Easy navigation between all pages
- Professional color scheme and typography

## Adding Your Photos

### For the Gallery Page (gallery.html)

To add your actual property photos to the gallery:

1. Place your images in the `images/` folder
2. Open `gallery.html` in a text editor
3. Find the gallery items (they currently have colored placeholder backgrounds)
4. Replace the placeholder `<div class="gallery-placeholder">` with an `<img>` tag

Example:
```html
<!-- Replace this: -->
<div class="gallery-item" onclick="openLightbox(0)">
    <div class="gallery-placeholder">
        <div style="text-align: center;">
            <p style="font-size: 1.5rem; margin-bottom: 0.5rem;">📸</p>
            <p>Lot Overview</p>
        </div>
    </div>
</div>

<!-- With this: -->
<div class="gallery-item" onclick="openLightbox(0)">
    <img src="images/your-photo-name.jpg" alt="Lot Overview">
</div>
```

### For the Hero Section (index.html)

To add a main hero image to the home page:

1. Place your best hero image in the `images/` folder
2. Open `index.html`
3. Find the `.hero` section
4. Look for the inline style with `background: linear-gradient...`
5. Replace the data URI with your image path:

```css
background: linear-gradient(rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.4)), 
            url('images/your-hero-image.jpg');
```

Or update the CSS in `styles.css` at line ~84.

### For Architectural Plans (plans.html)

Add your architectural plan images:

1. Place plan images in the `images/` folder
2. Open `plans.html`
3. Find the placeholder sections for floor plans and elevations
4. Replace the placeholder divs with actual images

## Viewing the Site

Simply open `index.html` in any modern web browser to view the site locally.

## Customization

- **Colors:** Edit the CSS variables in `styles.css` (lines 7-16)
- **Contact Information:** Update the footer sections in each HTML file
- **Text Content:** Edit the HTML files directly to modify any text

## Technology Stack

- Pure HTML5
- CSS3 with CSS Grid and Flexbox
- Vanilla JavaScript for gallery functionality
- No external dependencies - fully self-contained

## Browser Compatibility

Compatible with all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

---

Created January 2026
Truckee lot marketing page
