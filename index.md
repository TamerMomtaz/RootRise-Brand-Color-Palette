# RootRise Complete Brand Color Palette
**Logo Colors + Interface Design System**

---

## 🎨 PRIMARY BRAND COLORS (Logo)

### 🟡 Gold/Bronze (Brand Primary)
The signature gold used in the RootRise logo text.

- **HEX:** `#E1A549`
- **RGB:** `rgb(225, 165, 73)`
- **CMYK:** `C0 M27 Y68 K12`
- **HSL:** `hsl(36°, 72%, 58%)`

**Usage:** Logo text, primary headings, CTAs, key highlights, premium accents

---

### 🔵 Dark Blue-Teal (Brand Background)
The deep blue-teal color from the logo background.

- **HEX:** `#132938`
- **RGB:** `rgb(19, 41, 56)`
- **CMYK:** `C66 M27 Y0 K78`
- **HSL:** `hsl(204°, 49%, 15%)`

**Usage:** Logo backgrounds, hero sections, footer

---

### 🔷 Medium Blue-Teal (Brand Accent)
Mid-tone blue-teal for gradients and depth.

- **HEX:** `#23445B`
- **RGB:** `rgb(35, 68, 91)`
- **CMYK:** `C62 M25 Y0 K64`
- **HSL:** `hsl(205°, 44%, 25%)`

**Usage:** Gradient transitions, hover states, secondary surfaces

---

### 🔶 Light Blue-Teal (Brand Highlight)
Lighter teal for accents and visual depth.

- **HEX:** `#2D5068`
- **RGB:** `rgb(45, 80, 104)`
- **CMYK:** `C57 M23 Y0 K59`
- **HSL:** `hsl(204°, 40%, 29%)`

**Usage:** Borders, dividers, subtle highlights, light accents

---

## 💻 INTERFACE COLORS (Web/App)

### 🌑 Interface Dark (Sidebar/Navigation)
The dark navy-blue-gray used for sidebars and top navigation.

- **HEX:** `#18243D`
- **RGB:** `rgb(24, 36, 61)`
- **CMYK:** `C61 M41 Y0 K76`
- **HSL:** `hsl(218°, 44%, 17%)`

**Usage:** Sidebar backgrounds, top navigation bar, dark UI surfaces, app headers

---

### 💙 Interface Card Background
The blue-gray color used for card containers and content areas.

- **HEX:** `#213552`
- **RGB:** `rgb(33, 53, 82)`
- **CMYK:** `C60 M35 Y0 K68`
- **HSL:** `hsl(215°, 43%, 23%)`

**Usage:** Card backgrounds, content containers, panels, modal backgrounds

---

### ⬜ Text Primary (White)
Primary text color for headings and important content on dark backgrounds.

- **HEX:** `#FFFFFF`
- **RGB:** `rgb(255, 255, 255)`
- **CMYK:** `C0 M0 Y0 K0`
- **HSL:** `hsl(0°, 0%, 100%)`

**Usage:** Main headings, primary text on dark backgrounds, important labels

---

### 💬 Text Secondary (Light Gray)
Secondary text color for descriptions and body copy.

- **HEX:** `#9CA6BA`
- **RGB:** `rgb(156, 166, 186)`
- **CMYK:** `C16 M11 Y0 K27`
- **HSL:** `hsl(220°, 19%, 67%)`

**Usage:** Body text, descriptions, secondary information, timestamps

---

### 🎨 Icon Background (Gold/Tan)
Warm gold-tan color for icon backgrounds (premium features).

- **HEX:** `#B3A068`
- **RGB:** `rgb(179, 160, 104)`
- **CMYK:** `C0 M11 Y42 K30`
- **HSL:** `hsl(45°, 33%, 55%)`

**Usage:** Premium feature icons, special badges, highlighted UI elements

---

### ⚪ Icon Background (Cool Gray)
Neutral cool gray for standard icon backgrounds.

- **HEX:** `#5F6A73`
- **RGB:** `rgb(95, 106, 115)`
- **CMYK:** `C17 M8 Y0 K55`
- **HSL:** `hsl(207°, 10%, 41%)`

**Usage:** Standard icon backgrounds, neutral badges, utility elements

---

## 📋 QUICK REFERENCE

