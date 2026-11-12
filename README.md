# Shoebury Fishing Planner

A trip planner for shore fishing at Shoebury East Beach (Thames Estuary), using live
tide, weather and sea data. Open it on your phone and use "Add to Home screen".

**https://snxffbxxts.github.io/essexfishing/**

## How to use it
Tap the time bar at the top and set **when you're going** (a day up to a week
ahead, your arrival time, and how long you're staying), or tap **Live** if you're
going now. Every screen then works for that session.

### Plan (main screen)
- **Session rating**, the most productive hour, and the main target species
- **What to do:** the tide on arrival, high and low water with the best periods,
  sunset and sunrise effects, when to change setup, the lead to use, wind effects,
  crabs, and rain
- **Recommended setup** for the most bites, plus a second rod for bigger fish
- **Hour by hour:** the tide, rating, wind, light, and the setup to fish each hour
- **Expected catches** with chances, and the setup to use if you want to target
  each species
- **Conditions during the session:** tide, wind, air temperature, rain, cloud,
  pressure, sea and light
- **Better times to go** on the same day or later in the week, one tap to switch
- **Kit list** (tick items off) with bait quantities worked out for your session
- **Safety:** when the tide turns over the mud, dark hours, strong wind, MOD ranges

### Other screens
- **Conditions:** Overview, Tides (the next 8 tide times and a height chart),
  Weather (hour by hour) and Week (the best window on each day)
- **Catch:** *My setup* (pick a rig, hook, bait, distance and lead to see what
  you'll catch and what's holding each fish back) and *By species* (the best setup
  for each fish)
- **Species:** a guide to each fish
- **Data:** the status of each live feed, and how the predictions work

## Live data
- Environment Agency Southend tide gauge (observed level every 15 minutes)
- Open-Meteo marine: tide curve, waves and sea temperature, lined up against the gauge
- Open-Meteo forecast: wind, gusts, pressure, cloud, rain and temperature, hourly for about 7 days
- If a feed fails, it falls back to saved data, then to an astronomical tide estimate

## Roadmap
- [x] Live conditions engine; setup selection and catch predictions; species guide
- [x] Time travel up to 7 days ahead; week planner
- [x] Trip planner: session plan, hour-by-hour setups, kit list, safety, better times
- [ ] More tackle: bait cocktails, clipped-down rigs, attractors
- [ ] More marks: Southend Pier, Thorpe Bay, Canvey and so on
- [ ] Catch diary, to log real catches against the conditions
- [ ] Offline install (PWA)
