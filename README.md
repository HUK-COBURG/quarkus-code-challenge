# Aufgabe
Erstellen Sie einen Rest-Service der Endpoints zum Verwalten eines Warenkorbs bereitstellt. Die einzelnen Produkt-Einträge sollen dabei mindestens folgende Eigenschaften besitzen:
* Name d. Produkts (Max 100 Zeichen)
* Datum des Eintrags (DD.MM.YYYY)
* Es sollen max. 10 Einträge gespeichert werden dürfen
* Folgende Aktionen sollen über den Rest-Service möglich sein:
  * Anlegen eines Eintrags
  * Anzeige aller Einträge
  * Update eines Eintrags
  * Löschen eines Eintrages
  
# Hinweise
Verwenden Sie zur Umsetzung der Aufgabe folgende Technologien
* Quarkus in Version 3.30.5
* JavaEE, Jakarta-RS
* Swagger-Ui zur Visualisierung der APIs

Rahmenbedingungen
* Es ist ausreichend, wenn der Service alle Werte „in Memory“ zur Laufzeit speichert.
* Für alle individuell erstellten Klassen sollen Unittests geschrieben werden. Rest-Services sollen mit Rest-Assured getestet werden.
* Für das Anlegen eines Eintrages muss keine GUI gebaut werden. Dies kann via Swagger-Ui oder Postman (o.ä.) erfolgen.
* Der Rest-Service soll ausschließlich mit Json arbeiten
