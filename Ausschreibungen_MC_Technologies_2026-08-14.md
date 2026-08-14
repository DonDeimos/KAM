# Ausschreibungen-Radar MC Technologies — Woche KW33/2026 (Stand: 14.08.2026)

Betrachtungszeitraum: 07.08.2026 – 14.08.2026 (Publikationsdatum)

## Management Summary

Diese Woche wurden über die **TED-API (EU-Ebene)** 299 neue Ausschreibungen im relevanten CPV-/Volltext-Suchraster veröffentlicht. Die erste Volltextfilterung lieferte 18 Treffer; bei genauerer Prüfung stellte sich heraus, dass der Großteil davon **falsch-positive „IoT"-Treffer** waren (das Kürzel steckt z. B. als Teilstring in polnischen Wörtern wie „Przedmiotem" – „Gegenstand [der Ausschreibung]"). Nach Bereinigung um solche Störtreffer und um reine Bau-/Serviceleistungen ohne Hardwarebezug bleiben **4 Projekte mit belastbarem Bezug zu unserem Portfolio** übrig – alle im Bereich NB-IoT-/Fernauslese-Hardware (Wasserzähler, Straßenbeleuchtung, Prozessmonitoring). Ein Volltreffer davon liegt in Deutschland.

Auf den deutschen nationalen Vergabeplattformen wurde diese Woche erstmals der **RSS-Suchendpunkt von service.bund.de** erfolgreich angesteuert (Parameter `templateQueryString` + `jobsrss=true`), der Bund-, Landes- und Kommunalausschreibungen bündelt. Über ca. 20 Schlagwortvarianten aus allen vier Zielkategorien (Antennen, IoT/Router, Steckverbinder, Kabelkonfektion) konnte im 7-Tage-Fenster **kein zusätzliches Projekt mit direktem Hardwarebezug** identifiziert werden. Vier Treffer zu „Installation von Alarmanlagen und Antennen" betreffen Sicherheitstechnik-Installationsdienstleistungen (Objektschutz/Brandmeldeanlagen), keine RF-/Antennen-Hardwarelieferung – siehe Randnotiz unten. DTVP, evergabe.nrw.de, vergabe.bayern.de, vergabe.niedersachsen.de, had.de, evergabe.berlin.de/vergabe.brandenburg.de und vergabe.rib.de blieben ohne offenen Such-/RSS-Zugang weiterhin nur eingeschränkt automatisiert durchsuchbar (Details siehe technischer Hinweis).

**Empfehlung:** Priorität auf die Ausschreibung des **Wasserverbands Oleftal** (NB-IoT-Ultraschallwasserzähler, Los-/Produktdetails prüfen – direkter Heimatmarkt-Case für IoT-Kommunikationsmodule/Antennen) legen. Die Projekte in Spanien (GIAHSA) und Ungarn (Szerencs) als Referenz für NB-IoT-Fernauslese-Ausschreibungen beobachten, da vergleichbare Losstrukturen künftig auch in DACH zu erwarten sind.

---

## EU-Ebene (TED)

| Projekt | Vergabestelle | Land | Budget | Deadline | Einschätzung |
|---|---|---|---|---|---|
| [Suministro de dispositivos de telelectura de contadores de agua con NB-IoT integrado](https://ted.europa.eu/en/notice/-/detail/557776-2026) | Comisión Ejecutiva de Gestión Integral del Agua de Huelva (GIAHSA) | ES | k. A. | k. A. | NB-IoT-Wasserzähler-Fernauslesesystem inkl. Telekom-Dienste und Cloud-Plattform – Bedarf an NB-IoT-Kommunikationsmodulen/Antennen für die Zählerknoten. |
| [Közvilágítás korszerűsítés Szerencsen (Straßenbeleuchtungsmodernisierung mit NB-IoT)](https://ted.europa.eu/en/notice/-/detail/561520-2026) | Stadt Szerencs (Önkormányzata) | HU | k. A. | 11.09.2026 | Smart-City-Modernisierung der Straßenbeleuchtung mit NB-IoT-Steuerung – klassischer Smart-City-Hardware-Case, Bedarf an Funkmodulen/Antennen je Lichtpunkt. |
| [Sistem informatic integrat de monitorizare operațională](https://ted.europa.eu/en/notice/-/detail/561904-2026) | Exploatare Sistem Zonal Prahova SA | RO | 12.666.667 RON | 24.09.2026 | Integriertes Fernwirk-/Monitoring-System (Ausrüstung für Datenübertragung, IoT-Bezug) für ein Fernwärme-/Versorgungsnetz – Bedarf an M2M-Routern und Sensorknoten wahrscheinlich; Neuveröffentlichung/Korrektur einer bereits am 07.08. publizierten Fassung (Pub-Nr. 548162-2026). |

## DACH (nationale Ebene)

| Projekt | Vergabestelle | Land | Budget | Deadline | Einschätzung |
|---|---|---|---|---|---|
| [Lieferung von Ultraschallwasserzählern mit NB-IoT-Kommunikationseinheit und Datenverarbeitungssoftware](https://ted.europa.eu/en/notice/-/detail/554520-2026) | Wasserverband Oleftal | DE | k. A. | k. A. (Ausschreibungsunterlagen prüfen) | Direkter Volltreffer: NB-IoT-Kommunikationseinheiten für Wasserzähler – Bedarf an GNSS-/NB-IoT-Antennen sowie M12-Steckverbindern/Kabelkonfektion für die Zähler-Sensorknoten. Deutscher Heimatmarkt, daher hohe Priorität. |

**Randnotizen ohne direkten Handlungsbedarf diese Woche** (Sicherheitstechnik-Installationsdienstleistungen, kein Hardware-Lieferbezug zu unserem Portfolio, aber als Marktbeobachtung vermerkt):

- **Schulprojekt Kardinal-von-Galen-Schule, Stadt Harsewinkel** – Elektroinstallation Schwachstrom/Sicherheitstechnik inkl. Alarmanlagen und Antennen (Objektschutz, keine RF-Antennenlieferung).
- **SLUB Interim Haus F, Dresden** (Staatsbetrieb SIB) – Installation von Alarmanlagen und Antennen, Angebotsfrist 16.09.2026.
- **Automatisches Fahrgastzählsystem (AFZS), MOIN Mobilitätsinfrastruktur Landkreis Lüneburg** – Antennenerwähnung im Kontext eines Fahrgastzählsystems für Busse, Angebotsfrist 14.09.2026; ggf. für Folgeausschreibungen (Kommunikationshardware) im Blick behalten.

**Technischer Hinweis:** service.bund.de bietet unter `Content/DE/Ausschreibungen/Suche/Formular.html` einen öffentlichen RSS-Export (`jobsrss=true`), der Bund-, Landes- und Kommunalvergaben (importiert aus eVergabe, DTVP, Healy Hudson, VMP-VPBW u. a.) bündelt und künftig für die Automatisierung genutzt werden kann. Eine gezielte Volltextsuche direkt auf DTVP, evergabe.nrw.de, vergabe.bayern.de, vergabe.niedersachsen.de, had.de, evergabe.berlin.de/vergabe.brandenburg.de sowie vergabe.rib.de war ohne Konto/kostenpflichtigen Benachrichtigungsdienst weiterhin nicht zuverlässig automatisierbar; für lückenlose Abdeckung dieser Länder-Portale empfiehlt sich weiterhin ein bezahltes Suchprofil mit E-Mail-Benachrichtigung.
