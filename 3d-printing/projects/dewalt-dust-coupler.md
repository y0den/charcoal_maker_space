# DeWalt DWE7491 dust splitter coupler rescue

**Status:** Testing, not finalized.

## Purpose
Preserve the already printed V1.4 dust splitter (~260 g PETG) using a compact external female/female coupler. Connections must be **airtight under vacuum**, with no unnecessary internal flow constriction.

## Known measured/observed results
- Existing V1.4 printed splitter: external base taper approximately 57.7 to 57.3 mm, spigot approximately 25.8 mm (prior design context; verify against the actual file before revising CAD).
- Existing DeWalt outside-port measurements previously supplied: two readings 64.75 and 65.15 mm.
- v0.2.1 25 mm splitter-side test sleeve: **printed**, fit to depth, but retention inadequate (could be removed with two fingers). This is a failed functional test.
- v0.2.2: tightened candidate female socket; nominal entry 57.78 mm versus 57.98 mm previous, progressive approximately 0.25 mm diametral interference across engagement. **Not verified by physical test** in this record.
- Geometry-only 3MF exports were part of prior work; they are **not yet stored in this repository**.

## Next
Locate actual CAD/source and fit-test file before any new geometry revision. Verify external mating surfaces in a virtual assembly; print only a short test sleeve first. Confirm retention *and* vacuum seal before declaring success.
