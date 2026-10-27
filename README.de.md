# FetchJ – Download

[Español](README.md) · **Deutsch** · [English](README.en.md)

FetchJ („Fetch Judicial“) lädt alle Dokumente Ihrer Akten aus **Gestión en Línea** des Poder Judicial von Costa Rica auf Ihren Computer, hält sie aktuell und zeigt, was in jeder Akte neu ist.

> **Unabhängiges Produkt – kein Produkt des Poder Judicial.**

Dieses Repository enthält nur, was heruntergeladen wird: das Setup, die Zusätze und diese Hilfe. Der Programmcode ist nicht öffentlich.

---

## Herunterladen

| Was | Wo |
|---|---|
| **FetchJ für Windows** (neueste Version) | [**FetchJ_Setup.exe herunterladen**](https://github.com/fetchj/FetchJ-Public/releases/latest/download/FetchJ_Setup.exe) |
| **Benutzerhandbuch** (PDF) | [Deutsch](https://github.com/fetchj/FetchJ-Public/releases/latest/download/FetchJ_Handbuch_DE.pdf) · [Español](https://github.com/fetchj/FetchJ-Public/releases/latest/download/FetchJ_Manual_ES.pdf) · [English](https://github.com/fetchj/FetchJ-Public/releases/latest/download/FetchJ_Manual_EN.pdf) |
| **OCR-Zusatz** (Texterkennung für die Recherche) | [Release addons-1.0.0](https://github.com/fetchj/FetchJ-Public/releases/tag/addons-1.0.0) → `FetchJ_OCR_1.0.0.zip` |
| **FFmpeg-Zusatz** (Aufnahmen der Verhandlungen als eine .mp4) | [Release addons-1.0.0](https://github.com/fetchj/FetchJ-Public/releases/tag/addons-1.0.0) → `FetchJ_FFmpeg_1.0.0_windows-x64.zip` |

Das ganze Handbuch steht auch in FetchJ: *Hilfe & Info → Benutzerhandbuch* (mit Suche).

Die Zusätze müssen Sie **normalerweise nicht von Hand laden**: FetchJ installiert sie mit einem Klick („OCR-Zusatz installieren“ / „FFmpeg installieren“). Die Zip-Datei ist für Computer ohne Internet oder wenn der Administrator es so will („Aus Datei …“).

Jedes Release enthält eine Datei `SHA256_….txt` mit den Prüfsummen.

## Installieren

1. `FetchJ_Setup.exe` herunterladen und öffnen.
2. Windows zeigt eventuell „Der Computer wurde durch Windows geschützt“ → **Weitere Informationen** → **Trotzdem ausführen** (Testversionen sind noch nicht signiert).
3. Dem Assistenten folgen. Eine neue Version wird über die alte installiert; Akten, Einstellungen und Lizenz bleiben.

**Voraussetzungen:** Windows 10 oder 11 (64 Bit), Internet, ein Konto für Gestión en Línea mit Benutzer, Passwort und Bestätigungscode (2FA).

## Erste Schritte

1. FetchJ starten und wählen, wo die Akten gespeichert werden.
2. **Abgleich starten**. Das Portal-Fenster öffnet sich: Sie melden sich **selbst** an (Benutzer, Passwort, Code).
3. FetchJ liest „Mis expedientes“ und lädt die neuen Dokumente. Spätere Abgleiche holen nur Neues.

## Häufige Fragen

**Speichert FetchJ mein Passwort?** Nein. FetchJ tippt, liest oder speichert nie Benutzer, Passwort oder Code. Sie melden sich im Portal-Fenster selbst an.

**Schickt FetchJ meine Akten irgendwohin?** Nein. Die Dokumente bleiben nur auf Ihrem Computer. FetchJ spricht nur mit dem Portal des Poder Judicial (und, wenn Sie es nutzen, mit Nexus.PJ für die Recherche nach Urteilen).

**Das Portal liefert ein Dokument nicht.** Manche Dokumente scheitern im Portal selbst. FetchJ versucht es bei den nächsten Abgleichen wieder und zeigt sie als „Nicht ladbar“ mit dem Grund.

**Wofür ist der OCR-Zusatz?** Er liest den Text gescannter Dokumente (Bilder) für die Recherche. Ohne OCR liefern Scans keine Stichwörter.

**Wofür ist FFmpeg?** Es fügt Bild und Ton einer Verhandlungsaufnahme zu einer .mp4-Datei zusammen, ohne den Inhalt zu verändern.

## Support

E-Mail: **support@fetchj.com** – in FetchJ: *Hilfe & Info → Support-Daten senden* (ohne Passwörter).
Lizenz: **license@fetchj.com** · Kauf und Preise: **ventas@fetchj.com** · allgemeiner Kontakt: **info@fetchj.com**.

## Lizenzen Dritter

Die Zusätze enthalten freie Software Dritter; Einzelheiten in [ADDONS.md](ADDONS.md) und im Ordner [LICENSES](LICENSES/).

---
Download-Seite 1.1.0 · 22.10.2026
