# Unit Converter (Web)

A single-page unit converter. Pick a category, enter a value, and get the
converted result instantly — no internet needed, everything runs in the page.

## Categories

- **Length** — mm, cm, m, km, inch, foot, yard, mile
- **Weight** — g, kg, tonne, ounce, pound, stone
- **Temperature** — °C, °F, K (exact conversion formulas)
- **Area** — m², km², ft², yd², acre, hectare, **marla, kanal** (Pakistan land units)
- **Volume** — mL, L, m³, US gallon, pint, fluid ounce, cup
- **Speed** — km/h, m/s, mph, knots
- **Time** — second, minute, hour, day, week
- **Data** — B, KB, MB, GB, TB

Extras: a swap button (⇄), a live "1 unit = …" formula line, and one-click
common conversions (e.g. 1 km = 0.621 mi, 25 °C = 77 °F, 1 kanal = 20 marla).

## How to use

Open `index.html` in any modern browser (double-click the file, or serve the
folder with any static server). No build step, no dependencies.

## What was practiced

- Single self-contained HTML/CSS/JS page
- Conversion through a base unit (with special-case functions for temperature,
  which is not a simple ratio)
- DOM building (category tabs + unit dropdowns generated from one data table)
- Number formatting (precision + thousands separators, exponential for extremes)
