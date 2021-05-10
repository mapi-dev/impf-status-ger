# COVID-19 Impffortschritt
Das PHP-Skript erstellt automatisiert eine Übersichtsgrafik zum aktuellen Impffortschritt in Deutschland.
Die Daten werden durch das Robert Koch-Institut und das Bundesministerium für Gesundheit täglich aktualisiert bereitgestellt. (https://impfdashboard.de/daten).
Übersichtsgrafik wird täglich auf Twitter gepostet bei [@ImpfStatusGER](https://twitter.com/ImpfStatusGER).

Der Source-Code ist zeitnah hier öffentlich zugänglich.

Zu erreichen per DM auf Twitter unter [@ImpfStatusGER](https://twitter.com/ImpfStatusGER).

## FAQ

**Was bedeutet das Datum der Herdenimmunität?**

Vollimpfung (zwei Impfdosen oder eine Impfdosis J&J) für 80% der Bevölkerung. 


## Changelog

**10.05.21:**
  * Anpassung bei der Berechnung des Datums zur Herdenimmunität: RKI geht jetzt von 80% aus (https://www.pharmazeutische-zeitung.de/das-ziel-sind-jetzt-80-prozent/)

**01.05.21:**
  * Veränderung der Semantik der Prozentzahl: Bisher zeigt die Prozentzahl den Fortschritt der Impfungen bezogen auf die Gesamtzahl der zu verimpfenden Dosen. Dabei wurde generell von zwei Impfdosen pro Person für die Schutzwirkung ausgegangen und angenommen dass 11,5% der verimpften Dosen als Einmalimpfung von Johnson & Johnson durchgeführt werden (Anteil laut den veröffentlichten Lieferprognosen von BMI aus April 21). 
  * Die Prozentzahl bezieht sich nun aber auf die Bevölkerung und beantwortet die Frage: Wie viel Prozent der Bevölkerung wurden an diesem Tag geimpft?
  * Visuelle Anpassung der Grafik: Bevölkerungsicon hinzugefügt

**28.04.21:**
  * Bugfixing: Anpassung der visuellen Darstellung des Wertes 'Fortschritt zum Vortag'. Mehr als 1 Millionen Impfungen pro Tag? Damit hat das Skript nicht gerechnet :-)

**09.04.21:**
  * Anordnung der Zahlenwerte für 'Verabreichte Dosen' und 'Fortschritt zum Vortag' auf eine vertikale Linie angepasst
  * Johnson & Johson Impfdosis zählt im Fortschrittsbalken als Zeitimpfung (Vollimpfung)

**28.02.21:**
  * Anpassung und Verbesserung der Grafik in Anlehnung an alte Darstellung

**27.02.21:**
  * Berücksichtigung der Unterscheidung zwischen Erst- und Zweitimpfung
  * Vereinfachung der Visualisierung
  
**31.01.21:**
  * Anpassung der Berechnung für das aktuelle Datum der Herdenimmunität (Sonntage werden mitgezählt)
 
**23.01.21:** 
  * Inital version

## Links
* [Twitter Account - @ImpfStatusGER](https://twitter.com/ImpfStatusGER)
* [Datensätze zu täglich verabreichten Impfungen vom RKI](https://impfdashboard.de/daten)
* [Übersicht zu Liefermengen von Impfstoffdosen vom BMG](https://www.bundesgesundheitsministerium.de/coronavirus/faq-covid-19-impfung.html)
