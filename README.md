# 🚀 Professional Portfolio Website

A modern, responsive, and feature-rich portfolio website showcasing professional experience, skills, projects, and certifications. Built with pure HTML, CSS, and JavaScript with a focus on beautiful UI/UX design and smooth user experience.

![Portfolio Preview](https://img.shields.io/badge/Status-Live-success) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## ✨ Features

### 🎨 Design & User Experience
- **Modern UI/UX Design**: Clean, professional, and visually appealing interface
- **Dark Mode Toggle**: Seamless light/dark theme switching with persistent preference
- **Smooth Animations**: Elegant fade-in, scroll-reveal, and hover animations
- **Responsive Design**: Fully responsive layout optimized for all devices (desktop, tablet, mobile)
- **Glassmorphism Effects**: Modern glass-like navigation bar with backdrop blur
- **Gradient Accents**: Beautiful gradient color schemes throughout the website

### 📱 Sections
1. **Hero Section**: Eye-catching introduction with animated content and professional photo
2. **About Me**: Personal introduction with statistics and professional image
3. **CV Download**: Quick access to download resume/CV
4. **Experience**: Timeline-based work experience showcase
5. **Skills & Expertise**: Interactive skill bars with progress indicators
6. **Certifications**: Visual display of professional certifications
7. **Projects**: Portfolio of featured projects with links and descriptions
8. **Contact**: Contact form and social media links

### 🛠️ Technical Features
- **Pure HTML/CSS/JavaScript**: No framework dependencies
- **Smooth Scrolling**: Enhanced navigation with smooth scroll behavior
- **Intersection Observer**: Scroll-triggered animations for better performance
- **Local Storage**: Theme preference persistence
- **Mobile Menu**: Hamburger menu with smooth slide animations
- **Custom Scrollbar**: Styled scrollbar matching the design theme
- **Font Awesome Icons**: Professional iconography throughout

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: 
  - Flexbox & Grid Layout
  - CSS Animations & Transitions
  - Custom Properties (CSS Variables)
  - Backdrop Filters
  - Gradient Effects
- **JavaScript (ES6+)**:
  - DOM Manipulation
  - Event Listeners
  - Local Storage API
  - Intersection Observer API
- **Font Awesome 6.0**: Icon library
- **Google Fonts**: 
  - Inter (Body text)
  - Poppins (Headings)

## 📁 Project Structure

```
portfolio2/
│
├── index.html              # Main HTML file
├── styles.css              # All CSS styles and animations
├── README.md               # Project documentation
│
├── Images/
│   ├── mahbub.jpg          # Hero section profile image
│   ├── mahbub2.jpg         # About section image
│   ├── weather-pro.png     # Weather app project image
│   ├── port-pro.png        # Portfolio project image
│   ├── pro.jpg             # AI Food app project image
│   ├── ai.jpg              # AI certification image
│   └── [certificate images] # Certification documents
│
└── Documents/
    └── nibir_cv .pdf       # Resume/CV document
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, for development)

### Installation

1. **Clone the repository** (or download the project)
   ```bash
   git clone <repository-url>
   cd portfolio2
   ```

2. **Open the project**
   - Simply open `index.html` in your web browser, OR
   - Use a local development server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (http-server)
     npx http-server
     
     # Using PHP
     php -S localhost:8000
     ```

3. **Access the website**
   - Open your browser and navigate to `http://localhost:8000` (if using a server)
   - Or directly open `index.html` in your browser

## 📖 Usage

### Navigation
- **Desktop**: Use the top navigation menu to jump between sections
- **Mobile**: Tap the hamburger menu (☰) to access navigation
- **Smooth Scrolling**: All navigation links use smooth scroll behavior

### Dark Mode
- Click the moon/sun icon in the navigation bar to toggle between light and dark themes
- Your preference is automatically saved and will persist on page reload

### Download CV
- Click the "CV" button in the navigation bar to download the resume
- Or visit the "Download CV" section for more information

### Contact Form
- Fill out the contact form in the Contact section
- Connect via social media links provided

## 🎨 Customization

### Changing Personal Information

1. **Update Hero Section** (`index.html`):
   ```html
   <h1 class="hero-title">
       Hi, I'm <span class="highlight">Your Name</span>
   </h1>
   <p class="hero-subtitle">Your Title</p>
   ```

2. **Update About Section**: Modify the about text and statistics

3. **Update Experience**: Edit the timeline items with your work experience

4. **Update Skills**: Modify skill names and progress percentages

5. **Update Projects**: Replace project images, descriptions, and links

6. **Update Contact Information**: Change email, phone, and social media links

### Changing Colors

The website uses a gradient color scheme. To change colors, update the gradient values in `styles.css`:

```css
/* Primary Gradient */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Dark Mode Gradient */
background: linear-gradient(135deg, #a855f7 0%, #22c55e 100%);
```

### Adding New Sections

1. Add HTML structure in `index.html`
2. Add corresponding styles in `styles.css`
3. Add navigation link in the navbar
4. Ensure smooth scroll behavior is working

## 📱 Responsive Breakpoints

- **Desktop**: > 968px (Full navigation menu)
- **Tablet**: 768px - 968px (Condensed menu)
- **Mobile**: < 768px (Hamburger menu)
- **Small Mobile**: < 480px (Optimized spacing)

## 🌟 Key Features Explained

### Dark Mode Implementation
- Uses `localStorage` to save user preference
- Smooth transition between themes
- All components styled for both light and dark modes

### Smooth Animations
- **Fade-in animations**: Elements appear as you scroll
- **Hover effects**: Interactive feedback on all clickable elements
- **Scroll reveal**: Content animates into view using Intersection Observer

### Performance Optimizations
- CSS animations use `transform` and `opacity` for GPU acceleration
- Lazy loading considerations for images
- Efficient event listeners with proper cleanup

## 📧 Contact Information

- **Email**: mahbub0001@uftb.ac.bd
- **Phone**: +8801729341204
- **Location**: West Brahmondi, Narsingdi, Bangladesh

### Social Media
- **LinkedIn**: [Mahbub Ul Alam Bhuiyan](https://www.linkedin.com/in/mahbub-ul-alam-bhuiyan-289bb8294/)
- **GitHub**: [Mahbub0001](https://github.com/Mahbub0001)
- **Twitter**: [@Nibirbhuiyan18](https://x.com/Nibirbhuiyan18)
- **Facebook**: [Nibir.bhuiyan40](https://www.facebook.com/Nibir.bhuiyan40)

## 👨‍💻 Author

**Mahbub Ul Alam Bhuiyan**
- Web Backend & ML Engineer
- Freelance Developer
- Specialized in Django, Machine Learning, and Web Development

## 📄 License

This project is open source and available for personal use. Feel free to use it as a template for your own portfolio.

## 🙏 Acknowledgments

- **Font Awesome** for the icon library
- **Google Fonts** for Inter and Poppins fonts
- **Design Inspiration** from modern portfolio websites

## 🔮 Future Enhancements

Potential features for future updates:
- [ ] Blog section
- [ ] Project filtering/categories
- [ ] Multi-language support
- [ ] Contact form backend integration
- [ ] Analytics integration
- [ ] SEO optimizations
- [ ] Progressive Web App (PWA) features

## 📝 Notes

- Ensure all image paths are correct
- Update the CV file path if the filename changes
- Test on multiple browsers for compatibility
- Optimize images for web before deployment

## 🐛 Troubleshooting

### Images not loading?
- Check image file paths and names
- Ensure images are in the correct directory
- Verify file extensions match

### Dark mode not working?
- Clear browser cache and localStorage
- Check browser console for JavaScript errors
- Ensure JavaScript is enabled

### Mobile menu not opening?
- Check if hamburger menu JavaScript is loaded
- Verify z-index values for proper layering
- Test on actual device, not just browser dev tools

---

**Built with ❤️ by Mahbub Ul Alam Bhuiyan**

*Last updated: 2024*

