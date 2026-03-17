---
page: merci
---
A thank-you / confirmation page shown after the eligibility simulator form is submitted.

**Context:** The user just completed the 4-step subsidy simulator on SubventionRénovation.ch and submitted their contact details. This page confirms their request was received and sets expectations.

**DESIGN SYSTEM (REQUIRED):**
Colors: Dark theme (#0B0B0B background), ecological green (#2ECC71) for CTAs and accents, pure white (#FFFFFF) for text and card content.
Typography: DM Sans (Google Fonts), large bold headlines, generous white space.
Components: Rounded cards (12px radius), green CTA buttons, smooth transitions.
Vibe: Trustworthy Swiss governmental portal meets modern SaaS. Clean, professional, conversion-optimized.

**Page Structure:**
1. Navbar (same as index.html — logo + links)
2. Hero confirmation area:
   - Large animated checkmark (SVG, green)
   - H1: "Votre simulation est confirmée !"
   - Subtitle: "Un expert vous contactera dans les 24 heures avec votre estimation détaillée."
   - Summary card: show back the selected canton, project type, and estimated subsidy amount
3. What happens next — 3-step timeline:
   - Step 1: "Analyse de votre dossier" (within 2h)
   - Step 2: "Contact par un expert" (within 24h)
   - Step 3: "Accompagnement personnalisé" (ongoing)
4. Appointment CTA section:
   - "Vous souhaitez aller plus vite ?"
   - Calendly-style mock booking widget (3 time slots displayed as cards)
5. Footer (same as index.html)
