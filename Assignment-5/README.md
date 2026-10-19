# Nadan — Kerala food from God’s Own Country.

A responsive Kerala-inspired recipe finder built with React, React Router, and Axios. Browse original Kerala recipe adaptations with ingredients and step-by-step methods, search the local collection, fall back to Indian dishes from TheMealDB, and keep favourites saved between visits.

## Getting started

```sh
npm install
npm run dev
```

## Features

- Home, Recipes, Recipe Detail, and Favourites routes with active navigation.
- A built-in collection of Kerala recipes with ingredient lists, cooking steps, and controlled search.
- Kerala food photos are sourced from Wikimedia Commons; image credits and Creative Commons license links appear with each photo.
- Indian recipe search fallback backed by the public [TheMealDB API](https://www.themealdb.com/api.php).
- Loading, error, and no-results states for API requests.
- Recipe detail pages with ingredients, measurements, instructions, and an optional video link.
- A favourites list shared across routes and persisted in browser local storage.

## Checks

```sh
npm run lint
npm run build
```
