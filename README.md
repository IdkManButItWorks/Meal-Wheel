# PlateO

A single-file meal planner that builds plates from a protein + vegetable + carb, so meals stay flexible instead of following a fixed menu.

## Features

- **Diet filter** — Everything, Pescatarian, Vegetarian, or Vegan; filters every suggestion, shuffle, and shopping item (remembered between visits).
- **Budget tiers** — $ Thrifty, $$ Moderate, or $$$ Splurge; filters ingredients, shuffles, and shopping items by estimated cost per serving, shows ≈ cost per plate/day, and estimates the shopping list total (remembered between visits).
- **Meal-specific building blocks** — separate ingredient lists for breakfast, lunch, and dinner.
- **Highlight or exclude ingredients** — the building blocks panel starts collapsed (its header shows how many items are highlighted or excluded); open it and tap a chip once to highlight it (shuffles can draw only from highlighted items), twice to exclude it from every shuffle, and a third time to reset.
- **Shuffle** — one block with three modes: *One meal* (a single plate for the chosen meal), *Whole day* (breakfast, lunch and dinner), and *Meal prep* (three plates of the same meal for batch cooking). The mode is remembered between visits.
- **Recipe search** — opens a prefilled Google search built from the combo, meal, and diet.
- **Shopping list** — grouped checklist that hides items that don't fit your diet.
- **Print shopping list** — prints a clean, two-column checklist of the checked items (grouped, with tick boxes and estimated prices); use "Save as PDF" to share it from a phone.
- **Installable** — includes an icon and a generated web-app manifest, so it can be added to a phone home screen.

## Running it

Open `index.html` in any browser. There is no build step and no dependencies beyond Google Fonts.

## Project layout

```
index.html   the whole app (HTML, CSS, JS in one file)
README.md
```

## Roadmap

- Package as an Android app
- Calorie / macronutrient tracking
