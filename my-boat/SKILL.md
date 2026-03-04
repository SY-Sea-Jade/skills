---
name: my-boat
description: >
  Reference profile for Jey's Bavaria Cruiser 36 (2011). Use this skill proactively
  whenever Jey asks about sailing, seamanship, navigation, anchoring, passage planning,
  boat maintenance, engine servicing, electrical systems, antifouling, rigging, safety
  equipment, provisioning, Scottish waters, or anything boat-related — even if the
  question seems generic. Always tailor advice to this specific vessel, her systems,
  and the waters she sails. Trigger on keywords: boat, sail, engine, anchor, marina,
  passage, tidal, VHF, chart, foul, keel, antifoul, chandlery, bilge, diesel, mast,
  furler, winch, halyard, sheet, preventer, reefing, Bavaria, Volvo, D1-30, bow thruster,
  Garmin, AIS, Clyde, Hebrides, Mingulay, Scotland, west coast, corrosion, zinc, anode.
---

# Jey's Boat — Bavaria Cruiser 36 (2011)

## Vessel Summary

| Field | Detail |
|---|---|
| Make / Model | Bavaria Cruiser 36 |
| Year | 2011 |
| LOA | ~11.0 m (36 ft) |
| Beam | ~3.7 m |
| Draft | ~1.9 m (fin keel) |
| Displacement | ~6,200 kg |
| Hull | GRP (white topsides) |
| Rig | Fractional sloop, furling headsail, in-mast furling mainsail (standard BC36 fit) |

## Engine — Volvo Penta D1-30F

- **Type**: 3-cylinder, 4-stroke diesel, 28–30 hp
- **Saildrive**: SD40 saildrive unit (key galvanic corrosion risk area — see below)
- **Raw water cooling**: seawater pump drives impeller; check/replace impeller annually or every 200 hrs
- **Heat exchanger**: freshwater-cooled block with raw water exchanger
- **Fuel system**: Racor or equivalent pre-filter + engine-mounted secondary filter; bleed sequence: secondary filter → fuel pump → injectors
- **Oil**: 15W-40 marine diesel, sump ~3.5 L; change every 100–150 hrs or annually
- **Belts**: single serpentine-style belt drives alternator and raw water pump; check tension and cracking annually
- **Zincs**: saildrive anode (aluminium collar + propeller anode) — inspect every haul-out, replace if >50% consumed
- **Common faults**: injector seal weeping (smell of diesel in bilge), raw water impeller failure (rising temp alarm), air in fuel after filter change (requires bleed)

## Electrical & Battery

- **Charging**: engine alternator + **solar panels** (size unknown — add if known)
- **Battery bank**: house bank + start battery (configuration unknown — add if known)
- **Monitoring**: add details of any battery monitor (Victron BMV etc. if fitted)
- **Shore power**: 230 V shore power (standard BC36 fit)
- **Bow thruster**: electric, fitted (brand/model unknown — add if known); has dedicated thruster battery or draws from house bank — confirm; brushes and seals require inspection at haul-out

## Navigation & Electronics

- **Chartplotter**: Garmin GPSMAP 4010 (10.4" colour, older unit)
  - Chart source: Navionics or Imray charts; Antares charts for Scottish waters (you've worked on loading these)
  - No built-in AIS display unless connected via NMEA 0183 to AIS transponder
- **AIS**: transponder fitted (Class B assumed — confirm brand/model); connect to chartplotter via NMEA for target overlay
- **VHF**: assumed fitted (confirm if DSC-enabled and MMSI registered — required for Scottish passages)
- **Instruments**: standard BC36 wind/depth/speed instruments (confirm if networked via NMEA 2000)
- **Compass**: bulkhead-mounted (confirm if adjusted for Scottish deviation)

## Sailing Area

- **Primary**: Scottish west coast and Hebrides — Firth of Clyde, Kintyre, Islay, Jura, Colonsay, Mull, Ardnamurchan, Small Isles, Outer Hebrides including **Mingulay** (known anchorage interest)
- **General**: coastal cruising, not offshore/ocean passages
- **Tidal considerations**: significant tidal streams in Scottish waters — Sound of Luing, Dorus Mòr, Corryvreckan vicinity, Kyle of Lochalsh; always consult Reeds Almanac or CCC Sailing Directions
- **Weather**: Atlantic depressions move through quickly; forecasts from Met Office Inshore Waters, Windy, or PredictWind; VHF weather broadcasts on ch 23/84 from Coastguard

## Known Issues & Maintenance Focus Areas

### Galvanic Corrosion (Active Concern)
- Saildrive units on Bavaria 36s are a known vulnerability for galvanic and electrolytic corrosion
- Check: saildrive leg aluminium casing for pitting, saildrive bellows condition (replace every 5–7 years regardless of appearance), propeller shaft seal
- Mitigation: maintain saildrive anode, isolate shore power properly (use galvanic isolator or isolation transformer), check marina wiring quality
- At haul-out: inspect saildrive carefully before antifouling; photograph baseline

### General Maintenance Priorities
- **Antifouling**: annual haul-out typical for Scottish waters (heavy fouling season); use hard antifoul suitable for Clyde/west coast
- **Seacocks**: grease and exercise all seacocks annually; check for dezincification on bronze fittings
- **Rigging**: inspect standing rigging (swageless or swaged terminals) annually; check furler bearings and foil joints; in-mast furling motor (if electric) or manual operation
- **Sails**: UV strip on furling headsail; in-mast mainsail — check sail slug condition and furling drum
- **Bilge**: check bilge pump operation and float switch before each season

## Advice Defaults

When giving advice for this boat:
- **Assume Scottish tidal waters** unless stated otherwise — always flag tidal stream hazards
- **Assume a shorthanded crew** (skipper + 1–2, sometimes solo) — prefer conservative sail plans, easy reefing, roller furling use
- **Engine servicing**: reference D1-30F specifics, not generic diesel advice
- **Galvanic corrosion**: flag any advice that touches shore power, metal underwater fittings, or marina berths
- **Charts/navigation**: Garmin GPSMAP 4010 is the primary plotter; advice should be compatible with that unit's capabilities and age
- **Anchoring**: Jey has interest in remote Hebridean anchorages (Mingulay etc.) — consider holding ground, swell exposure, and emergency egress
