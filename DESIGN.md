---
name: Empowered Mobility
colors:
  surface: '#fff7fa'
  surface-dim: '#dfd8db'
  surface-bright: '#fff7fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f9f2f4'
  surface-container: '#f4ecee'
  surface-container-high: '#eee6e9'
  surface-container-highest: '#e8e1e3'
  on-surface: '#1e1b1d'
  on-surface-variant: '#5a4043'
  inverse-surface: '#332f31'
  inverse-on-surface: '#f7eff1'
  outline: '#8e7072'
  outline-variant: '#e2bec1'
  surface-tint: '#b81745'
  primary: '#a7013b'
  on-primary: '#ffffff'
  primary-container: '#ca2851'
  on-primary-container: '#ffe7e8'
  inverse-primary: '#ffb2ba'
  secondary: '#af2d32'
  on-secondary: '#ffffff'
  secondary-container: '#fe6665'
  on-secondary-container: '#69000e'
  tertiary: '#7d450f'
  on-tertiary: '#ffffff'
  tertiary-container: '#9a5c26'
  on-tertiary-container: '#ffe9da'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9dc'
  primary-fixed-dim: '#ffb2ba'
  on-primary-fixed: '#400011'
  on-primary-fixed-variant: '#910031'
  secondary-fixed: '#ffdad7'
  secondary-fixed-dim: '#ffb3af'
  on-secondary-fixed: '#410005'
  on-secondary-fixed-variant: '#8e121d'
  tertiary-fixed: '#ffdcc4'
  tertiary-fixed-dim: '#ffb77f'
  on-tertiary-fixed: '#2f1500'
  on-tertiary-fixed-variant: '#6e3903'
  background: '#fff7fa'
  on-background: '#1e1b1d'
  surface-variant: '#e8e1e3'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  margin: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system delivers an empowering, protective, and modern commuter experience tailored specifically for women commuters, university students, and working professionals across Bangladesh. It blends the uncompromising trust of safety-first technology with the welcoming warmth of community-focused transit. 

The aesthetic style is **Warm Minimalist Tactile**:
- High-clarity layouts engineered for quick, stress-free decision making in busy urban environments (Dhaka, Chittagong).
- Soft, generous corner radii (20px–24px) that feel human, protective, and friendly rather than harsh or purely corporate.
- A distinctive crimson-to-warm-peach gradient tone echoing the curves and warmth of the brand mark, balancing instant security recognition with everyday lifestyle comfort.
- Empathetic micro-copy translated into seamless bilingual clarity (English/Bangla context), prioritizing reassurance, SOS immediacy, verified rider badges, and transparent route sharing.

## Colors

The color palette is built around strength, community warmth, and uncompromising visual hierarchy:

- **Primary Accent (`#CA2851` - Deep Crimson / Dark Marple):** Anchors the brand identity, primary calls to action, active navigation states, verified user status seals, and critical security signals. It projects authority, vigilance, and resolute safety.
- **Secondary Highlight (`#FF6766` - Coral Pink):** Injects feminine vibrance and optimism. Applied to active tabs, secondary button borders, live tracking trails, and highlight cards.
- **Warm Accent (`#FFB173` - Peach / Warm Orange):** Expresses warmth and community solidarity in SafePool carpools, ride-sharing counters, and rating stars.
- **Soft Background Accent (`#FFE3B3` - Soft Cream / Pastel Warmth):** Utilized for soft badge backgrounds, pill chip fills, trip banner accents, and comforting modal callouts.
- **Neutral Canvas (`#FAFAFA` / `#FFFFFF`):** High-cleanliness white and off-white base providing pristine contrast.
- **Text & Structural Darks (`#1E1B1D` - Midnight Black & `#3A0815` - Deep Velvet Crimson):** Ensure AAA contrast ratios for body copy, addresses, ride timings, and critical safety typography.

## Typography

**Plus Jakarta Sans** is the sole typographic choice across all tiers. Its clean geometric underpinnings combined with warm, rounded counters resonate naturally with the curvilinear geometry of the primary brand mark.

- **Display & Headlines:** Bold, punchy, and instantly legible even during motion or direct sunlight. Tight tracking (-0.01em to -0.02em) provides an authoritative, premium app aesthetic.
- **Body:** Open apertures ensure legibility at smaller scales for route directions, Bengali location names, driver ratings, and emergency instructions.
- **Labels & Badges:** Slightly wider tracking on uppercase and title-case labels ensures fast scannability on small screens during time-sensitive journeys.

## Layout & Spacing

The layout model is mobile-first, prioritizing one-handed thumb-reach zones and clutter-free map overlays:

