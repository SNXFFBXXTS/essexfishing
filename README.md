# Shoebury Fishing Guide 🎣

A live, phone-friendly fishing guide for Shoebury East Beach (Thames Estuary).
Open the GitHub Pages link on your phone and use "Add to Home screen".

**https://snxffbxxts.github.io/essexfishing/**

## What it does
- **🌊 Now:** live tide, wind, pressure, sky, sea state and water temperature.
  A fishing rating with reasons, the best fishing window over the next 24 hours,
  the next high and low waters, and what's in season.
- **🎣 My setup:** pick a rig, hook size, bait, casting distance and lead. It
  shows what you're likely to catch with that setup right now, what's holding
  each species back (for example "hook too small, use 2/0–4/0"), and the best
  time in the next 24 hours to fish that setup.
- **⭐ Best setup:** it tries every combination of tackle against the live
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
- [ ] Planning ahead: pick a day later in the week using the forecast
- [ ] Offline install (PWA)

## Run locally
It's a single `index.html` file. Open it in any browser.
