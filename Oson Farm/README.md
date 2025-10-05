# Oson Farm Website

A modern, responsive website for Oson Farm inspired by One Acre Fund's design principles.

## Features

- **Modern Design**: Clean, professional layout with green color scheme
- **Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Interactive**: Smooth scrolling, animations, and form validation
- **Product Showcase**: Dynamic product grid with badges and icons
- **Contact Forms**: Order placement and contact forms with validation
- **Production Data**: Real-time farm production statistics

## File Structure

```
Oson Farm/
├── OsonFarmSite/
│   ├── index.html          # Main website file
│   └── images/             # Product images directory
└── README.md              # This file

oson.css                   # Main stylesheet (in root directory)
```

## How to Use

1. **View the Website**: Open `Oson Farm/OsonFarmSite/index.html` in your web browser
2. **Local Server** (recommended): 
   ```bash
   cd "Oson Farm/OsonFarmSite"
   python3 -m http.server 8000
   ```
   Then visit `http://localhost:8000`

## Sections

- **Home**: Hero section with call-to-action buttons
- **Products**: Dynamic grid of farm products with images and badges
- **Order**: Form to place orders for products
- **Production Data**: Real-time farm statistics
- **About Us**: Information about Oson Farm and testimonials
- **Contact**: Contact information and message form

## Customization

- **Colors**: Edit CSS variables in `oson.css` to change the color scheme
- **Products**: Modify the `products` array in the JavaScript section
- **Content**: Update text content directly in the HTML file
- **Images**: Add product images to the `images/` directory

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## Features Inspired by One Acre Fund

- Clean, professional design
- Green color scheme representing agriculture
- Focus on community and sustainability
- Clear call-to-action buttons
- Responsive grid layouts
- Modern typography and spacing