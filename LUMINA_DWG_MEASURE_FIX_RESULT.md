# LUMINA DWG and Measure Fix

Date: 2026-06-24

Latest package:

`LUMINA_DWG_LOAD_AND_MEASURE_EXIT_FIXED_V91_0_2_PACKAGE.zip`

Launch folder:

`LUMINA_1001_V91_0_2_DWG_MEASURE_FIXED`

Approved screen:

`Lumina V91 — Architect's Studio (21-05-2026)`

Changes:

- DWG upload now uses the local backend before browser fallback.
- ODA converted DWG geometry can render in the V91 workspace.
- Manual line measurement added.
- Manual radius measurement added.
- Measurement can now exit with right-click, Esc, double-click, or the visible close button.
- PDF support remains enabled.
- The rejected generated shell remains blocked.

Tests passed:

- npm run check
- npm test
- live health check
- live app check
- sample upload conversion check
