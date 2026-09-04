# TT600 59X Full 12V Conversion Basket

Date: 2026-09-04

Goal: implement a full, reliable 12V conversion on TT600 59X using a matched XT600 3TB electrical strategy.

This basket is split into three groups:

- mandatory donor electronics
- mandatory loom and protection hardware
- optional convenience upgrades

## 1) Mandatory donor electronics

Buy as one matched set whenever possible.

| Group | Part | Reference | Qty | Status |
|---|---|---|---|---|
| Charging | XT600 3TB stator | 3TB family | 1 | Source used donor |
| Charging | XT600 3TB flywheel rotor | 3TB family | 1 | Source used donor |
| Charging | Regulator rectifier | OE 3TJ-81960-01 | 1 | Source donor or equivalent |
| Ignition | CDI | OE 3TB-82305-00 or 3TB-82305-10 family | 1 | Source donor or aftermarket |
| Ignition | 12V ignition coil | XT600 3TB or 2KF 12V type | 1 | Source donor/new |
| Storage | AGM battery | YTX5L-BS or equivalent 12V 4-5Ah | 1 | Buy new |

Non-negotiable rule: stator, flywheel, CDI, and regulator/rectifier must be electrically compatible as one system.

## 2) Mandatory loom and protection hardware

These are cheap and prevent most electrical failures.

| Group | Part | Spec | Qty target |
|---|---|---|---|
| Fuse protection | Blade fuse block | ATO/ATC, 4 to 6 ways | 1 |
| Fuse protection | Main inline fuse holder | Weatherproof ATC/ATO | 1 |
| Fuse protection | Fuse assortment | 5A, 10A, 20A | 1 kit |
| Wire | Main feed wire | 4.0 mm2 (12 AWG) red/black | 5 m each |
| Wire | Charging and DC output | 2.5 mm2 (14 AWG) | 5 m |
| Wire | Ignition and lights | 1.5 mm2 (16 AWG) | 5 m |
| Wire | Signals and trigger | 0.5 to 1.0 mm2 (20 to 18 AWG) | 5 m |
| Connectors | Superseal 1.5 and/or Deutsch DT | 2-pin and multi-pin sets | 1 mixed kit |
| Protection | Adhesive heat shrink | Assorted diameters | 1 kit |
| Protection | Fleece loom tape | Tesa 51036 or equivalent | 1 roll |
| Protection | Split conduit | 10 and 13 mm | 2 to 4 m |
| Grounding | Star washers and clean earth bolt hardware | Stainless preferred | 1 set |

## 3) Mandatory 12V bulb and load conversion

Replace every bulb together.

| Circuit | Spec from workspace notes | Qty |
|---|---|---|
| Headlight | 12V 35/35W H4 or BA20d depending housing | 1 |
| Tail / brake | 12V 5W / 21W | 1 |
| Speedo illumination | 12V equivalent for your holder type | as fitted |

Any remaining 6V bulb in the loom can fail immediately after conversion.

## 4) Fuse map to build (initial values)

| Circuit | Fuse |
|---|---|
| Main feed battery to fuse block | 20A |
| Ignition CDI coil feed | 5A |
| Headlight | 10A |
| Tail and brake | 5A |
| Instruments | 5A |
| Spare accessory line | 5A to 10A |

## 5) Physical layout decisions

Decide these before making the loom.

1. Battery position:
under right side panel bracket or rear subframe area.

2. Regulator/rectifier location:
right side near airbox with airflow.

3. CDI and trigger routing:
keep CDI trigger wire isolated from HT lead with at least 50 mm separation.

4. Single earth point:
every component earth returns to one clean, common frame point.

## 6) Commissioning acceptance tests

Do not finalize loom wrap until all tests pass.

| Test | Pass condition |
|---|---|
| Spark path test | Engine sparks with temporary minimum ignition circuit |
| Charging test | 13.8V to 14.5V DC at battery around 3000 rpm |
| Earth continuity | Less than 0.2 ohm from each component earth to battery negative |
| Kill switch behavior | Engine stops by CDI grounding, not random cutout |
| Lighting test | All 12V bulbs work, no immediate failures |

## 7) Buy order

1. Buy now:
loom hardware, fuses, wire, connectors, battery, 12V bulbs.

2. Source in parallel:
matched 3TB donor electrical set.

3. Install only when complete:
avoid partial conversion operation.
