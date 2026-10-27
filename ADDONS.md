# FetchJ add-ons / Complementos / Zusätze

Release: [`addons-1.0.0`](https://github.com/fetchj/FetchJ-Public/releases/tag/addons-1.0.0) (21/10/2026)

The add-ons are optional parts of FetchJ that do not change with every program version. FetchJ installs them with one
click; it checks the SHA-256 checksum of the zip before it uses it. / Los complementos son partes opcionales que no
cambian con cada versión; FetchJ verifica la suma SHA-256 antes de usarlos. / Die Zusätze sind optionale Teile, die sich
nicht mit jeder Version ändern; FetchJ prüft vor der Installation die SHA-256-Prüfsumme.

## OCR – `FetchJ_OCR_1.0.0.zip` (all systems)

Text recognition for scanned documents in Research. Runs inside FetchJ (WebAssembly), the same file for every system.

| Part | Version | Licence |
|---|---|---|
| [tesseract.js](https://github.com/naptha/tesseract.js) (`worker.min.js`) | 7.0.0 | Apache-2.0 – [LICENSES/Apache-2.0-tesseract.js.txt](LICENSES/Apache-2.0-tesseract.js.txt) |
| [tesseract.js-core](https://github.com/naptha/tesseract.js-core) (`tesseract-core-*.wasm.js`) | 7.0.0 | Apache-2.0 – [LICENSES/Apache-2.0-tesseract.js-core.txt](LICENSES/Apache-2.0-tesseract.js-core.txt) |
| Trained data `spa`, `eng` ([tessdata](https://github.com/tesseract-ocr/tessdata_best), 4.0.0_best_int) | 4.0.0 | Apache-2.0 |

## FFmpeg – `FetchJ_FFmpeg_1.0.0_windows-x64.zip` (Windows 64-bit)

Only used to put picture and sound of a hearing recording into one .mp4 without re-encoding (`-c copy`).

| Part | Version | Licence |
|---|---|---|
| `ffmpeg.exe` – LGPL build of [BtbN/FFmpeg-Builds](https://github.com/BtbN/FFmpeg-Builds) (`win64-lgpl`) | N-127900-ge2798d5cad (2026-10-21) | LGPL-3.0 – [LICENSES/LGPL-3.0-ffmpeg.txt](LICENSES/LGPL-3.0-ffmpeg.txt) |

**Source code (LGPL):** FFmpeg commit [`e2798d5cad`](https://github.com/FFmpeg/FFmpeg/commit/e2798d5cad) –
https://github.com/FFmpeg/FFmpeg ; build scripts and configuration: https://github.com/BtbN/FFmpeg-Builds .
FetchJ uses `ffmpeg.exe` unchanged as a separate program (it is not linked into FetchJ). The LGPL-3.0 builds on the
GPL-3.0: https://www.gnu.org/licenses/gpl-3.0.txt . On request we send a copy of the corresponding source:
info@fetchj.com.


## Checksums

See `SHA256_addons-1.0.0.txt` in the release.
