# Knot — Living Memories Landing Page

> *"To transform silent family archives into living legacies, ensuring every photo preserves the voice, story, and emotion behind it."*

This is the **fake front door** / validation landing page for **Knot** — a tablet-based iPad app that uses Generative AI to animate family photos with voice narratives.

## What is Knot?

Knot addresses **Context Decay** — the inevitable loss of family history where stories, voices, and emotions behind photographs fade away once the storyteller is gone.

Using a proprietary **Re-Live Engine**, Knot synthesizes user-recorded voice narratives with static imagery, animating archival photos with subtle, emotionally congruent movements.

## Purpose of This Page

This is a **Fake Front Door** — a UX research method to validate the core assumption:

> **"Will people want this application?"**

The page measures:
- Scroll depth (do visitors engage with the content?)
- Waitlist sign-ups (are they willing to commit their email?)
- Prototype clicks (are they curious enough to explore?)

## How to Deploy

### Option 1: GitHub Pages (Free, Instant)
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to **main branch / root**
4. Your site will be live at `https://yourusername.github.io/knot-landing`

### Option 2: Netlify (Drag & Drop)
1. Go to [netlify.com](https://netlify.com)
2. Drag the `index.html` file onto the deploy zone
3. Live in 30 seconds

### Option 3: Vercel
```bash
npm i -g vercel
vercel --prod
```

## Tracking Waitlist Signups

To capture real email signups, replace the `handleWaitlist()` function with a form service:

### Using Formspree (Free)
1. Sign up at [formspree.io](https://formspree.io)
2. Create a new form, get your endpoint URL
3. Replace the form in `index.html`:

```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
  <input class="wl-input" type="email" name="email" placeholder="Enter your email address" required />
  <button class="wl-btn" type="submit">Reserve My Spot →</button>
</form>
```

### Using Mailchimp / ConvertKit
Embed their signup form JavaScript instead of the current form.

## Design System

| Token | Value |
|-------|-------|
| Primary | `#FF7A11` (Orange) |
| Background | `#FFF8F1` (Cream) |
| Dark | `#181D27` |
| Accent Blue | `#0088FF` |
| Highlight | `#FDD0A3` |
| Header Font | Merriweather (Google Fonts) |
| Body Font | DM Sans (Google Fonts) |

## Project Info

- **Designed by:** Aditya
- **Year:** 2026
- **Type:** Thesis Project — UX/Product Design
- **Prototype:** [View on Figma](https://www.figma.com/proto/yrThFyUEXJv7FHAHDT88Zq/Thesis?node-id=247-757)
- **Target Platform:** iPad (tablet-first)

## Validation Metrics to Track

| Metric | Target | What It Means |
|--------|--------|---------------|
| Waitlist signups | >20 in first week | Real demand exists |
| Prototype link clicks | >30% of visitors | Curiosity is high |
| Time on page | >60 seconds | Message resonates |
| Return visits | >10% | Strong emotional hook |
