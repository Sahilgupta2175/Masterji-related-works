# Live link: https://mintlify-landing-page-sg.vercel.app/

# Mintlify Documentation Landing Page Clone

A pixel-perfect recreation of the Mintlify.com landing page, built with HTML5 and CSS3.

## 🎯 Project Overview

This project is a responsive clone of the Mintlify Documentation Platform landing page, showcasing modern web design principles, clean code structure, and professional UI/UX implementation with smooth animations and interactive elements.

---

## 📋 Sections Recreated

### ✅ **1. Navigation Header**
- Fixed position navigation bar with glassmorphism effect
- Backdrop blur with semi-transparent background
- Mintlify logo with brand identity
- Center navigation menu (Features, Customers, Docs, Pricing)
- Contact Sales and Start for Free CTA buttons
- Glass-morphism border with shadow

### ✅ **2. Hero Section**
- Blog Autopilot announcement badge with hover animation
- Main headline: "The modern standard for documentation"
- Subtitle with compelling value proposition
- Email input field with integrated CTA button
- Large hero showcase image with blue glow shadow
- Centered layout with optimal spacing

### ✅ **3. Company Trust Section**
- 8 partner company logos in responsive grid:
  - Anthropic, Coinbase, X, Kalshi
  - Perplexity, Ramp, Nvidia, OpenAI
- 4-column grid layout
- Professional spacing and alignment

### ✅ **4. Feature Cards Section**
- **LLMs.txt Feature**: AI-friendly documentation format
  - Animated code snippet visualization
  - Brand green accent color
  - Interactive card with hover lift effect

- **Agent Feature**: Code-aware AI assistant
  - Terminal/command interface preview
  - Real-time suggestion mockup
  - Smooth transitions on hover

- **Assistant Feature**: Full-width feature card
  - AI chat interface screenshot
  - Complete documentation integration
  - Border glow effect on hover

### ✅ **5. Enterprise Reinvention Section**
- "Enterprise reinvention" heading
- Description: "Create clarity for your users..."
- Explore Enterprise CTA button with icon
- Partner & Compliance cards:
  - Partner card: "Work with an expert in your industry"
  - Compliance card: Security certifications

### ✅ **6. Interactive Content Section**
- Large background image with overlay
- Statistics overlay:
  - "20k+" - Hours saved
  - "1M+" - Questions answered
- "Read the case study" link with arrow
- Transform scale on hover

### ✅ **7. Customer Testimonials**
- "Customer stories" heading with section description
- 3 testimonial cards with carousel navigation:
  - Perplexity AI testimonial
  - X (Twitter) testimonial
  - Kalshi testimonial
- Company logos with background images
- Quote text and "Read more" links
- Left/right navigation dots

### ✅ **8. Pricing Section**
- "Flexible pricing, from hobbyists to enterprises" heading
- Two CTA buttons:
  - "View pricing" (primary)
  - "Talk to sales" (secondary with border)
- Three pricing cards:
  - Pricing icon with description
  - Building/enterprise icon with description
  - Vertical separator lines

### ✅ **9. Footer Section**
- **Social Media Links**: LinkedIn, X/Twitter, GitHub icons
- **5 Navigation Columns**:
  - Product (Features, Integrations, Changelog)
  - Resources (Docs, Community, Blog)
  - Solutions (Enterprise, Startups, Personal)
  - Guides (Getting Started, Analytics)
  - Company (About, Careers, Contact)
- **Security Badge**: "Backed by enterprise-grade security" with circular badge
- **Status Bar**:
  - Green status indicator with "All systems normal"
  - Copyright text "© 2026 Mintlify, Inc."
  - Theme switcher (System/Light/Dark)

---

## 🎨 Design System

### **Typography**
- **Font Family**: `'Segoe UI', Tahoma, Geneva, Verdana, sans-serif`
- **Headings**:
  - H1: 54px, font-weight: 600
  - H2: 40px, font-weight: 600
  - H3: 32px, font-weight: 500
  - H4: 24px, font-weight: 400-500
- **Body Text**: 14-18px
- **Line Heights**: 1.3 - 1.6 (optimized for readability)
- **Letter Spacing**: -2px (for large headings), 0.2-0.5px (body)

### **Color Palette**

#### Text Colors
```css
--text-color: #ffffff                    /* Primary text - Pure white */
rgba(255, 255, 255, 0.7)                 /* Secondary text - Transparent white */
#808080, #808080ee                       /* Muted text - Gray shades */
#dfdede                                  /* Footer links - Off-white */
```

