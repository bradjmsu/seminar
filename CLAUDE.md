# AI Implementation Summit Style Guide

## Typography

### Font Families
- **Primary Serif**: 'Crimson Text' - Used for headings, titles, and emphasis
- **Secondary Sans**: 'Inter' or system fonts (-apple-system, BlinkMacSystemFont) - Used for body text
- **Font Weights**: 300 (light), 400 (regular), 500 (medium), 600 (semibold), 700 (bold)

### Font Sizes
- **Hero Titles**: 3.75rem to 4rem (60-64px)
- **Section Titles**: 2.25rem to 2.5rem (36-40px)
- **Subsection Headers**: 1.625rem (26px)
- **Body Text**: 0.875rem to 1rem (14-16px)
- **Small Text/Labels**: 0.7rem to 0.75rem (11-12px)
- **Micro Text**: 0.65rem (10px)

### Text Styling
- **Letter Spacing**: 
  - Uppercase labels: 0.08em to 0.15em
  - Body text: 0.01em to 0.02em
  - Headlines: -0.01em to -0.02em (tighter)
- **Line Height**: 1.3 to 1.6 for readability
- **Text Transform**: Uppercase for labels and badges

## Color Palette

### Primary Colors
- **Deep Blue**: #0066cc (primary actions, links, accents)
- **Dark Blue Hover**: #0052a3
- **Text Black**: #0a0a0a (main text)
- **Dark Background**: #0a0b0d (for dark mode screens)

### Neutral Colors
- **White**: #ffffff
- **Off-White**: #fafafa, #f8f9fa
- **Light Gray**: #f5f5f5, #f0f0f0
- **Border Gray**: #e0e0e0, #e8e8e8
- **Medium Gray**: #666666 (secondary text)
- **Dark Gray**: #444444
- **Muted Text**: #888888, #999999

### Dark Mode Specific
- **Card Background**: #1a1b1e
- **Card Border**: #2a2b2e
- **Hover State**: #222326
- **Input Background**: #1f2023

### Accent Colors
- **Success Green**: #00aa66
- **Warning/Info Blue**: #0077b5 (LinkedIn blue)
- **Google Blue**: #4285f4

## Layout & Spacing

### Container Widths
- **Max Width**: 1200px for main content
- **Card Max Width**: 820px
- **Form Max Width**: 500px
- **Compact Elements**: 380px

### Spacing Scale
- **0.125rem** (2px) - Micro spacing
- **0.25rem** (4px) - Tight spacing
- **0.5rem** (8px) - Small spacing
- **0.75rem** (12px) - Default spacing
- **1rem** (16px) - Standard spacing
- **1.5rem** (24px) - Medium spacing
- **2rem** (32px) - Large spacing
- **3rem** (48px) - Extra large spacing
- **4rem** (64px) - Hero spacing

### Grid Systems
- **2-column**: 50/50 or 1fr/1fr
- **3-column**: Equal thirds for stats/features
- **5-column**: For agenda/timeline views

## Components

### Cards
- **Background**: White (#ffffff) or dark (#1a1b1e)
- **Border**: 1px solid #e0e0e0 (light) or #2a2b2e (dark)
- **Border Radius**: 6px to 12px
- **Padding**: 0.875rem to 2.5rem depending on content
- **Shadow**: Minimal (0 1px 3px rgba(0,0,0,0.04))

### Buttons
- **Primary Button**:
  - Background: #0066cc
  - Hover: #0052a3
  - Padding: 1rem 3rem (or 1.25rem for full-width)
  - Font Weight: 500
  - Letter Spacing: 0.02em
  - No border radius (sharp corners)
  
### Form Elements
- **Input Fields**:
  - Background: #f8f9fa (light) or #1a1b1e (dark)
  - Border: 1px solid #e0e0e0
  - Padding: 1rem 1.25rem
  - Focus Border: #0066cc
  - Transition: all 0.3s ease

### Status Indicators
- **Pulse Animation**: 2s infinite opacity fade
- **Progress Dots**: 8px circles, 32px when active
- **Step Indicators**: 60px x 2px bars
- **Type Indicators**: 4px x 24px colored bars

## Visual Hierarchy

### Content Organization
1. **Uppercase Labels** with wide letter spacing for categories
2. **Large Serif Headlines** for main titles
3. **Sans-serif Body Text** for readability
4. **Subtle Borders** instead of heavy dividers
5. **Generous White Space** for premium feel

### Interactive States
- **Hover**: Subtle background color shift, slight shadow
- **Active**: Border color change to primary blue
- **Selected**: Background tint with primary color at 10% opacity

## Animation & Transitions

### Standard Transitions
- **Duration**: 0.2s to 0.3s for micro-interactions
- **Easing**: ease, ease-out, or ease-in-out
- **Properties**: all, background-color, border-color, transform

### Page Transitions
- **Fade**: 0.6s ease-in-out
- **Slide Up**: translateY(30px) to translateY(0) with fade
- **Scale**: scale(0.8) to scale(1) for emphasis

## Professional Touches

### Key Design Principles
1. **Minimal Shadows** - Only where necessary for depth
2. **Consistent Spacing** - Use the spacing scale religiously
3. **Premium Feel** - Generous white space, refined typography
4. **High Contrast** - Ensure readability (AAA where possible)
5. **Subtle Animations** - Enhance, don't distract

### Brand Elements
- **Workshop Badge**: Small, uppercase, widely spaced
- **Location Indicator**: Separated by bullet or divider
- **Company Logos**: Contained in circular frames with borders
- **Time Display**: Large serif font for elegance

## Responsive Considerations

### Breakpoints
- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

### Mobile Adaptations
- Single column layouts
- Increased touch targets (min 44px)
- Simplified navigation
- Maintained typography scale

---

## Implementation Notes

When creating new components:
1. Start with this color palette and typography
2. Use consistent spacing from the scale
3. Maintain the premium, professional aesthetic
4. Keep interactions subtle and smooth
5. Ensure text remains highly readable
6. Use serif fonts for emphasis and headlines
7. Keep cards and containers clean with plenty of breathing room