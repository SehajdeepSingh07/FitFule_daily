# FitFuel Daily V3 — Real Static Product Build

FitFuel Daily V3 is a local-first static gym and wellness operating system built only with HTML, CSS and JavaScript. There is no backend, database server, login service or API requirement.

## Included product areas

- Dashboard / physiological readiness / priority actions / chrono-log
- Nutrition & Macro Command
- 70+ reference foods with automatic macro calculations
- Meal builder, copy-yesterday, water logging, CSV export
- Workouts / live session / set logging / RPE / e1RM / volume / rest timer / workout history
- Exercise Library with search, muscle, equipment and difficulty filters
- Progress: weight, waist, chest, arm, thigh, body fat and strength trends
- Recovery: sleep, sleep quality, stress, soreness and readiness estimate
- Planner: Monday–Sunday split, meal-prep focus and recovery blocks
- Reports: daily/weekly snapshot, print report, JSON backup/restore, CSV exports
- Settings: profile, goals, target vectors, theme, automation toggles and local data controls
- Voice quick add when the browser provides SpeechRecognition
- LocalStorage persistence; all data stays in the browser

## Run

For development, use any simple static server. Example:

```bash
python -m http.server 5500
```

Open `http://localhost:5500` and use `index.html`.

## Design basis

The UI follows the supplied FitFuel screenshots and Kinetic Obsidian design system: deep slate/charcoal surfaces, athletic emerald and electric lime accents, Plus Jakarta Sans + Inter hierarchy, dense telemetry cards, glass header, command sidebar, rounded analytical modules and high-throughput workout controls.

## Static-site limitation

A static build cannot provide true account sync, wearable ingestion, server notifications or remote backups without a backend. V3 therefore implements those workflows locally where browser capabilities allow and keeps the interface honest about what is local/demo data.

## Data

The built-in nutrition and exercise values are reference estimates for wellness tracking. They are not medical advice.
