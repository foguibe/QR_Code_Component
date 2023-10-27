# Project Readme

## QR Code Component

This project represents a simple web page that displays a QR code and related information using HTML and CSS. It showcases several front-end development skills and best practices. Below, you'll find a detailed breakdown of the skills and techniques demonstrated in this project.

### HTML Structure

The `index.html` file provides the structure and content of the web page. Here's an overview of the HTML components used:

1. **Document Structure**: The HTML document is properly structured with the `<!DOCTYPE>` declaration, `<html>`, `<head>`, and `<body>` elements.

2. **Meta Tags**: The use of meta tags, including specifying the character set and viewport settings, ensures proper rendering and responsive behavior across devices.

3. **External Stylesheet Link**: An external CSS file is linked using `<link rel="stylesheet">` to separate content from presentation.

4. **Google Fonts Import**: The project imports a Google Font, 'Outfit,' to style text.

5. **Main and Footer Sections**: The content is structured using `<main>` and `<footer>` elements, promoting semantic HTML.

6. **Image Element**: An `<img>` element is used to display the QR code image with an `alt` attribute for accessibility.

7. **Hyperlinks**: The use of anchor tags (`<a>`) creates hyperlinks for reference to Frontend Mentor and the project creator's GitHub.

### CSS Styling

The `styles.css` file contains CSS rules that style the web page, adhering to modern web design best practices. It showcases the following skills:

1. **Box Sizing**: The universal selector (`*`) is used to set `box-sizing` to `border-box`, ensuring consistent box models.

2. **Margin Reset**: Default margins are reset to zero, preventing unexpected spacing between elements.

3. **Typographic Enhancements**: Improvements to typography are made, including line height and text rendering.

4. **Media Defaults**: Images, videos, and other media elements are configured to be responsive.

5. **Form Styling**: Built-in form styles are removed for a more consistent and customized look.

6. **Text Overflow Handling**: The CSS rule for text overflow (`overflow-wrap: break-word`) ensures text doesn't overflow its container.

7. **Root Stacking Context**: The project creates a root stacking context to control element rendering.

8. **Flexbox Layout**: The project utilizes Flexbox for the main content, making it responsive and centered vertically and horizontally.

### Specific Styles

#### Body

- `display: flex` and `flex-direction: column` are used to create a responsive layout with a vertical flow.
- The background color is set using HSL.
- Appropriate margin and font-family ('Outfit') are defined for the entire page.

#### Main Section

- Flex properties are applied to `main` to make it the primary content area.

#### QR Code Container

- The container around the QR code has a background color, padding, and border-radius for a clean presentation.
- Margin and text alignment are adjusted for the `h1` and `p` elements.

#### Footer

- Font size and text alignment are adjusted for the footer.
- Hyperlinks are styled with color and a consistent text style.

### Acknowledgments

This project is a coding challenge by [Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H) and was coded by [Fortune Oguibe](https://github.com/foguibe).
