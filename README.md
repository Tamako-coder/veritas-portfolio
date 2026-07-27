# Verita Engineering - Company Website

A professional, responsive company website for Verita Engineering, showcasing services, projects, and company information. Built with vanilla HTML, CSS, and JavaScript for optimal performance and simplicity.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## ✨ Features

- **Pure HTML/CSS/JS**: No frameworks, fast loading times
- **Fully Responsive**: Works perfectly on all devices
- **SEO Optimized**: Includes sitemap.xml and robots.txt
- **Image Gallery**: Showcase projects and work
- **Contact Form**: Easy way for clients to reach out
- **Professional Design**: Clean, modern corporate aesthetic
- **Video Background**: Eye-catching hero section

## 🚀 Quick Start

### View Locally

1. Clone the repository:
```bash
git clone https://github.com/yourusername/verita-engineering.git
cd verita-engineering
```

2. Open `index.html` in your browser:
```bash
# On Mac
open index.html

# On Windows
start index.html

# On Linux
xdg-open index.html
```

Or use a local server (recommended):
```bash
# Python 3
python -m http.server 8000

# Node.js (with npx)
npx serve

# PHP
php -S localhost:8000
```

Then visit `http://localhost:8000`

## 📁 Project Structure

```
├── index.html              # Home page
├── styles.css              # Main stylesheet
├── script.js               # JavaScript functionality
├── robots.txt              # SEO robots file
├── sitemap.xml             # Site structure for search engines
├── Caddyfile              # Caddy server configuration
├── contact.vcf            # Contact vCard
├── about-us/
│   └── index.html         # About page
├── our-service/
│   └── index.html         # Services page
├── our-projects/
│   ├── index.html         # Projects page
│   └── *.webp             # Project images
├── gallery/
│   ├── index.html         # Photo gallery
│   └── *.webp             # Gallery images
├── contact-2/
│   └── index.html         # Contact page
└── assets/
    ├── logo.png           # Company logo
    ├── logo-768x133.webp  # Optimized logo
    ├── hero-bg.mp4        # Hero video background
    └── *.webp             # Various images
```

## 🎨 Pages

- **Home** (`/`) - Landing page with hero video and company overview
- **About Us** (`/about-us/`) - Company information and values
- **Our Services** (`/our-service/`) - Services offered
- **Our Projects** (`/our-projects/`) - Portfolio of completed work
- **Gallery** (`/gallery/`) - Photo gallery
- **Contact** (`/contact-2/`) - Contact information and form

## 🛠️ Technologies

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Flexbox/Grid
- **JavaScript** - Interactive elements
- **WebP Images** - Optimized image format for faster loading
- **MP4 Video** - Hero background video

## 🚢 Deployment

### Deploy to GitHub Pages (FREE)

1. Push your code to GitHub
2. Go to repository Settings → Pages
3. Select branch `main` and folder `/ (root)`
4. Click Save
5. Your site will be live at `https://yourusername.github.io/verita-engineering`

### Deploy to Netlify (FREE)

1. Drag and drop the project folder to [Netlify Drop](https://app.netlify.com/drop)
2. Your site is live instantly!

### Deploy to Vercel (FREE)

1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in the project folder
3. Follow the prompts

### Traditional Web Hosting

Upload all files via FTP to any web hosting provider:
- Hostinger
- Bluehost
- GoDaddy
- SiteGround
- etc.

## 📝 Customization

### Update Company Information

Edit the content directly in the HTML files:

**Logo**: Replace files in `/assets/`
```html
<img src="assets/logo.png" alt="Verita Engineering">
```

**Contact Info**: Edit in `contact-2/index.html` and `contact.vcf`

**Images**: Replace images in respective folders with same filenames, or update HTML references

### Modify Styles

Edit `styles.css` to change:
- Colors
- Fonts
- Layout
- Responsive breakpoints

### Add JavaScript Functionality

Edit `script.js` for:
- Form validation
- Interactive elements
- Animations
- Any custom functionality

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## 🔧 Server Configuration

The project includes a `Caddyfile` for Caddy server configuration. To use:

```bash
caddy run
```

For other servers (Apache/Nginx), standard configurations work fine.

## 📄 SEO

The site includes:
- ✅ `robots.txt` - Search engine crawling instructions
- ✅ `sitemap.xml` - Site structure for search engines
- ✅ Semantic HTML5 markup
- ✅ Optimized images (WebP format)
- ✅ Meta tags (add more in HTML `<head>` as needed)

## 📧 Contact

For inquiries about Verita Engineering:
- Import `contact.vcf` to your contacts app
- Visit the contact page on the website

## 📄 License

This project is proprietary and confidential.

## 👤 Developer

Website developed for Verita Engineering

---

© 2024 Verita Engineering. All rights reserved.
