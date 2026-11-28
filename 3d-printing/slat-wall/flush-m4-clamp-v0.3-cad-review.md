# Slat Wall Flush M4 Clamp — V0.3 (TEST, CAD REVIEWED)
Date: 2026-11-28
Status: **CAD REVIEWED — PHYSICAL PRINT & SLICER NOT VERIFIED; DO NOT PRINT PLATES 2/3 UNTIL PLATE 1 PASSES.**
Prior V0.2: **FAILED**, its oversized nut-access throat cut away anti-rotation walls.

## Output and rollback
- Local generated test project: `Charcoal_Slat_Wall_TEST_Flush_M4_Clamps_V0_3_X1C.3mf`
- CAD/STL/STEP/QA bundle: `Charcoal_Flush_M4_Clamps_V0_3_CAD_STEP_STL_QA.zip`
- V0.2 retained as failed archive, approved master unchanged.
- Project 3MF regenerated with unchanged Bambu profile settings from user's `CleanProject.3mf`; archive integrity confirmed; Bambu Studio import/slice **not executed**.

## V0.3 design and independent checks
- M4 standard hex nuts (nominal 7 mm across flats, 3.2 mm thick) enter 7.30 mm-wide open-back channels before mounting; screws must be pre-engaged so nuts do not drop out.
- CAD insertion sweep at 0.25 mm intervals, 10 nut positions: zero collision. Simulated nut rotation interferes with plastic walls by 10° (~0.45 mm³) and by 15° (~0.97 mm³). Actual retention strength **not** proven.
- Screw-axis repositioned to provide full 360° screw-head bearing annulus for sampled radii 2.25–3.5 mm near seat. M4 socket-head modeled 7 mm diameter, 4 mm tall. M4×20 tip reaches pad at ~12.45–14.69 mm from underhead for wood widths 36.5125–38.10 mm.
- Pad adds 1.1 mm locating foot supported by ledge, with uninterrupted nut access maintained.
- Wood width envelope 36.5125–38.10 mm, 9.525 mm nominal thickness, gaps 19.05 mm, cap underside 10.35 mm above drywall. Zero modeled intersections with wood, neighbors and drywall at tested endpoints on four fixture parts.
- Hinged shoes simulated noninterference at 90°–175°; hinge bolt/nut not physically tested.
- 5 source CAD solids and their STL meshes integrity checked; 14 print project objects on three labeled plates. PRINT PILOT PLATE 1 ONLY.

## Remaining unverified
Bambu Studio slicing, actual printed hole shrinkage, standard nut fit with real M4 hardware, wood surface wear, clamp friction/torsion capacity, slat finish-nail holding strength, overhead reach load, physical hinge operation. No FEA or certified load rating. Do not recommend hanging long scrap without separate support until testing.

## Immediate pilot protocol
1. Verify project opens, uses X1C/0.4 mm and expected filament; slice and visually inspect Plate 1 before print.
2. Print Plate 1 only (94 mm body, two pads).
3. Insert nuts via the narrow open underside, engage M4 screws, seat pads feet-down on ledges.
4. Verify nut does not free-spin under gentle hand torque, screws contact pads over actual fir widths, pad stays supported, wood sits flush on drywall and isn't gouged.
5. Test light twisting on a loose slat; stop if any binding, slipping, deformation or nut rotation occurs. Do not advance to Plate 2 or 3 unless user reports success.
