# CS300-Assignment-1

## Author
**Name:** Aliya Khan

## Component Choice
**Selected Component:** Profile Card

## Live Site
[View Live Site on GitHub Pages](https://abkhan79.github.io/CS300-Assignment-1/Profile_Card.html)

## Design Choices

### Layout & Structure
- **Semantic HTML5:** Used `<article>`, `<header>`, `<section>`, `<footer>`, `<nav>`, and `<figure>` elements for proper document structure and accessibility.
- **Responsive Design:** Implemented media queries for mobile devices (screens under 420px width).

### Styling
- **Color Scheme:** Vibrant gradient banner (purple to magenta) with high-contrast text on white background for accessibility (WCAG AA compliant).
- **Typography:** Google Fonts "Poppins" with multiple weights (300, 400, 600, 700) for visual hierarchy and readability.
- **Box Model:** Demonstrated margin, padding, and border properties throughout:
  - Avatar circle: 5px padding, 4px white border
  - Card body: 68px top padding for avatar overlap
  - Social links: 40px height/width with spacing

### Avatar Styling
- **Profile Image:** Flower image with `object-fit: cover` and `object-position: center` for proper centering.
- **Positioning:** Avatar positioned at 42% from left, overlapping the gradient banner and white content area.
- **Circular Crop:** 96px diameter with rounded corners and white background/border for visual separation.

### Interactive Elements
- **Hover Effects:**
  - Social media icons: transform with `translateY(-4px)`, color change, and shadow effect on hover/focus.
  - Card: subtle lift effect with `translateY(-6px)` on hover.
- **Transitions:** Smooth 180-200ms ease transitions for all interactive states.

### Accessibility
- **ARIA Labels:** Proper `aria-label` attributes on social media links and navigation.
- **Alt Text:** Descriptive alt text for profile image.
- **Focus States:** Visible 3px outline on social links for keyboard navigation.
- **Semantic HTML:** Proper heading hierarchy (h1 for name, h2 for role).

### CSS Selectors Used
- **Element Selectors:** `html`, `body`, `h1`, `h2`, `p`
- **Class Selectors:** `.profile-card`, `.card-header`, `.banner`, `.avatar-wrap`, `.avatar`, `.card-body`, `.social-link`, etc.
- **Descendant Selectors:** `.card-body p`, `.social ul`, `.social li a`
- **Pseudo-classes:** `:hover`, `:focus`

### External Files
- **HTML:** `Profile_Card.html` (semantic structure with comments)
- **CSS:** `styles.css` (external stylesheet with responsive design)
- **Images:** Flower image sourced from Unsplash (can be replaced with local images in `/images` folder)

## Notes
- The profile card matches the provided reference design with the avatar overlapping the gradient banner.
- All styling is in an external stylesheet for better maintainability and separation of concerns.
- The design is fully responsive and accessible for all users. 
