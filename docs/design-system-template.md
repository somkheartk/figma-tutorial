# Template: Design System สำหรับ Mobile App

## Color Palette

### Primary Colors
```
Primary: #6366F1
Primary Dark: #4F46E5
Primary Light: #818CF8
```

### Secondary Colors
```
Secondary: #8B5CF6
Secondary Dark: #7C3AED
Secondary Light: #A78BFA
```

### Neutral Colors
```
White: #FFFFFF
Gray 50: #F9FAFB
Gray 100: #F3F4F6
Gray 200: #E5E7EB
Gray 300: #D1D5DB
Gray 400: #9CA3AF
Gray 500: #6B7280
Gray 600: #4B5563
Gray 700: #374151
Gray 800: #1F2937
Gray 900: #111827
Black: #000000
```

### Semantic Colors
```
Success: #10B981
Success Light: #34D399
Success Dark: #059669

Warning: #F59E0B
Warning Light: #FBBF24
Warning Dark: #D97706

Error: #EF4444
Error Light: #F87171
Error Dark: #DC2626

Info: #3B82F6
Info Light: #60A5FA
Info Dark: #2563EB
```

---

## Typography

### Font Family
```
Primary: SF Pro / Inter / Roboto
Secondary: SF Pro Rounded / Poppins
Monospace: SF Mono / Roboto Mono
```

### Type Scale

#### Headings
```
H1 - Display Large
Size: 32px / 2rem
Weight: Bold (700)
Line Height: 40px
Letter Spacing: -0.5px

H2 - Display Medium
Size: 28px / 1.75rem
Weight: Bold (700)
Line Height: 36px
Letter Spacing: -0.5px

H3 - Display Small
Size: 24px / 1.5rem
Weight: Semi-bold (600)
Line Height: 32px
Letter Spacing: 0px

H4 - Heading
Size: 20px / 1.25rem
Weight: Semi-bold (600)
Line Height: 28px
Letter Spacing: 0px
```

#### Body Text
```
Body Large
Size: 18px / 1.125rem
Weight: Regular (400)
Line Height: 28px

Body
Size: 16px / 1rem
Weight: Regular (400)
Line Height: 24px

Body Small
Size: 14px / 0.875rem
Weight: Regular (400)
Line Height: 20px
```

#### Labels & Captions
```
Label
Size: 14px / 0.875rem
Weight: Medium (500)
Line Height: 20px

Caption
Size: 12px / 0.75rem
Weight: Regular (400)
Line Height: 16px

Overline
Size: 12px / 0.75rem
Weight: Bold (700)
Line Height: 16px
Letter Spacing: 1px
Text Transform: Uppercase
```

---

## Spacing System

### Base Unit: 8px

```
4px   = 0.5 unit
8px   = 1 unit
12px  = 1.5 units
16px  = 2 units
24px  = 3 units
32px  = 4 units
40px  = 5 units
48px  = 6 units
64px  = 8 units
80px  = 10 units
96px  = 12 units
```

### Usage Guidelines

**Component Padding:**
- Small: 8px
- Medium: 16px
- Large: 24px

**Section Spacing:**
- Between sections: 32px
- Between related items: 16px
- Between unrelated items: 24px

**Screen Margins:**
- Mobile: 16px - 24px
- Tablet: 24px - 32px

---

## Components

### Button

#### Sizes
```
Large:
- Height: 56px
- Padding: 24px horizontal
- Font Size: 16px
- Corner Radius: 12px

Medium (Default):
- Height: 48px
- Padding: 20px horizontal
- Font Size: 16px
- Corner Radius: 12px

Small:
- Height: 40px
- Padding: 16px horizontal
- Font Size: 14px
- Corner Radius: 8px
```

#### Variants
```
Primary:
- Background: Primary Color
- Text: White
- State (Hover): Primary Dark
- State (Pressed): Primary Dark + Opacity 90%
- State (Disabled): Gray 300, Text Gray 500

Secondary:
- Background: Transparent
- Border: 1px Primary Color
- Text: Primary Color
- State (Hover): Primary Color 10% background
- State (Pressed): Primary Color 20% background
- State (Disabled): Gray 300 border, Text Gray 500

Text:
- Background: Transparent
- Text: Primary Color
- State (Hover): Primary Color 10% background
- State (Pressed): Primary Color 20% background
- State (Disabled): Text Gray 500
```

### Input Field

