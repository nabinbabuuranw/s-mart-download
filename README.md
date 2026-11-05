# S Mart for Android: download page

Test build 0.1.0-m2 of the S Mart Android app (package `com.nabin.smart`).

- Page: https://nabinbabuuranw.github.io/s-mart-download/
- APK: `SMart-0.1.0-m2.apk`, 8,385,513 bytes, SHA-256 `5643cfdd1ab19add62cc4e79de40af38132a132dfd84004cd405b54e209f503a`
- Parts: `v0.1.0-m2/part-000.bin` to `part-006.bin` (1,258,291 bytes each, last one 835,767), listed with sizes and SHA-256 in `manifest.json`.

The page joins the parts in the browser, checks each part and the whole file against the manifest, and saves the APK only when the SHA-256 matches.

Source: https://github.com/nabinbabuuranw/s-mart (apps/android, docs/ANDROID.md).
