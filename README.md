Frontend Mentor - Single price grid component solution
This is a clean, responsive, and modern solution to the Single price grid component challenge on Frontend Mentor.

Links
Solution URL: https://github.com/veon321/Single-price-grid-component

Live Site URL: https://veon321.github.io/Single-price-grid-component/

Built with
Semantic HTML5 markup (including <article> container, proper accessibility headers, and structured unordered lists)

CSS Custom Properties (Variables) for a clean, design-guide compliant color palette and centralized font management

Flexbox layout for structural grid alignment and layout axis swapping

Modern CSS Math Functions (clamp()) for fluid typography and responsive scaling without rigid text jumps

Google Fonts (Karla)

Features
Nested Flexbox Architecture: By utilizing a primary flex container for vertical stacking and a secondary .card-bottom wrapper, the layout creates a flawless asymmetrical grid layout on desktop screens.

Fluid Typography & Adaptive Padding: The main headers (h1, h2), text descriptions, and internal section paddings scale fluidly using clamp(). This ensures the card shrinks gracefully on smaller tablets and laptops before hitting the main mobile breakpoint.

Responsive Axis Swapping: A clean, lightweight media query swaps the direction of the bottom panel to flex-direction: column at 600px, instantly restructuring the layout into a highly readable vertical format for mobile devices.

Accessible Text Contrast: Text opacities and subtle color variables are finely tuned for the pricing section and features list to ensure web accessibility (WCAG) compliance while staying true to the original design assets.

Robust Screen Centering: The component stays perfectly centered both vertically and horizontally via modern min-height: 100vh on the body for a clean desktop presentation, adapting smoothly to a flexible height on mobile platforms.
