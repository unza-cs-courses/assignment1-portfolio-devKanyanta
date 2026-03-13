[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/8NpkA7e4)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=22797279&assignment_repo_type=AssignmentRepo)
# Assignment 1: Responsive Portfolio Website

**Course:** CSC4035 Web Programming and Technologies
**Weight:** 5% of final grade
**Due:** Week 6, Friday 11:59 PM

---

## Overview

Create a professional, responsive portfolio website showcasing your skills, projects, and contact information. This assignment assesses your HTML5 and CSS3 skills, including semantic markup, modern layout techniques (Flexbox/Grid), and responsive design principles.

**Important:** No CSS frameworks (Bootstrap, Tailwind, etc.) are allowed. All CSS must be hand-written.

---

## Requirements

### Functional Requirements

Your portfolio must include **4 or more sections**:

| Section | Required Content |
|---------|------------------|
| **Home/Hero** | Your name, tagline, and call-to-action button |
| **About** | Professional bio (150+ words), profile image, skills list |
| **Projects** | Minimum 3 project cards with title, description, image, and links |
| **Contact** | Contact form with validation attributes (name, email, message) |

### Technical Requirements

| Requirement | Description |
|-------------|-------------|
| **HTML5** | Valid semantic HTML (header, nav, main, section, article, footer) |
| **CSS3** | External stylesheet only (no inline styles) |
| **CSS Variables** | Use custom properties for colors and spacing |
| **Flexbox** | Use for at least one layout component |
| **CSS Grid** | Use for at least one layout component |
| **Responsive** | Mobile-first with minimum 3 breakpoints |
| **Accessibility** | Alt text, form labels, color contrast, heading hierarchy |

### Breakpoints Required

```css
/* Mobile-first base styles */

/* Tablet (768px and up) */
@media (min-width: 768px) { }

/* Desktop (1024px and up) */
@media (min-width: 1024px) { }

/* Large Desktop (1200px and up) - optional */
@media (min-width: 1200px) { }
```

---

## Project Structure

```
csc4035-assignment1-portfolio/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # Main stylesheet
├── images/             # Your images (profile, projects, etc.)
├── screenshots/        # Screenshots at different breakpoints
│   ├── mobile.png
│   ├── tablet.png
│   └── desktop.png
└── README.md           # This file (update with your info)
```

---

## Getting Started

1. **Clone this repository** to your local machine
2. **Open `index.html`** in your code editor
3. **Complete the TODO comments** in each file
4. **Test responsiveness** using browser developer tools
5. **Take screenshots** at mobile, tablet, and desktop sizes
6. **Commit and push** your changes regularly

---

## Grading Rubric (100 points)

| Criterion | Points | Description |
|-----------|--------|-------------|
| **HTML Structure & Semantics** | 20 | Valid HTML5, semantic elements, proper document structure |
| **CSS Styling & Design** | 20 | Professional design, cohesive color scheme, typography |
| **Flexbox & Grid Usage** | 20 | Both techniques used appropriately and effectively |
| **Responsive Design** | 20 | Mobile-first, 3+ breakpoints, no horizontal scrolling |
| **Content & Completeness** | 10 | All sections complete with quality content |
| **Code Quality** | 10 | Clean, organized, well-commented code |

### Automated Tests (40% of grade)

The following are checked automatically on each push:
- HTML validation (no errors)
- Required HTML elements present
- CSS file linked correctly
- Required sections exist
- Responsive meta tag present

---

## Submission Checklist

Before submitting, verify:

- [ ] All 4 sections are complete (Home, About, Projects, Contact)
- [ ] HTML validates with no errors
- [ ] CSS uses custom properties (variables)
- [ ] Flexbox is used for at least one component
- [ ] CSS Grid is used for at least one component
- [ ] Site is responsive at all breakpoints
- [ ] All images have alt text
- [ ] Form inputs have labels
- [ ] Screenshots added to `/screenshots` folder
- [ ] README updated with your information

---

## Your Information

**Name:** Mapalo Kanyanta
**Student ID:** 2022063457
**Design Theme:** Modern, minimalist portfolio with dark mode support

### CSS Techniques Used
- [x] CSS Custom Properties
- [x] Flexbox
- [x] CSS Grid
- [x] Media Queries
- [x] Dark/Light Mode Toggle (CSS + JavaScript)
- [x] CSS Animations/Transitions
- [x] CSS-only Hamburger Menu
- [x] Print Stylesheet

### Features Implemented

#### Core Requirements
- Semantic HTML5 structure with proper elements (header, nav, main, sections, footer)
- Professional, responsive design with mobile-first approach
- 3+ breakpoints (mobile, tablet, desktop)
- CSS Variables for consistent theming
- Flexbox used for navigation, hero section, and footer layouts
- CSS Grid used for project cards, services, and about sections
- Form with validation attributes
- Accessibility features (skip link, ARIA labels, alt text)

#### Bonus Features
1. **Dark Mode Toggle** (+3%)
   - Toggle button in header with sun/moon icons
   - Respects system color scheme preference on first visit
   - Preference saved in localStorage for persistence
   - Comprehensive dark mode styling for all components

2. **CSS Animations & Transitions** (+3%)
   - Fade-in animations on page load
   - Smooth hover effects on buttons and cards
   - Transition effects on all interactive elements

3. **CSS-only Hamburger Menu** (+2%)
   - Responsive navigation menu
   - No JavaScript required for toggle functionality
   - Smooth transitions on mobile devices

4. **Print Stylesheet** (+2%)
   - Optimized print layout
   - Hides non-essential elements (buttons, navigation)
   - Clean, printer-friendly styling

### Challenges & Solutions

1. **Dark Mode Implementation**
   - Challenge: Ensuring all text and backgrounds have proper contrast in both light and dark modes
   - Solution: Created comprehensive CSS custom properties for dark mode, applied scoped selectors to `html.dark-mode` class

2. **Responsive Design**
   - Challenge: Making layout work across all device sizes without frameworks
   - Solution: Mobile-first approach with CSS Grid and Flexbox, media queries for breakpoints

3. **Form Styling in Dark Mode**
   - Challenge: Making form inputs visible and usable in dark mode
   - Solution: Added specific dark mode styles for inputs, textareas, and focus states with proper color contrast

### Credits
- Google Fonts: Inter (for body text) and Space Grotesk (for headings)
- Icons: SVG icons for dark mode toggle, hamburger menu, and social links
- Responsive Design Inspiration: Modern portfolio best practices
- All images: Personal portfolio images

---

## Academic Integrity

- All code must be your own work
- No CSS frameworks or libraries allowed
- Images must be royalty-free or your own (credit sources)
- Plagiarism detection tools will be used

**Violations result in zero marks and academic misconduct reporting.**

---

## Extension Opportunities (Bonus: up to +10%)

- Dark/light mode toggle with CSS (+3%)
- CSS animations/transitions (+3%)
- CSS-only hamburger menu (+2%)
- Print stylesheet (+2%)
