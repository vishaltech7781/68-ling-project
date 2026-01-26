# 68 Ling Yatra - Solapur Website

A comprehensive website for the 68 Ling Yatra pilgrimage in Solapur, Maharashtra. This website helps devotees and visitors navigate through all 68 sacred Shiva Lingams with location links to Google Maps.

## Features

- **Complete Directory**: Browse through all 68 lingams - just scroll to find any one
- **Google Maps Links**: Click on any location to open it in Google Maps (no API key needed!)
- **View Details**: Click "View Details" to see more information about each lingam
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Beautiful, user-friendly interface with smooth animations
- **No Setup Required**: Just open the HTML file - no API keys, no configuration!

## Getting Started

1. **Open `index.html`** in any web browser
2. Navigate using the top menu:
   - **Home**: Overview and statistics
   - **Directory**: Complete list of all 68 lingams
   - **About**: Information about the yatra

## How to Use

### Finding a Lingam:
1. Go to the **Directory** section
2. Scroll through the list of all 68 lingams
3. Click on the **location link** (📍 icon) to open it in Google Maps
4. Or click **"View Details"** for more information

### Opening in Google Maps:
- Click on any location link (marked with 📍)
- Or click **"Open in Google Maps"** button
- Google Maps will open in a new tab with the location

## File Structure

```
68lingproject/
├── index.html      # Main HTML structure
├── styles.css      # Styling and layout
├── script.js       # JavaScript functionality
└── README.md       # This file
```

## Technologies Used

- **HTML5**: Semantic structure
- **CSS3**: Modern styling with CSS variables and responsive design
- **JavaScript (ES6+)**: Interactive functionality
- **Google Maps Links**: Direct links to Google Maps (no API required)

## Features in Detail

### Lingam Directory
- **All 68 Lingams**: Complete list - no search needed, just scroll
- **Grid Layout**: Beautiful card-based layout
- **Each Card Shows**:
  - Lingam number
  - Name
  - Clickable location link (opens Google Maps)
  - View Details button
  - Open in Google Maps button

### Location Links
- **Clickable Links**: Every location is a clickable link
- **Google Maps Integration**: Opens directly in Google Maps
- **No API Key**: Uses simple Google Maps search links
- **Works Everywhere**: Works on desktop, mobile, and tablets

## Customization

### Colors
Edit CSS variables in `styles.css`:
```css
:root {
    --primary-color: #1a237e;
    --secondary-color: #d32f2f;
    --accent-color: #ff6f00;
    /* ... */
}
```

### Adding More Information
Edit the `lingamData` array in `script.js` to add more details to each lingam.

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Notes

- All 68 lingam data is included and displayed
- Location links use Google Maps search (no API key needed)
- Works completely offline for viewing (except when clicking map links)
- Simple and lightweight - no external dependencies

## License

Created for the betterment of Solapur and its devotees.

---

**Om Namah Shivaya**
