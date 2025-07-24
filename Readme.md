# 🌟 Ernanda Revalino - Personal Portfolio Website

![Portfolio Preview](https://img.shields.io/badge/Status-Live-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=flat&logo=bootstrap&logoColor=white)

## 📋 Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Customization](#customization)
- [Contributing](#contributing)

**Live Demo:** [Your Portfolio URL Here]

## ✨ Features

- 📱 **Fully Responsive Design** - Works seamlessly on all devices
- 🎨 **Modern UI/UX** - Clean and professional design with smooth animations
- ⚡ **Fast Loading** - Optimized performance with lazy loading images
- 🎭 **Interactive Elements** - Animated skill bars, typing effect, and hover animations
- 📊 **Project Showcase** - Filterable portfolio gallery with lightbox
- 📧 **Contact Form** - Working contact form with PHP backend
- 🌙 **Dark Theme** - Elegant dark color scheme
- 🔄 **Smooth Scrolling** - Enhanced navigation experience
- 📈 **SEO Optimized** - Meta tags and semantic HTML structure

## 🛠 Tech Stack

### Frontend
- **HTML5** - Semantic markup structure
- **CSS3** - Modern styling with animations
- **JavaScript** - Interactive functionality
- **Bootstrap 5.3.7** - Responsive framework
- **AOS (Animate On Scroll)** - Scroll animations
- **Typed.js** - Typing animation effect
- **GLightbox** - Image lightbox gallery
- **Swiper.js** - Touch slider
- **Isotope** - Filterable layouts

### Fonts & Icons
- **Google Fonts** - Roboto, Ubuntu, Nunito
- **Bootstrap Icons** - Comprehensive icon library

### External Libraries
- **PureCounter** - Animated counters
- **Waypoints** - Scroll-triggered events

## 🚀 Installation

### Prerequisites
- Web server (Apache/Nginx) or local development server
- PHP support (for contact form functionality)

### Setup Instructions

1. **Clone the repository**
```bash
git clone https://github.com/ernandarevalino/portfolio-website.git
cd portfolio-website
```

2. **Launch the website**
```bash
# Using Python (simple HTTP server)
python -m http.server 8000

# Using PHP built-in server
php -S localhost:8000

# Using Node.js live-server
npx live-server
```

3. **Access the website**
Open your browser and navigate to `http://localhost:8000`

## 📁 Project Structure

```
portfolio-website/
│
├── index.html              # Main homepage
├── service-details.html    # Service details page
├── starter-page.html       # Template starter page
├── Readme.txt             # Template information
│
├── assets/
│   ├── css/
│   │   └── main.css       # Main stylesheet
│   ├── js/
│   │   └── main.js        # Main JavaScript file
│   ├── img/
│   │   ├── portfolio/     # Portfolio images
│   │   └── profile/       # Profile images
│   └── vendor/            # Third-party libraries
│       ├── bootstrap/
│       ├── aos/
│       ├── glightbox/
│       ├── swiper/
│       └── ...
│
└── forms/
    └── contact.php        # Contact form handler
```

## 🎨 Customization

### Updating Personal Information
1. **Edit `index.html`** - Update personal details, skills, and project information
2. **Replace images** - Add your photos to `assets/img/` directory
3. **Update social links** - Modify social media URLs in the header and footer
4. **Customize colors** - Edit CSS variables in `assets/css/main.css`

### Adding New Projects
1. Navigate to the Portfolio section in `index.html`
2. Add new portfolio items following the existing structure:
```html
<div class="col-lg-6 col-md-6 portfolio-item isotope-item filter-webdev">
  <div class="portfolio-wrap">
    <img src="path/to/your/image.jpg" class="img-fluid" alt="Project Name">
    <div class="portfolio-info">
      <div class="content">
        <span class="category">Category</span>
        <h4>Project Name</h4>
        <div class="portfolio-links">
          <a href="path/to/image.jpg" class="glightbox" title="Project Name">
            <i class="bi bi-plus-lg"></i>
          </a>
          <a href="project-url" title="More Details">
            <i class="bi bi-arrow-right"></i>
          </a>
        </div>
      </div>
    </div>
  </div>
</div>
```

### Modifying Skills
Update the skills section by editing the progress bars and percentages:
```html
<div class="skill-item">
  <div class="d-flex justify-content-between align-items-center">
    <h4>Skill Name</h4>
    <span class="skill-percentage">90%</span>
  </div>
  <div class="progress">
    <div class="progress-bar" role="progressbar" aria-valuenow="90"></div>
  </div>
  <div class="skill-tooltip">Skill description</div>
</div>
```

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**
```bash
git checkout -b feature/amazing-feature
```
3. **Commit your changes**
```bash
git commit -m 'Add some amazing feature'
```
4. **Push to the branch**
```bash
git push origin feature/amazing-feature
```
5. **Open a Pull Request**

### Contribution Guidelines
- Follow existing code style and structure
- Test your changes across different browsers
- Update documentation if necessary
- Ensure responsive design is maintained

## 🔧 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Opera (latest)

## ⚡ Performance Features

- **Lazy Loading** - Images load as needed
- **Minified Assets** - Compressed CSS and JS files
- **Optimized Images** - WebP format support
- **Caching** - Browser caching for static assets
- **CDN Integration** - Fast loading of external libraries

## 📱 Mobile Optimization

- Responsive breakpoints for all screen sizes
- Touch-friendly navigation
- Optimized images for mobile devices
- Fast loading on mobile networks

## 🎯 SEO Features

- Semantic HTML structure
- Meta tags for social sharing
- Alt tags for all images
- Structured data markup
- Sitemap ready

## 📈 Analytics Integration

Ready for integration with:
- Google Analytics
- Google Tag Manager
- Facebook Pixel
- Other tracking solutions

## 🔒 Security Features

- XSS protection in contact forms
- CSRF token support
- Input validation and sanitization
- Secure headers implementation

---

## 🚀 Quick Start Commands

```bash
# Clone and setup
git clone https://github.com/ernandarevalino/portfolio-website.git
cd portfolio-website

# Start development server
python -m http.server 8000
# or
php -S localhost:8000
# or
npx live-server

# Open in browser
open http://localhost:8000
```

⭐ **If you find this portfolio inspiring, please consider giving it a star!**

*Last updated: July 2025*
