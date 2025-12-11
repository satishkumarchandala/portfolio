# Portfolio - Chandala Satish Kumar

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/satishkumarchandala/portfolio)

A modern, responsive portfolio website showcasing my work as a Full Stack Developer.

## ✨ Features

- 🎨 **Modern Design** - Clean and professional aesthetic with smooth animations
- 📱 **Fully Responsive** - Works perfectly on desktop, tablet, and mobile devices
- ⚡ **Fast Loading** - Optimized for performance
- 🎭 **Interactive Elements** - Typing effects, parallax scrolling, and hover animations
- 🚀 **Easy to Deploy** - Deploy to GitHub Pages, Netlify, or Vercel in minutes
- 🎯 **SEO Friendly** - Proper meta tags and semantic HTML

## 📋 Sections

1. **Hero** - Eye-catching introduction with animated typing effect
2. **About** - Personal information and statistics
3. **Projects** - Showcase of your best work with project cards
4. **Skills** - Display of your technical skills and tools
5. **Contact** - Contact form and social media links

## 🚀 Quick Start

### Local Development

1. Clone or download this repository
2. Open `index.html` in your browser
3. That's it! No build process required.

### Customization

Edit the following files to personalize your portfolio:

#### `index.html`
- Update personal information (name, title, description)
- Add your projects with links and descriptions
- Update contact information and social media links
- Replace skill items with your own technologies

#### `styles.css`
- Change color scheme by modifying CSS variables:
  ```css
  :root {
      --primary-color: #6366f1;
      --secondary-color: #8b5cf6;
      --accent-color: #ec4899;
  }
  ```

#### `script.js`
- Update the typing effect text in the `textArray`
- Modify form submission behavior

## 🌐 Deployment Options

### Option 1: GitHub Pages (Free)

1. Create a new repository on GitHub
2. Push your code to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/portfolio.git
   git push -u origin main
   ```
3. Go to repository Settings → Pages
4. Select `main` branch as source
5. Your site will be live at `https://yourusername.github.io/portfolio`

### Option 2: Netlify (Free)

1. Sign up at [netlify.com](https://netlify.com)
2. Drag and drop your portfolio folder to Netlify
3. Your site is live instantly!
4. Or connect your GitHub repository for automatic deployments

### Option 3: Vercel (Free)

1. Sign up at [vercel.com](https://vercel.com)
2. Install Vercel CLI:
   ```bash
   npm install -g vercel
   ```
3. Deploy from your project folder:
   ```bash
   vercel
   ```
4. Follow the prompts to complete deployment

### Option 4: Traditional Web Hosting

1. Upload all files to your web hosting via FTP
2. Ensure `index.html` is in the root directory
3. Access your site through your domain

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## 🎨 Color Customization

The portfolio uses CSS custom properties for easy theming. Main colors:

- **Primary**: `#6366f1` (Indigo)
- **Secondary**: `#8b5cf6` (Purple)
- **Accent**: `#ec4899` (Pink)

Change these in the `:root` selector in `styles.css` to match your brand.

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## 🔧 Adding Your Own Images

To replace placeholder icons with real images:

1. Add your images to the project folder
2. In `index.html`, replace:
   ```html
   <div class="image-placeholder">
       <i class="fas fa-user-circle"></i>
   </div>
   ```
   with:
   ```html
   <img src="your-image.jpg" alt="Your Name">
   ```
3. Add CSS styling as needed

## 📬 Contact Form Setup

The contact form currently shows an alert. To make it functional:

### Option 1: Formspree (Easiest)
1. Sign up at [formspree.io](https://formspree.io)
2. Update the form tag:
   ```html
   <form action="https://formspree.io/f/your-form-id" method="POST">
   ```

### Option 2: Netlify Forms (if using Netlify)
1. Add `netlify` attribute to form:
   ```html
   <form name="contact" method="POST" data-netlify="true">
   ```

### Option 3: Custom Backend
1. Create your own API endpoint
2. Update the form submission handler in `script.js`

## 🎯 SEO Tips

1. Update meta tags in `index.html` with your information
2. Add a `favicon.ico` file
3. Create a `robots.txt` file
4. Add Google Analytics (optional)
5. Submit your sitemap to Google Search Console

## 📄 License

This project is free to use for personal and commercial projects.

## 👤 About Me

**Chandala Satish Kumar**
- 🎓 BTech in Computer Science & Engineering at GMR Institute of Technology
- 💼 Former Django Developer Intern at Topnotch Softwares
- 📍 Morjampadu, Palnadu, Andhra Pradesh, India
- 📧 satishchandala834@gmail.com
- 📱 +91 8885632415

## 💡 Tips

- Keep your content concise and impactful
- Use high-quality images for projects
- Update your portfolio regularly with new work
- Test on multiple devices before deploying
- Use actual project links instead of "#" placeholders

## 🆘 Need Help?

If you encounter any issues:
1. Check browser console for errors
2. Ensure all files are in the same directory
3. Clear browser cache
4. Try a different browser

## 🌟 Credits

- Icons: [Font Awesome](https://fontawesome.com)
- Fonts: System fonts for optimal performance

---

**Ready to launch your portfolio?** Customize the content, deploy it, and share it with the world! 🚀