```
Default:
- Height: 48px
- Padding: 12px horizontal
- Border: 1px Gray 300
- Corner Radius: 8px
- Font Size: 16px
- Placeholder: Gray 500

States:
- Focus: Border Primary Color, 2px
- Error: Border Error Color, 2px
- Disabled: Background Gray 100, Border Gray 200
- Success: Border Success Color, 2px
```

### Card

```
Default:
- Background: White
- Corner Radius: 12px
- Shadow: 0px 2px 8px rgba(0,0,0,0.08)
- Padding: 16px

Elevated:
- Shadow: 0px 4px 16px rgba(0,0,0,0.12)

Interactive (Hover):
- Shadow: 0px 8px 24px rgba(0,0,0,0.16)
- Transform: translateY(-2px)
```

### Icon

```
Sizes:
- Small: 16x16px
- Medium: 24x24px
- Large: 32x32px
- XLarge: 48x48px

Colors:
- Primary: Gray 900 (default)
- Secondary: Gray 600
- Disabled: Gray 400
- Interactive: Primary Color
```

---

## Effects

### Shadows

```
Shadow Small:
- X: 0px, Y: 1px
- Blur: 2px
- Color: rgba(0,0,0,0.05)

Shadow Medium:
- X: 0px, Y: 2px
- Blur: 8px
- Color: rgba(0,0,0,0.08)

Shadow Large:
- X: 0px, Y: 4px
- Blur: 16px
- Color: rgba(0,0,0,0.12)

Shadow XLarge:
- X: 0px, Y: 8px
- Blur: 24px
- Color: rgba(0,0,0,0.16)
```

### Border Radius

```
None: 0px
Small: 4px
Medium: 8px
Large: 12px
XLarge: 16px
Round: 24px
Circle: 50% / 9999px
```

---

## Iconography

### Style Guidelines
- Line weight: 2px
- Style: Rounded caps
- Size: 24x24px canvas (default)
- Padding: 2px internal padding

### Recommended Icon Sets
- Material Icons
- Feather Icons
- Heroicons
- Phosphor Icons
- Iconify

---

## Grid & Layout

### Mobile (320px - 767px)
```
Columns: 4
Gutter: 16px
Margin: 16px
```

### Tablet (768px - 1023px)
```
Columns: 8
Gutter: 24px
Margin: 24px
```

### Desktop (1024px+)
```
Columns: 12
Gutter: 24px
Margin: Auto (max-width: 1200px)
```

---

## Animation & Transitions

### Duration
```
Fast: 150ms
Normal: 250ms
Slow: 350ms
Very Slow: 500ms
```

### Easing
```
Ease In: cubic-bezier(0.4, 0, 1, 1)
Ease Out: cubic-bezier(0, 0, 0.2, 1)
Ease In Out: cubic-bezier(0.4, 0, 0.2, 1)
```

### Common Animations
```
Fade In/Out:
- Duration: 250ms
- Easing: Ease In Out
- Opacity: 0 ↔ 1

Slide:
- Duration: 250ms
- Easing: Ease Out
- Transform: translateY/X

Scale:
- Duration: 150ms
- Easing: Ease Out
- Transform: scale(0.95 ↔ 1)
```

---

## Accessibility

### Contrast Ratios
- Normal text: 4.5:1 minimum
- Large text (18px+): 3:1 minimum
- UI components: 3:1 minimum

### Touch Targets
- Minimum: 44x44px
- Recommended: 48x48px
- Optimal: 56x56px

### Font Sizes
- Minimum: 14px for body text
- Recommended: 16px for body text
- Labels: 12px minimum

---

## Responsive Breakpoints

```
Mobile Small: 320px
Mobile: 375px (iPhone SE)
Mobile Large: 414px (iPhone Pro Max)
Tablet: 768px (iPad)
Tablet Large: 1024px (iPad Pro)
Desktop: 1280px
Desktop Large: 1440px
Desktop XL: 1920px
```

---

## Best Practices

1. **Always use the Design System**
   - Don't create custom colors or text styles
   - Use defined components when possible
   - Follow spacing guidelines

2. **Maintain Consistency**
   - Same actions should look the same
   - Use patterns consistently throughout
   - Keep visual hierarchy clear

3. **Consider Accessibility**
   - Check color contrast
   - Ensure touch targets are large enough
   - Test with screen readers in mind

4. **Document Changes**
   - Update this document when making changes
   - Version your design system
   - Communicate updates to the team

5. **Test Across Devices**
   - Check on different screen sizes
   - Test on actual devices
   - Verify in both light and dark modes (if applicable)
