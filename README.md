# Mohd Kaif - Portfolio Website

A modern, responsive portfolio website showcasing my skills, projects, and experience as a Full-Stack Developer and Entrepreneur.

## 🚀 Live Demo

Visit the live website: [https://mohd-kaif-portfolio.netlify.app](https://mohd-kaif-portfolio.netlify.app)

## ✨ Features

- **Responsive Design**: Works perfectly on all devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Smooth scrolling, hover effects, and animations
- **Contact Form**: Direct email functionality for inquiries
- **Project Showcase**: Detailed project cards with live demos
- **Skills Display**: Comprehensive technology stack showcase
- **Dark Theme Support**: Optimized for both light and dark preferences

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Custom CSS with Flexbox and Grid
- **Icons**: Font Awesome
- **Fonts**: Google Fonts (Inter)
- **Deployment**: Netlify

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── send_email.php      # Email handling (optional)
├── netlify.toml        # Netlify configuration
├── _redirects          # Netlify redirects
├── package.json        # Project metadata
└── README.md           # This file
```

## 🚀 Deployment

### Deploy to Netlify

1. **Fork/Clone this repository**
2. **Connect to Netlify**:
   - Go to [Netlify](https://netlify.com)
   - Click "New site from Git"
   - Connect your GitHub account
   - Select this repository
   - Deploy settings are pre-configured

3. **Manual Deploy**:
   - Drag and drop the project folder to Netlify
   - Or use Netlify CLI: `netlify deploy --prod`

### Deploy to Other Platforms

- **Vercel**: `vercel --prod`
- **GitHub Pages**: Push to `gh-pages` branch
- **Firebase**: `firebase deploy`

## 🔧 Local Development

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Kaif9927/portfolio.git
   cd portfolio
   ```

2. **Start local server**:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

3. **Open in browser**: `http://localhost:8000`

## 📧 Contact Form Setup

The contact form uses a fallback system:

1. **Primary**: PHP backend (requires server with PHP)
2. **Fallback**: Opens default email client

To enable PHP email:
1. Ensure `send_email.php` is uploaded
2. Configure your server's mail settings
3. Update the email address in `send_email.php`

## 🎨 Customization

### Personal Information
- Update personal details in `index.html`
- Replace placeholder images with your photos
- Modify the hero section content

### Styling
- Edit `styles.css` for custom colors and fonts
- Update the color scheme in CSS variables
- Modify animations and transitions

### Projects
- Add/remove projects in the projects section
- Update project links and descriptions
- Add new technology tags

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Contact

**Mohd Kaif**
- Email: Mohdkaifa909@gmail.com
- Phone: +91-9193581958
- LinkedIn: [Mohd Kaif](https://www.linkedin.com/in/mohd-kaif-12762b256)
- GitHub: [@Kaif9927](https://github.com/Kaif9927)
- LeetCode: [Kaif909](https://leetcode.com/u/Kaif909/)

---

⭐ Star this repository if you found it helpful!