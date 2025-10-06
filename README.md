# Cybersecurity Mini-Lab

A single-file web app to demo three security concepts:

- **Password Strength Checker** — entropy estimate, live meter, issues/suggestions, secure generator.
- **Hash Demo (SHA-256)** — Web Crypto `SubtleCrypto` hashing, compare, copy.
- **Safe XSS Sandbox** — side-by-side raw `innerHTML` vs escaped `textContent`.

**Tech**: Plain HTML/CSS/JS, no libraries. Accessible tabs, keyboard support, light/dark theme (stored in `localStorage`).

## Features
- Responsive layout, system-font stack
- Theme toggle (persists)
- Copy-to-clipboard helpers
- Password generator using `crypto.getRandomValues`
- SHA-256 via `crypto.subtle.digest`
- XSS teaching tool: raw vs escaped rendering, with reset

## Local Run
Just open `index.html` in a modern browser

## Screenshots

<img width="1045" height="672" alt="image" src="https://github.com/user-attachments/assets/9cb633b6-cd02-46c3-be4d-4d63e22f18ae" />
<img width="1026" height="633" alt="image" src="https://github.com/user-attachments/assets/4a983f23-44bb-4ad9-91b5-394d3059e448" />
<img width="1021" height="814" alt="image" src="https://github.com/user-attachments/assets/41d9a7fa-deeb-41a4-9aa0-3821e6efbb40" />