### CSS Variables
```css
:root {
  /* Brand Colors (Logo) */
  --brand-gold: #E1A549;
  --brand-blue-dark: #132938;
  --brand-blue-medium: #23445B;
  --brand-blue-light: #2D5068;
  
  /* Interface Colors */
  --ui-dark: #18243D;
  --ui-card-bg: #213552;
  --ui-text-primary: #FFFFFF;
  --ui-text-secondary: #9CA6BA;
  --ui-icon-gold: #B3A068;
  --ui-icon-gray: #5F6A73;
}

/* Gradients */
.brand-gradient {
  background: linear-gradient(90deg, 
    #132938 0%, 
    #23445B 50%, 
    #2D5068 100%
  );
}

.interface-gradient {
  background: linear-gradient(135deg,
    #18243D 0%,
    #213552 100%
  );
}
```

---

## 🎨 COLOR USAGE MATRIX

| Element | Primary Color | Secondary Color | Text Color |
|---------|--------------|-----------------|------------|
| **Logo** | Gold #E1A549 | Dark Blue #132938 | - |
| **Hero Section** | Dark Blue #132938 | Gold #E1A549 | White #FFFFFF |
| **Navigation** | Interface Dark #18243D | Gold #E1A549 | White #FFFFFF |
| **Cards** | Card BG #213552 | - | White #FFFFFF |
| **Body Text** | - | - | Light Gray #9CA6BA |
| **Premium Icons** | Icon Gold #B3A068 | Gold #E1A549 | Dark #18243D |
| **Standard Icons** | Icon Gray #5F6A73 | - | White #FFFFFF |
| **Buttons (Primary)** | Gold #E1A549 | - | Dark #18243D |
| **Buttons (Secondary)** | Transparent | Gold #E1A549 border | Gold #E1A549 |

---

## 🎯 DESIGN SYSTEM GUIDELINES

