# Sixhearts Foundation Website

A website for Sixhearts Foundation, a registered non-profit that resells gently used donated items and directs the proceeds to a rotating charity. The site explains the mission, shows which causes are being supported, and walks people through how to donate.

**Live:** [sixheartsfoundation.com](https://sixheartsfoundation.com/)

## About the project

Sixhearts is a real non-profit run by Sharon Hoang. It started small — selling a few friends' unused things and giving the money to charity — and is scaling up, so it needed a proper web presence to explain how it works and point donors in the right direction. I designed and built the site and deployed it under the organization's own domain.

The scope is deliberately a static, information-first site: the goal is to clearly communicate the mission and the donation process, not to handle transactions. Selling happens over email and direct pickup, so the site's job is to inform and convert visitors into donors.

## What's on the site

It's a single page with anchor navigation between sections:

- **Hero** — the pitch ("declutter for a good cause") and the primary donate action.
- **Where the proceeds go** — the rotating cause model, showing a previous cause, the current one, and what's coming up next, plus a suggestion box for proposing future charities.
- **How donating works** — a four-step walkthrough: send photos, the foundation posts and sells the item, the donor chooses the share that goes to the cause, and the buyer arranges pickup.
- **Origin story** — how Sixhearts started and where it's headed (including working toward CRA charitable registration).
- **Donate / contact** — a closing call to action; all actions route to the foundation's email with prefilled subject lines.

## How it works

- Built with plain HTML, CSS, and JavaScript — no framework or build step, which keeps it simple to host and easy for the organization to maintain.
- Single-page layout with smooth in-page anchor navigation between sections.
- Calls to action use prefilled `mailto:` links (with subject lines) rather than a form backend, so donations can start over email with no server to run.
- Responsive layout so the site reads cleanly on desktop, tablet, and mobile.

## Deployment

- Hosted on **GitHub Pages**.
- Served from the organization's custom domain, **sixheartsfoundation.com**, configured via DNS.

## Built with

- HTML
- CSS
- JavaScript
- GitHub Pages
