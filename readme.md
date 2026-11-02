# SMK Beauty Bar - Part 2

## Project Overview
SMK Beauty Bar is a five-page beauty salon website for Springs, Gauteng. Part 2 improves the Part 1 website by adding an external CSS stylesheet, desktop layout styling, responsive breakpoints, typography, visual states and responsive images.

## Pages
- `index.html` - Home
- `about.html` - About Us
- `pricelist.html` - Services & Pricing
- `enquiry.html` - Book Appointment
- `contact.html` - Contact Us

## Part 2 Requirements Implemented
### External stylesheet
All five HTML pages are linked to the shared `style.css` file. A consistent naming convention is used throughout the stylesheet.

### Base styling
- CSS reset using the universal selector.
- Consistent font family, font sizing, line height, colours and spacing.
- Responsive images using `max-width: 100%`.

### Typography
The site uses `font-family`, `font-size`, `font-weight`, `line-height`, `letter-spacing` and responsive `clamp()` sizing for headings.

### Layout
- Flexbox is used for the navigation.
- CSS Grid is used for highlights, galleries, the About page and contact layout.
- Cards, sections and tables have consistent spacing and visual hierarchy.

### Visual styles
- Background colours, borders and box shadows are applied consistently.
- `:hover` and `:focus-visible` states are included for interactive elements.
- Tables have alternating rows and hover feedback.

### Responsive design
Breakpoints are provided for:
- Desktop: above 800px
- Tablet: 520px to 800px
- Mobile: 520px and below

On smaller screens, multi-column sections switch to single-column layouts and navigation becomes vertical.

### Relative units
The stylesheet uses `%`, `rem`, `vw`, `min()`, `clamp()` and flexible grid units where appropriate.

### Responsive images
Image variants were created at approximately 400px and 800px widths and connected with `srcset` and `sizes`. The home page also demonstrates the `picture` element.

## Part 1 Feedback Changelog
| Date | Change | Reason |
|---|---|---|
| 18 September 2026 | Corrected navigation links so every page points to `pricelist.html` for Services & Pricing. | Prevent broken navigation from the Part 1 version. |
| 18 September 2026 | Corrected invalid/misplaced HTML in the price-list page, including the image section being placed inside a table row. | Improve HTML structure and browser rendering. |
| 18 September 2026 | Added missing `alt` text to images and improved form labels. | Improve accessibility and semantic quality. |
| 18 September 2026 | Removed inline layout styling and moved presentation into `style.css`. | Meet the Part 2 external stylesheet requirement. |
| 18 September 2026 | Added responsive layouts for desktop, tablet and mobile. | Meet the responsive design requirement. |

> If your lecturer gave you specific Part 1 feedback not listed above, add each feedback item and the exact correction you made as another row in this table.

## Responsive Testing Evidence
Use browser developer tools to test the website at the following sizes and add your screenshots to the repository:

### Desktop
**Suggested test size:** 1920 × 1080
- Navigation displays horizontally.
- Grid sections display multiple columns.
- Tables remain readable with horizontal scrolling available where necessary.

### Tablet
**Suggested test size:** 768 × 1024
- Navigation remains usable.
- Multi-column sections reduce to fewer columns.
- Images scale to the available width.

### Mobile
**Suggested test size:** 390 × 844
- Navigation changes to a vertical layout.
- Content changes to one column.
- Images scale without overflowing the viewport.
- Form fields remain usable on a small screen.

### Screenshot checklist
Add screenshots such as:
- `screenshots/desktop-home.png`
- `screenshots/tablet-home.png`
- `screenshots/mobile-home.png`
- `screenshots/mobile-pricelist.png`

## References
- MDN Web Docs - CSS: https://developer.mozilla.org/en-US/docs/Web/CSS
- MDN Web Docs - CSS media queries: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries
- MDN Web Docs - Responsive images: https://developer.mozilla.org/en-US/docs/Web/HTML/Guides/Responsive_images
- MDN Web Docs - CSS Grid Layout: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout
- MDN Web Docs - Flexbox: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_flexible_box_layout

## GitHub Submission
Before submission:
1. Save all changes.
2. Test every page and every navigation link.
3. Add responsive screenshots to the `screenshots` folder.
4. Update this README with any additional Part 1 feedback corrections.
5. Commit using a descriptive message, for example: `Complete Part 2 responsive CSS styling`.
6. Push the changes to the remote GitHub repository.
7. Submit the GitHub repository link through the Learning Management System.
