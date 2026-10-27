# FetchJ – Download

[Español](README.md) · [Deutsch](README.de.md) · **English**

FetchJ („Fetch Judicial“) downloads all documents of your cases from **Gestión en Línea** of the Poder Judicial of Costa Rica to your computer, keeps them up to date and shows what is new in each case.

> **Independent product – not a product of the Poder Judicial.**

This repository holds only what is downloaded: the installer, the add-ons and this help. The program code is not public.

---

## Download

| What | Where |
|---|---|
| **FetchJ for Windows** (newest version) | [**Download FetchJ_Setup.exe**](https://github.com/fetchj/FetchJ-Public/releases/latest/download/FetchJ_Setup.exe) |
| **User manual** (PDF) | [English](https://github.com/fetchj/FetchJ-Public/releases/latest/download/FetchJ_Manual_EN.pdf) · [Español](https://github.com/fetchj/FetchJ-Public/releases/latest/download/FetchJ_Manual_ES.pdf) · [Deutsch](https://github.com/fetchj/FetchJ-Public/releases/latest/download/FetchJ_Handbuch_DE.pdf) |
| **OCR add-on** (text recognition for Research) | [Release addons-1.0.0](https://github.com/fetchj/FetchJ-Public/releases/tag/addons-1.0.0) → `FetchJ_OCR_1.0.0.zip` |
| **FFmpeg add-on** (hearing recordings as one .mp4) | [Release addons-1.0.0](https://github.com/fetchj/FetchJ-Public/releases/tag/addons-1.0.0) → `FetchJ_FFmpeg_1.0.0_windows-x64.zip` |

The whole manual is also inside FetchJ: *Help & info → User manual* (with search).

You **normally do not need to download the add-ons by hand**: FetchJ installs them with one click („Install OCR add-on“ / „Install FFmpeg“). The zip file is for computers without internet or when the administrator prefers it („From file …“).

Every release has a `SHA256_….txt` file with the checksums.

## Install

1. Download `FetchJ_Setup.exe` and open it.
2. Windows may show „Windows protected your PC“ → **More info** → **Run anyway** (test versions are not signed yet).
3. Follow the wizard. A new version installs over the old one; your cases, settings and licence stay.

**Requirements:** Windows 10 or 11 (64-bit), internet, a Gestión en Línea account with user name, password and verification code (2FA).

## First steps

1. Start FetchJ and choose where the cases are stored.
2. **Start update**. The portal window opens: you log in **yourself** (user, password, code).
3. FetchJ reads „Mis expedientes“ and downloads the new documents. Later updates only fetch what is new.

## Frequently asked questions

**Does FetchJ store my password?** No. FetchJ never types, reads or stores user name, password or code. You log in yourself in the portal window.

**Does FetchJ send my cases anywhere?** No. The documents stay on your computer only. FetchJ talks only to the portal of the Poder Judicial (and, if you use it, to Nexus.PJ for the research of judgments).

**The portal does not deliver a document.** Some documents fail in the portal itself. FetchJ tries again in the next updates and shows them as „Not downloadable“ with the reason.

**What is the OCR add-on for?** It reads the text of scanned documents (images) for Research. Without OCR, scans give no keywords.

**What is FFmpeg for?** It joins picture and sound of a hearing recording into one .mp4 file without changing the content.

## Support

E-mail: **support@fetchj.com** – in FetchJ: *Help & Info → Send support data* (no passwords).
Licence: **license@fetchj.com** · purchase and prices: **ventas@fetchj.com** · general contact: **info@fetchj.com**.

## Third-party licences

The add-ons contain free third-party software; details in [ADDONS.md](ADDONS.md) and the folder [LICENSES](LICENSES/).

---
Download page 1.1.0 · 22/10/2026
