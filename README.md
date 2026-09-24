# goit-markup-hw-05

Homework assignment #5 from the [GoIT](https://goit.global/) HTML/CSS markup course. Building on homework #4, this task adds a footer newsletter subscription form and a "call back" modal dialog to the "Webstudio" landing page.

## 📋 About

The page is a styled business landing for a fictional web studio. Compared to the previous homework, this version adds:

- A **footer subscribe form** with an email input and a "Subscribe" button (with a send icon).
- A **modal dialog** ("Leave your contacts and we will call you back") triggered by the hero section's "Order Service" button (`data-modal-open` / `data-modal` / `data-modal-close` attributes are in place for wiring up JS later). The modal form includes:
  - Name, phone, and email inputs with icons.
  - A comment textarea.
  - A custom-styled "accept the Privacy Policy" checkbox.
  - A submit ("Send") button.
- Additional SVG icons (send, person, phone, email, checked, close) used by the new forms and modal.

The page itself still includes:

- A header with a logo, main navigation (Studio / Portfolio / Contacts), and contact links (email and phone).
- A hero section with a heading and an "Order Service" button that opens the modal.
- An "Our Features" section listing four company strengths, each with an icon.
- An "Our Team" section presenting four team members with photos, names, roles, and social links.
- An "Our Portfolio" section showcasing six sample projects with images, overlay descriptions, titles, and categories.
- A footer with the logo, a tagline, social media links, and the newsletter subscribe form.

> Note: this homework focuses on markup and styling only — the modal's open/close behavior is not yet wired up with JavaScript (no `.js` files are included).

## 🛠️ Tech Stack

- HTML5 (semantic elements: `header`, `nav`, `main`, `section`, `address`, `footer`)
- CSS3 (custom styles in `css/styles.css`)
- SVG sprite (`images/icons.svg`) for scalable icons
- [modern-normalize](https://github.com/sindresorhus/modern-normalize) (via CDN) for CSS resets
- Google Fonts (Raleway, Roboto)

## 📁 Project Structure

```
goit-markup-hw-05-main/
├── css/
│   └── styles.css       # Page styles, including modal and form styling
├── images/
│   ├── icons.svg          # SVG icon sprite (features, social links, form icons)
│   ├── people-office.jpg   # Hero section background image
│   ├── team1.jpg – team4.jpg     # Team member photos
│   └── Banking.jpg, Cashless.jpg, ...  # Portfolio project images
└── index.html                 # Page markup
```

## 🚀 Getting Started

No build step or server required — just open `index.html` in a browser (an internet connection is needed to load the Google Fonts and the normalize.css CDN link).
