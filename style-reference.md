# Quick Style Reference

## Essential Design DNA

### Typography Hierarchy
```
Hero Title:      Crimson Text, 3.75rem, weight 400
Section Title:   Crimson Text, 2.25rem, weight 400  
Subsection:      Inter, 1.125rem, weight 500
Body:            Inter, 0.875-1rem, weight 400
Label:           Inter, 0.75rem, weight 600, uppercase, 0.1em spacing
```

### Color Usage
```
Primary Action:   #0066cc (blue)
Main Text:        #0a0a0a (near black)
Secondary Text:   #666666 (gray)
Muted Text:       #888888 (lighter gray)
Borders:          #e0e0e0 (light gray)
Background:       #ffffff, #fafafa (white/off-white)
Dark Mode BG:     #0a0b0d, #1a1b1e
```

### Spacing Pattern
```
Micro:   0.125rem (2px)    - Between related elements
Small:   0.5rem (8px)      - Inside components  
Default: 1rem (16px)       - Between components
Medium:  1.5rem (24px)     - Section spacing
Large:   3rem (48px)       - Major sections
```

### Component Patterns

**Cards**
- White background
- 1px border (#e0e0e0)
- 6-12px border radius
- 0.875-2.5rem padding
- Minimal shadow (0 1px 3px rgba(0,0,0,0.04))

**Buttons**
- #0066cc background
- No border radius (sharp)
- 1rem vertical, 3rem horizontal padding
- Font weight 500
- 0.02em letter spacing
- All caps for small buttons

**Form Fields**
- Light gray background (#f8f9fa)
- 1px border
- 1rem padding
- Blue focus border (#0066cc)
- 0.3s transition

### Professional Touches
1. **Generous white space** - Never cramped
2. **Subtle animations** - 0.2-0.3s transitions
3. **High contrast** - Always readable
4. **Consistent alignment** - Grid-based layouts
5. **Typography mix** - Serif for emphasis, sans for body

### Key Differentiators
- **Serif headlines** (Crimson Text) for premium feel
- **Uppercase labels** with wide letter spacing
- **Minimal shadows** - Let borders do the work
- **Blue accent** - Used sparingly for impact
- **Clean cards** - Simple borders, no heavy shadows

## Usage Examples

### Workshop Title
```html
<h1 style="font-family: 'Crimson Text'; font-size: 3.75rem; font-weight: 400;">
  AI in <strong style="font-style: italic;">Marketing</strong>
</h1>
```

### Status Badge
```html
<div style="font-size: 0.75rem; text-transform: uppercase; 
           letter-spacing: 0.1em; color: #0066cc;">
  Executive Workshop
</div>
```

### Info Card
```html
<div style="background: white; border: 1px solid #e0e0e0; 
           border-radius: 10px; padding: 1.5rem;">
  <div style="font-family: 'Crimson Text'; font-size: 1.375rem;">42</div>
  <div style="font-size: 0.7rem; color: #666; text-transform: uppercase; 
             letter-spacing: 0.08em;">Participants</div>
</div>
```

This style creates a **premium, professional** aesthetic that's **modern yet timeless**, perfect for senior marketing professionals.