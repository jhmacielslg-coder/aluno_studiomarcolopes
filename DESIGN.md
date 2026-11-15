---
name: Biomecha Kinetic Dark
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#e6bdb9'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#ad8885'
  outline-variant: '#5c3f3d'
  surface-tint: '#ffb3ad'
  primary: '#ffb3ad'
  on-primary: '#68000a'
  primary-container: '#d91e2a'
  on-primary-container: '#fff0ee'
  inverse-primary: '#c0001c'
  secondary: '#c7c6c6'
  on-secondary: '#2f3131'
  secondary-container: '#484949'
  on-secondary-container: '#b8b8b8'
  tertiary: '#ffb3b0'
  on-tertiary: '#68000f'
  tertiary-container: '#dc1130'
  on-tertiary-container: '#fff0ef'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad7'
  primary-fixed-dim: '#ffb3ad'
  on-primary-fixed: '#410004'
  on-primary-fixed-variant: '#930013'
  secondary-fixed: '#e3e2e2'
  secondary-fixed-dim: '#c7c6c6'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#464747'
  tertiary-fixed: '#ffdad8'
  tertiary-fixed-dim: '#ffb3b0'
  on-tertiary-fixed: '#410006'
  on-tertiary-fixed-variant: '#93001a'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 40px
    fontWeight: '900'
    lineHeight: 48px
    letterSpacing: -0.02em
  display-sm:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 26px
    fontWeight: '800'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Montserrat
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 28px
  headline-sm:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '700'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.04em
  label-md:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-sm:
    fontFamily: Montserrat
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.08em
  timer-display:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 52px
    letterSpacing: -0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  margin: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system delivers an elite, high-performance athletic experience fused with cybernetic biomechanics and predictive artificial intelligence. It serves disciplined athletes, bodybuilders, and fitness enthusiasts who require precision tracking, high-energy feedback, and uncompromising aesthetic clarity.

The visual language blends **High-Contrast Dark Mode** with **Refined Tactile Skeuomorphism and Glassmorphism**:
- Deep obsidian and graphite canvas tones create an immersive, low-strain backdrop that highlights training metrics.
- High-velocity energetic reds and arterial crimson gradients ignite focus, adrenaline, and primary calls to action.
- Brushed chrome, titanium borders, and soft specular highlights evoke anatomical strength, heavy iron, and advanced AI diagnostics.
- The interface feels hyper-responsive, authoritative, and motivating—eliminating cognitive clutter so users can focus purely on execution and biometric progression.

## Colors

The palette is engineered for high-contrast dark environments, optimizing legibility during intense training sessions while conserving battery on OLED displays.

### Palette Architecture
- **Primary Red (`#D91E2A`):** The signature engine color. Used for primary interactive triggers, active states, progress rings, and key biometric highlights.
- **Vibrant Crimson (`#FF3344`):** The kinetic glow color. Paired with the primary red in 135-degree gradients to convey speed, heart rate acceleration, and high exertion.
- **Metallic Chrome & Platinum (`#B0B0B0`):** Provides a brushed metallic sheen for secondary icons, step counters, and technical micro-copy.
- **Deep Base & Layers:**
  - Base Obsidian: `#0A0A0A` (canvas ground)
  - Surface Tier 1: `#141414` (primary cards and navigation panels)
  - Surface Tier 2: `#1A1A1A` (nested cards, list rows, and input fields)
  - Surface Elevated: `#242424` (floating pills, active filters, and modal headers)
- **Borders & Overlays:** Low-opacity white strokes (`rgba(255, 255, 255, 0.08)`) and selective crimson highlights (`rgba(217, 30, 42, 0.4)`) define structural boundaries without visual noise.
- **Typography Contrasts:** Absolute white (`#FFFFFF`) for bold titles; high-readability cool silver (`#D1D5DB`) for functional body; muted metallic grey (`#8E8E93`) for passive labels and timestamps.

## Typography

Typography establishes an athletic cadence: commanding display headlines paired with ultra-legible utilitarian body text.

- **Headings & Badges (`Montserrat`):** Utilizes bold weights (700–900). Category tags, stat headers, and navigation markers leverage uppercase transformations with tracking (`+0.04em` to `+0.08em`) to mirror luxury automotive and sports instrumentation.
- **Body & Functional UI (`Inter`):** Delivers clean readability for exercise instructions, workout sets, reps, and conversational AI guidance. Neutral kerning ensures complex numerical data remains clear at high heart rates.
- **Timers & Biometric Metrics:** Rest intervals, countdowns, and load weights use heavy monospace figures derived from `Montserrat` to prevent layout shift during second-by-second updates.

## Layout & Spacing

The layout is built primarily for mobile viewports using a strict 4-column system on compact screens (up to 480px), transitioning to an 8-column layout on tablets and a centered max-width container on larger screens.

