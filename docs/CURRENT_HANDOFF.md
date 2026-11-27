# Current handoff — 2026-11-27

## Why this repository exists
One durable maker-space record across conversations. Organize by fabrication process, with a single project home for work that spans laser, printing, and CNC/routing. Update this file at significant milestones or before switching chats.

## Active threads

### NUT65 / 001
- **Verified by user (2026-11-27):** Black Weikav NUT65 and Real Wood Paper walnut sheets received. Goal is to **keep the NUT65 original mechanical and acoustic system** and make the outside black aluminum + genuine walnut.
- **Planned:** Begin with laser-cut Real Wood Paper walnut veneer on the wide top bezel, inspect fit and appearance before bonding.
- **Aspirational:** Mode Encore-inspired **flush** walnut accent, ideally using 1/8-in (3.175 mm) walnut stock; a recessed pocket cannot be dimensioned until the bezel is inspected and wall thickness verified. Wood can be thinned from the underside.
- **Aspirational:** Custom removable copper bottom weight; do not assume weight geometry, hole locations, or attachment until measured.
- **Active fabrication idea:** Reusable miniature precision router sled with removable NUT65 bezel cradle, constrained travel, and test stock. Full aluminum milling with a handheld wood router is *not yet qualified*.
- **Next:** Document stock NUT65 sound/feel; photograph and measure the received bezel top and underside, check sheet backing/thickness, and test cardboard template before cutting walnut. Establish available material thickness and case/keycap clearances. Prototype router sled on wood before any scrap-aluminum test.

### Walnut MK61 / GH60
- **Verified by user:** Existing walnut case + preferred GMK Stealth Colorized keycaps; user's benchmark is a deeper, fuller tray-mounted GK61 sound. Support/mounting is principal hypothesis.
- **Verified by user:** White silicone O-rings 4 mm OD × 1 mm ID × 1.5 mm section found in shop. Red 4 mm OD × 2 mm ID × 1 mm section, 50 Shore A, ordered.
- **Planned:** Test cushioned tray/burger-style mounts using proper post height and controlled screw engagement; compare against existing supports before changing other acoustic variables.
- **Next:** Record build configuration, screw/post dimensions, fit, USB-C alignment, and A/B sound notes. Do not assert a sound improvement without tests.

### Clock OS + Govee physical enclosures
- **Planned:** Slim matte-black printed housings with walnut accents for the ESP32 3.9-inch display and Govee H5075 sensor covers.
- **Next:** Fit-test USB-C connection, display clearances, sensor ventilation and access; decide which pieces should be laser-cut veneer versus CNC-machined hardwood. Clock OS firmware belongs to its own project; this repo tracks maker hardware.

### DeWalt dust splitter connection
- **Verified by user:** Printed v0.2.1 splitter-side test sleeve remained seated but pulled off with two fingers; too loose for vacuum-tight use.
- **Candidate (not verified):** v0.2.2 tighter female socket; test on the real V1.4 splitter before promoting to final. All joints must be airtight, not merely slip-fit.
- See [coupler record](../3d-printing/projects/dewalt-dust-coupler.md).

## Equipment on hand
- Bosch 1617-style corded router combo: fixed base, plunge base, router table
- Ryobi P601 18V fixed-base trim router
- Bambu Lab X1 Carbon + AMS, 0.4 mm nozzle
- 20W diode laser for wood/acrylic (not a metal cutting tool)
- Woodworking shop, scrap hardwood, measuring and finishing equipment

## CNC purchase status
**Not purchased.** A future ~4-foot woodworking CNC is a distinct goal. A small CNC is only justified if it has convincing evidence for accurate metalwork (aluminum, brass, ideally copper), sufficient workspace for a complete keyboard, real owner projects and support/community. The manual router-sled experiment comes first.

## Update rules
1. Put exact measurements, versions, photos, test outcomes and source files in the project page or associated fabrication page.
2. Separate *intent*, *bench result*, and *finished production file*.
3. Link every cross-process component from its primary project page.
4. At every handoff, update **last tested**, **open blocker**, **next action** and **file locations**.
