# Blockchain Developer Portfolio

A modern, interactive single-page portfolio website showcasing blockchain development projects and skills.

## ✨ Features

- **Animated Hero Section** with floating gradient blob background
- **Typewriter Effect** for dynamic subtitle animation
- **Interactive Project Grid** with hover effects and modal details
- **Modal System** with project details, technology tags, and screenshot support
- **Scroll Animations** with reveal-on-scroll effects
- **Accessibility Support** including ARIA attributes and keyboard navigation
- **Touch-Friendly Design** with optimized interactions for mobile devices
- **Modern CSS** with smooth animations and responsive design

## 🚀 Quick Start

### Option A: Direct File Opening (Quickest)
1. Double-click `Portfolio_website.html` in your file explorer
2. Or run from PowerShell:
   ```powershell
   Start-Process -FilePath "Portfolio_website.html"
   ```

### Option B: Local Server (Recommended)
For the most accurate preview with proper resource loading:

```bash
cd "path/to/your/portfolio/directory"
python -m http.server 8000
```

Then open your browser and navigate to: `http://localhost:8000/Portfolio_website.html`

## 📁 Project Structure

```
My_Portfolio/
├── Portfolio_website.html     # Main portfolio file
├── images/                    # Project screenshots (optional)
│   ├── voting.webp           # Voting system project image
│   ├── auction.webp          # Auction project image
│   └── scanner.webp          # Scanner project image
└── README.md                 # This file
```

## 🖼️ Adding Project Screenshots

To display project screenshots in the modal panels:

1. Create an `images/` folder next to `Portfolio_website.html`
2. Add screenshots with these specific names:
   - `voting.webp` or `voting.png`
   - `auction.webp` or `auction.png` 
   - `scanner.webp` or `scanner.png`

The system automatically tries WebP format first for better performance, falling back to PNG if unavailable.

## 🎯 Interactive Features

### Navigation
- **Keyboard Support**: Use Tab, Enter, and Space for navigation
- **Modal Controls**: Press Esc to close modals
- **Smooth Scrolling**: Click navigation links for smooth section transitions

### Animations
- **Typewriter Effect**: Animated subtitle in hero section
- **Scroll Reveals**: Projects and sections animate into view while scrolling
- **Hover Effects**: Interactive project cards with subtle animations
- **Tilt Effects**: Desktop-only subtle tilt interactions (disabled on touch devices)

## 🛠️ Technologies Used

- **HTML5** with semantic markup
- **CSS3** with modern features (Grid, Flexbox, Custom Properties)
- **Vanilla JavaScript** for interactions and animations
- **SVG Graphics** for project thumbnails and icons
- **WebP/PNG Images** for optimized screenshot display

## ♿ Accessibility

This portfolio includes comprehensive accessibility features:
- ARIA labels and attributes
- Keyboard navigation support
- Screen reader friendly structure
- Focus management for modal interactions
- High contrast design elements

## 📱 Responsive Design

- Mobile-first approach
- Touch-optimized interactions
- Adaptive layouts for all screen sizes
- Performance optimizations for mobile devices

## 🧪 Testing & Validation

The portfolio has been tested for:
- ✅ HTML/CSS/JavaScript syntax validation
- ✅ Cross-browser compatibility
- ✅ Responsive design across devices
- ✅ Accessibility standards compliance
- ✅ Performance optimization

### Manual Testing Checklist
- [ ] Page loads correctly
- [ ] Modal opens and closes properly
- [ ] Typewriter animation runs smoothly
- [ ] Cards reveal during scroll
- [ ] Keyboard navigation works
- [ ] All interactive elements respond correctly

## 🚀 Deployment

This is a static website that can be deployed to any web hosting service:

- **GitHub Pages**: Push to a GitHub repository and enable Pages
- **Netlify**: Drag and drop the file to Netlify
- **Vercel**: Import the repository or upload files
- **Traditional Web Hosting**: Upload `Portfolio_website.html` and `images/` folder

## 🔧 Customization

To customize the portfolio:

1. **Content**: Edit the HTML sections directly in `Portfolio_website.html`
2. **Styling**: Modify the CSS custom properties in the `<style>` section
3. **Projects**: Update the projects array in the JavaScript section
4. **Images**: Replace files in the `images/` folder with your own screenshots

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

For questions or suggestions about this portfolio:
- **GitHub**: [@Dawon-Mark-Lee](https://github.com/Dawon-Mark-Lee)
- **Portfolio**: [View Live Site](https://dawon-mark-lee.github.io/My_Portfolio/)



