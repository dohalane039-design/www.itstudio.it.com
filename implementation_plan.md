# MD Sohel Rana — Premium Portfolio Website Rebuild

আপনার বর্তমান ওয়েবসাইটটি বেশ basic। আমি এটিকে একটি **premium, modern, animated** portfolio website-এ রূপান্তর করব।

## Current State (সমস্যাগুলো)

- ❌ ডিজাইন খুবই সাধারণ, কোনো visual impact নেই
- ❌ কোনো প্রোফাইল ইমেজ নেই
- ❌ Skills এর কোনো visual representation (progress bar/chart) নেই
- ❌ Experience section এ timeline নেই
- ❌ Mobile responsive ঠিকমতো কাজ করে না
- ❌ কোনো particle/animated background নেই
- ❌ Smooth scroll, typing effect এসব নেই
- ❌ Contact form নেই
- ❌ Social links ঠিকমতো নেই
- ❌ SEO optimization নেই

## Proposed Design (নতুন ডিজাইন)

### 🎨 Visual Design
- **Dark theme** with deep navy/slate gradient background
- **Glassmorphism** cards with backdrop blur
- **Animated particle** background in hero section
- **Gradient accent** colors (blue → purple → cyan)
- **Google Font**: Inter + Outfit
- **Smooth micro-animations** on scroll and hover

### 📱 Sections
1. **Navigation** — Sticky, glassmorphism navbar with hamburger menu (mobile), smooth scroll links
2. **Hero Section** — Full-screen with particle canvas background, typing animation for roles, profile image, glowing CTA buttons
3. **About Section** — Professional summary with stats cards (3+ years, 50+ networks, etc.)
4. **Skills Section** — Animated circular progress indicators or skill bars with categories (Networking, Server, Security, Virtualization)
5. **Experience Section** — Beautiful vertical timeline with hover animations
6. **Education & Certifications** — Card layout with icons
7. **Contact Section** — Contact info cards with icons + simple contact form
8. **Footer** — Social links, copyright

### ✨ Animations
- Intersection Observer reveal animations (slide up, fade in)
- Typing effect in hero section
- Particle.js-style canvas background
- Skill bars fill animation on scroll
- Hover scale/glow on cards
- Smooth scroll between sections
- Navbar background change on scroll

## Proposed Changes

### [MODIFY] [index.html](file:///c:/Users/rana/Desktop/website/Sohel_Rana_Portfolio_Animated/index.html)
Complete rewrite with:
- Proper SEO meta tags (description, keywords, Open Graph)
- Google Fonts import (Inter, Outfit)
- Font Awesome icons CDN
- Semantic HTML5 structure
- All new sections as described above
- Canvas element for particle background
- Mobile hamburger menu
- Unique IDs for all interactive elements

### [MODIFY] [style.css](file:///c:/Users/rana/Desktop/website/Sohel_Rana_Portfolio_Animated/style.css)
Complete rewrite with:
- CSS custom properties (design tokens for colors, spacing, typography)
- Glassmorphism card styles
- Gradient backgrounds and text
- Responsive grid layouts
- Keyframe animations (fadeIn, slideUp, pulse, glow, typing cursor)
- Mobile-first responsive breakpoints
- Smooth transitions on all interactive elements
- Dark/light theme variables

### [MODIFY] [script.js](file:///c:/Users/rana/Desktop/website/Sohel_Rana_Portfolio_Animated/script.js)
Complete rewrite with:
- Particle canvas animation system
- Typing effect for hero subtitle
- Intersection Observer for scroll reveal
- Navbar scroll behavior (background change, active link highlight)
- Mobile hamburger menu toggle
- Theme toggle (dark/light)
- Skill bar animation on scroll
- Smooth scroll for anchor links

## Verification Plan

### Browser Testing
- Open the website in browser and verify:
  - All sections render correctly
  - Animations play smoothly
  - Dark/light theme toggle works
  - Mobile menu works
  - All links are functional
  - CV download works
  - Responsive on different screen sizes
