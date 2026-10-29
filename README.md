# EcoSort AI — Smart Waste Recognition and Recycling Assistant

A mobile-first web prototype for the EcoSort AI concept prepared for FundDev International Competition 2026.

## Current status

This repository contains a **front-end interaction prototype**, not a production AI classifier. The user can select an image, choose a demo category, and view category-specific sorting guidance. The category is selected manually to demonstrate the planned flow. The prototype does not upload images to a server.

## Features

- Responsive landing page for desktop and mobile
- Image picker and local image preview
- Simulated category result for plastic, paper/cardboard, metal, and organic waste
- Basic sorting guidance for each category
- Overview of the proposed workflow and SDG alignment
- Transparent notice that the prediction is simulated

## Run locally

No build tools are required.

1. Download or clone this repository.
2. Open `index.html` in a modern browser.

For a local web server, run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy to GitHub Pages

1. Create a new repository on GitHub, for example `ecosort-ai`.
2. Upload `index.html`, `style.css`, `app.js`, and this README to the repository root.
3. Open **Settings → Pages**.
4. Under Build and deployment, select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
5. Wait for GitHub Pages to publish the site and copy the generated URL into the competition form.

GitHub Pages deployment availability and settings can change; follow the current GitHub instructions if the menu differs.

## Suggested next development steps

1. Build a properly labeled dataset and document its source and license.
2. Train and evaluate a real image classification model.
3. Add confidence calibration and a fallback when the model is uncertain.
4. Verify recycling collection point information with local partners.
5. Conduct user testing and report real metrics (precision, recall, F1-score, confusion matrix, usability feedback).
6. Add privacy, accessibility, and local waste-handling guidance.

## Important for competition submission

Do not describe the current demo as a trained AI model. Replace simulated results only after the model is implemented and tested. Do not claim partnerships, accuracy, user numbers, or environmental impact without evidence.

## SDGs addressed

- SDG 11 — Sustainable Cities and Communities
- SDG 12 — Responsible Consumption and Production
- SDG 13 — Climate Action

## Project slogan

**Recognize Waste. Guide Action. Support a Circular Future.**
