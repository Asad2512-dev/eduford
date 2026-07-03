# Eduford University Landing Page

A premium, production-grade, and fully responsive university landing page built using only semantic HTML5 and vanilla CSS3. 

This project goes far beyond typical online tutorial templates. It has been redesigned and optimized by a Senior Frontend Engineer to showcase high-fidelity layout styling, responsive layouts across 7 specific viewport scales, modern glassmorphic headers, background floating keyframe animations, rich SEO meta tags, and WCAG-compliant accessibility configurations.

---

## Live Demo
👉 [Live Demo Link ](https://asad2512-dev.github.io/eduford/)

---

## Features

- **Modern Glassmorphic Sticky Header**: Floating navigation bar using `backdrop-filter` for a modern, glass-like transparency effect.
- **Mobile Glass Navigation Drawer**: Fully responsive mobile menu built with a pure CSS checkbox hack (no JavaScript required).
- **CSS Floating Glow Orbs**: Ambient glow circles in the hero background that use `@keyframes` animations to drift naturally.
- **Academic Program Cards**: Modern card designs for courses with glowing outlines, soft shadows, and clean hover shifts.
- **Overlay Zoom Campuses**: Interactive campus cards showcasing London, New York, and Tokyo with relative scaling transitions and slide-up meta text.
- **Premium Facilities Layout**: A structured grid showing libraries, sports arenas, and lounge cafes, with aspect-ratio constrained photos and zoom animations.
- **Accessible Testimonials Section**: Real student reviews structured using `<article>` semantic tags, star ratings, and clean avatars.
- **Dual-Action Call to Action**: Full-width gradient banner styled to increase admissions engagement.
- **Detailed Accessibility Integrations**: Skip-to-content links, visible keyboard outlines, ARIA attributes, semantic headings, and high contrast text ratios.
- **SEO & Social Optimization**: Configured Open Graph (OG) cards for Facebook, Twitter Cards, canonical links, keywords, and custom icon links.

---

## Technologies Used

- **HTML5**: Semantic tags, accessibility (skip-links, ARIA), SEO (meta, OG, Canonical).
- **CSS3**: CSS Custom Variables, Flexbox, Grid, custom CSS keyframe animations, glassmorphism filters, responsive media queries.
- **Font Awesome**: Clean vector icon fonts.
- **Google Fonts**: Plus Jakarta Sans & Playfair Display.

---

## Folder Structure

```
eduford/
├── index.html       # Main semantic landing page document
├── style.css        # Clean, modular CSS design system
├── images/          # Local high-fidelity generated images
│   ├── hero-bg.png
│   ├── campus-1.png
│   ├── campus-2.png
│   ├── campus-3.png
│   ├── facility-library.png
│   ├── facility-sports.png
│   ├── facility-cafeteria.png
│   ├── user1.png
│   └── user2.png
└── README.md        # Technical project documentation
```

---

## Installation & Local Execution

To run this project locally:
1. **Clone this repository**:
   ```bash
   git clone https://github.com/your-username/eduford.git
   ```
2. **Navigate into the directory**:
   ```bash
   cd eduford
   ```
3. **Run a local server** or double-click `index.html` to open it directly in a web browser.
   - For VS Code, right-click `index.html` and select **Open with Live Server**.

---

## Deployment Instructions

### GitHub Pages (Recommended)
1. Initialize git and push to your public GitHub repository.
2. Go to **Settings** > **Pages** inside the repository tabs.
3. Under **Build and deployment**, set the source to **Deploy from a branch** and select `main` (or `master`) and `/root`. Click **Save**.

### Netlify
- Drag and drop the `eduford/` directory directly into the Netlify Drop dashboard, or link your GitHub repository for automatic continuous integration. No build commands or configuration settings are needed.

### Vercel
- Import the repository into the Vercel dashboard. Vercel will automatically identify the project as a Static Web Page. Click **Deploy**.

---

## Learning Outcomes

- **Pure CSS Navigation Drawers**: Replaced traditional JS-toggled drawers with checkstate inputs for lightweight code loading.
- **Fluid Visual Hierarchy**: Utilized relative typography scales and modern line heights to optimize scanning readability.
- **Accessibility & Skip Links**: Implemented WCAG screen reader bypass targets (`.skip-link`) to support assistive keyboard controls.
- **Responsive Flex/Grid Layouts**: Built a layout that adapts across 320px, 375px, 425px, 768px, 1024px, 1440px, and ultra-wide displays.

---

## Future Improvements

- **Dark Mode Toggle**: Implement a CSS class toggle to support system dark/light modes.
- **Lazy Loading**: Set native `loading="lazy"` tags on below-the-fold images to speed up PageSpeed loads.
- **Form Validation**: Build a semantic contact form in the CTA section.

---

## Author
Developed and refactored by **Muhammad Asad Ullah**.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
# eduford
