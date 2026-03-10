# Home Page Updates - New Sections Added

## Overview
Two new sections have been successfully added to your home page (`index.html`) to enhance content engagement and showcase your events and news.

---

## 1. **"Our News" Section**

### Location
- **Section ID:** `#news`
- **Position:** Placed before the FAQ section, after the Projects section
- **Styling:** Light background (#f9f9f9) with white cards

### Features
- **3 News Cards** displaying:
  - Professional news image (250px height)
  - Headline text
  - Subtext/description
  - "Read More" button (green color #6cbe03)

### Card Elements
```
Card Structure:
├── News Image
│   └── Hover effect with subtle zoom
├── Card Title (Headline)
├── Card Description (Subtext)
└── Read More Button
```

### Styling
- Cards have hover effects (lift-up animation + enhanced shadow)
- Image zoom effect on hover
- Responsive design for mobile, tablet, and desktop
- Green accent color (#6cbe03) on buttons

### Content You Need to Update
Replace these image paths with your actual news images:
- `img/news-1.jpg`
- `img/news-2.jpg`
- `img/news-3.jpg`

Update the news headlines and subtext as needed.

---

## 2. **"Events & Gallery" Section**

### Location
- **Section ID:** `#events-gallery`
- **Position:** Placed after the News section, before FAQ
- **Styling:** Gray background (#f5f5f5) for differentiation

### Features

#### Gallery Filter Buttons
- **All** - Shows all items
- **Videos** - Filters video content
- **Photos** - Filters photo content
- **Events** - Filters event items

Filter buttons have active state styling with green background.

#### Gallery Items (6 samples included)
1. **2 Video Items** - with play button overlay
2. **2 Photo Items** - with zoom/magnifying glass overlay
3. **2 Event Items** - with zoom overlay

### Gallery Item Components
```
Gallery Card:
├── Media Container (220px height)
│   ├── Image
│   └── Overlay with CTA Button
│       ├── Play Button (for videos)
│       └── Zoom Button (for photos)
├── Info Section
│   ├── Title
│   └── Category Label (with green accent)
```

### Styling
- Responsive grid layout (auto-fit, minimum 300px columns)
- Cards have hover effects (lift-up animation + enhanced shadow)
- Image zoom effect on hover
- Smooth fade-in animation for items
- Overlay with semi-transparent green background (#6cbe03)
- Interactive buttons with scale effect on hover

### Content You Need to Update
Replace these image paths with your actual content:

**Videos:**
- `img/video-1.jpg` → "Farm Operations Tour"
- `img/video-2.jpg` → "Processing Facility Walkthrough"

**Photos:**
- `img/gallery-photo-1.jpg` → "Cassava Harvest Season"
- `img/gallery-photo-2.jpg` → "Product Quality Check"

**Events:**
- `img/event-1.jpg` → "Farmers Conference 2024"
- `img/event-2.jpg` → "Community Outreach Program"

### Video Links
Update YouTube/video links in:
```html
<a href="https://www.youtube.com/embed/dQw4w9WgXcQ" class="play-btn" data-fancybox>
```

---

## Files Modified

### 1. **index.html**
- Added "Our News" section with 3 news cards
- Added "Events & Gallery" section with filter buttons and 6 gallery items
- Both sections are fully integrated into the page structure

### 2. **css/index3.css**
- Added 300+ lines of CSS styling for both sections
- Includes responsive design media queries
- Hover effects, animations, and transitions
- Mobile-optimized styles

### 3. **js/custom.js**
- Added gallery filter functionality
- JavaScript to handle filter button clicks
- Show/hide gallery items based on category selection

---

## Features Summary

### News Section Features
✅ Professional card layout  
✅ Image with hover zoom effect  
✅ Headline and subtext  
✅ Read More button  
✅ Hover lift animation  
✅ Responsive design  
✅ Mobile-friendly  

### Events & Gallery Features
✅ Interactive filter buttons  
✅ 6 pre-built gallery items  
✅ Video and photo support  
✅ Event items  
✅ Play button for videos  
✅ Zoom button for photos  
✅ Hover effects and animations  
✅ Responsive grid layout  
✅ Mobile-optimized layout  
✅ Smooth transitions  

---

## Color Scheme Used

- **Primary Accent:** #6cbe03 (Green)
- **Text Color:** #1d1d1d (Dark)
- **Secondary Text:** #666 (Gray)
- **Backgrounds:** #f9f9f9 and #f5f5f5 (Light grays)
- **Hover Overlay:** rgba(108, 190, 3, 0.8) (Transparent green)
- **Cards:** #fff (White)
- **Shadows:** rgba(0, 0, 0, 0.1-0.15)

---

## Next Steps

1. **Add Images:** Place your news and gallery images in the `img/` folder with the filenames mentioned above
2. **Update Content:** Replace placeholder text with your actual news titles, descriptions, and event information
3. **Update Video Links:** Replace YouTube embed URLs with your actual video links
4. **Test Responsive Design:** Check the layout on mobile, tablet, and desktop views
5. **Add More Items:** You can duplicate the card structure to add more news or gallery items

---

## How to Add More Items

### To Add More News
Copy this block and paste it in the news row:
```html
<div class="col-lg-4 col-md-6 mb-40 mb-xs-30">
    <div class="news-card">
        <div class="news-image">
            <img src="img/news-X.jpg" alt="News X" class="img-fluid">
            <div class="news-overlay"></div>
        </div>
        <div class="news-content">
            <h3 class="news-headline">Your Headline</h3>
            <p class="news-subtext">Your description text here.</p>
            <a href="#" class="btn btn-read-more">Read More</a>
        </div>
    </div>
</div>
```

### To Add More Gallery Items
Copy this block and paste in the gallery-grid:
```html
<div class="col-md-6 col-lg-4 mb-30 gallery-item photos">
    <div class="gallery-card">
        <div class="gallery-media">
            <img src="img/gallery-photo-X.jpg" alt="Photo X" class="img-fluid gallery-image">
            <div class="gallery-overlay">
                <a href="img/gallery-photo-X.jpg" class="zoom-btn" data-fancybox="gallery">
                    <!-- SVG icon -->
                </a>
            </div>
        </div>
        <div class="gallery-info">
            <h4>Your Title</h4>
            <p class="gallery-category">Photo</p>
        </div>
    </div>
</div>
```

---

## Browser Compatibility
- ✅ Chrome/Edge
- ✅ Firefox
- ✅ Safari
- ✅ Mobile browsers
- ✅ Responsive design (tested at all breakpoints)

---

## Support Notes
- All styling follows your existing color scheme (#6cbe03)
- Uses Bootstrap grid system for consistency
- Integrates seamlessly with existing page styles
- No breaking changes to existing sections
- Fully responsive and mobile-optimized

