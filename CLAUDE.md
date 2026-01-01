# NextRev Rentals Website

Commercial van rental website for NextRev Rentals (nextrevrentals.com), a division of Next Rev Distribution, Inc.

## Project Overview

- **Type**: Static website (HTML/CSS/JS)
- **Hosting**: GitHub Pages
- **Domain**: nextrevrentals.com
- **Parent Company**: Next Rev (nxtrev.com)

## Tech Stack

- Static HTML5
- CSS3 (custom properties, flexbox, grid)
- Vanilla JavaScript
- Formspree for contact form (endpoint: xeeoewaw)

## Brand Guidelines

- **Colors**:
  - Primary: Black (#0a0a0a)
  - Accent: Gold (#FFAA00)
  - Dark backgrounds: Charcoal (#1a1a1a)
  - Light backgrounds: Off-white (#f8f7f4)
- **Fonts**: Montserrat (headings), Lato (body) via Google Fonts
- **Tone**: Professional, reliable, business-focused

## File Structure

```
├── assets/
│   ├── edited_van.png    # Van image for about/services sections
│   ├── logo.png          # NextRev logo (transparent)
│   └── van5.png          # Hero background image
├── contact.html          # Contact page with Formspree form
├── index.html            # Home page
├── services.html         # Services page
├── styles.css            # All styles
├── script.js             # Mobile menu, scroll effects, animations
└── CNAME                 # GitHub Pages custom domain
```

## Contact Form

- Uses Formspree (https://formspree.io/f/xeeoewaw)
- Submissions go to: rentals@nxtrev.com

## Development Notes

- Mobile-responsive (breakpoints at 1024px, 768px, 480px)
- Hero uses full-bleed background image with gradient overlay
- Header is transparent on hero, turns white on scroll
- Logo inverts based on header background
