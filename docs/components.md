# Component Documentation

This document provides detailed information about the components available in the Swaragh Design System.

## Table of Contents
- [Buttons](#buttons)
- [Navigation](#navigation)
- [Hero Section](#hero-section)
- [Cards](#cards)

## Buttons

Buttons are used for actions and navigation. They come in different variants to indicate importance and purpose.

### Primary Button

```html
<button class="sw-button sw-button--primary">Primary Button</button>
```

**Properties:**
- Background: var(--primary-blue)
- Text Color: var(--text-light)
- Padding: var(--spacing-sm) var(--spacing-lg)
- Border Radius: var(--radius-md)
- Hover Effect: Scale transform

### Secondary Button

```html
<button class="sw-button sw-button--secondary">Secondary Button</button>
```

**Properties:**
- Background: var(--accent-gold)
- Text Color: var(--text-dark)
- Padding: var(--spacing-sm) var(--spacing-lg)
- Border Radius: var(--radius-md)
- Hover Effect: Scale transform

## Navigation

The navigation component provides a consistent header with logo and menu items.

```html
<header class="sw-header">
    <nav class="sw-container sw-nav">
        <div class="sw-logo">
            <img src="../assets/logo.svg" alt="Swaragh Logo" width="150">
        </div>
        <ul class="sw-nav-items">
            <li><a href="#home">Home</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
            <li><button class="sw-button sw-button--primary">Get Started</button></li>
        </ul>
    </nav>
</header>
```

**Properties:**
- Fixed Position
- White Background
- Subtle Shadow
- Responsive Menu
- Hover Effects on Links

## Hero Section

The hero section is the main landing area of the website, featuring a gradient background and pattern overlay.

```html
<section class="sw-hero sw-fade-in">
    <div class="sw-container sw-hero__content">
        <h1 class="sw-hero__title">
            Transform Your Business with
            <span class="sw-hero__highlight">Innovative Solutions</span>
        </h1>
        <p>Description text here</p>
        <div class="sw-hero__cta-group">
            <button class="sw-button sw-button--primary">Get Started</button>
            <button class="sw-button sw-button--secondary">Learn More</button>
        </div>
    </div>
</section>
```

**Properties:**
- Gradient Background
- Pattern Overlay
- Centered Content
- Responsive Layout
- Fade-in Animation

## Cards

Cards are used to group related content and actions.

```html
<div class="sw-card">
    <h3 class="sw-card__title">Card Title</h3>
    <p>Card content goes here</p>
</div>
```

**Properties:**
- White Background
- Border Radius: var(--radius-lg)
- Box Shadow: var(--shadow-md)
- Padding: var(--spacing-lg)

## Best Practices

1. **Consistency**
   - Use the provided CSS variables for colors, spacing, and typography
   - Maintain consistent naming conventions with the `sw-` prefix
   - Follow the established component patterns

2. **Accessibility**
   - Include proper ARIA labels where needed
   - Maintain sufficient color contrast
   - Ensure keyboard navigation works properly

3. **Responsive Design**
   - Test components at all breakpoints
   - Use the provided media queries
   - Follow mobile-first approach

4. **Performance**
   - Optimize images before use
   - Minimize DOM nesting
   - Use CSS animations sparingly

## Browser Support

The design system supports all modern browsers:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

When creating new components:
1. Follow the established naming conventions
2. Document the component in this file
3. Include example usage
4. Add responsive styles
5. Test across supported browsers