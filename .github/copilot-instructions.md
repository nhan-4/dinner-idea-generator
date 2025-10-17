# AI Agent Instructions for Dinner Idea Generator

## Project Overview
A web-based application that helps users generate dinner ideas. The project uses vanilla HTML/CSS/JavaScript with a focus on simplicity and clean design.

## Architecture
- Single-page application (SPA) structure
- Core files:
  - `index.html`: Main entry point and UI structure
  - Static assets will be placed in their respective directories when added

## Design System
The project uses CSS custom properties for consistent theming:
```css
--primary-color: #FF6B6B    // Used for main headings and CTAs
--secondary-color: #4ECDC4  // Used for accents and highlights
--bg-color: #f8f9fa        // Page background
--text-color: #2C3E50      // Main text color
```

## Conventions
### HTML/CSS
- BEM-like class naming convention is used
- Semantic HTML elements preferred over generic divs/spans
- Mobile-first responsive design approach
- CSS custom properties for theming and maintainability

### Styling Guidelines
- Container max-width: 800px
- Border-radius: 20px for major containers
- Font stack: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif
- Consistent spacing using padding/margin in multiples of 10px (10px, 20px, etc.)

## Development Workflow
1. Make changes to the HTML/CSS/JS files directly
2. Test changes in a browser
3. Ensure mobile responsiveness

## Important Considerations
- Keep accessibility in mind when making UI changes
- Maintain clean, semantic HTML structure
- Follow the established color scheme and spacing patterns
- Consider mobile devices as a primary use case