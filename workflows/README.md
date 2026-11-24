# Repeatable maker workflows

## Project lifecycle
1. **Brief:** Objective, non-negotiables, existing hardware, desired appearance and acoustic/functional targets.
2. **Reality check:** Measurements, source CAD and physical fit. Separate `Measured`, `Reported`, `Estimated`, `Planned`.
3. **Geometry check:** Inspect mating surfaces, interference, alignment, assembly clearances and serviceability.
4. **Cheap prototype:** Printed fit coupon, scrap wood/cardstock, or inexpensive practice stock before final material.
5. **Physical test:** Record part/version, exact material, tool setup, actual result and photos. Mark failed tests explicitly.
6. **Revise one variable at a time** where feasible; include change log.
7. **Final approval:** Verify dimensions, fit, operation, finish and any special non-negotiables before labeling final.
8. **Handoff:** Update [current handoff](../docs/CURRENT_HANDOFF.md), project page, decision log, and link deliverable files.

## File conventions
`project_part_vMAJOR.MINOR[-variant].ext`, e.g. `nut65_walnut_bezel_v0.1.svg`. Place under `source/` or `exports/` in the relevant process project when such assets exist. Name failed trials clearly; never overwrite a verified successful part with an unverified revision.

### Quality rules
- Avoid repeated requests for measurements already provided in CAD or verified notes.
- Distinguish geometric fit from functional fit (e.g., an airtight vacuum joint needs leak and retention testing).
- Never claim a file contains printer/slicer presets unless checked.
- When changing chats, include latest known good version, tested failures, next test and exact repo paths.
