# S Mart for Android: download page

Test build 0.2.0-m3 of the S Mart Android app (package `com.nabin.smart`). The previous test build 0.1.0-m2 is still here.

- Page: https://nabinbabuuranw.github.io/s-mart-download/
- APK 0.2.0-m3: `SMart-0.2.0-m3.apk`, 8,477,851 bytes, SHA-256 `e600c1accb6e67de6dd94582c31990bc5f9b9109954e6358591071cbc992eb7a`
  - Parts: `v0.1.0-m3/part-000.bin` to `part-006.bin` (1,258,291 bytes each, last one 928,105), listed with sizes and SHA-256 in `manifest.json`.
- APK 0.1.0-m2 (earlier): `v0.1.0-m2/manifest.json` and its parts, `v0.1.0-m2/part-000.bin` to `part-006.bin`. The page loads it with `?build=v0.1.0-m2/manifest.json`.

The page joins the parts in the browser, checks each part and the whole file against the manifest, and saves the APK only when the SHA-256 matches.

Source: https://github.com/nabinbabuuranw/s-mart (apps/android, docs/ANDROID.md).
