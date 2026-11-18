# Forge DSP Community

Freie Software für die Forge-DSP-Geräte von Mark Duprau (Forge Audio, 2011–2021) und den baugleichen ETON CORE D8:
96ELN, 96ELN-3 und 96LN.

| Repo | Inhalt |
|---|---|
| [firmware](https://github.com/forge-dsp-community/firmware) | Firmware in C (avr-gcc/PlatformIO), protokollkompatibel zur BASCOM-Firmware 1.11.6000, flashbar über den vorhandenen Bootloader chip45boot3. Dazu Hardware-Doku in [`docs/`](https://github.com/forge-dsp-community/firmware/tree/main/docs) und ein [Wiki](https://github.com/forge-dsp-community/firmware/wiki) als Übersicht. |
| [gui](https://github.com/forge-dsp-community/gui) | Bedienoberfläche: [Web-GUI im Browser](https://forge-dsp-community.github.io/gui/) (Web Serial), Android-App für Headunits, Desktop-Pakete und ESP32-WLAN-Bridge. Firmware-Update direkt aus der GUI. |
| [hardware](https://github.com/forge-dsp-community/hardware) | KiCad-Entwürfe: Aufsatzplatine als Modulsteckplatz und Einschubmodule (Bluetooth, CAN). Entwurf, noch nicht gefertigt. |

## Loslegen

1. GUI öffnen: im Browser (Chrome/Edge) unter https://forge-dsp-community.github.io/gui/ oder als App aus den
   [Releases](https://github.com/forge-dsp-community/gui/releases/latest).
2. Forge per USB anstecken und verbinden.
3. Firmware-Update in der GUI; welche Datei zu welchem Gerät passt, steht in der
   [Kompatibilitätstabelle](https://github.com/forge-dsp-community/firmware#kompatibilität).

Fehler und Wünsche bitte als Issue im jeweiligen Repo.
