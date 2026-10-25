# Duet Night Abyss Assistent

Begleit-App für **Duet Night Abyss** (Windows): Demon Wedges, Builds, Prioliste, Geniemon-Sammlung und Covert Commissions – mit Hotkey-Erkennung direkt im Spiel. Läuft komplett lokal, ohne Konto und ohne KI-Dienste.

## Download

👉 **[Neueste Version herunterladen](../../releases/latest)** – unter „Assets“ die Datei `DnaAssistant.exe`.

- Keine Installation nötig, einfach starten (eine einzige Datei, kein .NET erforderlich).
- Die App fragt beim Start nach **Administratorrechten**. Das Spiel läuft mit erhöhten Rechten; ohne sie kommen Hotkeys und Bildschirmaufnahme im Spiel nicht an.
- Neue Versionen meldet die App beim Start selbst.
- Windows SmartScreen kann beim ersten Start warnen („Unbekannter Herausgeber“) – über „Weitere Informationen › Trotzdem ausführen“ starten.

## Funktionen

| Bereich | Was es kann |
|---|---|
| **Demon Wedges** | Alle Wedges mit Suche und Filtern (Kategorie, Element, Seltenheit, Polarität, Herkunft); Zähler für +10-Exemplare; Seltenheitsfarbe in der Vorschau. |
| **Kategorien & Ziele** | Wunschmenge pro Kategorie oder einzelnem Wedge (z. B. 1 oder 4), Sortierung nach fertig/offen, Maximalstufe (Gold +10, sonst +5). |
| **Builds** | Import per boarhat-Link/-Code, aus boarhat-Vorlagen oder aus einem Screenshot des Wedge-Sets. Charakter, Nah- und Fernkampfwaffe wählen, Fortschritt wie „3/10 Wedges fertig“, fehlende Wedges mit einem Klick auf die Prioliste, Builds als Link teilen. |
| **Prioliste** | Wedges, die du als Nächstes brauchst – im Spiel per Hotkey (Standard **F7**) einblendbar, mit Herkunft. |
| **Geniemons** | Sammlung je Variante (Miraculous, Ardent, Shiny) mit Wunschmenge, zusammengefasst und aufklappbar. Battle-Pass-Geniemons ohne Limit. |
| **Covert Commission** | Aktuelle Modi aller Regionen, Benachrichtigung mit Ton für deine Modi in deiner Region, Einstellungen per Code teilen. |
| **Aktionslog** | Jede Änderung lässt sich rückgängig machen; **F9** nimmt die letzte Hotkey-Aktion zurück. |

### Hotkey F8 im Spiel

- **Wedge-Detailansicht:** erkennt Wedge, Seltenheit und Stufe und zählt bei Maximalstufe.
- **Geniemon-Ansicht:** zählt die Variante, wenn sie auf Max-Level ist (Lv. 60/60, drei Sterne).
- **Fangen-Bildschirm:** sagt dir, ob du dieses Geniemon noch brauchst.

**Tipps für eine gute Erkennung**

- Spiel im **Fenster- oder randlosen Modus** spielen (im exklusiven Vollbild kann die Aufnahme schwarz sein).
- Am besten die englische Windows-Texterkennung installieren – in einer **Administrator-PowerShell**:
  ```
  Add-WindowsCapability -Online -Name "Language.OCR~~~en-US~0.0.1.0"
  ```

### Autostart (optional)

In den Einstellungen unter **Autostart**:

- **Steam:** die angezeigte Startoption in Steam bei Duet Night Abyss unter *Eigenschaften › Startoptionen* einfügen.
- **Launcher:** Desktop-Verknüpfung „DNA Assistant + Launcher“ erstellen und/oder mit Windows starten.

## Sprachen

Deutsch, English, Français, Español, Italiano, Português, Polski, Türkçe, Русский, Українська, 日本語, 한국어, 简体中文

## Daten & Datenschutz

Alle Daten (Fortschritt, Builds, Einstellungen) bleiben auf deinem PC unter `%LocalAppData%\DnaAssistant`. Online abgefragt werden nur öffentliche Spieldaten von [boarhat.gg](https://boarhat.gg/games/duet-night-abyss/), die Covert Commissions von [dna.marvib.de](https://dna.marvib.de/) und neue App-Versionen hier auf GitHub.

## Probleme oder Ideen?

Gern über [Issues](../../issues) melden – bei Erkennungsproblemen bitte einen Screenshot der betroffenen Ansicht anhängen.

---

Inoffizielles Fan-Projekt, nicht mit den Entwicklern oder Publishern von Duet Night Abyss verbunden.
