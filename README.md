# Modern Portfolio Website

A beautiful, responsive portfolio website built with HTML, CSS, and JavaScript. This template is perfect for showcasing your work and skills as a developer, designer, or freelancer.

## Features

- 🎨 Modern and clean design
- 📱 Fully responsive layout
- ✨ Smooth animations and transitions
- ⌨️ Typing animation effect
- 📝 Contact form with validation
- 🎯 Smooth scrolling navigation
- 🌙 Mobile-friendly navigation menu
- 📊 Skills section with icons
- 📂 Project showcase section
- 📬 Contact information section
- 🔗 Social media links

## Getting Started

1. Clone or download this repository
2. Open `index.html` in your browser
3. Customize the content to make it your own

## Customization

### Personal Information

Edit the following sections in `index.html`:

- Update your name in the hero section
- Modify the typing animation text in `script.js`
- Add your own profile picture
- Update personal information in the About section
- Add your own projects to the Projects section
- Customize skills in the Skills section
- Update contact information

### Styling

The website uses CSS variables for easy customization. Edit the following in `styles.css`:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    --text-color: #1f2937;
    --light-text: #6b7280;
    --background: #ffffff;
    --section-bg: #f3f4f6;
}
```

### Projects

To add a new project, copy and paste the project card structure in the Projects section:

```html
<div class="project-card">
    <div class="project-image">
        <img src="path-to-your-image" alt="Project Title">
    </div>
    <div class="project-info">
        <h3>Project Title</h3>
        <p>Project description goes here.</p>
        <div class="project-tags">
            <span>Tag 1</span>
            <span>Tag 2</span>
        </div>
        <div class="project-links">
            <a href="#" class="btn small-btn">View Live</a>
            <a href="#" class="btn small-btn">Source Code</a>
        </div>
    </div>
</div>
```

### Contact Form

The contact form includes basic validation. To make it functional:

1. Add your form handling logic in the `script.js` file
2. Update the form submission handler to send data to your server
3. Customize the validation messages as needed

## Browser Support

The website is compatible with all modern browsers:

- Chrome
- Firefox
- Safari
- Edge

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is open source and available under the [MIT License](LICENSE).

## Credits

- Font Awesome for icons
- Google Fonts for typography
- Placeholder.com for placeholder images 