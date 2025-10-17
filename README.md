# Abdulhakeem Sule - Profile Card

A modern, responsive profile card web application showcasing personal information, social links, hobbies, and real-time updates. Built with pure HTML, CSS, and JavaScript.

## Features
- **Responsive Design**: Fully responsive layout that works seamlessly on desktop, tablet, and mobile devices
- **Real-time Updates**: Dynamic time display showing current timestamp in milliseconds, updated every second
- **Modern UI**: Beautiful gradient backgrounds and smooth hover animations
- **Accessibility**: Keyboard navigation support and semantic HTML for better accessibility
- **Social Integration**: Quick links to GitHub, Twitter, and LinkedIn profiles
- **Clean Code**: Well-structured, commented code following best practices

## Technologies Used
- HTML5
- CSS3 (Flexbox, Gradients, Animations)
- Vanilla JavaScript
- Semantic HTML
- Responsive Design Principles

## Sections
The profile card includes the following sections:

1. **Header**: Profile picture, name, and real-time timestamp
2. **Bio**: Professional introduction and expertise
3. **Social Links**: Connected social media profiles
4. **Hobbies & Interests**: Personal interests and activities
5. **Dislikes**: Things to avoid in professional collaboration

## Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of HTML/CSS/JavaScript (for modifications)

## File Structure
profile-card/
├── index.html              # Main HTML file
├── Abdulhakeem Sule .jpg   # Profile avatar image
├── github.png              # GitHub social icon
├── twitter.png             # Twitter social icon
├── linkedin.png            # LinkedIn social icon
├── README.md               # Project documentation
└── screenshot.png          # Project screenshot (optional)

## Customization
### Changing Personal Information
1. **Update Name**: Modify the `<h1>` tag with `data-testid="test-user-name"`
2. **Update Bio**: Edit the `<p>` tag with `data-testid="test-user-bio"`
3. **Update Avatar**: Replace `Abdulhakeem Sule .jpg` with your own image
4. **Update Social Links**: Modify the `href` attributes in the social links section

### Modifying Colors
The color scheme can be customized by changing the gradient values in the CSS:

## CSS
/* Background gradient */
background: linear-gradient(135deg, #66d6ea 0%, #918fff 100%);

/* Header gradient */
background: linear-gradient(135deg, #2c51f3 0%, #62e0ff 100%);

## Features Breakdown
### Real-time Timestamp
The card displays the current time in milliseconds, updated every second using JavaScript:
```javascript
setInterval(updateTime, 1000);
```
### Responsive Design
Mobile-first approach with breakpoints at:
- Mobile: < 640px
- Tablet: 640px - 768px
- Desktop: > 768px

### Accessibility
- Semantic HTML elements (`<article>`, `<nav>`, `<section>`)
- ARIA labels for navigation
- Keyboard navigation support
- Alt text for images

##  Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Author
**Abdulhakeem Sule**
- GitHub: [@Hakimziyech18](https://github.com/Hakimziyech18)
- Twitter: [@hakiimii18](https://x.com/hakiimii18)
- LinkedIn: [Adoyiza Sule](https://www.linkedin.com/in/adoyiza-sule-5a4b21374)

## Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.
1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Acknowledgments
- Design inspiration from modern profile card layouts
- Icons sourced from respective platforms
- Built with passion for clean, accessible web development
