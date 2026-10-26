# Legal

## Compatibility components

Yuzu is an independent project. It is not affiliated with, endorsed by, or
sponsored by Leap Studio. The feature set is derived from publicly documented
behavior and black-box runtime observation of the installed Tangerine app.

This build includes compatibility components copied from the owner's own
Tangerine installation, with the owner's explicit authorization:

- `Resources/PowerPoint/lib/tangerine-powerpoint.jar` (PowerPoint/Spreadsheet
  conversion) and the bundled Java runtimes, Apache POI and PDFBox libraries;
- `Resources/Office/PagesWriter.js`, `Resources/Office/OfficePreview.js` and
  `Resources/Office/PagesTemplate.pages` (Pages read/write support).

These components remain the property of their respective owners and are not
licensed for redistribution by Yuzu. Publishing or redistributing this build
may require permission from the rights holders for those components.

## Third-party components

Yuzu bundles ffmpeg and may link system frameworks. Each component keeps its
own license and copyright notice. Apache POI and PDFBox are Apache-2.0
licensed. The bundled Java runtime is subject to its own license. The ffmpeg
builds are GPL; their configure lines and source links are documented in
[THIRD-PARTY.md](THIRD-PARTY.md). Tangerine components are proprietary and
included here under the owner's authorization.

## Trademarks

Tangerine is a product of Leap Studio. "Tangerine" is used in this repository
only to describe the product category and the compatibility target. Yuzu does
not use the Tangerine name, icon, or branding.

Apple, macOS, Swift, SwiftUI, and AppKit are trademarks of Apple Inc.

## Third-party components

Yuzu may bundle or link third-party components (for example ffmpeg, libwebp,
or ExifTool) in later milestones. Each component keeps its own license and
copyright notice; a generated third-party inventory will be added before any
distribution. Yuzu itself does not grant any license to commercial tools.

## Responsible use

Yuzu converts files the user owns or is authorized to process. Do not use it to
circumvent copyright, DRM, or license terms.