#### Background Colors
```css
--body-bg-color: #08090B                 /* Main background - Deep black */
--footer-bg-color: #151616              /* Footer - Dark charcoal */
#1f2121af                                /* Enterprise section - Transparent dark */
#4e4d4d42                                /* Footer container - Semi-transparent */
```

#### Accent & Brand Colors
```css
--mintlify-feature-card-text-color: #2CE19A    /* Brand green - Primary accent */
--blog-span-bg-color: #098d5d                  /* Badge green - Emerald */
rgba(44, 225, 154, 0.1)                        /* Hover background - Subtle green */
rgba(44, 225, 154, 0.4)                        /* Border hover - Green glow */
```

#### Button Colors
```css
--btn-bg-color: #ffffff                  /* Button background - White */
--btn-bg-hover-color: #D9D9D9           /* Button hover - Light gray */
rgba(61, 61, 62, 0.3)                    /* Secondary button - Transparent dark */
```

#### Input & Interactive Elements
```css
--email-input-bg-color: #80808066       /* Input field - Transparent gray */
rgba(255, 255, 255, 0.6)                 /* Placeholder text */
#32343477                                /* Status badge background */
```

#### Border & Effects
```css
rgba(128, 128, 128, 0.3)                 /* Card borders - Subtle */
rgba(255, 255, 255, 0.1)                 /* Navbar border - Glass effect */
#80808031                                /* Divider lines */
```

---

## 🎯 Key Features Implemented

### **Advanced Animations**
- Smooth 0.3s transitions on all interactive elements
- Card lift effects: `translateY(-4px)` on hover
- Button elevation with dynamic shadows
- Transform animations: scale, translate
- Glass-morphism navbar with backdrop blur

### **Interactive Elements**
- Navigation links: Color change to brand green
- Feature cards: Border glow + shadow + lift
- Buttons: Elevation with shadow enhancement
- Customer cards: 8px vertical lift with shadow
- Social icons: Brightness increase + lift
- Footer links: Slide right 4px on hover

### **Visual Effects**
- **Hero Image**: Dual-layer shadow (blue glow + depth)
- **Cards**: Green glow on hover `0 8px 24px rgba(44, 225, 154, 0.1)`
- **Navbar**: Glass effect with `backdrop-filter: blur(10px)`
- **Buttons**: White glow shadow on hover
- **Images**: Transform scale and opacity changes

### **Accessibility**
- Semantic HTML5 structure (`<header>`, `<main>`, `<footer>`, `<section>`)
- Descriptive alt text for all images
- Proper heading hierarchy (h1 → h2 → h3 → h4)
- ARIA attributes where appropriate
- Focus states on interactive elements

### **Performance Optimizations**
- Clean CSS with CSS custom properties
- Minimal JavaScript (none required)
- Hardware-accelerated transforms
- Efficient CSS selectors
- Smooth scrolling enabled

### **Modern CSS Techniques**
- CSS Grid (4-column, 5-column layouts)
- Flexbox for flexible components
- CSS Custom Properties for theming
- Advanced pseudo-selectors (`:hover`, `:nth-child()`)
- Transform and transition properties
- Backdrop filters for glass effects

---

## 📁 Project Structure

```
Documentation Website - Mintlify/
│
├── index.html              # Main HTML file
├── style.css               # Complete stylesheet
├── README.md              # This file
│
└── Assets/
    ├── svg/               # SVG icons and graphics
    │   ├── brand-logo.svg
    │   ├── hero-image.svg
    │   ├── hero-2-image.svg
    │   ├── animation-1.svg
    │   ├── animation-2.svg
    │   ├── animation-3.svg
    │   ├── anthropic-image.svg
    │   ├── coinbase.svg
    │   ├── partner.svg
    │   ├── compliance.svg
    │   ├── pricing.svg
    │   ├── building.svg
    │   ├── copy-right.svg
    │   ├── footer.svg
    │   ├── linkedin.svg
    │   ├── x.svg
    │   ├── github.svg
    │   ├── perplexity-text.svg
    │   ├── x-text.svg
    │   └── kalshi-text.svg
    │
    └── images/            # Raster images
        ├── feature-1.png
        ├── feature-2.png
        ├── feature-3.png
        ├── perplexity.webp
        ├── x.webp
        ├── kalshi.webp
        ├── footer.png
        ├── system-theme.png
        ├── sun-image.png
        └── moon-image.png
```

---

## 🚀 How to Run

1. Clone or download the project
   ```bash
   git clone <repository-url>
   cd "Documentation Website - Mintlify"
   ```

