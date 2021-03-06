# legacysurvey Change Log

## 7.1.0 (DR7, 2018-08-23)

- Additions to address DR7 [issues](https://github.com/legacysurvey/legacysurvey/issues/82) ([PR#83](https://github.com/legacysurvey/legacysurvey/pull/83)). Main changes:
    - Split random files into smaller subsets and place in a dedicated directory.
    - Document the 7.1 versions of the sweeps file.
- Deprecate DR1 and DR2 coadd directories.

## 7.0.1 (DR7, 2018-07-26)

- A few more additions for DR7 ([PR#81](https://github.com/legacysurvey/legacysurvey/pull/81)).

## 7.0.0 (DR7, 2018-07-26)

- Updated to release version for DR7 ([PR#80](https://github.com/legacysurvey/legacysurvey/pull/80)).
- Latest data model (new random catalog, new Gaia and fiber flux columns).
- Latest status and depth histogram plots.
- New more accurate calculations of area using random catalogs for DR7 (and for previous DRs).
- General updates to the description page for area/number of sources/new techniques/zeropoints, etc.
- Updates to publications.

## 6.0.2 (DR6, 2018-04-23)

- Fix typos regarding how to convert depths to magnitudes ([PR#79](https://github.com/legacysurvey/legacysurvey/pull/79)).
- Added extra command options to the DR5/DR6 cutouts.

## 6.0.1 (DR6, 2018-02-27)

- Correct "layer" argument in cutout server example URLs.
- List pixel scales of the coadds, and native Mosaic and 90prime pixel scales.

## 6.0.0 (DR6, 2018-02-23)

- Updated to release version for DR6 ([PR#77](https://github.com/legacysurvey/legacysurvey/pull/77)).
- Latest Data Model.
- Latest status plots.
- Added histogram plots for depth instead of referring back to DR2 calculations.
- General updates to the description page for area/number of sources, etc.
- Links to NOAO's publications page for the LS in addition to updating publications from the LS team.

## 5.0.1 (DR5, 2017-12-07)

- Update to ccds-annotated file to fix which CCDs were used in DR5.

## 5.0.0 (DR5, 2017-10-25)

- Updated to release version for DR5 ([PR#73](https://github.com/legacysurvey/legacysurvey/pull/73)).
- New Data Model where appropriate.
- Added `RELEASE=5000` description.
- Contents toolbars for quick-links on longer pages.
- Additional drop-down menus (*e.g.*, there are now tips and tricks for the viewer).
- `SIMP` has been deprecated by `REX`.
- ordering of bands for photometric model fits has changed.
- acknowledgment is now consistent with NOAO page.

## 4.0.0 (DR4, 2017-06-30)

- Updated to release version for DR4 ([PR#72](https://github.com/legacysurvey/legacysurvey/pull/72)).
- Extensive changes reflecting the new Legacy Survey Data Model.
- Removed references to DECam and made them more generic.
- Added references to MzLS, BASS and DECaLS as the "Legacy Surveys."
- Updated descriptions to new code, where needed.
- New plots for status of observations.
- Recalculated coverage, file sizes etc. for DR4.

## 3.1.1 (2016-11-28)

- Fix order of DEV and EXP in TYPE column ([PR#69](https://github.com/legacysurvey/legacysurvey/pull/69)).

## 3.1.0 (DR3.1, 2016-11-15)

- Add Caveat about tractor and sweep files with bad or corrupted data.

## 3.0.0 (DR3, 2016-09-26)

- Hopefully fixed hidden titles problem.
- Release version for DR3.
