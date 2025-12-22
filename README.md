# evcc-charge-settings
evcc-charge-settings stellt eine einfache Weboberfläche bereit, mit der sich die Schwellwerte von evcc‑Ladepunkten anzeigen und anpassen lassen. Das Projekt bietet eine leichtgewichtige HTML‑basierte Lösung, um Ladeeinstellungen schnell zu visualisieren und ohne Umwege zu ändern.

## Verwendung
1. **Hosten der Datei**: Kopiere `evcc-thresholds.html` auf einen Webserver, der Zugriff auf die EVCC-API hat (z.B. den gleichen Server, auf dem EVCC läuft).
2. **API-URL anpassen**: Öffne `evcc-thresholds.html` in einem Texteditor und passe die Variable `API_BASE_URL` am Anfang des Scripts an deine EVCC-Installation an (z.B. `http://dein-server:7070/api`).
3. **Öffnen im Browser**: Navigiere zu der gehosteten Datei (z.B. `http://dein-server/evcc-thresholds.html`) und verwende die Oberfläche, um Schwellwerte anzupassen.
4. **Ladepunkte auswählen**: Wähle den gewünschten Ladepunkt aus der Dropdown-Liste und stelle die Enable- (PV-Überschuss) und Disable-Schwellwerte (max. Netzbezug) ein. Eine Warnung erscheint, wenn die Werte zu nah beieinander sind, um sofortiges Ausschalten zu vermeiden.

## Funktionen
- Anzeige aktueller Schwellwerte pro Ladepunkt.
- Intuitive Slider zur Anpassung der Schwellwerte.
- Automatische Warnungen bei potenziellen Konflikten.
- Unterstützung für mehrere Ladepunkte.

## Voraussetzungen
- EVCC-Installation mit API-Zugang.
- Webserver zum Hosten der HTML-Datei.

## Lizenz
Siehe LICENSE-Datei.
