# Bahn-API

Wir überlegen hier gemeinsam, wie eine optimale API für Mobilität aussehen würde und bauen diese dann auch Stück für Stück auf.

Dazu sammeln wir unter anderem [Datenquellen](data-sources.md).

Wir beginnen mit der Sicht von Menschen, die von einem Punkt A an einen anderen Ort B kommen wollen. Es muss eine Route berechnet werden, auf der z.B. Störungen auftreten, was die Routenberechnung beeinflussen könnte.

Relevant ist auch die Auslastung der Verkehrsmittel, die bewirken kann, dass ich z.B. einzelne Verbindungen nicht nutzen kann oder möchte

## Was sind Orte?

- Adressen von Start und Ziel, Straße, PLZ, Ort
- Geo-Koordinaten
- Bahnhöfe, Haltestellen
- Taxistände
- Car-Sharing-Stationen
- Leih-Fahrrad-Stationen

## Wie ist eine Route definiert?

Eine Route ist eine Liste von Orten, an denen z.B. das Verkehrsmittel gewechselt wird.

## Was ist eine Störung?

- Verspätung
- Ausfall des Verkehrsmittels
- Ersatzverkehr
- Ausfall Klimaanlage / Bordrestaurant / ...
