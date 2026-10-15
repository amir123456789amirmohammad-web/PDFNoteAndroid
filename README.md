# PDF Note — Android 7 (API 24+)

A compact, fullscreen-first PDF annotation project intended for older Android phones, including devices running Android 7.

## How the workspace works
- The PDF occupies the whole work area; the blank white solving sheet is **closed by default**.
- Tap **«صفحه سفید +»** to open an opaque white sheet directly over the PDF. It covers the questions underneath so you can solve one question at a time.
- Drag the sheet by its dark top bar to move it up, down, left, or right. Drag the green bottom-right corner to resize it. Use **«مرکز»** to reset its size/position, and **×** or the toolbar button to close it.
- Opened PDF pages can be changed with the compact page controls.

## Tools
- Immersive fullscreen mode, compact toolbar, and minimal margins.
- Pen with simple straight-line snapping for near-horizontal/near-vertical strokes.
- Stroke eraser (tap near a mark), rectangle tool, undo-last mark, pen color cycling, and pen thickness controls.
- Open a PDF and export annotations drawn on PDF pages as a flattened PDF.
- The white solving sheet is a separate canvas and its writing is currently kept only while the app remains open; it is not merged into the exported PDF yet.
- Stylus input uses Android's standard motion events. Actual compatibility/performance on an LG Stylus 3 still needs device testing.

## Build
Open this project in an Android development environment that supports Android Gradle Plugin 8.2.2 and Android SDK 34, then build an APK. The app's `minSdk` is 24 (Android 7.0).

## Limitations
- This is source code, not a prebuilt or device-tested APK.
- PDF annotations are flattened into page images on export.
- The white solving sheet's marks are in-memory only and aren't included in PDF export.
- Undo applies to the pane most recently focused; tap the pane you want to undo first.
- Large PDFs may be slow on older devices.


### چیدمان ابزارها
نوار ابزار به صورت عمودی در سمت چپ صفحه قرار دارد؛ فضای باقی‌مانده تماماً برای PDF و برگهٔ سفید شناور است. برنامه از حالت تمام‌صفحهٔ immersive استفاده می‌کند.
