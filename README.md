# WiseQ voorraadmonitor - publieke weergave

De publieke weergave van WiseQ's voorraadmonitor.

**Wat hier staat:** de analyse. Hoeveel producten er zijn, hoe de dekking over de
maanden verdeeld is, hoe de risicoklassen eruitzien, welke artikelen als bundel
worden verkocht en wat er aan de data ontbreekt.

**Wat hier niet staat:** voorraad per artikel, inkoopprijzen, leveranciers, het
besteladvies en de cijfers uit het magazijn. Die zijn intern.

Een bundel heeft geen eigen voorraad: hij bestaat uit losse artikelen, en het aantal
dat op te bouwen is valt is het schaarste onderdeel.

## Op deze pagina

| Bestand | Wat het is |
| --- | --- |
| `index.html` | het dashboard zelf - één pagina, geen netwerk nodig |
| `schema.md` | het datamodel: tabellen, relaties en de maten (DAX) |
| `measure_catalog.csv` | elke maat met zijn DAX, formaat en uitleg |

## Verificatie

De pagina is een momentopname. De broncode, de werkboeken en de berekeningen staan in
een privérepository; deze repository bevat alleen de publieke uitvoer.
