# With Artifact Brand Guidelines

Version 1.0 - June 21, 2025

## Brand Identity

### Mission
Making AI collaboration into lasting artifacts

### Brand Voice
- Professional yet approachable
- Technical without being cold
- Direct and actionable
- Human-centered

## Logo

### Primary Mark
- Hand-drawn geometric "A" construction
- Grid-based design philosophy
- Maintains authentic, human touch
- **Status**: Pending trademark consultation

### Usage
- Always use original sketch-based design
- No AI-generated variations
- Maintain clear space equal to height of "A"
- Minimum size: 32px height

## Typography

### Font Family
**Inter** - Exclusive typeface for all applications
- Variable font for flexibility
- Geometric construction matches logo
- Tech industry standard
- Open source, no licensing issues

### Type Scale
Using fluid typography with clamp() for responsive design:

#### Wordmark/Hero
- Size: `clamp(3.5rem, 10vw, 6rem)`
- Weight: 700 (Bold)
- Color: zinc-100 (#f4f4f5)
- Letter-spacing: -0.02em

#### Tagline/Large Text
- Size: `clamp(1.5rem, 4vw, 2.25rem)`
- Weight: 400 (Regular)
- Color: zinc-200 (#e4e4e7)

#### Body/Links
- Size: 1.125rem (18px minimum)
- Weight: 400 (Regular)
- Color: zinc-300 (#d4d4d8)

#### Small Text/Legal
- Size: 1rem (16px)
- Weight: 400 (Regular)
- Color: zinc-500 (#71717a)

### Typography Principles
1. **Minimum 16px** for any text
2. **18px preferred** for body content
3. **Fluid scaling** over breakpoints
4. **Clear hierarchy** through size and color

## Color Palette

### Primary Colors
```css
--zinc-950: #09090b  /* Background */
--zinc-100: #f4f4f5  /* Primary text */
```

### Grayscale Hierarchy
```css
--zinc-100: #f4f4f5  /* Primary content */
--zinc-200: #e4e4e7  /* Secondary content */
--zinc-300: #d4d4d8  /* Tertiary content */
--zinc-400: #a1a1aa  /* Quaternary (unused) */
--zinc-500: #71717a  /* Minimal emphasis */
```

### Color Usage
- **No pure black/white** - Always use zinc scale
- **Grayscale only** - No accent colors (yet)
- **Hierarchy through value** - Lighter = more important
- **Consistent application** - Same gray for same purpose

## Layout Principles

### Spacing System
- Base unit: 0.25rem (4px)
- Common spacings: 1rem, 1.5rem, 2rem, 3rem, 4rem
- Maintain visual rhythm through consistent spacing

### Content Width
- Maximum: 42rem for readability
- Centered layout
- Responsive padding: 1rem mobile, 2rem desktop

### Visual Hierarchy
1. Brand name (largest, white)
2. Tagline (large, light gray)
3. Links/Actions (medium, medium gray)
4. Legal/Footer (small, dark gray)

## Digital Presence

### Website
- Minimal, single-page design
- Focus on brand and tagline
- Subtle call-to-action
- Mobile-first responsive

### Social Media
- Consistent @withartifact handle
- Profile image: Original "A" logo
- Bio: "Making AI collaboration into lasting artifacts"
- Link: withartifact.io

### Email
- Primary: hello@withartifact.io
- Signature: Minimal, text-only
- Include tagline under name

## Design Philosophy

### Core Principles
1. **Simplicity** - Less is more
2. **Authenticity** - Human touch over perfection
3. **Clarity** - Direct communication
4. **Consistency** - Same principles everywhere

### What We Don't Do
- Gradients or effects
- Multiple fonts
- Bright colors
- Complex layouts
- Stock imagery
- AI-generated content

## Implementation Notes

### CSS Architecture
- Use CSS custom properties for consistency
- Fluid typography with clamp()
- Mobile-first approach
- Semantic color naming

### Accessibility
- Minimum contrast ratios met
- Readable font sizes
- Clear focus states
- Semantic HTML

## Future Considerations

### Post-Legal Review
- Add ™ or ® as appropriate
- Implement logo lockup variations
- Create downloadable assets

### Potential Expansions
- Accent color (when needed)
- Secondary typeface (if required)
- Icon system (purpose-built)
- Motion principles (subtle, purposeful)

---

© 2025 With Artifact. All rights reserved.