---
name: Dynamic Precision
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#444651'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#757682'
  outline-variant: '#c5c5d3'
  surface-tint: '#4059aa'
  primary: '#00236f'
  on-primary: '#ffffff'
  primary-container: '#1e3a8a'
  on-primary-container: '#90a8ff'
  inverse-primary: '#b6c4ff'
  secondary: '#006398'
  on-secondary: '#ffffff'
  secondary-container: '#5bb8fe'
  on-secondary-container: '#00476e'
  tertiary: '#3e2400'
  on-tertiary: '#ffffff'
  tertiary-container: '#5c3800'
  on-tertiary-container: '#ef9900'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b6c4ff'
  on-primary-fixed: '#00164e'
  on-primary-fixed-variant: '#264191'
  secondary-fixed: '#cce5ff'
  secondary-fixed-dim: '#93ccff'
  on-secondary-fixed: '#001d31'
  on-secondary-fixed-variant: '#004b73'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
  brand-navy-dark: '#0F172A'
  brand-navy-surface: '#1E293B'
  electric-blue: '#2563EB'
  amber-highlight: '#F59E0B'
  amber-subtle: '#FEF3C7'
  slate-surface: '#F8FAFC'
  surface-border: '#E2E8F0'
  surface-border-strong: '#CBD5E1'
  success-green: '#10B981'
  critical-red: '#EF4444'
  critical-surface: '#FEE2E2'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.025em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-caps:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.06em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 1.5rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
  space-3xl: 6rem
---

## Brand & Style

### Brand Personality & Narrative
This design system modernizes the institutional automotive presence of an accredited driving school and driver credential agency into a precision-engineered, high-trust digital platform. The aesthetic replaces legacy municipal harshness with high-performance mobility cues: deep structural navies, calibrated electric cobalt accents, and warm golden-amber signals reminiscent of road instrument clusters and certification stamps.

The interface serves dual audiences:
1. **Aspiring standard motorists (Patente A, B):** Demanding clarity, straightforward booking flows, transparent pricing, and approachable exam preparation.
2. **Commercial & professional transport operators (CQC Merci/Persone, Patenti Superiori C/D/E, Recupero Punti):** Demanding certified compliance, institutional authority, schedule rigor, and operational trust.

### Visual Style Movement
The visual style is **Contemporary Automotive Modernism** layered onto an engineered bento grid. It combines clean geometric surfaces, hairline metallic borders, precise pill badges, and layered depth:
- **Foundational surfaces:** Pure crisp white containers resting over subtle cool-slate tinted backdrops.
- **Micro-accents:** Refined technical details including soft-toned border outlines, deliberate 2px structural accents, and focused status indicators.
- **Physical cues:** Measured elevation lifts on hover, tactile press states (`scale-98`), and high-readability typographic contrast engineered for low eye fatigue under varying mobile light conditions.

## Colors

### Color Strategy
The color architecture systematically deprecates the uncalibrated `rgb(0, 0, 255)` in favor of an intentional automotive palette that communicates safety, legal compliance, and technical mastery:

- **Primary (`#1E3A8A` - Automotive Navy):** The foundational anchor. Applied to key navigation frames, primary interactive targets, prominent headers, and high-trust certification modules.
- **Secondary (`#0284C7` - Electric Cobalt/Cyan):** The functional engine. Applied to focused interactive states, active link indicators, progress trackers, and secondary CTAs.
- **Tertiary (`#F59E0B` - Precision Amber/Gold):** The operational signifier. Reserved for urgency triggers, "PIÙ RICHIESTO" endorsements, professional CQC credential badges, and review status alerts.
- **Neutral (`#0F172A` - Midnight Slate):** Governs high-emphasis body text, header titles, and primary contrast zones, providing deeper contrast than generic grays.

### System Token Roles
- **Page Canvas:** `#F8FAFC` provides a clean, glare-free background that lifts `#FFFFFF` structural cards.
- **Card Fills:** Pure white `#FFFFFF` for default bento tiles; rich dark navy `#0F172A` with contrasting white copy for standout professional CQC modules.
- **Dividers & Outlines:** `#E2E8F0` for resting card borders and section breaks; `#CBD5E1` for hover states and active form boundaries.
- **Semantic Overlays:** `#FEE2E2` / `#EF4444` for points loss penalty warnings ("Recupero Punti") and validation errors; `#FEF3C7` / `#B45309` for urgent exam booking alerts.