2. Open in browser
   - Simply double-click `index.html`
   - Or use a local server (recommended):
     ```bash
     # Using Node.js http-server
     npx http-server

     # Using VS Code Live Server
     Right-click index.html → Open with Live Server
     ```

3. View the website
   - Navigate to `http://localhost:8080`
   - Explore all interactive elements!

**No build process or dependencies required!**

---

## 💡 Technical Highlights

### **Pure HTML/CSS Architecture**
- No frameworks or libraries
- Zero JavaScript required
- 100% hand-coded
- Clean, maintainable code

### **CSS Organization**
- CSS Variables for easy theming
- Logical section grouping
- Consistent naming conventions
- Comments for major sections

### **Interactive Design**
- Hover effects on 20+ elements
- 0.3s standard transition timing
- Transform animations (translate, scale)
- Progressive enhancement

### **Cross-browser Compatible**
- Tested on Chrome, Firefox, Safari, Edge
- Fallbacks for older browsers
- Vendor prefixes where needed (-webkit-, -moz-)

---

## 📱 Browser Support

| Browser | Version | Status |
|---------|---------|--------|
| Chrome | 90+ | ✅ Fully Supported |
| Firefox | 88+ | ✅ Fully Supported |
| Safari | 14+ | ✅ Fully Supported |
| Edge | 90+ | ✅ Fully Supported |
| Opera | 76+ | ✅ Fully Supported |

**Requirements:**
- CSS Grid & Flexbox support
- CSS Custom Properties
- Backdrop Filter (for glass-morphism)
- CSS Transforms & Transitions

---

## 🎓 Learning Outcomes

This project demonstrates proficiency in:

### **Frontend Development**
- Semantic HTML5 markup
- Advanced CSS3 techniques
- Responsive design patterns
- Cross-browser compatibility

### **Design Implementation**
- Pixel-perfect design recreation
- Color theory and palette selection
- Typography and spacing systems
- Visual hierarchy principles

### **Performance & Optimization**
- Efficient CSS selectors
- Hardware-accelerated animations
- Minimal DOM structure
- Optimized asset loading

### **User Experience**
- Smooth interactions and transitions
- Hover states and feedback
- Accessibility best practices
- Mobile-first responsive design

---

## 🌟 Key Improvements Made

### **Enhanced Interactivity**
- ✅ All navigation links have hover states
- ✅ Feature cards lift and glow on hover
- ✅ Buttons have elevation animations
- ✅ Customer cards have dramatic lifts
- ✅ Social icons brighten and lift
- ✅ Footer links slide with color change

### **Visual Polish**
- ✅ Glass-morphism navbar with blur
- ✅ Dual-layer shadows on hero image
- ✅ Green glow effects on cards
- ✅ Smooth 0.3s transitions everywhere
- ✅ Professional depth layering
- ✅ Consistent spacing system

### **Code Quality**
- ✅ Clean, organized CSS structure
- ✅ CSS variables for theming
- ✅ Semantic HTML throughout
- ✅ No inline styles
- ✅ Reusable class patterns
- ✅ Well-commented sections

---

## 📊 Project Statistics

- **HTML Lines**: ~1,500 lines
- **CSS Lines**: ~1,000 lines
- **Total Sections**: 11 major sections
- **Interactive Elements**: 50+ hover states
- **Color Variables**: 12 custom properties
- **SVG Graphics**: 19 files
- **Raster Images**: 10 files
- **Development Time**: Comprehensive implementation

---

## 📄 License

This is an educational project created for learning purposes. All design rights belong to [Mintlify](https://www.mintlify.com/).

---

## 👤 Author

**Sahil Gupta**
- Project: Mintlify Landing Page Clone
- Date: February 2026
- Purpose: Web Development Assignment

---

## 🙏 Acknowledgments

- **Design inspiration**: [Mintlify.com](https://www.mintlify.com)
- **Original concept**: Mintlify team
- **Learning platform**: Modern web development practices

---

## 🔗 Links

- **Live Demo**: [mintlify-landing-page-sg.vercel.app](https://mintlify-landing-page-sg.vercel.app/)
- **Original Site**: [mintlify.com](https://www.mintlify.com)

---

## 📞 Support

For questions or feedback about this project:
- Review the code in `index.html` and `style.css`
- Check the live demo for functionality
- Compare with original Mintlify design

---

<div align="center">

### *Created with ❤️ for learning and practice*

**Built with HTML5 & CSS3**

[View Live Demo →](https://mintlify-landing-page-sg.vercel.app/)

</div>
