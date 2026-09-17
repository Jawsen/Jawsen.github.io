# Thesis companion site

Visual companion to **Spatio-Temporal and Network Analysis of Gun Violence in Chicago: Background Risk and Near-Repeat Spillover**.

## Add a visualization

1. Put a `.png`, `.jpg`, or self-contained `.html` file in `assets/visualizations/`.
2. Open `assets/data/visualizations.json` and copy an existing object.
3. For an image, use `"type":"image"` and `"src":"assets/visualizations/chart.png"`.
4. For an interactive chart, use `"type":"iframe"` and `"src":"assets/visualizations/chart.html"`.

Categories are `temporal`, `spatial`, `category`, and `comparison`. Add `"size":"wide"` for a double-width card. Keep the JSON valid: separate objects with commas, with no comma after the last object.

```json
{
  "title": "Monthly event counts",
  "kicker": "EDA · Time",
  "category": "temporal",
  "format": "Interactive",
  "type": "iframe",
  "src": "assets/visualizations/monthly-events.html",
  "alt": "Monthly event counts by offence category",
  "size": "wide",
  "description": "Monthly firearm-involved events from 2015 through 2024."
}
```

The older survey pages and legacy assets remain available, but are not linked from the new thesis homepage.
