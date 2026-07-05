# MB Studio - Premium Audio Production & Artist Development

## Overview

MB Studio is a professional website for a premium audio production and artist development company based in Ghana. The website showcases services, portfolio, and provides a platform for client engagement.

## Features

### Pages
1. **Homepage** - Hero section with services preview, statistics, and call-to-action
2. **Portfolio** - Filterable gallery showcasing past projects and work
3. **Services** - Detailed information about audio production, artist development, and visual branding
4. **About** - Company story, mission, values, team, and achievements
5. **Contact** - Contact information, contact form, FAQ section, and map

### Key Features
- Responsive design optimized for mobile, tablet, and desktop
- Modern UI/UX with smooth animations and transitions
- Portfolio filtering system
- Contact form with validation
- SEO-optimized structure
- Accessibility-friendly design
- Font Awesome icons integration

## File Structure

```
MB-Studio/
├── index.html          # Homepage
├── portfolio.html      # Portfolio page
├── services.html       # Services page
├── about.html          # About page
├── contact.html        # Contact page
├── styles/
│   └── main.css        # Main stylesheet
├── js/
│   ├── main.js         # Main JavaScript
│   ├── portfolio.js    # Portfolio filter functionality
│   └── contact.js      # Contact form handling
└── README.md           # This file
```

## Color Scheme

- Primary Color: `#FF6B35` (Orange)
- Secondary Color: `#004E89` (Navy Blue)
- Accent Color: `#9C51B6` (Purple)
- Dark Background: `#1A1A1A` (Dark Gray)
- Light Background: `#F5F5F5` (Light Gray)

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript (ES6+)
- Font Awesome Icons

## Setup Instructions

1. Clone or download this repository
2. Open `index.html` in your web browser
3. No build process or dependencies required

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Features Breakdown

### Responsive Design
- Mobile-first approach
- Breakpoints at 768px and 480px
- Hamburger menu for mobile navigation

### Interactive Elements
- Smooth scroll behavior
- Hover effects on buttons and cards
- Portfolio filter with smooth transitions
- Form validation
- Scroll animations

### Accessibility
- Semantic HTML structure
- ARIA labels and roles
- Keyboard navigation support
- Color contrast compliance

## Customization

### Changing Colors
Edit the CSS variables in `styles/main.css`:

```css
:root {
    --primary-color: #FF6B35;
    --secondary-color: #004E89;
    --accent-color: #9C51B6;
    /* ... other colors ... */
}
```

### Adding New Portfolio Items
Add new items to the portfolio grid in `portfolio.html`:

```html
<div class="portfolio-item" data-category="production">
    <div class="portfolio-image">
        <i class="fas fa-icon"></i>
    </div>
    <div class="portfolio-info">
        <h3>Project Name</h3>
        <p>Project Description</p>
        <span class="category-tag">Category</span>
    </div>
</div>
```

### Updating Contact Information
Edit the contact details in `contact.html` in the `.contact-info` section.

## Performance Optimization

- Minified CSS and JavaScript in production
- Lazy loading for images (when implemented)
- Optimized font loading
- Minimal external dependencies

## Future Enhancements

- Backend integration for contact form
- Email notifications
- Blog section
- Client testimonials carousel
- Interactive music player
- Analytics integration
- CMS integration

## Support & Contact

For support or inquiries:
- Email: hello@mbstudio.com
- Phone: +233 (0) 123-456-7890
- Address: 123 Music Lane, Accra, Ghana

## License

All rights reserved © 2026 MB Studio

## Credits

Designed and developed for MB Studio - Elevating the Ghanaian Soundscape