# Orbit — Login Page

An original, responsive login page made with **HTML5 and CSS3 only**. No JavaScript, frameworks, downloads, or build step required.

## Preview

Open `index.html` in a modern browser. The page works offline.

## Features

- Username or email field and password field with native required-field validation.
- Login button with smooth hover and pressed states.
- Remember me checkbox, Forgot password link, and Create an account link.
- Midnight-blue and mint visual design with original CSS orbital geometry.
- Desktop split layout and compact mobile layout.
- Accessible labels, keyboard focus indicators, autocomplete hints, and reduced-motion support.
- CSS-only notices for login, password recovery, and account creation.

## Project files

```text
login-page-html-css/
├── index.html
├── style.css
├── assets/
│   └── favicon.svg
└── README.md
```

## Demo behavior

This is a front-end design assignment, not an authentication service. Login validates that both fields are filled and opens a demo notice. Input `name` attributes are deliberately omitted, so username and password values are not submitted in the URL. The page itself does not store credentials. Remember me toggles a checkbox only; persistent sessions, password recovery, and account creation require a secure backend. Browser-managed password saving is controlled by your browser.

## Publish on GitHub

1. Sign in to GitHub or create your own account.
2. Create a **public** repository named **login-page-html-css**.
3. Upload `index.html`, `style.css`, this README, and the `assets` folder to the repository root.
4. Verify that the repository is publicly accessible and submit its URL:
   `https://github.com/YOUR-USERNAME/login-page-html-css`.

Optional: In repository **Settings → Pages**, deploy from the `main` branch and `/ (root)` folder to get a live preview.

## Manual checks

- Open at desktop and mobile widths; check for horizontal scrolling and clipped content.
- Try submitting with empty fields: the browser should request the missing values.
- Fill both fields and submit: the demo notice should appear without credentials in the URL.
- Toggle Remember me and open both supporting links.
- Navigate with Tab and verify clear focus states.
- Hover over Log in and check its smooth lift effect.

Make the design your own and ensure your submission follows your course's rules about outside assistance.
