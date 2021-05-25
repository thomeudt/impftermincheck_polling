# UI Vision RPA Script für impfterminservice.de

Impfterminservice.de erscheint nicht nur auf den ersten Blick eine Zumutung für die arbeitende und homeschoolende Bevölkerung zu sein, da man quasi manuell (per Mausklick) einen Service "pollen" muss, um überhaupt die Möglichkeit zu haben, als impfberechtigter Bürger einen Termin anzufragen.

Dieses Script für UI.Vision RPA (ein UI Testwerkzeug) automatisiert diesen regelmäßigen Mausklick solange, bis zumindest die Prüfung auf einen Impftermin wieder möglich ist. Um den Server zu schonen, ist zwischen jedem Polling-Request eine Wartezeit von 60 Sekunden eingebaut.

# How To 

 1. UI.Vision RPA herunterladen (für Chrome oder Firefox, https://ui.vision/)
 2. UI.Vision RPA starten und impftermincheck_116117.json importieren
 3. Imptermin-Service Website öffnen, hier ggfs. die Postleitzahl auf Euer Impfzentrum vor Ort anpassen https://229-iz.impfterminservice.de/impftermine/service?plz=72072
 4. Makro in UI.Vision RPA auführen (Start Button)

Es wird so lange gepolled, bis die Warnmeldung "Es wurden keine freien Termine in Ihrer Region gefunden." nicht mehr erscheint. Alle weiteren Schritte müssen danach manuell ausgeführt werden.

Das man eine Impfberechtigung haben sollte, bevor man sich um einen Impftermin bemüht, sollte selbstverständlich sein.
