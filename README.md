# 404-Found---Team-Portfolio
Team portfolio site: https://srujan338.github.io/TeamPortfolio/

Members:

1) Name: Divyansh

Corpus username: divyansh1071

Contributions:
- Implemented the *scroll progress bar* at the top of the page using a scroll event listener that calculates how far down the page the user has scrolled and updates the bar width in real time.
- Built the *active navigation highlighting* system using IntersectionObserver — as the user scrolls through sections, the corresponding nav link automatically gets highlighted.
- Wrote the *animated stat counters* (team members, technologies, projects, cups of coffee) that count up from zero when the hero section enters the viewport, using requestAnimationFrame for smooth easing.
- Implemented the *scroll reveal animations* — elements fade up into view as they enter the viewport, using IntersectionObserver to add a .visible class only when needed (no layout thrash, no unnecessary repaints).
- Built the *skill tab switcher, **project filter* (All / In progress / Shipped / Planned), and *resume tab switcher* — all three use the same pattern of toggling active classes and showing/hiding panels cleanly.
- Set up the *Git repository structure*, defined the branching strategy the team follows, and managed merge conflicts during collaborative editing.
- Did a *performance and cross-browser review* pass — checking that animations don't fire on hidden elements, that the progress bar doesn't block rendering, and that the JS degrades gracefully if a section ID is missing.

2) Name: Srujan

Corpus username: srujan

Contributions:
- Designed the full *visual identity* of the site — colour palette, typographic scale (Instrument Serif for headings, Inter for body), spacing system, and border-radius conventions — all encoded as CSS custom properties in :root so the whole site can be re-themed by changing one block.
- Built every *UI component* in semantic HTML and CSS: the sticky nav with blur backdrop, hero section with animated badge and stat counters, team cards with colour-coded top accent borders, skills map with progress bars, goals grid, project cards with status badges, working-style tiles, open source section, and the full resume viewer with tab switching.
- Implemented the *dark theme* — carefully choosing background, surface, border, text, and accent colours that maintain contrast ratios and feel cohesive rather than just inverting the light theme.
- Made the entire site *fully responsive* — at mobile widths, the nav collapses, multi-column grids drop to single column, the resume header stacks vertically, and font sizes scale with clamp().
- Handled *micro-interactions* — card hover lifts with box-shadow and translateY, goal cards that border-highlight on hover, filter buttons with smooth colour transitions, and the fade-in animation for resume panels.
- Iterated through *multiple design revisions* based on feedback from Divyansh and Akshara, refining card layouts, tightening spacing, and improving readability of the skills section.
