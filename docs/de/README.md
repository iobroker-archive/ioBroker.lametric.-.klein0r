![Logo](../../admin/lametric.png)

# ioBroker.lametric

## Inhaltsverzeichnis

- [Apps](apps.md)
- [Blockly](blockly.md)
- [My Data DIY](my-data-diy.md)
- [Notifications](notifications.md)

## Anforderungen

- nodejs 18 (oder neuer)
- js-controller 5.0.0 (oder neuer)
- Admin Adapter 6.0.0 (oder neuer)
- _LaMetric Time_ mit Firmware _2.3.9_ (_3.1.2_ auf dem 2022er Modell) (oder neuer)

[Firmware-Changelog](https://firmware.lametric.com) [Firmware-Changelog Time2](https://firmware.lametric.com/?product=time2)

## Configuration

Du bekommst deinen Geräte-Schlüssel (API-Key) [hier](https://developer.lametric.com/user/devices).

![api-key](./img/api-key.png)

## Features

- Verändern der Display-Helligkeit (prozentual, Automatik/Manueller Modus)
- Verändern der Lautstärke (prozentual)
- Konfiguration des Bildschirmschoners (aktivieren/deaktivieren, Zeitbasiert, wenn dunkel)
- Bluetooth aktivieren/deaktivieren, Bluetooth Name verändern
- Zwischen Apps wechseln (nächste, vorige, gehe zu spezifischer App)
- Versenden von Notifications (mit konfigurierbarer Priorität, Sound, Icons, Text, ...)
- Kontrolle von speziellen Apps wie `clock`, `radio`, `stopwatch` oder `weather`
- Nutzung der _My Data (DIY)_ LaMetric App um regelmäßig Informationen darzustellen

Alle Funktionen sind nur durch die [offizielle API](https://lametric-documentation.readthedocs.io/en/latest/reference-docs/lametric-time-reference.html) limitiert.
