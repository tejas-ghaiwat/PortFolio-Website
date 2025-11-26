# Tejas Ghaiwat - Personal Portfolio Website

[![Portfolio](https://img.shields.io/badge/Portfolio-Live-brightgreen)](https://yourportfolio.com)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

A modern, responsive personal portfolio website showcasing my skills, experiences, and projects as a Full Stack Developer specializing in AI and MERN Stack development.

## 🌟 Features

- **Responsive Design** - Fully responsive across all devices (desktop, tablet, mobile)
- **Smooth Animations** - Dynamic typing effects and smooth scroll animations
- **Interactive UI** - Sticky navbar, scroll-to-top button, and mobile hamburger menu
- **Contact Form** - Integrated contact form with Web3Forms
- **Skills Showcase** - Visual representation of technical skills with progress bars
- **Modern Styling** - Clean and professional design with custom CSS animations

## 🚀 Live Demo

Visit the live website : https://port-folio-website-ebon.vercel.app/

## 🛠️ Technologies Used

### Frontend
- **HTML5** - Semantic markup
- **CSS3** - Custom styling with animations and transitions
- **JavaScript** - Interactive functionality
- **jQuery** - DOM manipulation and AJAX

### Libraries & Plugins
- [Typed.js](https://github.com/mattboldt/typed.js/) - Typing animation effect
- [Owl Carousel](https://owlcarousel2.github.io/OwlCarousel2/) - Responsive carousel
- [Font Awesome](https://fontawesome.com/) - Icon library
- [Google Fonts](https://fonts.google.com/) - Poppins & Ubuntu fonts
- [Web3Forms](https://web3forms.com/) - Contact form backend

## 📋 Prerequisites

Before running this project, make sure you have:
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of HTML/CSS/JavaScript (for modifications)
- A code editor (VS Code recommended)

## ⚙️ Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/portfolio.git
cd portfolio
```

2. **Open the project**
   - Simply open `index.html` in your browser
   - Or use a local development server:
   
   Using VS Code Live Server:
   - Install Live Server extension
   - Right-click on `index.html`
   - Select "Open with Live Server"

   Using Python:
   ```bash
   python -m http.server 8000
   ```

3. **Customize the content**
   - Update personal information in `index.html`
   - Modify styles in `style.css`
   - Adjust animations in `script.js`

## 📁 Project Structure

```
portfolio/
│
├── index.html              # Main HTML file
├── style.css              # Custom CSS styles
├── script.js              # JavaScript functionality
├── TejasGhaiwat_SWE.pdf   # Resume PDF
│
├── images/
│   ├── banner.jpeg        # Hero section background
│   └── ProfileChoice.jpg  # Profile picture
│
└── README.md             # Project documentation
```

## 🎨 Customization Guide

### Update Personal Information

1. **Profile Section** (`index.html` lines 60-70)
   - Update name, title, and typed strings
   - Modify LinkedIn link

2. **About Section** (`index.html` lines 75-100)
   - Replace profile image
   - Update biography and skills
   - Link your resume

3. **Skills Section** (`index.html` lines 105-180)
   - Modify skill percentages
   - Add/remove technologies
   - Update coursework and soft skills

4. **Experience Section** (`index.html` lines 185-210)
   - Add your achievements
   - Update education details
   - Include project highlights

5. **Contact Information** (`index.html` lines 215-260)
   - Update email, phone, and location
   - Configure Web3Forms access key

### Styling Customization

**Color Scheme** (`style.css`)
```css
/* Primary color (currently crimson) */
--primary-color: crimson;

/* Accent color (currently greenyellow) */
--accent-color: greenyellow;
```

**Typography**
- Modify Google Fonts import at the top of `style.css`
- Update font families in respective sections

### Animation Speeds

Edit typing animation speeds in `script.js`:
```javascript
var typed = new Typed(".typing", {
    typeSpeed: 100,    // Adjust typing speed
    backSpeed: 60,     // Adjust backspace speed
    loop: true
});
```

## 📧 Contact Form Setup

The contact form uses Web3Forms. To set it up:

1. Visit [Web3Forms](https://web3forms.com/)
2. Create a free account and get your access key
3. Replace the access key in `index.html`:
```html
<input type="hidden" name="access_key" value="YOUR_ACCESS_KEY_HERE">
```

## 🌐 Deployment

### GitHub Pages

1. Push your code to GitHub
2. Go to repository Settings → Pages
3. Select main branch as source
4. Your site will be live at `https://yourusername.github.io/portfolio`

### Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run: `vercel`
3. Follow the prompts

### Netlify

1. Drag and drop your project folder to [Netlify Drop](https://app.netlify.com/drop)
2. Or connect your GitHub repository for continuous deployment

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Tejas Ghaiwat**

- LinkedIn: [@tejas-ghaiwat](https://linkedin.com/in/tejas-ghaiwat)
- Email: tejasghaiwat167@gmail.com
- Location: Nagpur, Maharashtra, India

## 🙏 Acknowledgments

- Font Awesome for icons
- Google Fonts for typography
- Web3Forms for contact form backend
- Inspiration from various portfolio designs

## 📊 Stats

![GitHub repo size](https://img.shields.io/github/repo-size/tejas-ghaiwat/portfolio)
![GitHub stars](https://img.shields.io/github/stars/tejas-ghaiwat/portfolio?style=social)
![GitHub forks](https://img.shields.io/github/forks/tejas-ghaiwat/portfolio?style=social)

---

⭐️ If you like this project, please give it a star on GitHub!

**Made with ❤️ by Tejas Ghaiwat**
