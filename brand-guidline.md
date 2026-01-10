# Brand Visual Identity Guidelines
**AI Personal Growth Platform**

*Version 1.0 | January 2026*

---

## Table of Contents
1. [Brand Overview](#brand-overview)
2. [Color Palette](#color-palette)
3. [Typography System](#typography-system)
4. [Logo System](#logo-system)
5. [Imagery Style](#imagery-style)
6. [Design Elements](#design-elements)
7. [Component Specifications](#component-specifications)
8. [Responsive Design](#responsive-design)
9. [Application Examples](#application-examples)

---

## Brand Overview

### Visual Brand Essence
Our visual identity reflects the transformation from "doing" to "becoming." Every design decision reinforces our positioning as a wise companion that helps knowledge workers grow through focused work.

### Core Visual Principles
- **Trust through Clarity**: Clean, professional design with generous whitespace
- **Innovation through Motion**: Gradients and transitions that suggest forward movement
- **Wisdom through Balance**: Modern technology balanced with human warmth
- **Growth through Light**: Progressive illumination metaphors (emergence, dawn, insight)

### Design Philosophy
We blend the credibility of enterprise SaaS with the approachability of consumer apps. Our visual language should feel like a thoughtful colleague - professional but never cold, modern but never trendy, intelligent but never intimidating.

---

## Color Palette

### Primary Colors

#### Deep Ocean Blue - Brand Foundation
**Purpose**: Trust, depth, professional credibility
- **Hex**: `#0A2E4D`
- **RGB**: `10, 46, 77`
- **CMYK**: `87%, 40%, 0%, 70%`
- **HSL**: `206°, 77%, 17%`

**Usage**:
- Primary brand color for headers, navigation, CTAs
- Conveys stability and trustworthiness
- Use for text on light backgrounds
- Represents the "depth" users dive into during focus sessions

**Psychology**: Deep ocean blue suggests professionalism, intelligence, and reliability. It's the color of deep thought and focused concentration - perfect for knowledge workers seeking growth.

**Accessibility**:
- WCAG AAA compliant on white backgrounds (contrast ratio 13.42:1)
- Use for body text, headings, and primary UI elements

---

#### Insight Cyan - Growth Gradient Start
**Purpose**: Innovation, clarity, breakthrough moments
- **Hex**: `#00B4D8`
- **RGB**: `0, 180, 216`
- **CMYK**: `100%, 17%, 0%, 15%`
- **HSL**: `190°, 100%, 42%`

**Usage**:
- Gradient starting point
- Accent color for insights, breakthrough moments
- Active states, hover effects
- Progress indicators

**Psychology**: Cyan represents clarity, fresh perspective, and the "aha moment" - the instant insight emerges from focus.

**Accessibility**:
- WCAG AA compliant on dark backgrounds (contrast ratio 4.89:1 on Deep Ocean Blue)
- Do not use for body text
- Use for decorative elements, accents, and large UI components

---

#### Transformation Teal - Growth Gradient End
**Purpose**: Growth, transformation, evolution
- **Hex**: `#06D6A0`
- **RGB**: `6, 214, 160`
- **CMYK**: `97%, 0%, 25%, 16%`
- **HSL**: `164°, 95%, 43%`

**Usage**:
- Gradient ending point
- Success states, completion indicators
- Growth milestones, achievements
- Positive feedback, encouragement

**Psychology**: Teal bridges blue (trust) and green (growth), representing transformation and positive evolution. It's energizing without being aggressive.

**Accessibility**:
- WCAG AA compliant on dark backgrounds (contrast ratio 5.12:1 on Deep Ocean Blue)
- Do not use for body text
- Use for celebratory moments, progress completion

---

#### Warm Coral - Human Touch
**Purpose**: Empowerment, encouragement, human connection
- **Hex**: `#FF6B6B`
- **RGB**: `255, 107, 107`
- **CMYK**: `0%, 58%, 58%, 0%`
- **HSL**: `0°, 100%, 71%`

**Usage**:
- Secondary accent color (use sparingly)
- Highlighting important insights
- Emotional moments, encouragement
- Differentiates from pure tech aesthetic

**Psychology**: Warm coral adds humanity and warmth, preventing the design from feeling too clinical. It represents the supportive, encouraging aspect of the wise companion.

**Accessibility**:
- WCAG AA compliant on white backgrounds (contrast ratio 4.67:1)
- Use for highlights, not primary text
- Maximum 10% of any given screen

---

### Secondary Colors

#### Soft Lavender - Reflection
**Purpose**: Contemplation, pause, integration
- **Hex**: `#E0E7FF`
- **RGB**: `224, 231, 255`
- **CMYK**: `12%, 9%, 0%, 0%`
- **HSL**: `226°, 100%, 94%`

**Usage**:
- Background for reflection prompts
- Quiet moments between focus sessions
- Subtle highlights, hover states on light backgrounds

---

#### Dawn Gold - Insight Moments
**Purpose**: Illumination, discovery, awareness
- **Hex**: `#FFD166`
- **RGB**: `255, 209, 102`
- **CMYK**: `0%, 18%, 60%, 0%`
- **HSL**: `42°, 100%, 70%`

**Usage**:
- Highlighting key insights
- "Lightbulb moments" in UI
- Premium features, achievements
- Use minimally for maximum impact

---

### Neutral Colors

#### Pure White - Clarity
- **Hex**: `#FFFFFF`
- **RGB**: `255, 255, 255`
- **Usage**: Primary backgrounds, cards, clean space

#### Light Cloud - Subtle Background
- **Hex**: `#F8FAFB`
- **RGB**: `248, 250, 251`
- **Usage**: Alternative backgrounds, subtle differentiation

#### Soft Gray - Borders & Dividers
- **Hex**: `#E4E9F0`
- **RGB**: `228, 233, 240`
- **Usage**: Dividers, borders, inactive states

#### Medium Gray - Secondary Text
- **Hex**: `#6B7888`
- **RGB**: `107, 120, 136`
- **Usage**: Secondary text, captions, metadata
- **Accessibility**: WCAG AA compliant on white (contrast ratio 6.47:1)

#### Deep Charcoal - Primary Text
- **Hex**: `#1F2937`
- **RGB**: `31, 41, 55`
- **Usage**: Primary body text, headings
- **Accessibility**: WCAG AAA compliant on white (contrast ratio 14.87:1)

---

### Color Psychology & Strategy

#### Trust Building (Blues)
Our foundation colors establish credibility with knowledge workers who need assurance that AI won't diminish their growth. Deep ocean blues connect to:
- Professional environments (where our users spend their days)
- Deep thinking and concentration
- Reliability and consistency

#### Transformation Signal (Cyan/Teal Gradient)
The gradient from cyan to teal is our signature visual metaphor:
- **Left to right**: Movement from current state to evolved state
- **Light to slightly darker**: Depth gained through growth
- **Cool to warm**: Emotional journey from analytical to empowered
- Never use reversed (teal to cyan) - always suggests forward progression

#### Human Warmth (Coral)
Coral prevents our design from feeling cold or robotic:
- Sparingly applied (5-10% of visual weight)
- Used for moments of encouragement and connection
- Balances technological precision with human empathy

---

### Gradient Specifications

#### Primary Brand Gradient - "Evolution"
```css
background: linear-gradient(135deg, #00B4D8 0%, #06D6A0 100%);
```
**Usage**:
- Primary CTAs
- Feature highlights
- Progress indicators
- Hero sections

**Angle**: 135° (diagonal, suggesting upward-right movement)
**Transition**: Smooth, no color stops except start/end

---

#### Subtle Background Gradient - "Dawn"
```css
background: linear-gradient(180deg, #FFFFFF 0%, #F8FAFB 100%);
```
**Usage**:
- Page backgrounds
- Card backgrounds
- Subtle depth without distraction

---

#### Success Gradient - "Achievement"
```css
background: linear-gradient(135deg, #06D6A0 0%, #00D896 100%);
```
**Usage**:
- Completed milestones
- Success messages
- Achievement celebrations

---

#### Accent Gradient - "Insight"
```css
background: linear-gradient(90deg, #00B4D8 0%, #FFD166 100%);
```
**Usage**:
- Special insight moments
- Premium features
- Rare, high-impact moments only

---

### Accessibility Standards

#### Contrast Requirements
All text must meet WCAG 2.1 standards:
- **AAA (7:1 ratio)**: Body text, critical content
- **AA (4.5:1 ratio)**: Minimum for all text
- **Large text AA (3:1 ratio)**: 18pt+ or 14pt bold

#### Color Blindness Considerations
- Never use color alone to convey information
- Always pair color with icons, text, or patterns
- Tested with Deuteranopia, Protanopia, Tritanopia simulators
- All critical states (error, success, warning) include iconography

#### Approved Text Combinations
- Deep Charcoal on White: 14.87:1 (AAA)
- Deep Ocean Blue on White: 13.42:1 (AAA)
- Medium Gray on White: 6.47:1 (AA)
- White on Deep Ocean Blue: 13.42:1 (AAA)
- White on Insight Cyan: 3.12:1 (Large text only)

---

## Typography System

### Type Philosophy
Typography should feel modern but not trendy, professional but approachable, clear but not cold. We use a two-font system that balances geometric precision (for UI) with humanist warmth (for content).

---

### Font Families

#### Primary Font - Inter (UI, Headings, Body)
**Purpose**: Clean, modern, highly legible interface font
- **Weights Used**: 400 (Regular), 500 (Medium), 600 (Semibold), 700 (Bold)
- **License**: Open Font License
- **Web Import**:
```html
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
```

**Why Inter**:
- Designed specifically for user interfaces
- Exceptional legibility at all sizes
- Geometric but humanist (technical yet approachable)
- Wide language support
- Open source and free

**Character**: Modern, clean, trustworthy, neutral

---

#### Secondary Font - Fraunces (Display, Emotional Moments)
**Purpose**: Humanist serif for special moments, quotes, emphasis
- **Weights Used**: 400 (Regular), 600 (Semibold)
- **Style**: Soft serifs, slightly organic
- **License**: Open Font License
- **Web Import**:
```html
<link href="https://fonts.googleapis.com/css2?family=Fraunces:wght@400;600&display=swap" rel="stylesheet">
```

**Why Fraunces**:
- Adds warmth and humanity to key moments
- Soft, approachable serifs (not corporate or academic)
- Creates visual hierarchy for wisdom/reflection content
- Variable font for fine-tuning

**Usage**:
- User testimonials
- Reflection prompts
- Inspirational quotes
- Marketing hero headlines (optional)
- Maximum 10% of text content

**Character**: Wise, warm, thoughtful, human

---

### Type Scale

#### Desktop Scale (Base: 16px)
```css
/* Display - Marketing moments only */
--font-size-display-1: 72px;    /* Line height: 80px, Weight: 700 */
--font-size-display-2: 60px;    /* Line height: 68px, Weight: 700 */

/* Headings - Inter Semibold/Bold */
--font-size-h1: 48px;           /* Line height: 56px, Weight: 700 */
--font-size-h2: 36px;           /* Line height: 44px, Weight: 600 */
--font-size-h3: 28px;           /* Line height: 36px, Weight: 600 */
--font-size-h4: 24px;           /* Line height: 32px, Weight: 600 */
--font-size-h5: 20px;           /* Line height: 28px, Weight: 600 */
--font-size-h6: 18px;           /* Line height: 24px, Weight: 600 */

/* Body - Inter Regular/Medium */
--font-size-body-xl: 20px;      /* Line height: 32px, Weight: 400 */
--font-size-body-lg: 18px;      /* Line height: 28px, Weight: 400 */
--font-size-body: 16px;         /* Line height: 24px, Weight: 400 */
--font-size-body-sm: 14px;      /* Line height: 20px, Weight: 400 */
--font-size-body-xs: 12px;      /* Line height: 16px, Weight: 400 */

/* UI - Inter Medium */
--font-size-button: 16px;       /* Line height: 24px, Weight: 500 */
--font-size-label: 14px;        /* Line height: 20px, Weight: 500 */
--font-size-caption: 12px;      /* Line height: 16px, Weight: 500 */
```

#### Mobile Scale (Base: 16px)
```css
/* Headings - Reduced for mobile */
--font-size-h1-mobile: 36px;    /* Line height: 44px */
--font-size-h2-mobile: 28px;    /* Line height: 36px */
--font-size-h3-mobile: 24px;    /* Line height: 32px */
--font-size-h4-mobile: 20px;    /* Line height: 28px */
--font-size-h5-mobile: 18px;    /* Line height: 24px */
--font-size-h6-mobile: 16px;    /* Line height: 22px */

/* Body remains same (16px base is mobile-optimized) */
```

---

### Typography Specifications

#### Line Height Guidelines
- **Headings**: 1.2-1.3x font size (tighter for hierarchy)
- **Body text**: 1.5-1.6x font size (comfortable reading)
- **UI elements**: 1.5x font size (click target optimization)
- **Captions**: 1.4x font size (space efficiency)

#### Letter Spacing
```css
/* Headings - Slightly tight for cohesion */
h1, h2, h3 { letter-spacing: -0.02em; }

/* Body - Optical default */
body { letter-spacing: 0em; }

/* All caps - Increased for readability */
.all-caps {
  letter-spacing: 0.08em;
  text-transform: uppercase;
}

/* Small text - Slight increase for clarity */
.caption, .small { letter-spacing: 0.01em; }
```

#### Font Weights Mapping
```css
/* Semantic weight variables */
--font-weight-regular: 400;
--font-weight-medium: 500;
--font-weight-semibold: 600;
--font-weight-bold: 700;

/* Usage */
body { font-weight: var(--font-weight-regular); }
.label { font-weight: var(--font-weight-medium); }
.heading { font-weight: var(--font-weight-semibold); }
.emphasis { font-weight: var(--font-weight-bold); }
```

---

### Text Color Applications

#### Primary Text Hierarchy
```css
/* Primary - Main content */
.text-primary {
  color: #1F2937; /* Deep Charcoal */
  font-weight: 400;
}

/* Secondary - Supporting content */
.text-secondary {
  color: #6B7888; /* Medium Gray */
  font-weight: 400;
}

/* Tertiary - Metadata, timestamps */
.text-tertiary {
  color: #9CA3AF;
  font-weight: 400;
}

/* Brand accent - Links, CTAs */
.text-brand {
  color: #0A2E4D; /* Deep Ocean Blue */
  font-weight: 500;
}

/* Interactive - Hover states */
.text-interactive {
  color: #00B4D8; /* Insight Cyan */
  font-weight: 500;
}
```

---

### Typographic Patterns

#### Insight Card - Wisdom Moment
```css
.insight-card__quote {
  font-family: 'Fraunces', serif;
  font-size: 24px;
  line-height: 36px;
  font-weight: 400;
  color: #0A2E4D;
  font-style: italic;
}

.insight-card__attribution {
  font-family: 'Inter', sans-serif;
  font-size: 14px;
  line-height: 20px;
  font-weight: 500;
  color: #6B7888;
  text-transform: uppercase;
  letter-spacing: 0.08em;
}
```

#### Section Headers
```css
.section-label {
  font-family: 'Inter', sans-serif;
  font-size: 12px;
  line-height: 16px;
  font-weight: 600;
  color: #00B4D8;
  text-transform: uppercase;
  letter-spacing: 0.1em;
  margin-bottom: 8px;
}

.section-title {
  font-family: 'Inter', sans-serif;
  font-size: 36px;
  line-height: 44px;
  font-weight: 700;
  color: #0A2E4D;
  letter-spacing: -0.02em;
}
```

#### Call-to-Action Text
```css
.cta-primary {
  font-family: 'Inter', sans-serif;
  font-size: 16px;
  line-height: 24px;
  font-weight: 600;
  letter-spacing: 0;
}

.cta-secondary {
  font-family: 'Inter', sans-serif;
  font-size: 14px;
  line-height: 20px;
  font-weight: 500;
  letter-spacing: 0;
}
```

---

### Text Rendering Optimization
```css
body {
  font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-rendering: optimizeLegibility;
  font-feature-settings: 'kern' 1, 'liga' 1;
}
```

---

## Logo System

### Logo Concept: The Growth Spiral

#### Primary Logo Mark - "The Upward Spiral"
The logo represents continuous growth through focused work - a spiral that moves both inward (focus) and upward (evolution).

**Conceptual Meaning**:
- **Spiral form**: Continuous growth, never-ending evolution
- **Upward direction**: Progress, elevation, transformation
- **Inward-outward**: From focus to insight to expanded capability
- **Gradient application**: Journey from current state (cyan) to evolved state (teal)

**Visual Description**:
```
A minimalist spiral composed of a single continuous line that:
- Starts at the outer bottom-left with Insight Cyan (#00B4D8)
- Spirals inward and upward
- Ends at the inner top-right with Transformation Teal (#06D6A0)
- Line weight: 3px (scales proportionally)
- 3-4 revolutions of the spiral
- Overall form suggests upward-right movement
- Clean, geometric, modern
```

---

### Logo Variations

#### 1. Primary Logo (Full Color)
**Usage**: Digital applications, color backgrounds, marketing
- Spiral: Cyan to Teal gradient
- Wordmark: Deep Ocean Blue (#0A2E4D)
- Spacing: 24px clearance on all sides (minimum)

```
[Spiral Icon]  FOCUS GROWTH
               PLATFORM
```

---

#### 2. Monochrome Logo (Single Color)
**Usage**: Limitations in color reproduction, stamps, merchandise
- All elements: Deep Ocean Blue (#0A2E4D)
- Maintains all proportions
- No gradient

**Sub-variations**:
- **Dark**: Deep Ocean Blue for light backgrounds
- **Light**: White for dark backgrounds
- **Black**: Pure black for print/legal

---

#### 3. Icon Only (App Icon, Favicon)
**Usage**: Small applications, social media avatars, app icons
- Spiral only, no wordmark
- Square format with 15% padding
- Gradient maintained in digital applications
- Solid color for small sizes (< 32px)

**Sizes**:
- Favicon: 32x32px (solid color)
- iOS App Icon: 1024x1024px (gradient)
- Social Media: 400x400px (gradient)

---

#### 4. Horizontal Lockup
**Usage**: Website headers, email signatures, documents
```
[Icon] Platform Name | Tagline
```
- Icon: 40px height
- Wordmark: 32px height
- Tagline: 14px, Medium Gray
- Separator: 1px line, Soft Gray

---

#### 5. Vertical Lockup
**Usage**: Posters, mobile splash screens, vertical layouts
```
    [Icon]
Platform Name
   Tagline
```
- Icon: Centered
- Text: Center-aligned
- Proportional spacing

---

### Logo Specifications

#### Sizing Guidelines
**Minimum Sizes**:
- Full logo (with wordmark): 120px width (digital), 25mm (print)
- Icon only: 24px (digital), 6mm (print)
- Below minimum: Use monochrome version

**Optimal Sizes**:
- Website header: 180-200px width
- Email signature: 150px width
- Print letterhead: 50mm width

---

#### Clear Space
Minimum clear space around logo = height of icon
```
     [Clear Space Border]

         [LOGO]

     [Clear Space Border]
```
- No text, graphics, or other elements within clear space
- Exception: Wordmark can be within icon's clear space in lockup

---

#### Color Backgrounds

**On Light Backgrounds**:
- Use primary full-color logo
- Best on: White, Light Cloud (#F8FAFB), Soft Lavender (#E0E7FF)

**On Dark Backgrounds**:
- Use white monochrome version
- Ensure contrast ratio > 4.5:1
- Best on: Deep Ocean Blue, Deep Charcoal, gradients

**On Colored/Photo Backgrounds**:
- Place logo on 70% opacity white or dark overlay
- Ensure clear visual separation
- Test legibility before implementation

**Never**:
- Place gradient logo on busy backgrounds without overlay
- Use low-contrast combinations
- Place logo on Insight Cyan or Transformation Teal directly

---

#### Wordmark Typography
```css
.logo-wordmark {
  font-family: 'Inter', sans-serif;
  font-weight: 700; /* Bold */
  letter-spacing: -0.03em; /* Tight for cohesion */
  color: #0A2E4D; /* Deep Ocean Blue */
}

.logo-tagline {
  font-family: 'Inter', sans-serif;
  font-weight: 500; /* Medium */
  letter-spacing: 0.05em;
  text-transform: uppercase;
  font-size: 0.4em; /* Relative to wordmark */
  color: #6B7888; /* Medium Gray */
}
```

---

### Logo Usage Rules

#### Do's
- Use approved logo files only
- Maintain aspect ratio when scaling
- Ensure adequate clear space
- Use on appropriate background colors
- Convert to monochrome when color reproduction is limited

#### Don'ts
- Do not rotate or distort the logo
- Do not change colors outside approved variations
- Do not add effects (drop shadows, glows, outlines)
- Do not place logo on busy backgrounds without overlay
- Do not separate icon from wordmark in non-approved layouts
- Do not recreate or redraw the logo
- Do not use old versions of the logo

---

### Logo File Formats

#### Digital Applications
- **SVG**: Vector, preferred for web (scalable, small file size)
- **PNG**: Transparent background, various sizes (1x, 2x, 3x for retina)
- **WebP**: Modern format for web performance

#### Print Applications
- **EPS**: Vector, CMYK color space
- **PDF**: High-resolution, embedded fonts
- **AI**: Adobe Illustrator source file (preserve gradients)

#### File Naming Convention
```
brand-logo-[variation]-[color]-[size].[format]

Examples:
brand-logo-primary-full-color.svg
brand-logo-horizontal-monochrome-dark.png
brand-logo-icon-gradient-2x.png
brand-logo-vertical-white.eps
```

---

### Secondary Brand Marks

#### Pattern Mark - "Focus Grid"
A subtle background pattern using the spiral element:
- Repeated spiral icons at 20% opacity
- Grid spacing: 120px x 120px
- Monotone (Soft Gray or Deep Ocean Blue at low opacity)
- Usage: Website backgrounds, presentation slides, stationery

#### Animated Logo - "Emergence"
For digital applications, an animated version showing the spiral drawing itself:
- 2-second animation
- Spiral draws from outer-left to inner-right
- Color gradient follows the drawing line
- Easing: ease-in-out
- Usage: App loading, video intros, website hero

---

## Imagery Style

### Photography Direction

#### Overall Aesthetic
Our photography should feel like a documentary of knowledge workers in genuine moments of focus and insight - not staged stock photography. Images should be:

- **Authentic, not performative**: Real work environments, genuine expressions
- **Contemplative, not busy**: Moments of thought, not frantic activity
- **Modern, not sterile**: Clean spaces that feel lived-in and human
- **Diverse, not monolithic**: Representation across ages, ethnicities, work styles

---

#### Composition Guidelines

**Perspective**:
- Eye-level or slightly elevated angles (human perspective)
- Avoid extreme angles or distortion
- Medium shots that show person + environment context
- Close-ups for emotional moments (breakthrough, satisfaction)

**Lighting**:
- Natural light preferred (windows, soft daylight)
- Warm, diffused quality (dawn/golden hour feel)
- Avoid harsh shadows or artificial lighting that feels cold
- Suggestion: "Morning light streaming in" aesthetic

**Depth of Field**:
- Shallow depth (f/2.8 - f/4) for subject focus
- Soft background blur suggesting environment without distraction
- Keep subject crisp, surroundings implied

**Negative Space**:
- 40-50% negative space in composition
- Allows for text overlay in marketing
- Reinforces "clarity" and "breathing room"
- Subject positioned in rule-of-thirds grid

---

#### Subject Matter

**Primary Subjects**:
1. **Focus Sessions**: Person working with visible concentration
   - Natural postures (not stiff)
   - Visible computer/notebook but not screen content
   - Expressions of engagement, not stress

2. **Reflection Moments**: Pauses between work
   - Looking away from screen (out window, at distance)
   - Contemplative expressions
   - Coffee cup, journal, empty desk space

3. **Breakthrough Expressions**: Moments of insight
   - Slight smile, raised eyebrows, "aha" look
   - Leaning back in satisfaction
   - Note-taking with energy

4. **Workspace Environments**: Context without people
   - Clean desk with minimal items
   - Plants, notebooks, natural elements
   - Warm wood, soft textiles
   - Technology integrated naturally

**Age Range**: 25-45 (primary target audience)
**Settings**: Home offices, coffee shops, co-working spaces, libraries
**Wardrobes**: Casual professional (not suits, not pajamas)

---

#### Color Grading

**Color Temperature**:
- Slightly warm (2% shift toward yellow/orange)
- Avoid cold blue casts
- Natural skin tones (do not over-process)

**Color Palette Alignment**:
- Desaturate busy backgrounds
- Enhance blues and teals in environment naturally
- Coral/warm tones in human elements (clothing, objects)
- Overall muted palette with selective pops

**Contrast & Exposure**:
- Lifted blacks (slightly milky shadows, not crushed)
- Soft highlights (avoid blown-out whites)
- Medium contrast (not flat, not dramatic)
- Overall exposure: bright but not overexposed

**Post-Processing Style**:
```
Brightness: +5
Contrast: +10
Saturation: -10
Temperature: +2
Highlights: -15
Shadows: +20
Clarity: +5
Vibrance: +10
```

---

### Illustration Style

#### When to Use Illustration vs Photography
- **Photography**: Real user moments, testimonials, authentic scenarios
- **Illustration**: Abstract concepts, onboarding flows, empty states, technical explanations

---

#### Illustration Aesthetic

**Style**: Modern, minimal, geometric with organic touches
- Line-based with selective fills
- 2-3 colors maximum per illustration
- Uses brand color palette
- Slightly rounded corners (4px border-radius on shapes)
- Combination of lines (2px weight) and filled shapes

**Characteristics**:
- Friendly but not childish
- Conceptual but not abstract
- Professional but not corporate
- Human figures simplified but recognizable

**Complexity Level**: Medium
- Not overly detailed
- Not flat/oversimplified
- Enough detail to be recognizable
- Focus on clear communication over artistic expression

---

#### Illustration Subjects

**Conceptual Metaphors**:
- Growth: Sprouting plants, upward arrows, expanding circles
- Focus: Magnifying glass, spotlight, framing devices
- Transformation: Butterfly, dawn/sunrise, gradient transitions
- Insight: Lightbulb, opening door, cleared path

**User Journey Illustrations**:
- Simple character performing actions
- 3-5 step sequences
- Consistent character style across journey
- Environment minimal (focus on action)

**Data Visualization Style**:
- Clean, minimal charts
- Brand colors for data categories
- Ample whitespace
- Clear labels, no decoration
- Rounded corners on bars/elements

---

#### Icon Illustration Guidelines

**Style**: Outlined, 2px stroke weight
- Rounded line caps and joins
- 24x24px base grid
- 2px padding from edge
- Optical alignment over mathematical

**Categories**:
1. **Focus Actions**: Timer, play, pause, stop
2. **Growth Concepts**: Trending up, growth chart, milestone
3. **Reflection Tools**: Journal, thinking, question mark
4. **Navigation**: Home, profile, settings, menu
5. **Feedback**: Success, insight, suggestion, encouragement

**Color Application**:
- Default: Medium Gray (#6B7888)
- Active: Insight Cyan (#00B4D8)
- Success: Transformation Teal (#06D6A0)
- Alert: Warm Coral (#FF6B6B)

---

### Image Treatment

#### Overlay for Text Legibility
When placing text over images:
```css
.image-overlay {
  background: linear-gradient(
    180deg,
    rgba(10, 46, 77, 0) 0%,
    rgba(10, 46, 77, 0.7) 100%
  );
}
```
- Dark gradient from transparent to 70% opacity Deep Ocean Blue
- Text in white
- Minimum height: 200px

---

#### Duotone Effect - "Growth Filter"
For background images behind content:
```css
.image-duotone {
  filter: grayscale(100%);
  mix-blend-mode: multiply;
  opacity: 0.3;
}

/* Applied over cyan-to-teal gradient background */
```
- Convert image to grayscale
- Overlay on brand gradient
- Results in branded duotone effect
- Reduces visual competition with content

---

#### Border Radius & Masking
```css
.image-standard {
  border-radius: 12px; /* Desktop */
}

.image-mobile {
  border-radius: 8px; /* Mobile */
}

.image-hero {
  border-radius: 0; /* Full-bleed heroes */
}
```

---

### Image Specifications

#### File Formats
- **Web**: WebP (primary), JPEG (fallback)
- **Retina**: 2x resolution
- **Compression**: 80% quality (balance file size/quality)

#### Aspect Ratios
- **Hero Images**: 16:9 (1920x1080px)
- **Feature Cards**: 4:3 (800x600px)
- **Portraits**: 3:4 (600x800px)
- **Square Icons**: 1:1 (400x400px)
- **Wide Banners**: 5:2 (1200x480px)

#### Loading Strategy
- Lazy loading for below-fold images
- Placeholder: Brand gradient or blurred preview
- Progressive JPEG for fast perceived loading

---

### Photography Mood Board Reference

**Aesthetic Keywords**:
- "Early morning productivity"
- "Thoughtful knowledge worker"
- "Clean minimal workspace"
- "Natural light home office"
- "Contemplative professional"
- "Quiet focus moment"

**Avoid**:
- High-energy hustle culture imagery
- Sterile corporate environments
- Obvious stock photography poses
- Cluttered or distracting backgrounds
- Harsh lighting or high contrast
- Overly saturated colors

---

## Design Elements

### Iconography System

#### Icon Style Specification
```css
.icon {
  stroke-width: 2px;
  stroke-linecap: round;
  stroke-linejoin: round;
  fill: none;
  width: 24px;
  height: 24px;
}
```

**Grid**: 24x24px
**Stroke**: 2px, rounded caps and joins
**Style**: Outlined (not filled)
**Padding**: 2px from edge of grid
**Alignment**: Optical over mathematical

---

#### Icon Categories & Examples

**Navigation Icons** (Outline style)
- Home: House outline
- Profile: User circle outline
- Settings: Gear outline
- History: Clock with arrow
- Insights: Lightbulb outline

**Action Icons** (Outline style)
- Start: Play circle
- Pause: Pause in circle
- Stop: Square in circle
- Complete: Checkmark in circle
- Add: Plus in circle

**Status Icons** (Can be filled)
- Success: Checkmark in circle (filled teal gradient)
- Info: "i" in circle (filled cyan)
- Warning: Exclamation in triangle (filled gold)
- Error: X in circle (filled coral)

**Concept Icons** (Outline style)
- Growth: Trending up arrow
- Focus: Crosshair/target
- Reflection: Chat bubble with dots
- Insight: Lightbulb with sparkle
- Evolution: Spiral upward

---

#### Icon Color States
```css
/* Default - Inactive */
.icon-default {
  stroke: #6B7888; /* Medium Gray */
}

/* Hover */
.icon-hover {
  stroke: #00B4D8; /* Insight Cyan */
  transition: stroke 0.2s ease;
}

/* Active/Selected */
.icon-active {
  stroke: #0A2E4D; /* Deep Ocean Blue */
}

/* Disabled */
.icon-disabled {
  stroke: #E4E9F0; /* Soft Gray */
  opacity: 0.5;
}

/* Success State */
.icon-success {
  stroke: #06D6A0; /* Transformation Teal */
}
```

---

### Patterns & Textures

#### Subtle Noise Texture
For preventing flat digital feel:
```css
.surface-with-texture::after {
  content: '';
  position: absolute;
  inset: 0;
  background-image: url('noise-texture.png');
  opacity: 0.03;
  mix-blend-mode: multiply;
  pointer-events: none;
}
```
- 5% opacity
- Subtle film grain
- Applies to large background surfaces only
- Never on text or icons

---

#### Dot Grid Pattern - "Focus Grid"
Subtle background pattern suggesting structure:
```css
.dot-grid-background {
  background-image:
    radial-gradient(circle, #E4E9F0 1px, transparent 1px);
  background-size: 24px 24px;
  opacity: 0.4;
}
```
- 24px grid spacing
- 1px dots
- Soft Gray color
- 40% opacity
- Usage: Empty states, background sections

---

#### Gradient Mesh - "Evolution Field"
Organic gradient background for hero sections:
```css
.gradient-mesh {
  background:
    radial-gradient(ellipse at 20% 30%, rgba(0, 180, 216, 0.1) 0%, transparent 50%),
    radial-gradient(ellipse at 80% 70%, rgba(6, 214, 160, 0.1) 0%, transparent 50%),
    linear-gradient(180deg, #FFFFFF 0%, #F8FAFB 100%);
}
```
- Subtle, organic feel
- Not distracting
- Suggests innovation without being loud

---

### Shadows & Depth

#### Shadow System
```css
/* Elevation 1 - Subtle cards */
--shadow-sm: 0 1px 3px rgba(10, 46, 77, 0.08),
             0 1px 2px rgba(10, 46, 77, 0.06);

/* Elevation 2 - Hover cards, dropdowns */
--shadow-md: 0 4px 6px rgba(10, 46, 77, 0.07),
             0 2px 4px rgba(10, 46, 77, 0.06);

/* Elevation 3 - Modals, popovers */
--shadow-lg: 0 10px 15px rgba(10, 46, 77, 0.1),
             0 4px 6px rgba(10, 46, 77, 0.05);

/* Elevation 4 - High-priority modals */
--shadow-xl: 0 20px 25px rgba(10, 46, 77, 0.1),
             0 10px 10px rgba(10, 46, 77, 0.04);

/* Elevation 5 - Maximum elevation */
--shadow-2xl: 0 25px 50px rgba(10, 46, 77, 0.15);
```

**Usage Guidelines**:
- Use sparingly (flat design is default)
- Shadows indicate interactive elevation
- Hover states increase shadow
- Use brand color (Deep Ocean Blue) not pure black
- Soft, diffused shadows only

---

#### Glow Effects - "Insight Moment"
For special emphasis:
```css
.insight-glow {
  box-shadow:
    0 0 20px rgba(0, 180, 216, 0.3),
    0 0 40px rgba(0, 180, 216, 0.1);
  animation: pulse-glow 2s ease-in-out infinite;
}

@keyframes pulse-glow {
  0%, 100% { opacity: 1; }
  50% { opacity: 0.8; }
}
```
- Use for breakthrough insights only
- Cyan glow suggests "lightbulb moment"
- Subtle pulse animation
- Maximum 1 glowing element per screen

---

### Borders & Dividers

#### Border Specifications
```css
/* Subtle border - Default */
--border-width: 1px;
--border-color: #E4E9F0; /* Soft Gray */
--border-radius: 8px;

/* Focus border - Interactive elements */
--border-focus-width: 2px;
--border-focus-color: #00B4D8; /* Insight Cyan */

/* Accent border - Highlighted sections */
--border-accent-width: 2px;
--border-accent-color: linear-gradient(135deg, #00B4D8, #06D6A0);
```

---

#### Divider Styles
```css
/* Horizontal Divider */
.divider-horizontal {
  height: 1px;
  background: linear-gradient(
    90deg,
    transparent 0%,
    #E4E9F0 10%,
    #E4E9F0 90%,
    transparent 100%
  );
  margin: 32px 0;
}

/* Section Divider - With accent */
.divider-section {
  height: 2px;
  background: linear-gradient(
    90deg,
    transparent 0%,
    #00B4D8 50%,
    transparent 100%
  );
  margin: 48px 0;
}
```

---

### Spacing System

#### Base Unit: 4px
All spacing follows an 4px base unit for consistency:

```css
--spacing-unit: 4px;

/* Spacing Scale */
--spacing-2xs: 4px;   /* 1 unit */
--spacing-xs: 8px;    /* 2 units */
--spacing-sm: 12px;   /* 3 units */
--spacing-md: 16px;   /* 4 units */
--spacing-lg: 24px;   /* 6 units */
--spacing-xl: 32px;   /* 8 units */
--spacing-2xl: 48px;  /* 12 units */
--spacing-3xl: 64px;  /* 16 units */
--spacing-4xl: 96px;  /* 24 units */
```

#### Application Guidelines
- **2xs (4px)**: Icon-to-text spacing, tight inline elements
- **xs (8px)**: Button padding vertical, input padding
- **sm (12px)**: Small component spacing
- **md (16px)**: Default spacing, card padding
- **lg (24px)**: Section internal spacing, card spacing
- **xl (32px)**: Component group spacing
- **2xl (48px)**: Section spacing
- **3xl (64px)**: Major section breaks
- **4xl (96px)**: Page section spacing (hero to content)

---

### Motion & Animation

#### Animation Principles
- **Purposeful**: Every animation serves communication
- **Subtle**: Enhance, don't distract
- **Fast**: 200-300ms for most interactions
- **Natural**: Ease curves, not linear

---

#### Timing Functions
```css
/* Standard easing - Most interactions */
--ease-standard: cubic-bezier(0.4, 0.0, 0.2, 1);

/* Deceleration - Entering elements */
--ease-decelerate: cubic-bezier(0.0, 0.0, 0.2, 1);

/* Acceleration - Exiting elements */
--ease-accelerate: cubic-bezier(0.4, 0.0, 1, 1);

/* Smooth - Continuous animations */
--ease-smooth: cubic-bezier(0.4, 0.0, 0.6, 1);
```

---

#### Duration Scale
```css
--duration-instant: 100ms;   /* Hover states */
--duration-fast: 200ms;      /* Button clicks, toggles */
--duration-normal: 300ms;    /* Modals, dropdowns */
--duration-slow: 500ms;      /* Page transitions */
--duration-slower: 800ms;    /* Emphasis animations */
```

---

#### Standard Transitions
```css
/* Button hover */
.button {
  transition: all 200ms var(--ease-standard);
}

/* Card elevation */
.card {
  transition:
    box-shadow 300ms var(--ease-standard),
    transform 300ms var(--ease-standard);
}

/* Modal entrance */
.modal {
  animation: modal-enter 300ms var(--ease-decelerate);
}

@keyframes modal-enter {
  from {
    opacity: 0;
    transform: translateY(-16px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}
```

---

#### Signature Animation - "Insight Reveal"
For displaying insights after focus sessions:
```css
@keyframes insight-reveal {
  0% {
    opacity: 0;
    transform: translateY(24px) scale(0.95);
    filter: blur(4px);
  }
  100% {
    opacity: 1;
    transform: translateY(0) scale(1);
    filter: blur(0);
  }
}

.insight-card {
  animation: insight-reveal 500ms var(--ease-decelerate);
}
```

---

#### Loading States
```css
/* Skeleton loading */
@keyframes skeleton-pulse {
  0%, 100% {
    opacity: 1;
  }
  50% {
    opacity: 0.5;
  }
}

.skeleton {
  background: linear-gradient(
    90deg,
    #E4E9F0 0%,
    #F8FAFB 50%,
    #E4E9F0 100%
  );
  background-size: 200% 100%;
  animation: skeleton-pulse 1.5s ease-in-out infinite;
}

/* Spinner - Uses brand gradient */
@keyframes spinner-rotate {
  from { transform: rotate(0deg); }
  to { transform: rotate(360deg); }
}

.spinner {
  width: 40px;
  height: 40px;
  border: 3px solid #E4E9F0;
  border-top-color: #00B4D8;
  border-radius: 50%;
  animation: spinner-rotate 800ms linear infinite;
}
```

---

## Component Specifications

### Buttons

#### Primary Button
The main call-to-action button with brand gradient:

```css
.button-primary {
  /* Layout */
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 8px;
  padding: 12px 24px;
  border-radius: 8px;
  border: none;

  /* Typography */
  font-family: 'Inter', sans-serif;
  font-size: 16px;
  font-weight: 600;
  line-height: 24px;
  letter-spacing: 0;
  color: #FFFFFF;

  /* Visual */
  background: linear-gradient(135deg, #00B4D8 0%, #06D6A0 100%);
  box-shadow: 0 2px 4px rgba(0, 180, 216, 0.2);
  cursor: pointer;

  /* Interaction */
  transition: all 200ms cubic-bezier(0.4, 0.0, 0.2, 1);
}

.button-primary:hover {
  transform: translateY(-1px);
  box-shadow: 0 4px 8px rgba(0, 180, 216, 0.3);
  background: linear-gradient(135deg, #00A5C8 0%, #05C590 100%);
}

.button-primary:active {
  transform: translateY(0);
  box-shadow: 0 1px 2px rgba(0, 180, 216, 0.2);
}

.button-primary:focus-visible {
  outline: 2px solid #00B4D8;
  outline-offset: 2px;
}

.button-primary:disabled {
  opacity: 0.5;
  cursor: not-allowed;
  transform: none;
}
```

**Sizes**:
```css
.button-sm { padding: 8px 16px; font-size: 14px; }
.button-md { padding: 12px 24px; font-size: 16px; } /* Default */
.button-lg { padding: 16px 32px; font-size: 18px; }
```

---

#### Secondary Button
For less-emphasized actions:

```css
.button-secondary {
  /* Same layout as primary */
  padding: 12px 24px;
  border-radius: 8px;

  /* Visual - Outlined style */
  background: transparent;
  border: 2px solid #0A2E4D;
  color: #0A2E4D;
  box-shadow: none;

  /* Interaction */
  transition: all 200ms cubic-bezier(0.4, 0.0, 0.2, 1);
}

.button-secondary:hover {
  background: #0A2E4D;
  color: #FFFFFF;
  transform: translateY(-1px);
  box-shadow: 0 4px 8px rgba(10, 46, 77, 0.15);
}
```

---

#### Tertiary Button (Ghost)
Minimal button for low-priority actions:

```css
.button-tertiary {
  padding: 12px 24px;
  border-radius: 8px;
  background: transparent;
  border: none;
  color: #6B7888;

  transition: all 200ms cubic-bezier(0.4, 0.0, 0.2, 1);
}

.button-tertiary:hover {
  background: #F8FAFB;
  color: #0A2E4D;
}
```

---

#### Icon Button
For toolbar actions:

```css
.button-icon {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 40px;
  height: 40px;
  border-radius: 8px;
  border: none;
  background: transparent;
  color: #6B7888;
  cursor: pointer;

  transition: all 200ms cubic-bezier(0.4, 0.0, 0.2, 1);
}

.button-icon:hover {
  background: #F8FAFB;
  color: #00B4D8;
}

.button-icon:active {
  background: #E4E9F0;
}
```

---

### Form Inputs

#### Text Input
```css
.input-text {
  /* Layout */
  width: 100%;
  padding: 12px 16px;
  border-radius: 8px;
  border: 1px solid #E4E9F0;

  /* Typography */
  font-family: 'Inter', sans-serif;
  font-size: 16px;
  font-weight: 400;
  line-height: 24px;
  color: #1F2937;

  /* Visual */
  background: #FFFFFF;
  box-shadow: 0 1px 2px rgba(10, 46, 77, 0.04);

  /* Interaction */
  transition: all 200ms cubic-bezier(0.4, 0.0, 0.2, 1);
}

.input-text::placeholder {
  color: #9CA3AF;
}

.input-text:hover {
  border-color: #00B4D8;
}

.input-text:focus {
  outline: none;
  border-color: #00B4D8;
  box-shadow:
    0 0 0 3px rgba(0, 180, 216, 0.1),
    0 1px 2px rgba(10, 46, 77, 0.04);
}

.input-text:disabled {
  background: #F8FAFB;
  color: #9CA3AF;
  cursor: not-allowed;
}

/* Error state */
.input-text.error {
  border-color: #FF6B6B;
}

.input-text.error:focus {
  box-shadow: 0 0 0 3px rgba(255, 107, 107, 0.1);
}
```

---

#### Text Area
```css
.textarea {
  /* Inherits from .input-text */
  min-height: 120px;
  resize: vertical;
  line-height: 24px;
}
```

---

#### Select Dropdown
```css
.select {
  /* Same as input-text */
  appearance: none;
  background-image: url('data:image/svg+xml;utf8,<svg>...</svg>');
  background-repeat: no-repeat;
  background-position: right 12px center;
  padding-right: 40px;
}
```

---

#### Checkbox
```css
.checkbox {
  appearance: none;
  width: 20px;
  height: 20px;
  border: 2px solid #E4E9F0;
  border-radius: 4px;
  background: #FFFFFF;
  cursor: pointer;
  position: relative;

  transition: all 200ms cubic-bezier(0.4, 0.0, 0.2, 1);
}

.checkbox:hover {
  border-color: #00B4D8;
}

.checkbox:checked {
  background: linear-gradient(135deg, #00B4D8, #06D6A0);
  border-color: transparent;
}

.checkbox:checked::after {
  content: '';
  position: absolute;
  left: 6px;
  top: 2px;
  width: 5px;
  height: 10px;
  border: solid white;
  border-width: 0 2px 2px 0;
  transform: rotate(45deg);
}

.checkbox:focus-visible {
  outline: 2px solid #00B4D8;
  outline-offset: 2px;
}
```

---

#### Radio Button
```css
.radio {
  appearance: none;
  width: 20px;
  height: 20px;
  border: 2px solid #E4E9F0;
  border-radius: 50%;
  background: #FFFFFF;
  cursor: pointer;
  position: relative;

  transition: all 200ms cubic-bezier(0.4, 0.0, 0.2, 1);
}

.radio:hover {
  border-color: #00B4D8;
}

.radio:checked {
  border-color: #00B4D8;
}

.radio:checked::after {
  content: '';
  position: absolute;
  inset: 3px;
  border-radius: 50%;
  background: linear-gradient(135deg, #00B4D8, #06D6A0);
}
```

---

#### Toggle Switch
```css
.toggle {
  position: relative;
  width: 48px;
  height: 24px;
  background: #E4E9F0;
  border-radius: 12px;
  cursor: pointer;

  transition: background 200ms cubic-bezier(0.4, 0.0, 0.2, 1);
}

.toggle::after {
  content: '';
  position: absolute;
  top: 2px;
  left: 2px;
  width: 20px;
  height: 20px;
  background: #FFFFFF;
  border-radius: 50%;
  box-shadow: 0 2px 4px rgba(10, 46, 77, 0.15);

  transition: transform 200ms cubic-bezier(0.4, 0.0, 0.2, 1);
}

.toggle[aria-checked="true"] {
  background: linear-gradient(135deg, #00B4D8, #06D6A0);
}

.toggle[aria-checked="true"]::after {
  transform: translateX(24px);
}
```

---

### Cards

#### Standard Card
```css
.card {
  background: #FFFFFF;
  border-radius: 12px;
  border: 1px solid #E4E9F0;
  padding: 24px;
  box-shadow: 0 1px 3px rgba(10, 46, 77, 0.08);

  transition: all 300ms cubic-bezier(0.4, 0.0, 0.2, 1);
}

.card:hover {
  box-shadow: 0 4px 6px rgba(10, 46, 77, 0.07);
  transform: translateY(-2px);
}

/* Card header */
.card__header {
  margin-bottom: 16px;
  padding-bottom: 16px;
  border-bottom: 1px solid #E4E9F0;
}

/* Card title */
.card__title {
  font-size: 20px;
  font-weight: 600;
  line-height: 28px;
  color: #0A2E4D;
  margin: 0;
}

/* Card content */
.card__content {
  color: #1F2937;
  line-height: 24px;
}

/* Card footer */
.card__footer {
  margin-top: 16px;
  padding-top: 16px;
  border-top: 1px solid #E4E9F0;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
```

---

#### Insight Card (Special)
For displaying post-focus insights:

```css
.card-insight {
  background: linear-gradient(135deg, rgba(0, 180, 216, 0.05) 0%, rgba(6, 214, 160, 0.05) 100%);
  border: 2px solid transparent;
  border-radius: 12px;
  padding: 24px;
  position: relative;
  overflow: hidden;
}

/* Gradient border effect */
.card-insight::before {
  content: '';
  position: absolute;
  inset: 0;
  border-radius: 12px;
  padding: 2px;
  background: linear-gradient(135deg, #00B4D8, #06D6A0);
  -webkit-mask:
    linear-gradient(#fff 0 0) content-box,
    linear-gradient(#fff 0 0);
  -webkit-mask-composite: xor;
  mask-composite: exclude;
  pointer-events: none;
}

/* Icon before title */
.card-insight__icon {
  width: 40px;
  height: 40px;
  margin-bottom: 16px;
  background: linear-gradient(135deg, #00B4D8, #06D6A0);
  border-radius: 8px;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
}

.card-insight__quote {
  font-family: 'Fraunces', serif;
  font-size: 18px;
  line-height: 28px;
  color: #0A2E4D;
  font-style: italic;
  margin: 16px 0;
}
```

---

### Navigation

#### Top Navigation Bar
```css
.navbar {
  position: sticky;
  top: 0;
  z-index: 100;
  background: rgba(255, 255, 255, 0.95);
  backdrop-filter: blur(10px);
  border-bottom: 1px solid #E4E9F0;
  padding: 16px 24px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.navbar__logo {
  height: 32px;
}

.navbar__menu {
  display: flex;
  gap: 8px;
  align-items: center;
}

.navbar__link {
  padding: 8px 16px;
  border-radius: 8px;
  font-weight: 500;
  color: #6B7888;
  text-decoration: none;
  transition: all 200ms cubic-bezier(0.4, 0.0, 0.2, 1);
}

.navbar__link:hover {
  background: #F8FAFB;
  color: #0A2E4D;
}

.navbar__link--active {
  color: #00B4D8;
  background: rgba(0, 180, 216, 0.1);
}
```

---

#### Sidebar Navigation
```css
.sidebar {
  width: 240px;
  height: 100vh;
  background: #F8FAFB;
  border-right: 1px solid #E4E9F0;
  padding: 24px 16px;
  position: fixed;
  left: 0;
  top: 0;
}

.sidebar__nav {
  display: flex;
  flex-direction: column;
  gap: 4px;
}

.sidebar__link {
  display: flex;
  align-items: center;
  gap: 12px;
  padding: 12px 16px;
  border-radius: 8px;
  font-weight: 500;
  color: #6B7888;
  text-decoration: none;
  transition: all 200ms cubic-bezier(0.4, 0.0, 0.2, 1);
}

.sidebar__link:hover {
  background: #FFFFFF;
  color: #0A2E4D;
}

.sidebar__link--active {
  background: linear-gradient(135deg, rgba(0, 180, 216, 0.1) 0%, rgba(6, 214, 160, 0.1) 100%);
  color: #00B4D8;
  font-weight: 600;
}

.sidebar__icon {
  width: 20px;
  height: 20px;
}
```

---

### Modals

#### Modal Overlay & Container
```css
.modal-overlay {
  position: fixed;
  inset: 0;
  background: rgba(10, 46, 77, 0.5);
  backdrop-filter: blur(4px);
  z-index: 1000;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 24px;

  animation: fade-in 200ms cubic-bezier(0.0, 0.0, 0.2, 1);
}

@keyframes fade-in {
  from { opacity: 0; }
  to { opacity: 1; }
}

.modal {
  background: #FFFFFF;
  border-radius: 16px;
  max-width: 500px;
  width: 100%;
  max-height: 90vh;
  overflow: auto;
  box-shadow: 0 20px 25px rgba(10, 46, 77, 0.1);

  animation: modal-enter 300ms cubic-bezier(0.0, 0.0, 0.2, 1);
}

@keyframes modal-enter {
  from {
    opacity: 0;
    transform: translateY(-16px) scale(0.95);
  }
  to {
    opacity: 1;
    transform: translateY(0) scale(1);
  }
}

.modal__header {
  padding: 24px 24px 16px;
  border-bottom: 1px solid #E4E9F0;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.modal__title {
  font-size: 24px;
  font-weight: 600;
  color: #0A2E4D;
  margin: 0;
}

.modal__close {
  width: 32px;
  height: 32px;
  border-radius: 8px;
  border: none;
  background: transparent;
  color: #6B7888;
  cursor: pointer;
  transition: all 200ms cubic-bezier(0.4, 0.0, 0.2, 1);
}

.modal__close:hover {
  background: #F8FAFB;
  color: #0A2E4D;
}

.modal__content {
  padding: 24px;
}

.modal__footer {
  padding: 16px 24px 24px;
  display: flex;
  gap: 12px;
  justify-content: flex-end;
}
```

---

### Alerts & Notifications

#### Toast Notification
```css
.toast {
  position: fixed;
  bottom: 24px;
  right: 24px;
  min-width: 320px;
  max-width: 400px;
  background: #FFFFFF;
  border-radius: 12px;
  padding: 16px;
  box-shadow: 0 10px 15px rgba(10, 46, 77, 0.1);
  border-left: 4px solid #00B4D8;
  display: flex;
  gap: 12px;
  align-items: start;

  animation: toast-enter 300ms cubic-bezier(0.0, 0.0, 0.2, 1);
}

@keyframes toast-enter {
  from {
    opacity: 0;
    transform: translateX(100%);
  }
  to {
    opacity: 1;
    transform: translateX(0);
  }
}

.toast--success {
  border-left-color: #06D6A0;
}

.toast--error {
  border-left-color: #FF6B6B;
}

.toast--warning {
  border-left-color: #FFD166;
}

.toast__icon {
  flex-shrink: 0;
  width: 24px;
  height: 24px;
}

.toast__content {
  flex: 1;
}

.toast__title {
  font-weight: 600;
  color: #0A2E4D;
  margin-bottom: 4px;
}

.toast__message {
  font-size: 14px;
  color: #6B7888;
  line-height: 20px;
}

.toast__close {
  flex-shrink: 0;
  width: 24px;
  height: 24px;
  border: none;
  background: transparent;
  color: #9CA3AF;
  cursor: pointer;
  border-radius: 4px;
  transition: all 200ms cubic-bezier(0.4, 0.0, 0.2, 1);
}

.toast__close:hover {
  background: #F8FAFB;
  color: #6B7888;
}
```

---

#### Inline Alert
```css
.alert {
  padding: 16px;
  border-radius: 8px;
  border: 1px solid transparent;
  display: flex;
  gap: 12px;
  align-items: start;
}

.alert--info {
  background: rgba(0, 180, 216, 0.1);
  border-color: rgba(0, 180, 216, 0.3);
  color: #0A2E4D;
}

.alert--success {
  background: rgba(6, 214, 160, 0.1);
  border-color: rgba(6, 214, 160, 0.3);
  color: #0A2E4D;
}

.alert--warning {
  background: rgba(255, 209, 102, 0.1);
  border-color: rgba(255, 209, 102, 0.4);
  color: #1F2937;
}

.alert--error {
  background: rgba(255, 107, 107, 0.1);
  border-color: rgba(255, 107, 107, 0.3);
  color: #1F2937;
}
```

---

### Progress Indicators

#### Progress Bar
```css
.progress {
  width: 100%;
  height: 8px;
  background: #E4E9F0;
  border-radius: 4px;
  overflow: hidden;
}

.progress__bar {
  height: 100%;
  background: linear-gradient(90deg, #00B4D8 0%, #06D6A0 100%);
  border-radius: 4px;
  transition: width 300ms cubic-bezier(0.4, 0.0, 0.2, 1);
}

/* With label */
.progress-labeled {
  display: flex;
  flex-direction: column;
  gap: 8px;
}

.progress-labeled__label {
  display: flex;
  justify-content: space-between;
  font-size: 14px;
  font-weight: 500;
  color: #6B7888;
}
```

---

#### Circular Progress
```css
.circular-progress {
  width: 80px;
  height: 80px;
  position: relative;
}

.circular-progress svg {
  transform: rotate(-90deg);
}

.circular-progress__background {
  fill: none;
  stroke: #E4E9F0;
  stroke-width: 8;
}

.circular-progress__bar {
  fill: none;
  stroke: url(#gradient);
  stroke-width: 8;
  stroke-linecap: round;
  transition: stroke-dashoffset 300ms cubic-bezier(0.4, 0.0, 0.2, 1);
}

.circular-progress__text {
  position: absolute;
  inset: 0;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 20px;
  font-weight: 600;
  color: #0A2E4D;
}
```

---

## Responsive Design

### Breakpoint System

```css
/* Mobile First Breakpoints */
--breakpoint-xs: 0px;      /* Extra small devices (phones) */
--breakpoint-sm: 640px;    /* Small devices (large phones) */
--breakpoint-md: 768px;    /* Medium devices (tablets) */
--breakpoint-lg: 1024px;   /* Large devices (laptops) */
--breakpoint-xl: 1280px;   /* Extra large devices (desktops) */
--breakpoint-2xl: 1536px;  /* 2X large devices (large desktops) */
```

#### Media Query Mixins
```css
/* Mobile first approach */
@media (min-width: 640px) { /* sm */ }
@media (min-width: 768px) { /* md */ }
@media (min-width: 1024px) { /* lg */ }
@media (min-width: 1280px) { /* xl */ }
@media (min-width: 1536px) { /* 2xl */ }
```

---

### Container System

```css
.container {
  width: 100%;
  margin: 0 auto;
  padding: 0 16px;
}

/* Responsive container widths */
@media (min-width: 640px) {
  .container { max-width: 640px; padding: 0 24px; }
}

@media (min-width: 768px) {
  .container { max-width: 768px; }
}

@media (min-width: 1024px) {
  .container { max-width: 1024px; padding: 0 32px; }
}

@media (min-width: 1280px) {
  .container { max-width: 1200px; }
}

@media (min-width: 1536px) {
  .container { max-width: 1280px; }
}
```

---

### Responsive Typography

Typography scales down on smaller screens:

```css
/* Headings responsive scaling */
h1 {
  font-size: 36px; /* Mobile */
  line-height: 44px;
}

@media (min-width: 768px) {
  h1 {
    font-size: 48px; /* Desktop */
    line-height: 56px;
  }
}

h2 {
  font-size: 28px; /* Mobile */
  line-height: 36px;
}

@media (min-width: 768px) {
  h2 {
    font-size: 36px; /* Desktop */
    line-height: 44px;
  }
}

/* Body text remains consistent */
body {
  font-size: 16px;
  line-height: 24px;
}
```

---

### Responsive Spacing

Spacing scales proportionally on smaller screens:

```css
.section {
  padding: 48px 0; /* Mobile */
}

@media (min-width: 768px) {
  .section {
    padding: 64px 0; /* Tablet */
  }
}

@media (min-width: 1024px) {
  .section {
    padding: 96px 0; /* Desktop */
  }
}
```

---

### Grid System

#### Responsive Grid
```css
.grid {
  display: grid;
  gap: 24px;
  grid-template-columns: 1fr; /* Mobile: single column */
}

@media (min-width: 640px) {
  .grid-2 { grid-template-columns: repeat(2, 1fr); }
}

@media (min-width: 768px) {
  .grid-3 { grid-template-columns: repeat(3, 1fr); }
}

@media (min-width: 1024px) {
  .grid-4 { grid-template-columns: repeat(4, 1fr); }
}
```

---

### Mobile Navigation

Mobile menu transforms to hamburger:

```css
.navbar__menu {
  display: none; /* Hidden on mobile */
}

.navbar__hamburger {
  display: block; /* Shown on mobile */
  width: 40px;
  height: 40px;
}

@media (min-width: 768px) {
  .navbar__menu {
    display: flex; /* Shown on desktop */
  }

  .navbar__hamburger {
    display: none; /* Hidden on desktop */
  }
}

/* Mobile menu drawer */
.mobile-menu {
  position: fixed;
  top: 0;
  right: 0;
  width: 280px;
  height: 100vh;
  background: #FFFFFF;
  box-shadow: -4px 0 10px rgba(10, 46, 77, 0.1);
  transform: translateX(100%);
  transition: transform 300ms cubic-bezier(0.4, 0.0, 0.2, 1);
}

.mobile-menu--open {
  transform: translateX(0);
}
```

---

### Touch Target Sizing

All interactive elements meet 44x44px minimum for touch:

```css
.button,
.input,
.checkbox,
.radio,
.toggle {
  min-height: 44px;
  min-width: 44px;
}

/* Or with padding */
.link {
  padding: 12px; /* Creates 44px+ touch target */
}
```

---

### Responsive Images

```css
.responsive-image {
  width: 100%;
  height: auto;
  display: block;
}

/* Responsive background images */
.hero {
  background-size: cover;
  background-position: center;
  min-height: 400px;
}

@media (min-width: 768px) {
  .hero {
    min-height: 600px;
  }
}
```

---

### Responsive Cards

Cards adapt layout on mobile:

```css
.card {
  padding: 16px; /* Mobile */
}

@media (min-width: 768px) {
  .card {
    padding: 24px; /* Desktop */
  }
}

/* Card grid */
.card-grid {
  display: grid;
  gap: 16px;
  grid-template-columns: 1fr; /* Mobile: stack */
}

@media (min-width: 640px) {
  .card-grid {
    grid-template-columns: repeat(2, 1fr); /* Tablet: 2 columns */
    gap: 24px;
  }
}

@media (min-width: 1024px) {
  .card-grid {
    grid-template-columns: repeat(3, 1fr); /* Desktop: 3 columns */
  }
}
```

---

### Hide/Show Responsive Utilities

```css
/* Hide on mobile, show on desktop */
.hidden-mobile {
  display: none;
}

@media (min-width: 768px) {
  .hidden-mobile {
    display: block;
  }
}

/* Show on mobile, hide on desktop */
.visible-mobile {
  display: block;
}

@media (min-width: 768px) {
  .visible-mobile {
    display: none;
  }
}
```

---

## Application Examples

### Landing Page Hero Section

```html
<section class="hero">
  <div class="container">
    <div class="hero__content">
      <h1 class="hero__title">Focus. Reflect. Evolve.</h1>
      <p class="hero__subtitle">
        Turn every focus session into a growth session with AI-powered
        insights that help you learn from your work patterns.
      </p>
      <div class="hero__cta">
        <button class="button-primary button-lg">Start Growing Today</button>
        <button class="button-secondary button-lg">Learn More</button>
      </div>
    </div>
    <div class="hero__image">
      <img src="hero-image.webp" alt="Knowledge worker in focus" />
    </div>
  </div>
</section>
```

```css
.hero {
  min-height: 600px;
  background: linear-gradient(180deg, #FFFFFF 0%, #F8FAFB 100%);
  display: flex;
  align-items: center;
  padding: 48px 0;
}

.hero .container {
  display: grid;
  grid-template-columns: 1fr;
  gap: 48px;
  align-items: center;
}

@media (min-width: 1024px) {
  .hero .container {
    grid-template-columns: 1fr 1fr;
    gap: 64px;
  }
}

.hero__title {
  font-size: 48px;
  line-height: 56px;
  font-weight: 700;
  color: #0A2E4D;
  margin-bottom: 24px;
  background: linear-gradient(135deg, #0A2E4D 0%, #00B4D8 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.hero__subtitle {
  font-size: 20px;
  line-height: 32px;
  color: #6B7888;
  margin-bottom: 32px;
}

.hero__cta {
  display: flex;
  gap: 16px;
  flex-wrap: wrap;
}

.hero__image img {
  width: 100%;
  border-radius: 12px;
  box-shadow: 0 20px 25px rgba(10, 46, 77, 0.1);
}
```

---

### Focus Session Timer Interface

```html
<div class="timer-interface">
  <div class="timer-interface__header">
    <h2>Focus Session</h2>
    <button class="button-icon" aria-label="Settings">
      <svg>...</svg>
    </button>
  </div>

  <div class="timer-interface__display">
    <svg class="circular-progress">
      <circle class="circular-progress__background" />
      <circle class="circular-progress__bar" />
    </svg>
    <div class="timer-interface__time">25:00</div>
  </div>

  <div class="timer-interface__task">
    <input
      type="text"
      placeholder="What are you focusing on?"
      class="input-text"
    />
  </div>

  <div class="timer-interface__controls">
    <button class="button-primary button-lg timer-start">
      <svg>...</svg>
      Start Focus
    </button>
  </div>
</div>
```

```css
.timer-interface {
  max-width: 500px;
  margin: 0 auto;
  padding: 48px 24px;
  text-align: center;
}

.timer-interface__header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 48px;
}

.timer-interface__display {
  position: relative;
  width: 240px;
  height: 240px;
  margin: 0 auto 48px;
}

.timer-interface__time {
  position: absolute;
  inset: 0;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 48px;
  font-weight: 700;
  color: #0A2E4D;
  font-variant-numeric: tabular-nums;
}

.timer-interface__task {
  margin-bottom: 32px;
}

.timer-interface__controls {
  display: flex;
  justify-content: center;
  gap: 16px;
}

.timer-start {
  width: 100%;
  max-width: 300px;
}
```

---

### Insight Card Display

```html
<div class="card-insight" role="article">
  <div class="card-insight__icon">
    <svg>...</svg>
  </div>

  <h3 class="card-insight__title">Pattern Recognition</h3>

  <blockquote class="card-insight__quote">
    "You've analyzed three competitors this week using the same
    framework each time. What if you examined them through a
    customer's emotional journey rather than features?"
  </blockquote>

  <div class="card-insight__actions">
    <button class="button-secondary button-sm">Reflect on This</button>
    <button class="button-tertiary button-sm">Save for Later</button>
  </div>
</div>
```

---

### Dashboard Layout

```html
<div class="dashboard">
  <aside class="sidebar">
    <div class="sidebar__logo">
      <img src="logo.svg" alt="Platform Logo" />
    </div>
    <nav class="sidebar__nav">
      <a href="#" class="sidebar__link sidebar__link--active">
        <svg class="sidebar__icon">...</svg>
        Dashboard
      </a>
      <a href="#" class="sidebar__link">
        <svg class="sidebar__icon">...</svg>
        Focus Sessions
      </a>
      <a href="#" class="sidebar__link">
        <svg class="sidebar__icon">...</svg>
        Insights
      </a>
      <a href="#" class="sidebar__link">
        <svg class="sidebar__icon">...</svg>
        Growth Timeline
      </a>
    </nav>
  </aside>

  <main class="dashboard__content">
    <header class="dashboard__header">
      <h1>Welcome back, Sarah</h1>
      <p>Ready to turn today's focus into growth?</p>
    </header>

    <div class="dashboard__grid">
      <div class="card">
        <h3>Today's Focus</h3>
        <!-- Content -->
      </div>
      <div class="card">
        <h3>Recent Insights</h3>
        <!-- Content -->
      </div>
      <div class="card">
        <h3>Growth Streak</h3>
        <!-- Content -->
      </div>
    </div>
  </main>
</div>
```

```css
.dashboard {
  display: flex;
  min-height: 100vh;
}

.dashboard__content {
  flex: 1;
  margin-left: 240px;
  padding: 48px;
  background: #F8FAFB;
}

.dashboard__header {
  margin-bottom: 48px;
}

.dashboard__header h1 {
  font-size: 36px;
  font-weight: 700;
  color: #0A2E4D;
  margin-bottom: 8px;
}

.dashboard__header p {
  font-size: 18px;
  color: #6B7888;
}

.dashboard__grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 24px;
}

@media (max-width: 768px) {
  .sidebar {
    transform: translateX(-100%);
    transition: transform 300ms cubic-bezier(0.4, 0.0, 0.2, 1);
  }

  .sidebar--open {
    transform: translateX(0);
  }

  .dashboard__content {
    margin-left: 0;
    padding: 24px;
  }
}
```

---

## Design System Maintenance

### Version Control
- All design tokens stored in CSS variables
- Changes tracked in design-system.css file
- Version numbering: Major.Minor.Patch
- Document all changes in changelog

### Component Library
- Maintain Figma component library
- Sync with code components quarterly
- Document component usage examples
- Provide code snippets for developers

### Accessibility Audits
- Quarterly WCAG 2.1 AA compliance checks
- Automated contrast ratio testing
- Keyboard navigation verification
- Screen reader testing

### Design Tokens Export
```css
/* Export for other platforms */
:root {
  /* Colors */
  --color-brand-primary: #0A2E4D;
  --color-brand-secondary: #00B4D8;
  --color-accent: #06D6A0;

  /* Typography */
  --font-family-primary: 'Inter', sans-serif;
  --font-size-base: 16px;

  /* Spacing */
  --spacing-unit: 4px;

  /* Border Radius */
  --radius-sm: 4px;
  --radius-md: 8px;
  --radius-lg: 12px;

  /* Shadows */
  --shadow-sm: 0 1px 3px rgba(10, 46, 77, 0.08);

  /* Breakpoints */
  --breakpoint-mobile: 640px;
  --breakpoint-tablet: 768px;
  --breakpoint-desktop: 1024px;
}
```

---

## Quick Reference

### Primary Brand Colors
- Deep Ocean Blue: `#0A2E4D`
- Insight Cyan: `#00B4D8`
- Transformation Teal: `#06D6A0`
- Warm Coral: `#FF6B6B`

### Typography
- Primary: Inter (400, 500, 600, 700)
- Secondary: Fraunces (400, 600)
- Base size: 16px
- Line height: 1.5 (body), 1.2 (headings)

### Spacing Scale
4px, 8px, 12px, 16px, 24px, 32px, 48px, 64px, 96px

### Border Radius
- Small: 4px
- Medium: 8px
- Large: 12px
- Extra Large: 16px

### Breakpoints
- Mobile: 640px
- Tablet: 768px
- Desktop: 1024px
- Wide: 1280px

---

## Contact & Support

For questions about implementing these guidelines:
- Design System Documentation: [Link to living style guide]
- Figma Component Library: [Link to Figma]
- Code Repository: [Link to GitHub]
- Design Team: design@platform.com

---

*These guidelines are a living document. Last updated: January 2026*
*Version 1.0 - Initial Release*
