# Senior High Secondary School Jammu Website

## Project Overview

The **Senior High Secondary School Jammu Website** is a professional, responsive, and feature-rich web application designed to showcase the institution's offerings, including academics, admissions, events, and community engagement. Built with **HTML**, **CSS**, and **JavaScript**, the website is tailored for accessibility, performance, and user experience, catering to students, parents, staff, and visitors. It consists of seven core pages (`index.html`, `about.html`, `academics.html`, `admissions.html`, `events.html`, `gallery.html`, `contact.html`), each with approximately 1000 lines of CSS and JavaScript for deep styling and interactivity.

This project emphasizes:
- **Responsive Design**: Optimized for devices from 320px mobile screens to 4K displays.
- **Accessibility**: WCAG-compliant with ARIA roles, keyboard navigation, and focus management.
- **Performance**: Lazy loading, debounced events, and optimized animations.
- **Interactivity**: Advanced navbar, sliders, modals, lightboxes, and form validation.
- **Modularity**: Organized code structure for maintainability and scalability.

## Table of Contents

- [Project Structure](#project-structure)
- [Features](#features)
  - [Shared Features](#shared-features)
  - [Page-Specific Features](#page-specific-features)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Development](#development)
- [Testing](#testing)
- [Accessibility](#accessibility)
- [Performance Optimizations](#performance-optimizations)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Structure

The project is organized as follows:

```
senior-high-school-jammu/
├── css/
│   └── styles.css          # Comprehensive CSS (~8000 lines) for all pages
├── js/
│   └── scripts.js         # Comprehensive JavaScript (~8000 lines) for interactivity
├── images/
│   ├── logo.png           # School logo
│   ├── hero-1.jpg         # Hero section images
│   ├── academics.jpg      # Placeholder images for sections
│   └── ...                # Additional images for gallery, cards, etc.
├── index.html             # Homepage
├── about.html             # About page
├── academics.html         # Academics page
├── admissions.html        # Admissions page
├── events.html            # Events page
├── gallery.html           # Gallery page
├── contact.html           # Contact page
└── README.md              # Project documentation
```

- **CSS**: A single `styles.css` file (~8000 lines) with shared styles, page-specific styling, and responsive media queries.
- **JavaScript**: A single `scripts.js` file (~8000 lines) with shared utilities and page-specific modules using IIFEs for encapsulation.
- **Images**: Placeholder images from `via.placeholder.com` (replace with actual school images).
- **HTML**: Seven pages with semantic markup, each styled and scripted for unique functionality.

## Features

### Shared Features

- **Advanced Navbar**:
  - Sticky navigation with hamburger toggle for mobile devices.
  - Multi-level dropdowns with mouse and keyboard support.
  - ARIA attributes for accessibility (`aria-expanded`, `aria-label`).
  - Smooth scroll for anchor links.
- **Theme Toggle**: Dark/light mode switch with local storage persistence.
- **Lazy Loading**: Images load only when in viewport using IntersectionObserver.
- **Back-to-Top Button**: Scroll-triggered button with smooth scroll to top.
- **Scroll Progress Indicator**: Visual indicator of scroll position.
- **Analytics Tracking**: Placeholder for tracking user interactions (extendable to Google Analytics).
- **Accessibility**:
  - Keyboard navigation for all interactive elements.
  - Focus trapping in modals and lightboxes.
  - ARIA roles and labels for screen readers.
- **Performance**:
  - Debounced and throttled event listeners for scroll and resize.
  - Optimized animations with requestAnimationFrame.

### Page-Specific Features

#### Index Page
- **Hero Section**: Dynamic background rotator, animated stats counter, and call-to-action buttons.
- **Quick Links**: Filterable grid with category-based animations.
- **Testimonials**: Responsive slider with auto-slide, touch support, and pause-on-hover.
- **News Ticker**: Dynamic updates with fade animations.
- **Scroll Animations**: IntersectionObserver-triggered slide-in effects for cards.
- **Additional Features** (expandable to ~1000 lines):
  - Featured programs carousel.
  - Alumni spotlight modal.
  - User testimonial submission form.
  - Interactive polls.
  - Social media feed integration.

#### About Page
- **Hero Section**: Unique gradient and animated text.
- **Mission/Vision**: Accordion with smooth transitions.
- **Timeline**: Scroll-triggered animations for history milestones.
- **Team**: Modals with dynamic bios and focus trapping.
- **Facilities**: Lightbox for images with zoom support.
- **Additional Features** (expandable to ~1000 lines):
  - Interactive history timeline with filters.
  - Values section with hover modals.
  - Accreditations carousel.
  - Facilities booking form.
  - Team contact form.

#### Academics Page
- **Hero Section**: Academic-themed gradient and CTAs.
- **Course Filter**: Category-based filtering with animations.
- **Curriculum Accordion**: Expandable sections for course details.
- **Extracurricular Grid**: Interactive cards with expandable details.
- **Programs Carousel**: Responsive carousel for special programs.
- **Additional Features** (expandable to ~1000 lines):
  - Faculty profiles modal.
  - Course schedule calendar.
  - Academic resources downloader.
  - Syllabus viewer with search.
  - Student progress tracker.

#### Admissions Page
- **Hero Section**: Admissions-themed gradient and CTAs.
- **Admission Steps**: Animated list with scroll triggers.
- **Form Validation**: Real-time validation for admission forms.
- **Fee Table**: Sortable table with highlighting.
- **Scholarship Checker**: Dynamic eligibility calculator.
- **Additional Features** (expandable to ~1000 lines):
  - Application status tracker.
  - FAQ accordion with search.
  - Document upload system.
  - Payment gateway placeholder.
  - Admissions chatbot.

#### Events Page
- **Hero Section**: Event-themed gradient and CTAs.
- **Event Calendar**: Dynamic rendering of events with category filters.
- **Registration Form**: Validation with error handling.
- **Gallery Preview**: Lightbox for event images.
- **Additional Features** (expandable to ~1000 lines):
  - RSVP system with local storage.
  - Event timeline with animations.
  - Social sharing buttons.
  - Live event streaming placeholder.
  - Event reminders.

#### Gallery Page
- **Hero Section**: Gallery-themed gradient and CTAs.
- **Slider**: Touch-supported slider with auto-slide and ARIA.
- **Masonry Grid**: Dynamic row spanning for images.
- **Lightbox**: Zoomable image viewer with captions.
- **Filter**: Category-based filtering with animations.
- **Additional Features** (expandable to ~1000 lines):
  - Pagination for large galleries.
  - Video gallery with player controls.
  - Image download system.
  - Zoom and pan functionality.
  - Gallery search by tags.

#### Contact Page
- **Hero Section**: Contact-themed gradient and CTAs.
- **Contact Form**: Real-time validation with email format checks.
- **FAQ Accordion**: Expandable FAQs with animations.
- **Interactive Map**: Animated iframe with ARIA labels.
- **Social Links**: Tracked clicks for analytics.
- **Additional Features** (expandable to ~1000 lines):
  - Social media widget with live feed.
  - Office hours toggle.
  - Feedback form with rating.
  - Live chat placeholder.
  - Multi-language support.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-repo/senior-high-school-jammu.git
   cd senior-high-school-jammu
   ```

2. **Set Up a Local Server**:
   Use a local server to avoid CORS issues with JavaScript:
   ```bash
   python -m http.server 8000
   ```
   or use tools like Live Server in VS Code.

3. **Replace Images**:
   Replace placeholder images in the `images/` folder with actual school images (e.g., `logo.png`, `hero-1.jpg`).

4. **Link Dependencies**:
   Ensure the following are included in each HTML file:
   ```html
   <link rel="stylesheet" href="css/styles.css">
   <script src="js/scripts.js"></script>
   <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;700&family=Montserrat:wght@700&display=swap" rel="stylesheet">
   ```

5. **Open in Browser**:
   Navigate to `http://localhost:8000` to view the website.

## Usage

- **Navigation**: Use the navbar to access all pages. On mobile, click the hamburger icon to toggle the menu.
- **Interactivity**: Engage with sliders, modals, lightboxes, and forms. All interactive elements support mouse, touch, and keyboard input.
- **Forms**: Complete forms (e.g., admission, registration, contact) with real-time validation. Alerts confirm successful submissions.
- **Gallery**: View images in the slider or grid, with lightbox support for zooming.
- **Accessibility**: Navigate using the keyboard (Tab, Enter, Space, Esc) and screen readers.
- **Theme Toggle**: Switch between light and dark modes using the theme toggle button.

## Dependencies

- **Google Fonts**: Poppins and Montserrat for typography.
- **No External Libraries**: The project uses vanilla HTML, CSS, and JavaScript for maximum compatibility and performance.
- **Placeholder Images**: Replace `via.placeholder.com` images with actual assets.

## Development

### Prerequisites
- Code editor (e.g., VS Code).
- Browser with developer tools (e.g., Chrome, Firefox).
- Local server (e.g., Python’s `http.server` or Live Server).

### Adding Features
- **Extend JavaScript**: Add new modules in `scripts.js` using IIFEs. Use `utils` for shared functions (`$`, `$$`, `on`, etc.).
- **Update CSS**: Modify `styles.css` for new styles, ensuring consistency with existing variables and animations.
- **New Pages**: Create new HTML files, link `styles.css` and `scripts.js`, and add page-specific JavaScript modules.
- **API Integration**: Replace mock data (e.g., news ticker, event calendar) with API calls using `fetch`.

### Code Style
- **JavaScript**: Follow ES6 standards, use camelCase, and include detailed comments.
- **CSS**: Use BEM naming, CSS custom properties, and modular structure.
- **HTML**: Use semantic elements (`<nav>`, `<section>`, `<article>`) and ARIA attributes.

## Testing

1. **Browser Compatibility**:
   - Test on Chrome, Firefox, Safari, and Edge.
   - Verify mobile responsiveness on devices (320px–1920px).

2. **Accessibility**:
   - Use screen readers (e.g., NVDA, VoiceOver) to test ARIA implementation.
   - Ensure keyboard navigation works for all interactive elements.

3. **Performance**:
   - Check lazy loading with browser developer tools (Network tab).
   - Monitor frame rates for animations using Performance tab.

4. **Functionality**:
   - Test form validation, sliders, modals, and lightboxes.
   - Verify event tracking in the console (extend to analytics service).

5. **Tools**:
   - Lighthouse for performance, accessibility, and SEO audits.
   - WAVE for accessibility evaluation.

## Accessibility

The website adheres to **WCAG 2.1** guidelines:
- **ARIA Roles**: Used for navbar, modals, sliders, and lightboxes.
- **Keyboard Navigation**: All interactive elements support Tab, Enter, Space, and Esc keys.
- **Focus Management**: Traps focus in modals and lightboxes.
- **High Contrast**: Focus states use high-contrast outlines.
- **Screen Reader Support**: Tested with NVDA and VoiceOver.

## Performance Optimizations

- **Lazy Loading**: Images load only when in viewport using IntersectionObserver.
- **Debouncing/Throttling**: Scroll and resize events are optimized to prevent performance bottlenecks.
- **Animations**: Use `requestAnimationFrame` for smooth animations.
- **Code Splitting**: JavaScript is modularized with IIFEs to reduce initial load.
- **Minification**: Minify `styles.css` and `scripts.js` for production using tools like Terser or CSSNano.

## Contributing

1. **Fork the Repository**:
   ```bash
   git fork https://github.com/your-repo/senior-high-school-jammu.git
   ```

2. **Create a Branch**:
   ```bash
   git checkout -b feature/your-feature
   ```

3. **Commit Changes**:
   Follow conventional commits (e.g., `feat: add event calendar`, `fix: navbar toggle bug`).
   ```bash
   git commit -m "feat: add new gallery filter"
   ```

4. **Push and Create Pull Request**:
   ```bash
   git push origin feature/your-feature
   ```
   Submit a pull request with a detailed description of changes.

5. **Code Review**:
   Ensure code follows style guidelines and passes tests.

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback:
- **Email**: info@seniorhighjammu.edu.in
- **Website**: [Senior High Secondary School Jammu](#) (replace with actual URL)
- **Maintainer**: [Your Name] (replace with actual maintainer details)

---

**Last Updated**: July 05, 2025

This README provides a comprehensive guide to the **Senior High Secondary School Jammu Website**. For further assistance, contact the maintainer or open an issue on the repository.