# AI Defense Lab

An interactive AI security lab inspired by Prisma AIRS, featuring animated attack simulations, configurable defenses, and side-by-side outcomes for prompt injection, sensitive data exposure, and AI agent risks.

Created by [Mariyam Maahin](https://www.linkedin.com/in/mariyam-maahin-b436a3223/).

## Explore the lab

- Three missions: a poisoned support document, a synthetic credential in a reply, and an agent attempting an unnecessary external export.
- Animated attack and defense flows with pause, replay, speed controls, presentation view, and clickable evidence.
- Configurable illustrative controls for injection, sensitive data, tools, and approvals.
- A twelve-case policy bench with downloadable simulated results.
- Original cybersecurity incident scenarios in `incident-lab.html`.

## Simulation boundary

This is an independent educational prototype, not an official Palo Alto Networks product or product interface. It does not call an AI model, Prisma AIRS, or external tools. All incidents, credentials, records, outputs, and security verdicts are synthetic and deterministic. The demo controls do not reproduce Prisma AIRS detection logic or configuration. External example destinations use `.invalid` and are not contacted.

Palo Alto Networks and Prisma AIRS names and logo assets belong to Palo Alto Networks. See `ASSET_SOURCES.md` for asset provenance.

## Run locally

Open `index.html` in a modern browser. The site is plain HTML, CSS, JavaScript, and SVG, with no build step or API keys. Policy preferences and personal bests are stored in the browser.

## Publish with GitHub Pages

In repository Settings → Pages, select **Deploy from a branch**, choose **main** and **/(root)**, then Save. After GitHub finishes publishing, open the URL displayed in Pages settings.

## Project structure

- `index.html`: page structure and creator footer
- `style.css`: responsive design and animation styles
- `app.js`: scenario data, deterministic policy logic, and interactive visualizations
- `assets/`: official brand assets
- `incident-lab.html`: original incident-response scenario lab
