# Third-party components

Yuzu bundles the following components in the application resources.

| Component | Version / source | License |
|---|---|---|
| ffmpeg arm64 | 7.1 static, osxexperts.net build | GPL (see `ffmpeg -version`) |
| ffmpeg x86_64 | 7.1 static, evermeet.cx build | GPL (see `ffmpeg -version`) |
| Java runtime arm64 | OpenJDK 21, Tangerine-trimmed JRE | GPLv2 with Classpath Exception |
| Java runtime x86_64 | OpenJDK 21, Tangerine-trimmed JRE | GPLv2 with Classpath Exception |
| Apache POI / PDFBox | bundled under `Resources/PowerPoint/lib` | Apache License 2.0 |
| Tangerine PowerPoint/Spreadsheet converter | `Resources/PowerPoint/lib/tangerine-powerpoint.jar` | proprietary, owner-authorized private use |
| PagesWriter / OfficePreview / PagesTemplate | `Resources/Office` | proprietary, owner-authorized private use |

The ffmpeg source code is available at <https://ffmpeg.org/download.html>.
The GPLv3 text is included at `docs/licenses/GPL-3.0.txt`; the arm64 build is
GPLv2-or-later and the x86_64 build is GPLv3, so both can be distributed under
GPLv3 with the corresponding source/config offer.
The Java runtime license files are under
`Resources/PowerPoint/arm64/legal` and `Resources/PowerPoint/x86_64/legal`.
Apache POI/PDFBox license texts are available from their upstream projects.

This repository is a private project. Do not redistribute the Tangerine
compatibility components without permission from the rights holders.
