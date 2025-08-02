# Girlfriend Guide

A digital interactive flipbook containing relationship tips and advice for boyfriends. This project presents a humorous and practical guide in an engaging book format with page-turning animations.

## 🌟 Features

- **Interactive Flipbook**: Realistic page-turning animations using Turn.js
- **Responsive Design**: Works on desktop and mobile devices
- **Navigation**: 
  - Click/tap to turn pages
  - Use arrow keys for navigation
  - Slider control at the bottom
  - Mouse wheel support for page navigation
- **Beautiful Design**: Custom fonts and styling for an authentic book experience
- **40 Pages**: Full content with relationship tips and advice

## 🚀 Getting Started

### Prerequisites

- Modern web browser with JavaScript enabled
- No server setup required - can run directly from files

### Installation

1. Clone or download this repository
2. Open `index.html` in your web browser
3. Enjoy reading the Girlfriend Guide!

### Alternative Version

There's also a version in the `samples/girlfriend-guide/` directory which may contain additional features or variations.

## 🎮 How to Use

- **Page Navigation**: 
  - Click on the right side of the book to go forward
  - Click on the left side to go backward
  - Use left/right arrow keys
  - Drag the slider at the bottom
  - Use mouse wheel to scroll through pages

- **Zoom**: Click on the book to zoom in/out (if zoom feature is enabled)

## 🛠️ Technical Details

- **Built with**: HTML5, CSS3, JavaScript, jQuery
- **Animation Library**: Turn.js for flipbook functionality
- **UI Framework**: jQuery UI for slider component
- **Background**: Unicorn Studio for animated background effects
- **Responsive**: Uses modern CSS and viewport meta tags

### Key Libraries

- jQuery 1.7.0
- Turn.js (for page flipping)
- jQuery UI (for slider)
- Modernizr (for feature detection)
- jQuery MouseWheel (for scroll navigation)

## 📁 File Structure

```
├── index.html              # Main entry point
├── css/                    # Stylesheets
├── js/                     # JavaScript files
├── lib/                    # External libraries
├── fonts/                  # Custom fonts
├── pics/                   # Images and graphics
├── svgs/                   # SVG assets including logo
├── pages/                  # Individual page content
└── samples/                # Alternative implementation
    └── girlfriend-guide/   # Sample version
```

## 🎨 Customization

### Adding Content

- Page content is stored in the `pages/` directory
- Each page is an individual HTML file (page1.html, page2.html, etc.)
- SVG graphics for tips are in the `svgs/` directory

### Styling

- Main styles are in `css/girlfriend-guide.css`
- Font definitions and preloading in the HTML head
- Responsive breakpoints included

### Configuration

- Page count can be modified in the JavaScript (currently set to 40 pages)
- Animation settings can be adjusted in the Turn.js configuration

## 🌐 Browser Support

- Chrome/Chromium (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)


## 🤝 Contributing

This appears to be a personal/creative project. If you'd like to contribute improvements to the technical implementation, please feel free to submit issues or pull requests.

---