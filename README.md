# Przelewy24 Payments - Stripe Documentation Page

A static HTML/CSS implementation of the Stripe documentation page for Przelewy24 payments, built from a Figma design.

## Project Structure

```
przelewy24-docs/
├── index.html          # Main HTML page
├── css/
│   ├── styles.css      # Primary stylesheet (layout, components, typography)
│   └── icons.css       # Icon-specific styles and utility classes
├── assets/             # Directory for static assets (images, fonts)
└── README.md           # This file
```

## Sections

The page includes the following content sections matching the Figma design:

- **Header** - Stripe docs branding, search bar, navigation tabs, account selector
- **Left Sidebar** - Hierarchical navigation for Payment Methods, Interfaces, Scenarios
- **Overview** - Feature table with payment method properties
- **Eligibility and Availability** - Account eligibility, payment support tables with country flags
- **Capabilities** - Recurring payments, authorizations, captures, refunds, disputes
- **Stripe Support** - Products and APIs compatibility matrix
- **Payment Flow** - Step-by-step redirect flow with phone mockup
- **Get Started** - Integration quick start guide
- **Right Sidebar** - "On this page" anchor navigation

## How to View

Open `index.html` in any modern browser:

```bash
open index.html
```

## Design Tokens

Key colors used from the Stripe design system:

| Token                | Value     | Usage                    |
|----------------------|-----------|--------------------------|
| Text/Default         | `#353A44` | Primary text             |
| Text/Primary         | `#414552` | Section titles, nav labels |
| Text/Secondary       | `#687385` | Subtitles, descriptions  |
| Brand/Primary        | `#635BFF` | Links, active states     |
| Border/Default       | `#E3E8EE` | Table borders, dividers  |
| Background/Surface   | `#FFFFFF` | Page background          |
| Neutral/150          | `#D5DBE1` | Disabled icons, dividers |

## Browser Support

Tested with modern browsers (Chrome, Safari, Firefox, Edge). Uses standard CSS flexbox and sticky positioning.
