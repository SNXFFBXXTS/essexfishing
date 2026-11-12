# Shoebury Fishing Guide 🎣

A live, phone-friendly fishing guide for Shoebury East Beach (Thames Estuary).
Open the GitHub Pages link on your phone and use "Add to Home screen".

**https://snxffbxxts.github.io/essexfishing/**

## What it does
Use the **time bar** at the top to pick any day and hour up to about 7 days ahead
(◀ ▶ step an hour, tap the time to choose a day or slide the hour, and **Live**
jumps back to now). Every tab then shows that moment.

- **🌊 Now:** a fishing rating with reasons, plus tide, wind, sky, pressure,
  sea, light and moon
- **🌙 Tides:** tide stage, springs or neaps, the next 8 tide times, and a height chart
- **🌬️ Weather:** detailed weather and sea, plus an hour-by-hour rating for the next 12 hours
- **⏰ Best times:** a 24-hour rating chart, and a week planner with the best window
  for each day (tap a day to jump there)
- **🎣 My catch / 🧰 Tackle:** pick a rig, hook size, bait, casting distance and lead. It
  shows what you're likely to catch with that setup right now, what's holding
  each species back (for example "hook too small, use 2/0–4/0"), and the best
  time in the next 24 hours to fish that setup.
- **⭐ Recommended:** it tries every combination of tackle against the live
  conditions and recommends the setup for the most bites and the one for a bigger
  fish, plus the best setup for each fish that's in season. Tap "Use this
  setup" to load it.
- **🐟 Species:** a guide to each Shoebury species: season, baits, hooks, rigs,
  where, when and water temperature.

## Live data
- Environment Agency Southend tide gauge, the observed level every 15 minutes
- Open-Meteo marine: tide curve, waves and sea temperature. The game lines the
  curve up against the gauge to get the next high and low waters.
- Open-Meteo forecast: current and hourly wind, gusts, pressure, cloud and rain
- If a feed fails, it falls back to saved data, then to a moon-based tide model

## Roadmap
- [x] v0.1–0.2: live conditions engine (started out as a game)
- [x] v0.3: switched to a guide app, with setup selection, catch predictions,
  recommendations and a species guide
- [ ] More tackle: bait cocktails (lug + squid), clipped-down rigs, bead and spoon attractors
- [ ] More marks: Southend Pier, Thorpe Bay, Canvey and so on, each with its own
  species, distances and snags
- [ ] Your own catch diary, to log real catches against the conditions on the day
- [x] v0.4: bigger text and more tabs; time bar to wind forward to any day or hour; week planner
- [ ] Offline install (PWA)

## Run locally
It's a single `index.html` file. Open it in any browser.
