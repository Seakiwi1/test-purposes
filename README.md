## Requirements

Die Webapplikation soll alle erstellen Pendenzen, mit dem Datum der Erstellung, der Pendenzart, dem zugewiesenen Mitarbeiter und dem aktuellen Status, in einer Liste ausgeben.

Die Liste soll mit verschiedenen Filter- und Suchfunktionen, genauer gesagt Filter für einen bestimmten Zeitraum der Erstellung, der Pendenzart, dem Mitarbeiter und des aktuellen Status. 

Ebenso soll eine Suche nach Kunden möglich sein.

In der Webapplikation können keine Änderungen gemacht werden, es findet lediglich eine Ausgabe statt, welche durch Filter manipulieren ist.

Der Standardfilter ist "Alle", hierbei werden alle Pendenzen in je 25 Pendenzen pro Seite aufgeteilt und ausgegeben, startend mit den Neusten.

Die Zugriffskontrolle findet über die, bereits im GAMS integrierte, Benutzerverwaltung statt. Diese wird nicht im Zuge dieser Webapplikation erweitert.

Die Zugangsdaten zu Datenbanken und Servern werden uns zur Verfügung gestellt.

Die Umsetzung der Webapplikation erfolgt mithilfe von HTML5, CSS3, PHP und Symfony und wird auf einem Server, mit dem Betriebssystem Windows Small Business Server 2003, eingepflegt.