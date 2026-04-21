# 🥘 IngredientIQ

**Cook something delicious with what you already have.**

IngredientIQ is a single-page AI-powered web app that takes whatever ingredients you have in your fridge and generates real, cookable recipes — with full instructions, ingredient lists, and cooking tips.

👉 **[Live Demo](https://your-username.github.io/ingredientiq/)**

---

## What it does

- You type in your available ingredients (e.g. *"eggs, leftover rice, soy sauce, spring onions"*)
- Claude AI matches them to 3 real recipes you can cook **right now**
- Each recipe shows full step-by-step instructions, time, difficulty, and which items you might be missing
- Filter by dietary preference: vegetarian, vegan, gluten-free, quick meals, comfort food
- Works instantly in the browser — no signup, no backend, no data stored

---

## Tech stack

- Pure HTML + CSS + Vanilla JS — zero frameworks, zero dependencies
- [Anthropic Claude API](https://docs.anthropic.com) (`claude-sonnet-4-20250514`)
- Deployable to GitHub Pages with a single file

---

## Getting started

### Run locally

Just open `index.html` in your browser. The app calls the Anthropic API directly from the browser.

> **Note:** You'll need an Anthropic API key. The key is injected via the Claude.ai artifact environment. For your own deployment, add your API key to the fetch headers in the script.

### Deploy to GitHub Pages

1. Fork or clone this repo
2. Go to **Settings → Pages → Source → main branch / root**
3. Your site will be live at `https://your-username.github.io/ingredientiq/`

---

## Project structure

```
ingredientiq/
├── index.html      # Entire app — UI, logic, AI call
├── GRANDMA.md      # Plain English explanation (no jargon!)
└── README.md       # This file
```

---

## Why this exists

Most recipe apps make you search for a dish name. This works backwards — start with **what you have**, and get the dish. Helps reduce food waste and answers the eternal question: *"what do I cook tonight?"*

---

## Honest notes

- The AI sometimes gets creative. Double-check ingredient quantities before cooking.
- Recipes are generated dynamically — they vary each time.
- No data is stored. Ever.

---

> For a jargon-free explanation of this project, read [GRANDMA.md](./GRANDMA.md) 👵
