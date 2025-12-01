# EcoProw Website

Modern, responsive single-page website for EcoProw Seamless Surface Solutions featuring glassmorphism design, Three.js animated background, and comprehensive product information.

## Features

- **Animated Background**: Interactive Three.js geometric shapes with mouse tracking
- **Responsive Design**: Mobile-first approach with hamburger menu
- **Product Showcases**: ECOLAIN 18 and ECORAMIC 24 with detailed guides
- **Interactive Modals**: Step-by-step application guides and policy information
- **Contact Forms**: Career applications and general inquiry forms
- **Social Integration**: Links to Instagram, LinkedIn, Facebook, and WhatsApp
- **QR Code**: Automatic QR code generation for website URL

## Sections

1. **Home** - Hero section with call-to-action
2. **About** - Company information and mission
3. **Services** - Technical support, logistics, and consultation
4. **Products** - Premium adhesive products
5. **Gallery** - Product and team photos
6. **Timeline** - Company milestones
7. **Careers** - Job application form
8. **Contact** - Contact details and inquiry form

## Local Development

Start a local server to preview the website:

### Python
```bash
python -m http.server 8000
```

### Node.js
```bash
npx http-server -p 8000
```

### PHP
```bash
php -S localhost:8000
```

Then open your browser to `http://localhost:8000`

## Deployment Options

### GitHub Pages
1. Create a new repository on GitHub
2. Push this folder to the repository
3. Go to Settings → Pages
4. Select the branch and save
5. Your site will be live at `https://username.github.io/repository-name`

### Netlify
1. Visit [netlify.com](https://netlify.com)
2. Drag and drop this folder
3. Your site will be deployed in seconds
4. Configure custom domain if needed

### Traditional Hosting
Upload `index.html` to your web hosting provider via:
- FTP client (FileZilla, etc.)
- cPanel file manager
- Other hosting control panel

## File Structure

```
website_ecoprow/
├── index.html          # Main website file (self-contained)
└── README.md          # This file
```

## Technologies Used

- **HTML5** - Structure
- **Tailwind CSS** (CDN) - Styling framework
- **Three.js** (CDN) - 3D animated background
- **QRious** (CDN) - QR code generation
- **Font Awesome** (CDN) - Icons
- **Google Fonts** - Poppins typography

## External Dependencies

All dependencies are loaded via CDN, so no installation is required:
- Tailwind CSS
- Three.js r128
- QRious 4.0.2
- Font Awesome 6.0.0-beta3
- Google Fonts (Poppins)

## Features & Functionality

### Navigation
- Smooth scroll between sections
- Active section highlighting
- Mobile-responsive hamburger menu

### Forms
- Career application form with file upload
- Contact form with validation
- Success messages on submission

### Modals
- Product detail modals with step-by-step guides
- Policy modals (Privacy, Cookies, Terms, Returns)
- Keyboard support (ESC to close)

### Animations
- Three.js particle system background
- Hover effects on cards and buttons
- Smooth transitions and transforms

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Contact Information

**EcoProw Seamless Surface Solutions**
- Address: 1015 Katrol Ave, Robertville, Johannesburg, 1709, South Africa
- Email: info@ecoprow.co.za | sales@ecoprow.co.za
- Phone: +27 81 487 0717 (WhatsApp)

## License

© 2025 EcoProw Seamless Surface Solutions. All Rights Reserved.
