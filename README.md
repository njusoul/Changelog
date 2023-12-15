# Changelog
This file contains the notable changes to the project

Version 1.0.0 (15-12-2023)
## New
    - Added column classifiers(Date, Time, PerUniteCost, TotalCost, etc.)
    - Added column "AveCost" to track average item cost

## Changes
    - Changed date format to MM-DD-YYYY
    - Removal of whitespace (cosmetic)

## Fixes
    - Fixed misalignment in Column "TotalCost" where some rows did not match with correct dates
    - Fixed SUM to run over entire column instead of partial
