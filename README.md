# Business Analytics Portfolio Website

A modern, responsive portfolio website designed specifically for business analytics students and professionals. This website showcases your skills in data visualization, analytics tools, and programming languages.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, and dynamic content
- **Social Media Integration**: Direct links to Facebook, Instagram, WhatsApp, and LinkedIn
- **Contact Form**: Functional contact form with validation
- **Skills Showcase**: Highlight your expertise in PowerBI, Tableau, Python, R, SQL, and Canva
- **Project Portfolio**: Display your analytics projects with descriptions and technologies used
- **SEO Optimized**: Clean HTML structure for better search engine visibility

## Customization Guide

### 1. Personal Information
Update the following in `index.html`:

- **Name**: Replace "Your Name" with your actual name
- **Photo**: Replace `your-photo.jpg` with your profile picture
- **Email**: Update `your.email@example.com` with your email
- **Phone**: Update `+1 (555) 123-4567` with your phone number
- **Location**: Update `Your City, Country` with your location

### 2. Social Media Links
Update the social media links in the contact section:

```html
<a href="https://facebook.com/yourprofile" target="_blank" class="social-link facebook">
<a href="https://instagram.com/yourprofile" target="_blank" class="social-link instagram">
<a href="https://wa.me/1234567890" target="_blank" class="social-link whatsapp">
<a href="https://linkedin.com/in/yourprofile" target="_blank" class="social-link linkedin">
```

Replace:
- `yourprofile` with your actual social media usernames
- `1234567890` with your WhatsApp number (include country code)

### 3. About Section
Customize the about section text to reflect your personal story and goals.

### 4. Projects Section
Update the project cards with your actual projects:

- **Project Titles**: Change the project names
- **Descriptions**: Write detailed descriptions of your projects
- **Technologies**: Update the technology tags
- **Links**: Add actual links to your projects (GitHub, live demos, etc.)

### 5. Skills Section
The skills section is already configured with your mentioned tools:
- PowerBI
- Tableau
- Canva
- Python
- R Language
- SQL

You can add or remove skills as needed.

### 6. Color Scheme
To change the color scheme, update the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #fbbf24;
    --accent-color: #667eea;
}
```

### 7. Adding Your Photo
1. Save your photo as `your-photo.jpg` in the same directory as `index.html`
2. Make sure the image is square (recommended: 400x400 pixels)
3. The image will be automatically cropped to a circle

## File Structure

```
portfolio-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript for interactivity
├── your-photo.jpg      # Your profile picture (add this)
└── README.md           # This file
```

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Features

- Optimized images and animations
- Smooth scrolling and transitions
- Mobile-first responsive design
- Fast loading times
- SEO-friendly structure

## Getting Started

1. Download all files to a folder
2. Add your profile photo as `your-photo.jpg`
3. Customize the content as described above
4. Open `index.html` in a web browser to preview
5. Upload to a web hosting service to make it live

## Hosting Options

- **GitHub Pages**: Free hosting for static websites
- **Netlify**: Easy deployment with drag-and-drop
- **Vercel**: Fast deployment with custom domains
- **Traditional Web Hosting**: Upload files via FTP

## Tips for Success

1. **Keep it Updated**: Regularly update your projects and skills
2. **Professional Photo**: Use a high-quality, professional headshot
3. **Clear Descriptions**: Write clear, concise project descriptions
4. **Contact Information**: Make sure all contact details are current
5. **Test on Mobile**: Always test your site on mobile devices
6. **Social Media**: Keep your social media profiles professional and up-to-date

## Support

If you need help customizing your portfolio or have questions about the code, feel free to reach out!

---

**Built with ❤️ for Business Analytics Professionals**