## Typography

### Typographic Pairing Logic
- **Headlines & Action Labels (Plus Jakarta Sans):** Geometric clarity with sculpted apertures and modern automotive tech proportions. It provides immediate readability and punch across page titles, stat callouts, navigation items, and pill badges.
- **Body & Longform Copy (Inter):** Highly neutral and legible grotesque designed for effortless screen readability across dense licensing requirements, schedules, and legal notices.

### Hierarchy & Responsive Rules
- All headlines above 30px automatically step down on mobile screens (`<= 768px`) using dedicated responsive tokens (`display-hero-mobile`, `headline-lg-mobile`) to prevent awkward line breaks and overflow.
- `label-caps` is strictly uppercase with `0.06em` tracking for meta categories (e.g., "CATEGORIA CQC", "DURATA MINIMA", "NOVITÀ CODICE").
- Numerical statistics (e.g., "+20 PUNTI", "98% PROMOSSI") must utilize tabular figures (`tnum`) in Plus Jakarta Sans Semi-Bold or Bold.

## Layout & Spacing

### Grid Architecture & Spacing Rhythm
The design system implements an 8pt spatial grid centered around an engineered 12-column layout with a strict maximum container width of `1240px`:

- **Desktop (>= 1024px):** 12-column fluid grid, `gutter: 1.5rem` (24px), page canvas `margin: 2rem` (32px).
- **Tablet (768px - 1023px):** 8-column layout, `gutter: 1.25rem` (20px), outer margin `1.5rem` (24px).
- **Mobile (< 768px):** 4-column layout, `gutter: 1rem` (16px), outer margin `1rem` (16px).

### Bento Composition Guidelines
- **Featured Driver Module (Patente B / Guida Accompagnata):** Spans 8 columns on desktop, showcasing vehicle preview, pricing, and next available session dates.
- **Accompanying License Modules (Patente A / Superiori):** Span 4 columns on desktop, stacked with direct spec lists.
- **Professional Enterprise Row (CQC & Cronotachigrafo):** Spans 12 columns as a dark inverse-surface banner (`#0F172A`) or split 7/5 with an integrated fast-track registration trigger.
- **Vertical Rhythm:** Standard component card padding defaults to `space-lg` (24px). Section dividers and macro layout stacks enforce `space-2xl` (64px) on desktop and `space-xl` (40px) on mobile.

## Elevation & Depth

### Depth Model
Visual elevation eschews heavy diffuse black drops in favor of **Crisp Architectural Layering**: high-precision borders, subtle surface container contrast, and directional cool-tinted shadows.

1. **Level 0 (Flat Canvas):** Page body `#F8FAFC`. Completely unshadowed.
2. **Level 1 (Default Containers & Bento Cards):** `#FFFFFF` fill bounded by a crisp 1px hairline border in `#E2E8F0`. Rest elevation shadow:
   `box-shadow: 0 1px 3px 0 rgba(15, 23, 42, 0.04), 0 1px 2px -1px rgba(15, 23, 42, 0.03);`
3. **Level 2 (Interactive Card Hover):** 
   Card surfaces elevate upward with a `-2px` Y-translate and a cool-tinted navy shadow:
   `box-shadow: 0 12px 24px -4px rgba(15, 23, 42, 0.08), 0 4px 6px -2px rgba(15, 23, 42, 0.03);`
   Border transitions to `#CBD5E1`.
4. **Level 3 (Sticky Navigation & Floating Action Bars):**
   `#FFFFFF/95` with `backdrop-filter: blur(12px)` and a directional floor outline:
   `box-shadow: 0 4px 20px -2px rgba(15, 23, 42, 0.06);`
   Bottom border: `1px solid #E2E8F0`.
5. **Level 4 (Modals & Flyout Sheets):**
   `box-shadow: 0 24px 48px -12px rgba(15, 23, 42, 0.18);`

## Shapes

