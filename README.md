# NSV Vijay - Resume Website

A modern, animated resume website built with HTML, CSS, and JavaScript.

## Features

- **Modern Design**: Clean, professional UI with gradient accents
- **Smooth Animations**: Scroll-triggered reveal animations, floating shapes, and custom cursor
- **Responsive**: Fully responsive design that works on all devices
- **Interactive Elements**: Hover effects, typing animation, and skill progress bars
- **Contact Form**: Functional contact form layout
- **Fast Loading**: Lightweight, no build tools required

## Sections

- **Hero**: Eye-catching introduction with animated elements
- **About**: Personal information and statistics
- **Skills**: Technical skills with animated progress bars
- **Experience**: Timeline of work experience
- **Contact**: Contact information and form

## Deployment

### Option 1: Netlify Drop (Easiest)

1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag and drop the `resume-website` folder onto the page
3. Your site will be live instantly with a URL like `your-site-name.netlify.app`

### Option 2: GitHub Pages

1. Create a new GitHub repository
2. Upload all files from the `resume-website` folder
3. Go to repository Settings > Pages
4. Select `main` branch as source
5. Your site will be available at `your-username.github.io/repository-name`

### Option 3: Vercel

1. Install Vercel CLI: `npm i -g vercel` (requires npm)
2. Run `vercel` in the `resume-website` directory
3. Follow the prompts to deploy

## Customization

### Personal Information

Edit the following in `index.html`:
- Name and title in the hero section
- About text and statistics
- Skills and progress percentages
- Experience timeline
- Contact information
- Social media links

### Colors

Modify CSS variables in `styles.css`:
```css
:root {
    --primary: #6366f1;
    --primary-dark: #4f46e5;
    --secondary: #8b5cf6;
    --dark: #0f172a;
    --dark-light: #1e293b;
    --light: #f8fafc;
    --gray: #64748b;
    --gradient: linear-gradient(135deg, #6366f1 0%, #8b5cf6 100%);
}
```

### Profile Image

Replace the icon in the hero section with your actual photo:
```html
<div class="profile-image">
    <img src="your-photo.jpg" alt="Your Name" style="width: 100%; height: 100%; object-fit: cover; border-radius: 50%;">
</div>
```

## Local Development

Simply open `index.html` in your browser to view the website locally. No server or build process required.

## Technologies Used

- HTML5
- CSS3 (Custom properties, Flexbox, Grid, Animations)
- JavaScript (ES6+)
- Font Awesome (Icons)
- Google Fonts (Inter)

## License

This project is open source and available for personal use.
