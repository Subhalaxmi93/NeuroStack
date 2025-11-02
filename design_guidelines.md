# NeuroStack Website Design Guidelines

## Design Approach

**Selected Approach:** Reference-Based (Modern Tech Company Aesthetic)

Drawing inspiration from Vercel, Stripe, and Linear for their clean, technical sophistication. This approach balances professional credibility with modern visual impact—essential for a company showcasing cutting-edge technologies.

**Core Principles:**
- Technical precision meets visual elegance
- Clear information hierarchy for different technology domains
- Progressive disclosure of capabilities
- Trust-building through polished presentation

---

## Typography System

**Font Families:**
- Primary: Inter (Google Fonts) - Headings and UI elements
- Secondary: Space Grotesk (Google Fonts) - Accent headings and technology labels

**Hierarchy:**
- Hero Headline: 4xl to 6xl, font-bold, tracking-tight
- Section Headings: 3xl to 4xl, font-bold
- Technology Titles: xl to 2xl, font-semibold
- Body Text: base to lg, font-normal, leading-relaxed
- Small Text/Labels: sm, font-medium

---

## Layout System

**Spacing Primitives:** Tailwind units of 4, 6, 8, 12, 16, 20, 24
- Component padding: p-6, p-8
- Section spacing: py-16, py-20, py-24
- Card gaps: gap-6, gap-8
- Content margins: mb-4, mb-6, mb-8

**Container Strategy:**
- Full-width sections with inner max-w-7xl
- Content sections: max-w-6xl
- Text content: max-w-3xl for readability

---

## Page Structure & Components

### 1. Navigation Header
**Sticky header with blur backdrop:**
- Logo (left): NeuroStack wordmark with subtle tech-inspired icon
- Navigation links (center/right): Technologies, Services, About, Contact
- CTA button (right): "Get Started" or "Schedule Demo"
- Mobile: Hamburger menu with slide-out navigation

### 2. Hero Section (80-90vh)
**Impactful introduction with gradient backdrop:**
- **Large Hero Image:** YES - Abstract tech visualization showing neural networks, code patterns, or geometric data structures. Position as background with overlay gradient for text readability.
- Headline: "Building Tomorrow's Technology Today" or similar bold statement
- Subheadline: Brief description of NeuroStack's mission (2-3 lines)
- Two CTAs: Primary "Explore Our Technologies" + Secondary "View Case Studies"
- Floating stat indicators: "50+ Projects Delivered", "5 Core Technologies", "100% Client Satisfaction"
- Subtle animated gradient background or particle effect

### 3. Technologies Showcase (Multi-column Grid)
**5-column grid (3 on tablet, 1 on mobile):**

Each technology card includes:
- Icon from Heroicons (Cog, CircleStack, CodeBracket, Sparkles, Server)
- Technology name: AI, Machine Learning, MERN Stack, Web Development, Database
- Brief description (2-3 sentences) of capabilities
- "Learn More" link with arrow icon
- Hover state: Slight elevation and border glow

**Layout:** grid grid-cols-1 md:grid-cols-3 lg:grid-cols-5 gap-6

### 4. Capabilities Deep Dive (Alternating Layout)
**Three sections with alternating image-text layout:**

**AI & Machine Learning:**
- Left: Text content with feature bullets
- Right: Abstract visualization of neural networks or data processing
- Highlight: NLP, Computer Vision, Predictive Analytics

**MERN Stack & Web Development:**
- Right: Text content
- Left: Screenshot of modern dashboard or code editor mockup
- Highlight: Full-stack development, Scalable architecture, Modern frameworks

**Database Solutions:**
- Left: Text content
- Right: Data flow diagram or database architecture visualization
- Highlight: SQL/NoSQL, Optimization, Cloud integration

### 5. Process/Approach Section
**4-step timeline or card layout:**
- Discovery & Planning
- Design & Architecture
- Development & Integration
- Testing & Deployment

Each step with number badge, title, description, and connecting line

### 6. Stats/Metrics Bar
**4-column centered layout:**
- Years of Experience
- Technologies Mastered
- Successful Projects
- Client Satisfaction Rate

Large numbers with labels, separator lines between

### 7. Call-to-Action Section
**Centered with background treatment:**
- Headline: "Ready to Transform Your Ideas into Reality?"
- Description paragraph
- Email input + Submit button combo
- Alternative: "Or schedule a consultation" link below
- Background: Subtle gradient or geometric pattern

### 8. Footer (Comprehensive)
**4-column layout:**
- Column 1: NeuroStack logo, tagline, social links (LinkedIn, GitHub, Twitter)
- Column 2: Technologies (links to each tech section)
- Column 3: Company (About, Blog, Careers, Contact)
- Column 4: Contact info (Email, Phone, Location)
- Bottom bar: Copyright, Privacy Policy, Terms of Service

---

## Component Library

**Cards:**
- Rounded corners (rounded-lg to rounded-xl)
- Subtle border treatment
- Padding: p-6 to p-8
- Hover: transform scale(1.02) with smooth transition

**Buttons:**
- Primary: Full background, bold text, padding px-6 py-3
- Secondary: Border with transparent background
- Both: Rounded-lg, font-medium
- On images: Backdrop blur (backdrop-blur-md) with semi-transparent background

**Icons:**
- Use Heroicons via CDN
- Size: w-8 h-8 for cards, w-6 h-6 for inline
- Consistent stroke width

**Forms:**
- Input fields: Border focus state, padding p-3
- Labels: font-medium, mb-2
- Validation states with clear indicators

---

## Images Strategy

**Required Images:**
1. **Hero Background:** Abstract tech visualization (neural network nodes, flowing data, code matrices) - Full-width, with gradient overlay
2. **AI/ML Section:** Conceptual visualization of machine learning pipeline or neural network architecture
3. **MERN/Web Dev Section:** Modern dashboard interface or development environment screenshot
4. **Database Section:** Data architecture diagram or visualization of database connections
5. **Decorative Elements:** Subtle geometric patterns or gradient shapes as section backgrounds

**Image Treatment:**
- Consistent rounded corners (rounded-xl)
- Subtle shadows for depth
- Gradient overlays where text appears on images

---

## Animation Guidelines

**Minimal, purposeful animations:**
- Scroll-triggered fade-ins for section entries (use intersection observer)
- Card hover elevations (transform + shadow)
- Button hover states (slight scale or brightness change)
- Hero element subtle parallax or floating effect
- NO: Excessive scroll animations, spinners, or distracting effects

---

## Accessibility

- Semantic HTML throughout (header, nav, main, section, footer)
- ARIA labels for interactive elements
- Keyboard navigation support
- Focus states clearly visible
- Sufficient contrast ratios (WCAG AA minimum)
- Alt text for all images
- Form labels properly associated