# Live link: https://cursor-homepage-sg.vercel.app

---

# Cursor Landing Page Clone

A pixel-perfect recreation of the Cursor.com landing page, built with HTML5 and CSS3.

## 🎯 Project Overview

This project is a responsive clone of the Cursor AI Code Editor landing page, showcasing modern web design principles, clean code structure, and professional UI/UX implementation.

---

## 📋 Sections Recreated

### ✅ **1. Navigation Header**
- Fixed position navigation bar with rounded corners
- Logo with brand identity
- Center navigation menu (Features, Enterprise, Pricing, Resources)
- Resources dropdown menu with hover animation
- Sign In and Download buttons
- Smooth scroll behavior

### ✅ **2. Hero Section**
- Main headline with compelling copy
- Download for Windows CTA button with icon
- Hero image showcasing the Cursor editor interface
- Centered layout with optimal spacing

### ✅ **3. Company Trust Section**
- "Trusted by millions" statement
- Logo grid featuring major companies:
  - Stripe, OpenAI, Linear, Datadog
  - Nvidia, Figma, Ramp, Adobe
- Responsive grid layout with hover effects

### ✅ **4. Feature Cards (3 Sections)**
- **Agent Feature**: AI-powered code generation
- **Tab Autocomplete**: Smart prediction system
- **Ecosystem Integration**: GitHub, Slack, and more
- Alternating image-text layout
- Call-to-action links with arrow icons
- Smooth hover transitions

### ✅ **5. Testimonials Section**
- 6 testimonial cards from industry leaders:
  - Diana Hu (Y Combinator)
  - shadcn (shadcn/ui creator)
  - Andrej Karpathy (Eureka Labs)
  - Patrick Collison (Stripe)
  - ThePrimeagen (Content Creator)
  - Greg Brockman (OpenAI)
- Avatar images with names and titles
- Responsive grid layout

### ✅ **6. Product Features**
- Three feature cards:
  - Access to best AI models
  - Complete codebase understanding
  - Enterprise-grade development
- Image thumbnails with descriptions
- External documentation links

### ✅ **7. Changelog Section**
- Version history display
- Release notes with dates
- Version badges (2.4, 2.3)
- Link to full changelog

### ✅ **8. Join Us Section**
- Team mission statement
- Join Us CTA button
- Team photo showcase
- Center-aligned layout

### ✅ **9. Recent Highlights**
- Blog-style content cards
- Research and product updates
- Date and category tags
- "View more posts" link

### ✅ **10. Download CTA Section**
- Large "Try Cursor now" headline
- Prominent download button
- Clean, focused layout

### ✅ **11. Footer**
- Five navigation columns:
  - Product (Features, Enterprise, CLI, etc.)
  - Resources (Download, Docs, Forum, etc.)
  - Company (Careers, Blog, Community, etc.)
  - Legal (Terms, Privacy, Security)
  - Connect (Social media links)
- Copyright and SOC 2 certification
- Theme switcher (System, Light, Dark)
- Language selector

---

## 🎨 Design System

### **Typography**
- **Font Family**: `'Segoe UI', Tahoma, Geneva, Verdana, sans-serif`
- **Headings**:
  - H1: 42px, font-weight: 500
  - H2: 36-42px, font-weight: 500
  - H3: 22-32px, font-weight: 500
- **Body Text**: 16-18px
- **Line Heights**: 1.3 - 1.6 (responsive to content)
- **Letter Spacing**: -0.02em (for large headings)

### **Color Palette**

#### Text Colors
```css
--text-color: #E8E6E3          /* Primary text - Light warm white */
--text-secondary: #9CA3AF      /* Secondary text - Medium gray */
--text-muted: #6B7280           /* Muted text - Dark gray */
```

