# YSTN Proto Tech - Portfolio Website

## Overview
A modern, responsive portfolio website for YSTN Proto Tech, a custom electronics and IoT prototyping service. Built with Tailwind CSS for styling and vanilla JavaScript for interactivity.

## Features

✨ **Design & UX**
- Dark/Light theme toggle with localStorage persistence
- Fully responsive design (mobile-first approach)
- Modern gradient backgrounds and glowing effects
- Smooth scrolling and transitions
- Electric blue accent color (#00E5FF)

🔧 **Sections**
- **Header/Navbar**: Sticky navigation with mobile menu
- **Hero Section**: Eye-catching introduction with CTA buttons
- **Portfolio**: Showcase of custom electronics, ESP32, and academic projects
- **Project Request Form**: Comprehensive form for client inquiries
- **Contact Section**: Direct communication channels
- **Footer**: Copyright and branding

📱 **Responsive Breakpoints**
- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

## Tech Stack
- **HTML5**: Semantic markup
- **Tailwind CSS v3**: Utility-first CSS framework (via CDN)
- **FontAwesome 6.4.0**: Icon library
- **Google Fonts**: Inter typeface
- **Vanilla JavaScript**: Theme toggle, mobile menu, and interactions

## File Structure
```
.
├── index.html          # Main website file
├── README.md           # This file
└── assets/             # (Optional) For local images and files
```

## Installation & Deployment

### Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/yatharthjangra62-afk/YSTN_Proto.Tech.git
   cd YSTN_Proto.Tech
   ```

2. Open `index.html` in your browser or use a local server:
   ```bash
   python -m http.server 8000
   # or
   npx serve
   ```

### GitHub Pages Deployment
1. Go to repository settings → Pages
2. Select "main" branch as source
3. Click "Save"
4. Your site will be live at: `https://yatharthjangra62-afk.github.io/YSTN_Proto.Tech/`

### Other Hosting Options
- **Vercel**: Connect GitHub repo, auto-deploys on push
- **Netlify**: Similar to Vercel, drag-and-drop support
- **Firebase Hosting**: Google's free tier
- **Heroku**: Traditional server deployment

## Customization

### Theme Colors
Edit the Tailwind config in `<script>` tag:
```javascript
colors: {
    brandBlack: '#0B0F19',
    electricBlue: '#00E5FF',
    // ... modify as needed
}
```

### Contact Information
Update in multiple places:
- Header phone/email links
- Mobile menu
- Contact section

### Project Examples
Modify the portfolio section with your own projects and images.

## Features to Add
- [ ] Backend form submission (Node.js, Python Flask, etc.)
- [ ] Email notifications on form submit
- [ ] Blog section for case studies
- [ ] Client testimonials carousel
- [ ] Google Analytics integration
- [ ] Chatbot for instant support
- [ ] Project filtering by category
- [ ] Image optimization and WebP format

## Browser Support
- Chrome/Edge: Latest 2 versions
- Firefox: Latest 2 versions
- Safari: Latest 2 versions
- Mobile browsers: iOS 12+, Android 8+

## License
MIT License - Feel free to use and modify

## Contact
📞 +91 7982095215
📧 support.ystn_proto.tech@gmail.com

---
**Built by YSTN Proto Tech Team**