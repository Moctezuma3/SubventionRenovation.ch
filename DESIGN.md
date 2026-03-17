# DESIGN.md — SubventionRénovation.ch

## 1. Brand Identity
- **Name**: SubventionRénovation.ch
- **Tagline**: Les aides financières pour votre rénovation énergétique
- **Tone**: Trustworthy, governmental, simple, ecological, serious

## 2. Color System

| Token           | Value     | Usage                             |
|-----------------|-----------|-----------------------------------|
| `--color-bg`    | #0B0B0B   | Page background (premium black)   |
| `--color-green` | #2ECC71   | CTAs, highlights, badges, accents |
| `--color-white` | #FFFFFF   | Body text, cards background       |
| `--color-card`  | #141414   | Dark card backgrounds             |
| `--color-border`| #1E1E1E   | Subtle borders                    |
| `--color-muted` | #888888   | Secondary / muted text            |
| `--color-light-bg` | #F5F7F4 | Light section backgrounds        |

## 3. Typography

- **Font Stack**: `'Inter', 'Manrope', system-ui, sans-serif`
- **H1**: 56px / Bold 700 / line-height 1.1
- **H2**: 36px / Bold 700 / line-height 1.2
- **H3**: 22px / SemiBold 600
- **Body**: 16px / Regular 400 / line-height 1.6
- **Small**: 13px / Regular 400
- **CTA / Button**: 16px / SemiBold 600

## 4. Component Tokens

- **Border Radius**: 12px (cards), 8px (buttons), 4px (badges)
- **Shadow (card)**: `0 4px 24px rgba(0,0,0,0.15)`
- **Shadow (elevated)**: `0 8px 40px rgba(0,0,0,0.25)`
- **Transition**: `all 0.25s ease`
- **Max Width**: 1200px
- **Section Padding**: 100px 0

## 5. Button Styles

- **Primary**: bg `#2ECC71`, text `#0B0B0B`, bold, border-radius 8px, padding 14px 28px
- **Secondary**: bg transparent, border 2px `#2ECC71`, text `#2ECC71`
- **Hover**: brightness(1.1), translateY(-1px), shadow

## 6. Design System Notes for Stitch Generation

**DESIGN SYSTEM (REQUIRED):**
Colors: Dark theme (#0B0B0B background), ecological green (#2ECC71) for CTAs and accents, pure white (#FFFFFF) for text and card content. Clean, minimal layout.
Typography: Inter or Manrope, large bold headlines, generous white space.
Components: Rounded cards (12px radius), green CTA buttons, progress bars in green, smooth transitions.
Vibe: Trustworthy Swiss governmental portal meets modern SaaS landing page. Clean, professional, conversion-optimized.