#### Background Colors
```css
--bg-color: #0A0908                         /* Main background - Deep black */
--header-bg-color: #1A1917                  /* Header - Dark brown */
--card-bg-color: #161513                    /* Cards - Very dark brown */
--company-bg-color: #1C1B18                 /* Company section - Dark warm */
--dropdown-bg-color: #1F1E1B                /* Dropdown menu - Medium dark */
--recent-highlight-card-bg-color: #22221f   /* Highlight cards - Subtle */
```

#### Accent Colors
```css
--accent-primary: #F54E00       /* Primary accent - Vibrant orange */
--accent-hover: #FF6B2B         /* Hover state - Bright orange */
```

#### Button Colors
```css
--btn-bg-color: #F5F5F4         /* Button background - Off-white */
--btn-bg-hover-color: #E5E5E4   /* Button hover - Light gray */
--btn-text-color: #0A0908       /* Button text - Dark */
```

#### Border & Divider Colors
```css
--border-color: rgba(255, 255, 255, 0.06)     /* Subtle borders */
--border-hover: rgba(255, 255, 255, 0.12)     /* Hover state borders */
```

---

## 🎯 Key Features Implemented

### **Responsive Design**
- Mobile-first approach
- Breakpoints: 1400px, 1200px, 992px, 768px, 480px
- Flexible grid layouts
- Optimized for all screen sizes

### **Interactive Elements**
- Hover effects on cards and links
- Smooth transitions (0.2-0.3s)
- Dropdown menu with fade-in animation
- Transform animations on hover

### **Accessibility**
- Semantic HTML5 structure
- Descriptive alt text for all images
- Proper heading hierarchy
- ARIA-friendly navigation

### **Performance Optimizations**
- Clean CSS with CSS variables
- Minimal JavaScript (none required)
- Optimized image loading
- Efficient selector usage

### **Modern CSS Techniques**
- CSS Grid and Flexbox layouts
- CSS Custom Properties (variables)
- Smooth transitions and transforms
- Advanced selectors and pseudo-classes

---

## 📁 Project Structure

```
Cursor Dev tool Landing Page/
│
├── index.html              # Main HTML file
├── style.css               # Complete stylesheet
├── README.md              # This file
│
└── Assest/
    ├── Logo.svg           # Cursor logo
    ├── stripe.svg         # Company logos
    ├── openai.svg
    ├── linear.svg
    ├── datadog.svg
    ├── nvidia.svg
    ├── figma.svg
    ├── ramp.svg
    ├── adobe.svg
    │
    └── images/
        ├── hero-image.png
        ├── card-1-image.png
        ├── card-2-image.png
        ├── card-3-image.png
        ├── feature-1-image.png
        ├── feature-2-image.png
        ├── feature-3-image.png
        ├── diana-hu-avatar.webp
        ├── shadcn-avatar.webp
        ├── andrej-karpathy-avatar.webp
        ├── patrick-collison-avatar.webp
        ├── theprimeagen-avatar.webp
        ├── greg-brockman-avatar.webp
        ├── homepage-team-photo.webp
        ├── system-theme.png
        ├── sun-image.png
        ├── moon-image.png
        └── icons8-world-50.png
```

---

## 🚀 How to Run

1. Clone or download the project
2. Open `index.html` in any modern web browser
3. No build process or dependencies required!

---

## 💡 Technical Highlights

- **Pure HTML/CSS** - No frameworks or libraries
- **CSS Variables** - Easy theming and maintenance
- **Semantic HTML** - SEO-friendly structure
- **BEM-inspired** - Clean class naming conventions
- **Cross-browser Compatible** - Works on all modern browsers

---

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

---

## 🎓 Learning Outcomes

This project demonstrates proficiency in:
- Modern CSS layout techniques (Grid, Flexbox)
- Responsive web design principles
- UI/UX best practices
- Color theory and typography
- Clean code organization
- Performance optimization

---

## 📄 License

This is a educational project created for learning purposes.

---

## 👤 Author

**Sahil Gupta**

---

## 🙏 Acknowledgments

- Design inspiration: [Cursor.com](https://cursor.com)
- Original concept by Cursor AI team

---

*Created with ❤️ for learning and practice*