- **Mobile Canvas Margins:** 16px (`1rem`) outer margins allow edge-to-edge immersion while maintaining safe tap boundaries.
- **Vertical Rhythm:**
  - Card internal padding: 16px (`space-md`) for workout cards; 20px–24px (`space-lg`) for hero telemetry modules.
  - Inter-card gap: 12px–16px (`space-md`) to separate distinct routine steps and workout categories.
  - Section stack spacing: 24px–32px (`space-xl`) between distinct training blocks (e.g., Active Timer vs. Series Checklist).
- **Safe Area Insets:** Strict 16px clearance above native bottom navigation bars and dynamic island notches, ensuring action triggers are thumb-accessible within the lower 40% of the screen.

## Elevation & Depth

Visual depth is achieved through layered dark surfaces, crisp inner borders, and chromatic luminescence rather than conventional murky drop shadows.

- **Surface Tiers:**
  - **Level 0 (Canvas):** Pure `#0A0A0A`. Background void.
  - **Level 1 (Structural Cards):** `#141414` with a 1px border of `rgba(255, 255, 255, 0.08)`.
  - **Level 2 (Active Modules & Inputs):** `#1A1A1A` with a subtle top highlight (`inset 0 1px 0 rgba(255, 255, 255, 0.05)`).
- **Kinetic Glow (Red Accent):** Key active elements (such as running countdown timers, recording indicators, and selected workouts) use a dual-tier crimson aura:
  - Inner core: `box-shadow: 0 0 16px rgba(217, 30, 42, 0.45)`
  - Outer ambient: `box-shadow: 0 0 40px rgba(255, 51, 68, 0.20)`
- **Glassmorphic Navigation Bar:** Floating dock utilizes `rgba(18, 18, 18, 0.85)` background with a `backdrop-filter: blur(20px)` and a top border of `1px solid rgba(255, 255, 255, 0.1)`.

## Shapes

The geometric identity balances organic biomechanics with precision engineering through generous, aerodynamic curves:

- **Base Corner Radius:** Standard interactive items (inputs, list items, small alerts) use `rounded-lg` (16px / 1rem).
- **Cards & Hero Modules:** Content cards, media containers, and modal sheets adopt modern `rounded-2xl` (20px) to `rounded-3xl` (24px) corners, echoing ergonomic gym hardware.
- **Pills & Circular Triggers:** Category chips, status indicators, checklist circles, play/pause controls, and primary action buttons utilize full pill curvature (`rounded-full` / 9999px) to invite direct physical interaction.
- **Border Treatments:** Hairline 1px borders encase each rounded geometry to preserve edge contrast between stacked `#141414` and `#0A0A0A` dark surfaces.

## Components

### Buttons & CTAs
- **Primary Brand Button:** Full-width or auto pill shape with a linear gradient from `#FF3344` (top-left) to `#D91E2A` (bottom-right). White bold text in `Montserrat` uppercase. Displays an ambient red glow on hover or active states.
- **Secondary / Ghost Button:** Transparent background with an outer border of `rgba(255, 255, 255, 0.15)`, transitioning to `#D1D5DB` text.
- **Circular Media Controls:** Dedicated round controls for workout timers and audio cues. Play/pause button uses the primary red gradient; previous/next buttons use muted dark circle fills (`#1A1A1A`) with silver icons.

### Exercise Cards & Series Checklist
- **Workout Card:** `#141414` base, `rounded-2xl`, with integrated 16:9 thumbnail, dynamic category badge, duration chip, and directional chevron (`#8E8E93`). Highlighted state wraps the card in a 1px `#D91E2A` border with red drop aura.
- **Checklist Series Row:** Compact horizontal item (`#1A1A1A`) featuring a custom rounded-md checkbox. Unchecked state: empty dark square with `rgba(255, 255, 255, 0.2)` border. Checked state: solid `#D91E2A` background containing a sharp white checkmark icon, with the text switching from `#FFFFFF` to muted `#8E8E93`.

### Badges, Pills & Tabs
- **Filter Pills:** Segmented tabs (e.g., "Todos", "Força", "HIIT", "Mobilidade"). Active pill uses solid `#D91E2A` with white bold text; inactive pills use `#1A1A1A` with `#8E8E93` text and hover brightness.
- **Biometric Badges:** Small upper-right tags indicating exercise difficulty or muscle group with dark translucent red tint (`rgba(217, 30, 42, 0.15)`) and `#FF3344` border.

### Input Fields & Chat Surface
- **Text Inputs:** `#1A1A1A` surface with `1px solid rgba(255, 255, 255, 0.08)`, `rounded-full` or `rounded-xl`, populated by `#FFFFFF` input text and `#8E8E93` placeholder. Focus state illuminates the border with `#D91E2A`.
- **Chat Bubbles (AI & Coach):**
  - Coach / System AI: Left-aligned, `#1E1E1E` surface with light silver text (`#D1D5DB`) and micro avatar.
  - User Response: Right-aligned, `#2A2A2A` surface or deep crimson wash with white text.

### Navigation Dock
- **Mobile Bottom Bar:** Fixed translucent dock (`#121212` with 85% opacity and blur). 5-tab layout: Início, Treino, Treinador (IA), Plano, Perfil. Active tab renders an illuminated red icon with a subtle glow dot underneath; inactive tabs render in `#8E8E93`.