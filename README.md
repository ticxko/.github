# Reir Technology and Consulting - Landing Page

A modern, responsive landing page for Reir Technology and Consulting, showcasing core services in technology consulting, UI/UX design, custom application development, and system integration.

![Landing Page Preview](preview.png)

## 🚀 Features

- **Modern Design**: Clean, professional UI with gradient accents and smooth animations
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Interactive Elements**: Scroll animations, counter animations, and smooth navigation
- **Contact Form**: Ready-to-use form with validation (integrate with your backend)
- **Fast Loading**: Pure HTML, CSS, and JavaScript - no heavy frameworks
- **SEO Ready**: Semantic HTML structure with proper meta tags

## 📁 Project Structure

```
/
├── index.html      # Main HTML file
├── styles.css      # CSS styles with custom properties
├── script.js       # JavaScript for interactivity
└── README.md       # This file
```

## 🛠️ Getting Started

### Option 1: Open Directly
Simply open `index.html` in your web browser.

### Option 2: Use a Local Server
For the best development experience, use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (with http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## 🎨 Customization

### Colors
Edit the CSS custom properties in `styles.css`:

```css
:root {
    --primary: #6366f1;        /* Main brand color */
    --primary-dark: #4f46e5;   /* Darker shade */
    --primary-light: #818cf8;  /* Lighter shade */
    --secondary: #0ea5e9;      /* Accent color */
    --accent: #8b5cf6;         /* Additional accent */
}
```

### Content
- **Company Info**: Update company name, tagline, and descriptions in `index.html`
- **Services**: Modify the service cards in the services section
- **Contact**: Update email, phone, and address in the contact section
- **Statistics**: Change the numbers in the hero section

### Fonts
The page uses [Inter](https://fonts.google.com/specimen/Inter) from Google Fonts. To change:
1. Update the Google Fonts link in `index.html`
2. Update `--font-family` in `styles.css`

## 📧 Contact Form Integration

The contact form includes client-side validation. To make it functional:

1. **With a Backend API**:
   Replace the `setTimeout` simulation in `script.js` with an actual API call:
   ```javascript
   fetch('/api/contact', {
       method: 'POST',
       headers: { 'Content-Type': 'application/json' },
       body: JSON.stringify(data)
   })
   ```

2. **With Formspree**:
   Update the form action in `index.html`:
   ```html
   <form action="https://formspree.io/f/YOUR_ID" method="POST">
   ```

3. **With Netlify Forms**:
   Add `netlify` attribute to the form:
   ```html
   <form name="contact" netlify>
   ```

## 📱 Sections Included

1. **Navigation** - Sticky header with smooth scroll links
2. **Hero** - Eye-catching introduction with statistics
3. **Services** - Four core services with detailed descriptions
4. **About** - Company values and client satisfaction rate
5. **Process** - Four-step development methodology
6. **Technologies** - Tech stack showcase
7. **CTA** - Call-to-action banner
8. **Contact** - Contact form and company details
9. **Footer** - Links and social media

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

This project is open source and available under the MIT License.

---

Built with ❤️ for Reir Technology and Consulting
