# Shoebury Shore Fishing 🎣

A phone-friendly sea fishing game set on Shoebury East Beach (Thames Estuary).
It runs in the browser. Open the GitHub Pages link on your phone, then use
"Add to Home screen" to get it as an app icon.

## How it plays
- **Live conditions:** the game uses the real clock. It works out the tide (height,
  flooding or ebbing, springs or neaps), sunrise and sunset, the moon phase and the
  season for Shoebury. Fish bite best when real anglers would expect them to.
- **Tackle box:** pick a rig (flappers, pulley pennel, running ledger, float), a
  hook size (6 up to 4/0), a bait (lug, rag, squid, mackerel, peeler, sandeel) and a
  plain or grip lead.
- **Cast:** hold the button and let go at full power.
- **Bite:** a rattle on the tip comes first. Strike on the big pull-round.
- **Fight:** hold to reel and let go when the tension goes red. Snap the line and you
  lose the rig.
- **Shop and log:** sell your catch for cash, buy tackle, and track your PBs.

## Roadmap
- [x] **v0.1 Basics:** cast, bite, strike and fight loop; tackle box; shop; catch log;
  modelled tide, sun, moon and season; 11 Shoebury species plus crabs
- [ ] **v0.2 Live weather:** wind speed and direction, pressure and sea state from
  Open-Meteo (free, no API key). An onshore blow or a dropping barometer switches
  fish on.
- [ ] **v0.3 Real tide data:** swap the tide model for real predicted tide times
- [ ] **v0.4 More tackle:** rods and reels, clipped-down rigs, bait cocktails,
  bait-collecting trips at low water (dig lug, gather peeler crab)
- [ ] **v0.5 More marks:** Southend Pier, Thorpe Bay, Canvey and so on, each with
  its own fish and snags
- [ ] **v0.6 Polish:** sounds (reel, bite alarm, waves), better art, an offline
  installable app (PWA)
- [ ] **Later:** connect it to the real fishing "bible" app, so species, bait and
  mark info come from the same data

## Run locally
It's a single `index.html` file. Open it in any browser.
