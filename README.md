# Aufgabe
Erstellen sie einen Rest-Service der Endpoints zum Verwalten einer TODO-Liste bereitstellt. Die einzelnen TODO-Einträge sollen dabei mindestens folgende Eigenschaften besitzen:
* Beschreibung (Max 100 Zeichen)
* Erledigungsdatum (DD.MM.YYYY)
* Es sollen maximal 10 Einträge gespeichert werden dürfen
* Die TODO-Einträge sollen auf einer Webseite dargestellt werden und dem Nutzer folgende Aktionen ermöglichen:
  * Anlegen eines Eintrags
  * Update eines Eintrags
  * Anzeige aller Einträge
  * Löschen eines Eintrages
  
# Hinweise
Verwenden Sie zur Umsetzung der Aufgabe folgende Technologien
* Quarkus in Version 2.7
* JavaEE, Jax-RS
* Swagger-Ui zur Visualisierung der APIs

Rahmenbedingungen
* Es ist ausreichend, wenn der Service alle Werte „in Memory“ zur Laufzeit speichert.
* Für alle individuell erstellten Klassen sollen Unittests geschrieben werden. Rest-Services sollen mit Rest-Assured getestet werden.
* Für das Anlegen eines Eintrages muss keine GUI gebaut werden. Dies kann via Swagger-Ui oder Postman erfolgen. Ein entsprechender Endpunkt muss also vorhanden sein.
