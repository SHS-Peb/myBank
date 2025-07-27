# MyBank – Multi-Page Mobile Banking App

Welcome to **MyBank**, a fictional mobile-first banking application built using HTML and CSS. This project is part of the _Learn HTML & CSS_ curriculum and focuses on building a real-world, multi-page site while applying accessibility best practices.

---

## About This Project

Unlike the single-page Portfolio project, **MyBank** includes **seven separate HTML pages** and demonstrates how to structure a real-world app with multiple screens and meaningful navigation. The project is designed to simulate a digital banking experience with an emphasis on:

- Data and action-driven content
- Semantic HTML
- Accessible design

> Accessibility is essential — if users can't access their banking interface, they can't access their money.

---

## Pages

This project includes the following HTML pages:

- `landing.html` – Introduction to the app
- `onboarding.html` – Get started guide
- `signin.html` – Login screen
- `dashboard.html` – Main account view
- `services.html` – Overview of bank services
- `transactions.html` – View transaction history
- `profile.html` – Account management

---

## Accessibility Notes

Accessibility is a core focus of this project. Key principles include:

- Semantic HTML elements: `<nav>`, `<main>`, `<section>`, `<button>`, etc.
- Clear button vs link distinction (`<button>` for actions, `<a>` for navigation)
- Good color contrast and focus states
- Keyboard navigability
- Screen reader-friendly structure

---

## Design Reference

The UI was based on a design provided via Figma. Some modifications were made during development, so the final version may not exactly match the original.

- Mobile-only layout
- Light theme
- Compact UI focused on numbers and actions, not text-heavy content

---

## Getting Started (Optional Vite Setup)

You can use [Vite](https://vitejs.dev/) to serve your project locally:

```bash
npm create vite@latest mybank -- --template vanilla
cd mybank
npm install
npm run dev
