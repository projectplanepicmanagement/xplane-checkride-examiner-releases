# xplane-checkride-examiner-releases

Distribution repo for [Checkride Examiner](https://github.com/projectplanepicmanagement/xplane-checkride-examiner)
(an X-Plane 12/XPPython3 plugin). This repo is intentionally public and
holds nothing but built release zips and `manifest.json` -- the actual
source lives in the private main repo.

`manifest.json` is read by the plugin's own in-app updater
(`checkride_examiner/updater.py`) via a "Check for Updates" button in the
Update screen. It is not used by any third-party updater service.

**Only edition-restricted builds are ever published here** -- never a
full/unrestricted (all-ratings) build. Per-rating sales depend on it.