### Shape Language
The shape hierarchy balances contemporary software precision with industrial resilience:
- **Base Components (`roundedness: 2` - 8px / 0.5rem):** Form inputs, default buttons, select menus, image viewports, and card containers.
- **Expanded Structures (`rounded-lg` - 16px / 1rem):** Master Bento cards, highlighted callout banners, and interactive modals.
- **Pill Elements (`rounded-full`):** Badges ("PIÙ RICHIESTO", "CQC MERCI"), status chips, floating map actions, and tab switchers.
- **Proportional Consistency:** Child elements nested inside cards (e.g. inner thumbnail containers or stat widgets) maintain an inner radius of `rounded-sm` (4px to 6px) to maintain harmonious concentric corners with the outer 16px frame.

## Components

### Buttons
- **Primary Action (Call to Action):**
  - Fill: Deep Automotive Navy (`#1E3A8A`) transitioning to `#172554` on hover.
  - Text: `#FFFFFF`, `label-md` (Plus Jakarta Sans Semi-Bold).
  - Shape & Size: Height `44px` (desktop), padding `0 20px`, `rounded-md` (8px).
  - Micro-interaction: Press state executes `transform: scale(0.98)` with `transition: all 150ms ease-out`.
- **Secondary / Ghost Button:**
  - Fill: Transparent.
  - Border: `1px solid #CBD5E1`, text `#0F172A`.
  - Hover: Background `#F1F5F9`, border `#94A3B8`.
- **Accent Highlight Button (Exam Booking / CQC Direct Action):**
  - Fill: Precision Amber (`#F59E0B`) with text `#0F172A` (Bold).
  - Hover: `#D97706` with slight ambient amber glow `0 4px 14px rgba(245, 158, 11, 0.35)`.

### Badge Tags & Status Chips
- **"Più Richiesto" / Top Choice Badge:**
  - Pill shape (`rounded-full`), padding `4px 12px`.
  - Background `#FEF3C7`, text `#B45309`, border `1px solid #FDE68A`.
  - Typography: `label-caps` (11px Bold, uppercase tracking).
- **License Category Tag (e.g., "PATENTE B", "CQC CORSO"):**
  - Background `#EFF6FF`, text `#1E40AF`, border `1px solid #BFDBFE`.
- **Warning / Demerit Indicator ("Recupero Punti"):**
  - Background `#FEE2E2`, text `#991B1B`, border `1px solid #FECACA`.

### Navigation Bar
- Fixed top navigation, height `72px`, background `#FFFFFF/95` with `backdrop-filter: blur(12px)`.
- Border bottom `1px solid #E2E8F0`.
- Left-aligned bold brand mark with dual-tone treatment ("AUTOSCUOLA **DS**").
- Centered desktop nav links in `label-md` with `#475569` resting state; active item features an electric cobalt underline bar (`height: 2px`, bottom: `-1px`, color: `#0284C7`) and `#0F172A` text.
- Right-aligned contact action button with integrated phone / fast contact trigger.

### Cards & Bento Tiles
- **Standard Course Card:**
  - Surface `#FFFFFF`, border `1px solid #E2E8F0`, padding `24px`.
  - Image frame: 16:9 aspect ratio, overflow hidden, subtle zoom (`scale-103`) on hover.
  - Divided metadata footer (duration, exam requirements) separated by `1px solid #F1F5F9`.
- **Professional Enterprise Banner (CQC / Driver License Card):**
  - Surface `#0F172A` (Midnight Slate), text `#FFFFFF`.
  - Accent details highlighted in `#38BDF8` (Sky) and `#F59E0B` (Amber).
  - Accentuated button in vibrant high-contrast fill.

### Input Fields & Forms
- Base height `46px`, padding `0 14px`, border `1px solid #CBD5E1`, background `#FFFFFF`.
- Typography: `body-md` (Inter 15px), text `#0F172A`, placeholder `#94A3B8`.
- Focus state: Border color `#0284C7`, outline none, box shadow `0 0 0 3px rgba(2, 132, 199, 0.15)`.
- Error state: Border color `#EF4444`, ring `0 0 0 3px rgba(239, 68, 68, 0.15)`.

### Checkboxes & Radios
- Size `18px × 18px`, border `1.5px solid #94A3B8`, `rounded` (4px for checkbox, fully round for radio).
- Selected state: Background `#1E3A8A`, check glyph pure white `#FFFFFF`.