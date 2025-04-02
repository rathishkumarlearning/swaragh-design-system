# Swaragh Design System

A comprehensive design system based on Swaragh Technologies website design, providing guidelines and components for creating consistent, modern, and professional web applications.

## Design Tokens

### Colors
```css
/* Primary Colors */
--primary-blue: #0088FF;
--primary-dark: #1E1656;
--primary-navy: #0A1933;
--accent-gold: #FFD700;

/* Secondary Colors */
--secondary-gray: #F5F5F5;
--secondary-light: #FFFFFF;
--text-dark: #333333;
--text-light: #FFFFFF;
```

### Typography
```css
/* Font Family */
--font-primary: 'Poppins', system-ui, sans-serif;

/* Font Sizes */
--text-xs: 0.75rem;   /* 12px */
--text-sm: 0.875rem;  /* 14px */
--text-base: 1rem;    /* 16px */
--text-lg: 1.125rem;  /* 18px */
--text-xl: 1.25rem;   /* 20px */
--text-2xl: 1.5rem;   /* 24px */
--text-3xl: 2rem;     /* 32px */
--text-4xl: 2.5rem;   /* 40px */
--text-5xl: 3rem;     /* 48px */
--text-6xl: 4rem;     /* 64px */
```

### Spacing
```css
--spacing-xs: 0.25rem;  /* 4px */
--spacing-sm: 0.5rem;   /* 8px */
--spacing-md: 1rem;     /* 16px */
--spacing-lg: 1.5rem;   /* 24px */
--spacing-xl: 2rem;     /* 32px */
--spacing-2xl: 3rem;    /* 48px */
--spacing-3xl: 4rem;    /* 64px */
```

## Components

### 1. Navigation
```html
<header class="sw-header">
  <nav class="sw-nav">
    <div class="sw-logo">
      <!-- Logo -->
    </div>
    <ul class="sw-nav-items">
      <!-- Nav items -->
    </ul>
    <button class="sw-cta-button">
      Start A Project
    </button>
  </nav>
</header>
```

### 2. Hero Section
```html
<section class="sw-hero">
  <div class="sw-hero__content">
    <h1 class="sw-hero__title">
      Want To Build The
      <span class="sw-hero__highlight">PRODUCT</span>
      People Remember
    </h1>
    <div class="sw-hero__cta-group">
      <!-- CTAs -->
    </div>
  </div>
</section>
```

### 3. Buttons
```html
<!-- Primary Button -->
<button class="sw-button sw-button--primary">
  Know How
</button>

<!-- Secondary Button -->
<button class="sw-button sw-button--secondary">
  Contact Us
</button>
```

## Layout System

### Grid
- 12-column grid
- Maximum container width: 1200px
- Responsive breakpoints:
  - Mobile: < 768px
  - Tablet: 768px - 1199px
  - Desktop: 1200px+

### Component Spacing
- Section margins: 48px (var(--spacing-2xl))
- Card padding: 16px (var(--spacing-md))
- Container padding: 24px (var(--spacing-lg))

## Implementation Guide

### Required Technologies
1. HTML5
2. CSS3 with CSS Custom Properties
3. Modern JavaScript (ES6+)
4. Responsive Design Principles

### Setup Steps
1. Include base styles:
```html
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap" rel="stylesheet">
<link href="styles/main.css" rel="stylesheet">
```

2. Add required meta tags:
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

### Best Practices
1. Use semantic HTML
2. Follow BEM naming convention
3. Implement mobile-first approach
4. Optimize images and assets
5. Ensure accessibility compliance

## Assets

### Required Files
1. Logo (SVG format)
2. Background patterns
3. Social media icons
4. UI icons
5. Mascot illustration

### Image Guidelines
- Use SVG for icons and logos
- Optimize JPG/PNG for photos
- Implement lazy loading
- Provide responsive images

## Animation Guidelines

### Transitions
```css
/* Default transition */
transition: all 0.3s ease;

/* Button hover */
transform: scale(1.05);
transition: transform 0.2s;

/* Page transitions */
animation: fadeIn 0.4s ease-in;
```

## Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Contributing
Contributions are welcome! Please read our contributing guidelines before submitting changes.

## License
MIT License - feel free to use this design system in your projects.