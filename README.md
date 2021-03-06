# Boxl Lead-Import API

Boxl Lead-Import ist ein Service zum Import von Leads in BOXL für BHW Partner.
Es werden verschiedene Versionen der Schnittstelle unterstützt.

## HTTP-SOAP Service
Der Service ist unter folgendem Pfad für die jeweils genutzte Version der Schnittstelle erreichbar.
```
https://dunkelboxl.hypoport.de/boxl-hv/service/leadImport/v01
https://dunkelboxl.hypoport.de/boxl-hv/service/leadImport/v02
https://dunkelboxl.hypoport.de/boxl-hv/service/leadImport/v03
```
## Security
Die Schnittstelle ist über HTTPS ansprechbar. Zum Zugriff ist ein gültiges Zertifikat nötig.
Weitere Sicherheitsdetails sind Bestandteil des jeweiligen Anbindungsprojekts.

## Versionen der Schnittstelle
Die WSDL-Dateien und XSD-Dateien (Anfrage und Anwort) finden sich für jede Version der Schnittstelle in einem eigenen Ordner.
Weiterhin enthält der Ordner jeweils einen gültigen Beispiel-Request (SOAP).

###Version 03
Datum: 02.06.2016
- neues Element: importMitteilenAktiv (Lead-Import an BHW kommunizieren), Element ist optional (default: true)

###Version 02
Datum: 26.06.2015
- neues Element: kunde.geburtsDatum

###Version 01
Datum: 26.06.2015
- initiale Version
