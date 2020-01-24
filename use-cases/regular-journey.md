# Use case: Regular journey

Ich fahre regelmäßig von einem Ort zum anderen, z.B. zur Arbeitsstelle und brauche immer wieder die gleiche Verbindung.

Manchmal variieren jedoch die Zeiten geringfügig, da ich vorher noch die Kinder in den Kindergarten bringen muss
und nicht immer klar ist, wann genau ich dort heraus komme.

Auch auf der Rückfahrt ist nicht sicher, dass mich die Arbeit täglich zur genau gleichen Zeit los lässt.

(Aus https://github.com/dbsystel/Bahn-API/issues/7)
Als Pendler möchte ich (regelmässig) Meldungen von Bahnverspätung / -ausfällen ab einer Stunde vor Abfahrt des Zuges über gewohnte Kanäle (WhatsApp, Telegram, & Co) via Bot Gruppen Push-Nachricht bekommen.

Beispiel: Pendler (ca. 50 Personen pro Tag) von Müllheim (79379) mit dem 7:49er Richtung Basel Bad / SBB proaktiv zu informieren.

Warum gewohnte Kanäle / (grosse) Gruppenchats: bei Störungen / Ausfällen können so die betroffenen Pendlergruppen gemeinsam direkt alternative Lösungen besprechen / vorschlagen: Fahrgemeinschaften, alternative Wege, ...

Wird so bereits im Kleinen gelebt - produktiver PoC auf node.js Basis (unter Crawling der Bahnwebseite - ja, ist aktuell laut AGB nicht vorgesehen) ist hier zu finden: https://github.com/joachimprinzbach/db-ontime
