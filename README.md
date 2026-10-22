# Wetterstation Langenlois

PWA mit Live-Messwerten der TAWES-Station Langenlois (GeoSphere Austria), PV-Prognose für die eigene Anlage und Entscheidungshilfe für Speicher, Auto und große Verbraucher. Ziel: kein Netzbezug.

Live: https://astasik.github.io/sonne-langenlois/

- **Jetzt:** PV-Leistung aus der gemessenen Globalstrahlung der Station, umgerechnet auf die Modulneigung, mit Ampel für große Verbraucher.
- **Speicher → Auto:** stündliche Akku-Simulation bis übermorgen früh; zeigt die größte Menge, die ohne Netzbezug ins Auto kann.
- **PV-Prognose 24 h:** Open-Meteo (Strahlung auf Modulebene), durch die Stationsmessung der letzten Stunden korrigiert.
- Anlagendaten (kWp, Ausrichtung, Neigung, Speicher, Grundlast) in der App unter „Anlage einstellen“; gespeichert lokal im Browser.
- Station wird über den Namen gesucht; per `?station=ID` fix setzbar.

Daten: GeoSphere Austria TAWES (CC BY 4.0), Open-Meteo.com (CC BY 4.0).
