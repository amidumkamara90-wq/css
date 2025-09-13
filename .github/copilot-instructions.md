# Copilot Instructions for This CSS Project

## Project Overview
This project demonstrates core CSS concepts, including the box model, text and font styling, link customization, and list formatting. It consists of a single HTML file (`css.html`) and a CSS stylesheet (`main.css`).

## File Structure
- `css.html`: Main HTML file. Links to `main.css` and contains sample content (headings, lists, paragraphs, and a link) to showcase CSS features.
- `main.css`: Stylesheet with custom styles for body, headings, paragraphs, lists, and more. Uses Google Fonts and modern CSS features (e.g., `hwb` color, box-shadow, border-radius).

## Key Patterns & Conventions
- **Font Management**: Uses `@import` to load the Roboto font from Google Fonts. Default font for body is Roboto, with fallbacks.
- **Box Model**: Demonstrates padding, margin, border, and box-shadow on elements like `h1` and `ul`.
- **Color Usage**: Uses modern CSS color functions (e.g., `hwb`, `rgba`) and custom color schemes for different elements.
- **Semantic HTML**: Content is organized with semantic tags (`h1`, `h2`, `ul`, `li`, `p`, `a`).
- **No Build Tools**: This project is static. No build, test, or dependency management tools are present or required.

## Developer Workflow
- **Edit `main.css`** to update or add styles. Changes are reflected immediately in the browser.
- **Edit `css.html`** to modify content or structure.
- **Preview**: Open `css.html` directly in a browser to view changes. No server or build step is needed.

## Project-Specific Notes
- **No JavaScript**: This project is CSS/HTML only. Do not add JavaScript unless explicitly requested.
- **No Frameworks**: No CSS frameworks (e.g., Bootstrap) are used. All styles are custom.
- **Accessibility**: Use semantic HTML and readable color contrasts when extending the project.
- **Extending**: Add new sections to `css.html` and style them in `main.css` following the existing patterns.

## Example: Adding a Styled Section
1. Add a new section to `css.html`:
   ```html
   <section class="about">About this project...</section>
   ```
2. Add styles in `main.css`:
   ```css
   .about {
     background: #f0f0f0;
     padding: 20px;
     border-radius: 10px;
   }
   ```

## References
- `css.html` (structure)
- `main.css` (styling patterns)

---
For questions or major changes, consult the project owner.
