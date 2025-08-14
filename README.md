# BUFFY Landing Page

A fully responsive, modern landing page for BUFFY - Your Ruthless Startup Stress-Tester. Built with a dark mode/futuristic neon aesthetic and optimized for smooth performance.

## 🚀 Features

- **Fully Responsive Design**: Optimized for mobile, tablet, and desktop
- **Dark Mode/Futuristic Aesthetic**: Neon purple and electric blue color scheme with Effect3 branding
- **Animated Particles Background**: Interactive particle system using particles.js with performance optimizations
- **Smooth Animations**: GSAP-powered scroll animations and hover effects
- **Modern Typography**: Clean Inter font family
- **Accessibility Features**: ARIA attributes, reduced motion support, high contrast mode
- **Performance Optimized**: Responsive particle counts, hardware detection, optimized animations
- **Single File Structure**: Easy to deploy and maintain

## 📋 Sections

1. **Hero Section**: Full-screen with animated title, subtitle, CTA buttons, and BUFFY AI avatar
2. **How It Works**: 4-step process with animated icons
3. **Key Features**: Feature cards with hover effects
4. **Why BUFFY**: Two-column layout with animated AI brain graphic
5. **Testimonials**: Glowing testimonial cards
6. **Final CTA**: Large call-to-action section
7. **Footer**: Complete footer with Effect3 branding and logo

## 🛠️ Technologies Used

- **HTML5**: Semantic markup with accessibility features
- **Tailwind CSS**: Utility-first CSS framework via CDN
- **JavaScript**: Vanilla JS with performance optimizations
- **Particles.js**: Particle animation system
- **GSAP**: Professional animation library
- **Google Fonts**: Inter font family
- **SVG Graphics**: Custom Effect3 logo and BUFFY AI avatar

## 📁 File Structure

```
buffy/
├── index.html          # Complete landing page with all assets inline
└── README.md          # This file
```

## 🚀 Getting Started

### Local Development

1. **Simple Setup**:
   - Simply open `index.html` in your browser
   - No build process required - all dependencies loaded via CDN

2. **Live Server** (Recommended):
   ```bash
   # Using Python
   python -m http.server 8000

   # Using Node.js
   npx serve .

   # Using PHP
   php -S localhost:8000
   ```

3. **Deploy to Production**:
   - Upload `index.html` to any web server
   - Works with GitHub Pages, Netlify, Vercel, etc.

### Performance Features

- **Responsive Particles**: Automatically adjusts particle count based on device capabilities
- **Hardware Detection**: Reduces animations on low-end devices
- **Reduced Motion Support**: Respects user accessibility preferences
- **Mobile Optimizations**: Lighter animations and particle effects on mobile devices

## Customization

### Colors
The color scheme is defined in the Tailwind config:
- `neon-purple`: #9A4DFF
- `electric-blue`: #00C2FF
- `dark-bg`: #0A0A0A
- `dark-card`: #1A1A1A

### Content
- Update company information in the footer
- Modify testimonials with real customer quotes
- Replace placeholder mockup with actual chatbot interface
- Update social media links

### CTA Links
- Update button links to point to your actual app/signup page
- Modify navigation links as needed

## Performance Optimization

- Particles are automatically reduced on mobile devices
- Animations are disabled for users with `prefers-reduced-motion`
- Hardware detection reduces animations on low-end devices
- Responsive image loading and optimized particle counts

## Browser Support

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

## Accessibility Features

- Semantic HTML5 structure
- ARIA labels and attributes
- Keyboard navigation support
- Screen reader friendly
- High contrast mode support
- Reduced motion preferences respected

## Testing Checklist

### Desktop Testing
- [ ] Chrome (latest)
- [ ] Firefox (latest)
- [ ] Safari (latest)
- [ ] Edge (latest)

### Mobile Testing
- [ ] iOS Safari
- [ ] Android Chrome
- [ ] Mobile Firefox

### Responsive Breakpoints
- [ ] Mobile (320px - 768px)
- [ ] Tablet (768px - 1024px)
- [ ] Desktop (1024px+)
- [ ] Large screens (1440px+)

### Performance
- [ ] Page load speed < 3 seconds
- [ ] Smooth animations at 60fps
- [ ] Particle system performance on mobile
- [ ] Memory usage optimization

### Accessibility
- [ ] Screen reader compatibility
- [ ] Keyboard navigation
- [ ] Color contrast ratios
- [ ] Focus indicators
- [ ] Alt text for images

## Deployment

### GitHub Pages
1. Push to GitHub repository
2. Enable GitHub Pages in repository settings
3. Select source branch (main/master)

### Netlify
1. Drag and drop the file to Netlify
2. Or connect GitHub repository for automatic deployments

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in project directory
3. Follow deployment prompts

## License

© 2024 Effect3. All rights reserved.

## Support

For questions or issues, contact the Effect3 team.
