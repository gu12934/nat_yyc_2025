# nat_yyc_2025
# natYYC Website

## Overview

natYYC is a static website for Calgary's digital health innovation community. The site is built as a GitHub Pages-deployable static website using HTML, CSS, and vanilla JavaScript. It serves as an informational hub showcasing the community's mission, events, projects, and community involvement in healthtech innovation. The website focuses on presenting natYYC as Calgary's grassroots healthtech node within the larger natNetwork ecosystem.

## Recent Changes

**September 29, 2025** - Complete website implementation
- Created all four main pages (index.html, about.html, projects.html, experience.html)
- Implemented responsive CSS design with blue color scheme matching natYYC branding
- Added JavaScript for mobile navigation and scroll animations
- Integrated all social media links (YouTube, Instagram, LinkedIn, TikTok, Facebook)
- Added DevPost project showcases (Neural.ly and BraVRy)
- Integrated Google Forms signup and Luma event calendar
- Website is fully GitHub Pages ready with no build process required

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture

**Multi-Page Static Site Design**
- Decision: Pure HTML/CSS/JavaScript static site without frameworks
- Rationale: Optimized for GitHub Pages deployment with zero build process
- Benefits: Fast loading, simple deployment, no dependencies or build steps
- Structure: Separate HTML pages (index, about, projects, experience) with shared navigation

**Responsive Mobile-First Design**
- Decision: CSS-based responsive design with mobile menu toggle
- Implementation: Flexbox/Grid layouts with media queries
- Navigation: Sticky header with hamburger menu for mobile devices
- Approach: Progressive enhancement from mobile to desktop layouts

**Client-Side Interactivity**
- Decision: Vanilla JavaScript for all interactions (no jQuery or frameworks)
- Features implemented:
  - Mobile navigation toggle functionality
  - Active page highlighting in navigation
  - Smooth scroll behavior for anchor links
  - Intersection Observer API for scroll-based animations
- Rationale: Keeps site lightweight and eliminates external dependencies

### Styling Architecture

**CSS Custom Properties (Variables)**
- Color scheme defined in `:root` for consistent theming
- Primary palette: Blues (#00b4d8, #0077b6, #90e0ef) with dark navy (#03045e)
- Enables easy theme modifications across entire site

**Component-Based CSS Structure**
- Modular class naming (cards-grid, hero, section-title, etc.)
- Reusable components: cards, buttons, navigation, hero sections
- Consistent spacing and typography system

### Content Structure

**Information Hierarchy**
- Home page: Overview, mission, why now statistics, community offerings, and call-to-action
- About page: natYYC identity, mandate, Calgary-specific needs, target audiences, and collaboration opportunities
- Projects page: Featured healthtech innovations (Neural.ly neurofeedback and BraVRy VR therapy)
- Experience page: Events and programs (natHACKS, natChat, workshops, demo nights) with Luma calendar integration

**External Integration Points**
- Google Forms integration for community signup
- DevPost project links for hackathon submissions (Neural.ly and BraVRy)
- Social media links (YouTube, Instagram, LinkedIn, TikTok, Facebook)
- Luma event calendar integration

## External Dependencies

### Hosting & Deployment

**GitHub Pages**
- Static site hosting solution
- No server-side processing required
- Direct deployment from repository

### Third-Party Services

**Google Forms**
- Community signup/registration: `https://docs.google.com/forms/d/e/1FAIpQLSduQs6ky6hpkpuqMW3mu-PIglSuM__gY0vZS8CtWOacHeGebQ/viewform`
- Purpose: Collecting community member information

**DevPost**
- Project showcase integration
- Neural.ly (neurofeedback): `https://devpost.com/software/neural-ly`
- BraVRy (VR exposure therapy): `https://devpost.com/software/bravry-vr-exposure-therapy`
- natHacks project gallery: `https://nathacks.devpost.com/project-gallery`

**Luma**
- Event calendar integration: `https://lu.ma/bxufnmrd`
- Purpose: Community event discovery and registration

**Social Media Platforms**
- YouTube: `https://www.youtube.com/@networkforappliedtech/playlists`
- Instagram: `https://www.instagram.com/nat.ltd`
- LinkedIn: `https://www.linkedin.com/company/networkforappliedtech/`
- TikTok: `https://www.tiktok.com/@networkforappliedtech`
- Facebook: `https://www.facebook.com/networkforappliedtech/`

### Future Enhancement Opportunities

**Content Management**
- Project data: Could be moved to JSON data files for easier updates
- Event information: Potential for dynamic loading from external sources
- YouTube video embedding: Direct video embeds rather than playlist links

### Browser APIs

**Intersection Observer API**
- Used for scroll-based animations
- Progressive enhancement - site functions without it

**CSS Features**
- Custom properties (CSS variables)
- Flexbox and Grid layouts
- Gradients and modern selectors
