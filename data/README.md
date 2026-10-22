# Local measurement data

Use `raw/` for camera measurements, `calibration/` for calibration data, and
`processed/` for reconstruction outputs as those features are developed. These
local directories are ignored by Git and can be created when needed.

Record units, capture settings, hardware revision, calibration reference, and
processing parameters with each dataset. Future small, reproducible test fixtures
belong under `tests/fixtures/`; document the source and retrieval procedure for
larger datasets instead of committing them here.
