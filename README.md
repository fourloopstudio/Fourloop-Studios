# 🚀 Fourloop Website

A modern, professional website for **Fourloop** - Your technical backup for academic project success.

## 🎯 About Fourloop

Fourloop is a student-focused tech services startup that helps college students successfully complete major and minor academic projects by providing:

- **Custom-built projects** tailored to syllabus and requirements
- **Installation & execution support** with debugging and deployment
- **Clear explanations** for understanding and viva preparation
- **Ongoing technical guidance** throughout the project lifecycle

## ✨ Website Features

### Design Highlights
- 🎨 **Premium Dark Theme** with vibrant gradients
- ✨ **Glassmorphism Effects** for modern aesthetics
- 🌊 **Smooth Animations** and micro-interactions
- 📱 **Fully Responsive** design for all devices
- ⚡ **Fast & Optimized** performance

### Sections
1. **Hero Section** - Eye-catching introduction with animated gradients
2. **Services** - Detailed showcase of offerings
3. **Domains** - Technology expertise areas
4. **Why Us** - Value propositions with testimonials
5. **Contact** - Interactive form for inquiries

## 🛠️ Tech Stack

- **HTML5** - Semantic structure with SEO optimization
- **CSS3** - Modern design system with custom properties
- **Vanilla JavaScript** - Interactive features and animations
- **Google Fonts** - Inter & Space Grotesk typography

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Optional: Local web server for testing

### Running Locally

1. **Simple Method** - Just open the file:
   ```
   Double-click index.html
   ```

2. **With Live Server** (Recommended):
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (http-server)
   npx http-server -p 8000
   
   # Using PHP
   php -S localhost:8000
   ```

3. Open your browser and navigate to:
   ```
   http://localhost:8000
   ```

## 📁 Project Structure

```
FOURLOOP/
├── index.html          # Main HTML structure
├── styles.css          # Complete styling and design system
├── script.js           # Interactive features and animations
└── README.md           # This file
```

## 🎨 Design System

### Color Palette
- **Primary**: Purple gradient (#667eea → #764ba2)
- **Secondary**: Pink gradient (#f093fb → #f5576c)
- **Tertiary**: Blue gradient (#4facfe → #00f2fe)
- **Background**: Dark theme (#0a0a0f)

### Typography
- **Display Font**: Space Grotesk (headings)
- **Body Font**: Inter (content)

## 📱 Responsive Breakpoints

- **Desktop**: 1024px and above
- **Tablet**: 768px - 1023px
- **Mobile**: Below 768px

## 🔧 Customization

### Update Contact Information
Edit the contact section in `index.html`:
```html
<div class="contact-info-value">fourloopstudio4@gmail.com</div>
<div class="contact-info-value">@fourloop.tech</div>
```

### Modify Colors
Update CSS variables in `styles.css`:
```css
:root {
    --color-primary: #667eea;
    --color-secondary: #764ba2;
    /* ... more variables */
}
```

### Form Submission
The contact form currently logs to console. To integrate with a backend:

1. Open `script.js`
2. Find the form submission handler
3. Replace the demo code with your API endpoint:
```javascript
await fetch('/api/contact', {
    method: 'POST',
    headers: { 'Content-Type': 'application/json' },
    body: JSON.stringify(formData)
});
```

## 🌐 Deployment

### Option 1: GitHub Pages
1. Push code to GitHub repository
2. Go to Settings → Pages
3. Select branch and deploy

### Option 2: Netlify
1. Drag and drop the folder to Netlify
2. Or connect your Git repository

### Option 3: Vercel
```bash
npx vercel
```

## 📊 Performance Optimization

- ✅ Minimal dependencies (no frameworks)
- ✅ Optimized animations with CSS transforms
- ✅ Lazy loading for scroll animations
- ✅ Efficient event listeners

## 🎯 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📝 Future Enhancements

- [ ] Add blog section for tech articles
- [ ] Integrate with CMS for dynamic content
- [ ] Add project portfolio showcase
- [ ] Implement dark/light theme toggle
- [ ] Add multi-language support

## 🤝 Contributing

This is a custom website for Fourloop. For suggestions or improvements, please contact the development team.

## 📄 License

© 2026 Fourloop. All rights reserved.

## 💬 Support

For questions or support:
- 📧 Email: fourloopstudio4@gmail.com
- 📱 Instagram: @fourloop.tech

---

**Made with 💜 for students by Fourloop**
