# The Plan

## Steps
1. Ziel und Scope festlegen: Definieren, welche lokalen Netzwerkinfos (z. B. IP, SSID, Signalstärke) sowie Kamera-/Mikrofon-Metadaten übertragen werden sollen, und klar ausschließen, dass Rohbild/-audio ohne explizite Zustimmung gesendet wird.  
2. Plattform entscheiden: Für eine echte Headless-App auf dem Handy Android als primäre Zielplattform wählen (Foreground Service + optional unsichtige UI nur für Berechtigungs-Setup).  
3. Sicherheits- und Datenschutzkonzept erstellen: Zustimmung, minimale Datenerhebung, lokale Verarbeitung, klare Datenschutzhinweise, und HTTP nur im lokalen Netz oder besser HTTPS/WSS.  
4. Kommunikationsdesign definieren: Datenmodell für Statusmeldungen festlegen und Push-Mechanismus zum Browser bestimmen (WebSocket oder Server-Sent Events statt Polling).  
5. App-Architektur planen: Service für Erfassung, Kommunikationsmodul für Streaming, Berechtigungsmanager, und robustes Fehler-/Reconnect-Handling bei Netzwechseln.  
6. Browser-Seite planen: Kleine Weboberfläche mit Live-Status, Verbindungszustand, Zeitstempeln und Warnungen bei fehlenden Berechtigungen/Hardware.  
7. Berechtigungs- und Laufzeitverhalten absichern: Android Runtime Permissions, Hintergrundbetrieb, Energiespar-Restriktionen, und Nutzerfluss für erstmalige Freigaben definieren.  
8. Testplan aufstellen: Tests für WLAN-Wechsel, App-Neustart, Bildschirm aus, fehlende Kamera/Mikrofon-Hardware, Permission-Entzug und unterschiedliche Browser im selben LAN.  
9. Rollout und Betrieb: Logging, einfache Diagnoseansicht, Versionsstrategie und klare Grenzen dokumentieren (was die App sammelt, wann sie sendet, wie sie gestoppt wird). 
