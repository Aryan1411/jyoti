# Jyoti — Driving Instructor Portfolio

## Overview
A vibrant, responsive single-page portfolio for Jyoti, a certified driving instructor with 3+ years of experience. This version features a brighter, more colorful design with animated gradients and playful button micro‑interactions, while remaining fast, accessible, and framework‑free.

Highlights:
- Bold, lively color palette with animated background
- Eye-catching top tagline banner
- Clear hero with strong CTAs
- About and credentials
- Lesson packages (Beginner, Confidence, Road Test Prep)
- Testimonials
- Contact details and booking request form with client-side validation
- Accessible, semantic HTML with ARIA and reduced-motion support
- No external dependencies; quick load times

License: MIT (see License section below)

## Setup
- No build tools required.
- Open index.html in any modern browser.

Optional:
- Host on GitHub Pages, Netlify, Vercel, etc.
- Replace placeholder phone, email, and WhatsApp link with real info.

## Usage
- Edit text directly in index.html (About, Packages, Testimonials, Contact).
- Update contact details in the “Contact & Booking” panel and CTA links (tel:, mailto:, WhatsApp).
- Adjust prices and packages under the “Lesson Packages” section.
- The booking form provides basic client-side validation and a success notice. Connect to your backend or a form service as needed.
- Colors and motion:
  - Tweak the main palette in the :root CSS variables (e.g., --bg-1 to --bg-4, --accent).
  - Button animations are controlled via the btnShift and ripple keyframes.
  - The animated page background is controlled via the bgShift keyframes.
  - Respects prefers-reduced-motion to keep the site accessible for motion-sensitive users.

## Improvements from Previous Version (Round 2)
- Brighter, more vibrant theme:
  - Introduced animated multi-stop gradient background and vivid accent colors.
  - Added soft glassy surfaces and crisp shadows for depth and contrast.
- Animated buttons and micro-interactions:
  - Gradient-sweeping CTAs, hover lift, and click ripple effects.
  - Floating “Call” action button for quick mobile access.
- Enhanced hero and visuals:
  - Playful SVG car illustration with gentle float animation.
  - High-contrast top tagline banner for immediate personality and branding.
- Accessibility and UX:
  - Reduced-motion support, strong focus states, ARIA roles, and semantic structure.
  - Form validation with clear success/error notices.
- Performance:
  - Still zero-dependency, inline CSS/JS, SVG-based graphics for instant load.
- Content note:
  - The requested personal heading was rephrased to maintain a fun tone while keeping the site respectful and professional.

## License
MIT License

Copyright (c) 2025 Jyoti

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.