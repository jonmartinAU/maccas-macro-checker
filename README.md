# McDonald's Australia Nutrition Calculator

A comprehensive, self-contained nutrition calculator for McDonald's Australia menu items.

## Files

- `aus-nutrition-calculator.html` - Main nutrition calculator (self-contained, January 2026 data)
- `index.html` - Legacy macro checker (older version)
- `Aus Core Food Menu_January 2026.pdf` - Official nutrition data source

## Features

- **80+ Menu Items** - Complete nutrition data across all categories:
  - Beef (Big Mac, Quarter Pounder, Big Arch, etc.)
  - Chicken & Fish (McNuggets, McCrispy, McWings, Filet-O-Fish, etc.)
  - Wraps (Classic Chicken McWrap, Spicy Chicken McWrap, Snack Wrap)
  - Fries (Small, Medium, Large)
  - Breakfast (McMuffins, McGriddles, Hash Browns, Hotcakes, etc.)
  - Condiments (BBQ Sauce, Sweet & Sour, Ranch, Aioli, etc.)
  - Fruit (Apple Slices)

- **Interactive Filtering**
  - Search by product name
  - Filter by category
  - Toggle between per-serving and per-100g nutrition views

- **Complete Nutrition Data**
  - Energy (kJ and Cal)
  - Macronutrients (Protein, Carbs, Fat)
  - Saturated Fat
  - Sugars
  - Sodium
  - Serving sizes

- **Responsive Design**
  - Desktop (4-column grid)
  - Tablet (3-column grid)
  - Mobile (1-2 column grid)
  - McDonald's Australia brand colors and styling

## Tech Stack

- Vanilla HTML/CSS/JavaScript
- No build step required
- Google Fonts (Barlow) loaded from CDN
- **Deployment**: Vercel

## Usage

Simply open `aus-nutrition-calculator.html` in a web browser. No server, dependencies, or build process required.

The calculator stores your view preference (per-serving vs per-100g) in localStorage for convenience.

## Development

```bash
# Open the calculator locally
open aus-nutrition-calculator.html
```

## Deployment

Deploy to Vercel:
```bash
vercel --prod --yes
```

The single HTML file will be served as a static site.

## Data Accuracy

All nutrition information is extracted from the official **McDonald's Australia Main Food Menu - January 2026** (Revision 113).

The data represents standard product formulations and serving sizes. Actual values may vary due to:
- Individual preparation
- Product assembly variations
- Supplier and regional differences
- Seasonal variations

For allergen information and dietary concerns, visit [mcdonalds.com.au](https://mcdonalds.com.au/our-impact/food-quality-sourcing/nutrition)

## Browser Compatibility

Works in all modern browsers:
- Chrome (latest)
- Safari (latest)
- Firefox (latest)
- Edge (latest)