- **Mobile Viewport (360px - 480px):** Built on a 4-column fluid layout with a default screen margin of `1.25rem` (20px) and `1rem` (16px) gutters. The bottom 35% of the viewport is reserved for dynamic action sheets (ride booking, captain verification, SafePool matchmaking).
- **Tablet / Responsive Expand (481px - 768px):** Expands to 8 columns with centered container cards (max width 600px) keeping interaction points within comfortable reach.
- **Spacing Rhythm:** Structured on an 8pt baseline scale. Micro elements (icon-to-label, badge tags) use `0.25rem` (4px) and `0.5rem` (8px). Card inner padding standardizes at `1rem` to `1.25rem` to sustain an airy, unhurried feel.

## Elevation & Depth

Visual hierarchy uses a combination of **tonal surface layering** and **warm ambient shadows**:

- **Surface Level 0 (Canvas):** Crisp `#FAFAFA` neutral background.
- **Surface Level 1 (Resting Cards & Lists):** Pure `#FFFFFF` cards with a warm-tinted ambient drop shadow: `0 4px 20px rgba(58, 8, 21, 0.04)`.
- **Surface Level 2 (Floating Pickups, Active Filters, Sheet Headers):** `0 8px 30px rgba(202, 40, 81, 0.08)`.
- **Surface Level 3 (SOS Trigger, Emergency Modals & Floating Action Hubs):** `0 12px 36px rgba(202, 40, 81, 0.22)`. The SOS trigger utilizes a pulsating glow `0 0 0 8px rgba(202, 40, 81, 0.15)` for effortless recognition in crisis scenarios.
- **Glass Overlays:** Bottom sheets over live maps leverage `backdrop-filter: blur(16px)` with `background: rgba(255, 255, 255, 0.92)` to preserve spatial awareness of real-time transit paths.

## Shapes

The shape system embraces friendly, generous curvilinear architecture:
- Standard cards, interactive tiles, and bottom sheets use **20px to 24px corner radii** (`rounded-xl` / `rounded-2xl` equivalent), directly echoing the fluid circular forms in the brand monogram.
- Form inputs, segmented tabs, and standard buttons employ **14px to 16px corner radii**.
- Badges, status tags, pill buttons, and the SOS quick-dock utilize full circular or **pill-shaped (9999px)** profiles.

## Components

### Buttons
- **Primary Action (Book SheGO, Request Ride):** Solid `#CA2851` gradient to `#FF6766` background, crisp white typography (`label-lg`), minimum 52px height for thumb ergonomics, rounded at 16px or full-pill, slight forward elevation.
- **SafePool Shared Ride:** Tinted warm peach background (`#FFE3B3`) with `#3A0815` typography and `#FFB173` subtle borders.
- **SOS Button:** Persistent floating red badge with prominent white typography and tactile outer ring pulse. A single long-press (1.5s) dispatches live audio, location, and emergency SMS alerts to verified guardians and Bangladesh Police National Emergency Service (999).

### Cards & Feed Tiles
- **Ride Option Card:** White container (`#FFFFFF`), 20px rounded corners, with vehicle icon (Scooty, Car, SafePool micro-bus), driver gender verification mark ("100% Female Verified"), transparent price breakdown, and ETA indicator.
- **Driver / Pool Buddy Profile Card:** Circular avatar with a dual-colored verification border (`#CA2851` + `#FF6766`), ride count badge, safety badges, and direct call/masking options.

### Chips & Badges
- **Safety Badges:** Pill-shaped, 11px uppercase (`label-sm`), styled with `#FFE3B3` background and `#CA2851` text (e.g., "FEMALE PILOT", "CAMPUS POOL", "NID VERIFIED").
- **Ride Category Filters:** Resting on white background with `#1E1B1D` text; active state fills with `#CA2851` and turns text white.

### Input Fields & Search Bars
- **Location Selector (Pickup / Drop-off):** 54px height, background `#FFFFFF`, border `1px solid rgba(202, 40, 81, 0.12)`, 16px corner radius. Focused state glows with `#FF6766` at 20% opacity. Destination dots use `#CA2851` for pickup and `#FFB173` for drop-off.

### Selection Controls
- **Radio & Checkboxes:** Custom rounded selectors with `#CA2851` active fill and clean white checkmark / inner dot. Unselected states feature a soft `#1E1B1D` stroke at 15% opacity.

### Emergency & Safety Sheets
- **Guardian Tracking Drawer:** Displays 3 trusted emergency contacts with quick-dial icons, battery state of the passenger's phone, and real-time live-stream GPS link.