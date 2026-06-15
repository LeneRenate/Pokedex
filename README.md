# PokéDex 1.0

A static, browser-based Pokédex built with plain HTML and CSS — all 151 Generation I Pokémon, no JavaScript, no API.

## Background

The Pokédex is my go-to project whenever I pick up something new. Building the same familiar product lets me focus on the technology rather than the problem domain — so the differences between versions reflect what I've actually learned.

**v1.0** _(this repo)_ — Static markup written with Emmet, locally saved images, Gen I Pokémon only. No JavaScript, no API.

**v2.0** — Rebuilt with vanilla JavaScript ES Modules. Pulls live data from PokéAPI, covers all 1025 Pokémon across 9 generations, and adds filtering, a detail modal, and a loading screen.

**v3.0 — React** — Rebuilt with React, Vite, and Tailwind CSS. Component-based architecture, client-side routing via React Router, and a dedicated detail page per Pokémon.

**v4.0 — Next.js** is in progress.

> See the [full series](#the-pokedex-series) below.

## Features

- **All 151 Gen I Pokémon** — Every card shows the official artwork, Pokédex number, and name, with locally saved images.
- **Type-based color styling** — Each card is styled according to its type(s) using CSS custom properties — 17 types covered, each with a distinct color and border.
- **Type filter list** — A styled list of all 17 types is displayed at the top of the page.
- **Evolutionary lines grouped** — Pokémon are laid out in sections by evolutionary family, keeping related Pokémon visually together.
- **No JavaScript, no dependencies** — Entirely static; opens directly in any browser with no build step.

## Tech Stack

- HTML (written with Emmet)
- CSS (custom properties for all type colors, flexbox layout)
- Locally saved PNG images (250px sprites from the Pokémon wiki)

## Project Structure

```
├── index.html          # All markup — header, type list, and all 151 Pokémon cards
├── Pokedex.css         # All styles — layout, type colors, card styling
└── ImagesPokemon/
    ├── pokedex.png         # Header image
    ├── PokedexPattern.png  # Header background pattern
    └── 250px-####Name.png  # Sprite for each of the 151 Gen I Pokémon
```

## Getting Started

No build step or dependencies required. Just open `index.html` in a browser.

---

## The PokéDex Series

| Version                             | Stack                     | Highlights                                               |
| ----------------------------------- | ------------------------- | -------------------------------------------------------- |
| **v1.0 — HTML & CSS** _(this repo)_ | HTML, CSS (Emmet)         | Static, local images, Gen I only                         |
| v2.0 — Vanilla JS                   | HTML, CSS, JS ES Modules  | PokéAPI, all 1025 Pokémon, filtering, modal              |
| v3.0 — React                        | React, Vite, Tailwind CSS | Component architecture, client-side routing, detail page |
| v4.0 — Next.js                      | Next.js                   | _(in progress)_                                          |
