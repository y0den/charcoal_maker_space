# Charcoal Maker Space — Mandatory CAD & Mechanical Release Gate

Status: ACTIVE / mandatory for all future functional 3D-printing projects
Established: 2026-11-28
Reason: Repeated slat-wall jig prototypes failed basic fit, retention, hardware capture, wall clearance, and slicing checks despite earlier claims of readiness. Rebuilding trust requires evidence, not confident language.

## Non-negotiable release policy

A mesh being manifold/watertight or loading in a 3MF is **not** proof it works mechanically. Do not recommend printing a functional jig until its relevant checks below have documented evidence. If a critical check is impossible to perform, report it as **unverified** and **do not call the design print-ready**. Do not claim "no mistakes," guaranteed fit, safe suspended load, successful slicing, or physical validation without evidence.

## 1. Requirements and real-use constraints

- Establish actual mating geometry from user files, physical measurements, and approved prints; label assumptions and tolerances separately.
- Show the fixture in the real surrounding assembly, including parts that must not be penetrated or displaced.
- Record the installation / removal path and required access to all fasteners.
- For current slat-wall jigs: nominal slat width 36.51–38.10 mm, thickness **approximately** 9.525 mm (not a verified uniform thickness), 19.05 mm gaps, installed wood flush to drywall, nailed in place. Do not place material behind an installed slat. Never change previously approved L/M/F spacers and V3 Extra Grip center-jig geometry without explicit approval.
- For overhead work, account for a 24-inch-plus scrap extension, gap-spacing accessories, handling forces, and the nails' unknown withdrawal capacity. An alignment jig is **not a load-bearing hanger** unless positively validated.

## 2. Mechanical CAD validation

- Build and inspect a **full CAD assembly**, with drywall, installed slat, loose scrap, adjacent slats, and all hardware.
- Sweep parts across full stated dimensions (narrowest/widest wood; wall/ceiling angle; hardware insertion, clamp open/closed, hinge pivot).
- Check interference/clearance, screw travel, stop limits, pressure-pad contact, removal access, gap intrusion, and ability to seat wood flush.
- Model actual screws, nut dimensions, washers where applicable, and tool access. For captive nuts: verify full anti-rotation faces, insertion route, axial retention, wrench/driver access, and that *no access cut deletes the anti-spin walls*.
- Confirm intended flexible elements actually have uninterrupted relief and the necessary deflection path; rigid body must not accidentally bond a flexure.
- Evaluate mechanical load path, twisting, bending, screw pullout, crushing of softwood, PLA layer orientation, and repeated use. Basic estimates must state assumptions; no invented load rating.
- Reject designs that cannot meet functional constraints; do not iterate an invalid mechanism solely to preserve sunk CAD effort.

## 3. Printability and packaging

- Confirm all parts sit on the build plate with no unsupported floating islands, fragile hinge roots, or unprintable flexure bridges in intended orientation.
- Mesh integrity, unit-scale checks, minimum walls, tolerances, support accessibility, and removal from print supports.
- Preserve working Bambu X1 Carbon/0.4 mm profiles from an authentic user-saved Bambu Studio project, not synthesized incomplete preset stubs.
- Keep TEST projects separate from the MASTER. One labeled-plate 3MF for a kit; provide STLs/STEP and source where useful.
- Verify 3MF content, plate bounds, model associations and settings, and printer/slicer compatibility to the extent tools allow.
- When Bambu Studio is not available, explicitly mark **slice test NOT RUN** and do not imply slicer success.

## 4. Release documentation

For every release, provide:
1. Revision / purpose / changes vs physical reference.
2. Verified dimensional table (target, actual CAD, gap/travel) and critical hardware specification.
3. Assembly fit evidence (interference/clearance, hardware retention, tool/remove path).
4. Structural evaluation and assumptions, including overhead load caveats.
5. Printability, mesh, 3MF and slicing results; clearly distinguish inspections from unperformed tests.
6. Specific minimal pilot test with measurable pass/fail conditions; stop before larger prints if pilot fails.
7. Known unknowns and failure risks.

Use explicit statuses:
- **CAD REVIEWED** — geometry/assembly analyzed, no physical proof.
- **SLICER VERIFIED** — sliced in named slicer/printer/profile with no relevant errors, with evidence.
- **PHYSICALLY TESTED** — user confirmed on real hardware/wood, describe exact test.
- **APPROVED MASTER** — user explicitly approved proven version. Unverified/failed versions belong in TEST or ARCHIVE, never the print-ready master.

## 5. Revision discipline

- Protect prior proven geometry and maintain rollbacks.
- Change one primary mechanical variable per test when feasible, with a stated hypothesis.
- Do not ask the user to waste a full-size print to discover an avoidable CAD or hardware-assembly error.
- When a critical check fails, **stop**. Redesign or use simpler independent support; do not say the part is ready.
- Be candid: errors can never be guaranteed impossible. The binding commitment is to catch foreseeable mechanical mistakes *before printing*, document tests honestly, and admit unverified limits.

## Project-specific incident record

- Earlier Reach Bridge V1 aligned wood well but would not independently hold long scrap overhead.
- Reach V2 required so much deflection the fir could not enter; V2.1 eliminated useful preload; subsequent test coupons did not represent full cantilever loading.
- Miter Plate 6 fit failed; later versions had spring/first-layer geometry problems.
- M4 Clamp V0.1 obstructed flush-to-drywall mounting.
- M4 Clamp V0.2 had a hex-nut anti-rotation feature cut away by its nut loading slot. **FAILED — DO NOT PRINT PLATES 2/3.**
- Known successes: center V3 Extra Grip jig and original 3/4-inch L/M/F spacing clips.