### Background Layers (Dark to Light)
1. **Base:** Interface Dark (#18243D) - Sidebar, navigation
2. **Layer 1:** Card Background (#213552) - Content containers
3. **Layer 2:** Medium Blue-Teal (#23445B) - Elevated elements
4. **Layer 3:** Light Blue-Teal (#2D5068) - Highest elevation

### Text Hierarchy
1. **H1-H2 Headings:** White (#FFFFFF) at 100% opacity
2. **H3-H4 Subheadings:** White (#FFFFFF) at 90% opacity
3. **Body Text:** Light Gray (#9CA6BA) at 100% opacity
4. **Caption/Meta:** Light Gray (#9CA6BA) at 70% opacity

### Interactive States
- **Default:** Base color
- **Hover:** Lighten 10% or add gold tint
- **Active:** Gold (#E1A549)
- **Disabled:** 40% opacity
- **Focus:** Gold (#E1A549) border/outline

---

## 🖨️ PRINT SPECIFICATIONS

### Logo (Print)
- **Gold Text:** C0 M27 Y68 K12
- **Dark Blue Background:** C66 M27 Y0 K78

### Business Cards
- **Front:** Dark Blue (#132938) background, Gold (#E1A549) logo
- **Back:** White background, Dark Blue (#132938) text

### Letterhead
- **Header:** Interface Dark (#18243D)
- **Accent Line:** Gold (#E1A549)
- **Body Text:** Dark Blue (#132938)

---

## ♿ ACCESSIBILITY COMPLIANCE

### Contrast Ratios (WCAG Standards)

| Foreground | Background | Ratio | Rating |
|------------|------------|-------|--------|
| Gold #E1A549 | Dark Blue #132938 | 8.5:1 | AAA ✅ |
| White #FFFFFF | Interface Dark #18243D | 14.2:1 | AAA ✅ |
| White #FFFFFF | Card BG #213552 | 11.3:1 | AAA ✅ |
| Light Gray #9CA6BA | Card BG #213552 | 6.1:1 | AA ✅ |
| Gold #E1A549 | White #FFFFFF | 3.2:1 | AA (Large text only) ⚠️ |

**Note:** Always use gold on dark backgrounds for optimal readability.

---

## 🌈 COLOR PSYCHOLOGY & BRAND MESSAGING

### Gold (#E1A549)
**Represents:** Premium quality, transformation, achievement, growth, excellence, success, value, warmth

**Evokes:** Trust through expertise, aspiration, high-quality service, professional transformation

### Dark Blue-Teal (#132938-#2D5068)
**Represents:** Trust, professionalism, stability, depth, intelligence, technology, reliability, corporate strength

**Evokes:** Confidence in systems, technical competence, established authority, digital innovation

### Combined Message
**"Professional transformation and measurable growth rooted in solid, trustworthy, intelligent foundations."**

The palette communicates that RootRise delivers premium, expert-guided transformation (gold) through reliable, professional, technology-driven systems (blue-teal).

---

## 🎨 BRAND COLOR COMBINATIONS

### Primary Combination (High Impact)
- Background: Dark Blue (#132938)
- Primary: Gold (#E1A549)
- Text: White (#FFFFFF)
- **Use for:** Hero sections, CTAs, key messaging

### Interface Combination (Web/App)
- Background: Interface Dark (#18243D)
- Cards: Card Background (#213552)
- Primary Text: White (#FFFFFF)
- Secondary Text: Light Gray (#9CA6BA)
- Accents: Gold (#E1A549)
- **Use for:** Application UI, dashboards, admin panels

### Print Combination (Marketing Materials)
- Primary: Dark Blue (#132938)
- Accent: Gold (#E1A549)
- Text: Dark Blue on white, White on dark blue
- **Use for:** Brochures, business cards, presentations

### Monochrome (When Limited to One Color)
- Option 1: Gold (#E1A549) only - for premium feel
- Option 2: Dark Blue (#132938) only - for corporate feel
- **Use for:** Single-color printing, stamps, embossing

---

## 📱 RESPONSIVE DESIGN NOTES

### Mobile
- Increase contrast for outdoor viewing
- Use Interface Dark (#18243D) for larger backgrounds (less battery drain on OLED)
- Gold accents remain at full saturation

### Desktop
- Full gradient usage allowed
- Richer depth with all blue-teal variations
- More sophisticated icon treatments

### Dark Mode (Already Optimized)
- Current palette IS dark mode optimized
- No adjustments needed

### Light Mode Alternative (If Needed)
- Background: #F5F7FA (light blue-gray)
- Cards: #FFFFFF (white)
- Text: #18243D (interface dark)
- Accents: Gold #E1A549 (unchanged)
- CTAs: Dark Blue #132938 (unchanged)

---

## 🔧 DESIGN TOOL EXPORTS

### Figma/Sketch Color Styles
```
Brand/Gold Primary: #E1A549
Brand/Blue Dark: #132938
Brand/Blue Medium: #23445B
Brand/Blue Light: #2D5068
UI/Dark: #18243D
UI/Card Background: #213552
UI/Text Primary: #FFFFFF
UI/Text Secondary: #9CA6BA
UI/Icon Gold: #B3A068
UI/Icon Gray: #5F6A73
```

### Adobe Creative Suite
**Swatches:**
- RootRise Gold: C0 M27 Y68 K12
- RootRise Blue: C66 M27 Y0 K78
- Interface Dark: C61 M41 Y0 K76
- Card Background: C60 M35 Y0 K68

---

## ✅ QUALITY CONTROL CHECKLIST

When creating RootRise materials, verify:

- [ ] Gold is #E1A549 (not yellow, not orange)
- [ ] Dark backgrounds use #132938 or #18243D (not pure black)
- [ ] White text on dark backgrounds (never reversed)
- [ ] Gold elements have sufficient contrast (8:1 minimum)
- [ ] Icon backgrounds match style (gold for premium, gray for standard)
- [ ] Gradients follow brand direction (dark to light, left to right)
- [ ] Print colors use CMYK values (not RGB/HEX conversions)
- [ ] Accessibility standards met (AA minimum, AAA preferred)

---

## 📞 BRAND SUPPORT

For questions about color usage or brand guidelines:
- Refer to this official color palette document
- Contact: RootRise Marketing Team
- Version: 2.0 (includes interface colors)
- Last Updated: November 2025

---

## 🎯 FILE FORMATS INCLUDED

This complete color palette includes:
- **Logo Colors:** 4 brand colors for logo usage
- **Interface Colors:** 6 UI colors for web/app design
- **Total Colors:** 10 distinct colors in the system
- **All Formats:** HEX, RGB, CMYK, HSL provided for each

---

*This comprehensive color palette is proprietary to RootRise/DEVONEERS. Consistent use of these exact color values across all materials ensures strong brand recognition, professional presentation, and cohesive user experience.*
