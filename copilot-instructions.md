# AI Agent Instructions for CallCenter Pro Website

## Project Overview
This is a website for CallCenter Pro, a call center solutions provider. The site is built using vanilla HTML, CSS, and JavaScript with a focus on clean, responsive design.

## Key Design Patterns

### Color System
The project uses a consistent color palette defined as CSS variables:
```css
--azul-escuro: #1a3a5f  /* Dark blue - Primary color */
--azul-medio: #2c5a8c   /* Medium blue - Secondary color */
--azul-claro: #4a8cd6   /* Light blue - Accent color */
--vermelho: #e63946     /* Red - Call-to-action color */
--branco: #ffffff       /* White */
--cinza-claro: #f5f5f5  /* Light gray - Background */
--cinza-escuro: #333333 /* Dark gray - Text */
```
When making changes, maintain this color scheme for consistency.

### Layout Structure
- Uses `.container` class for content width control (90% width, max 1200px)
- Responsive design with mobile-first approach
- Sticky header with z-index handling for proper layering

### Component Patterns
1. **Buttons**: Use the `.btn-contato` class pattern for call-to-action buttons:
   ```css
   .btn-contato {
       background-color: var(--vermelho);
       color: var(--branco);
       padding: 10px 20px;
       border-radius: 5px;
       /* Include hover transitions */
   }
   ```

2. **Navigation**: Horizontal menu with hover effects and proper spacing

## CSS Conventions
- BEM-like naming convention for classes
- CSS variables for colors and reusable values
- Consistent use of padding/margin units
- Transitions for interactive elements (0.3s duration)

## Common Development Tasks
1. To add new sections, follow the existing container pattern and spacing conventions
2. Match typography using 'Segoe UI' font family with provided fallbacks
3. Maintain responsive layout patterns using existing breakpoints

## File Organization
- `Allo.html` - Main HTML file containing structure and inline styles
- Consider moving styles to a separate CSS file as the project grows

Need more information or clarification on any of these sections? Let me know what aspects need expansion or adjustment.