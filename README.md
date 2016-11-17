#Warum Git?

Die Entwicklung von Git ist eine Erfolgsgeschichte. Als [Linus Torvalds](https://de.wikipedia.org/wiki/Linus_Torvalds) 2005 die Entwicklung von Git initiierte lag dem ein ganz pragmatisches Problem zugrunde: Als Verwalter der Entwicklung des [Linux-Kernels](https://www.kernel.org/) benötigte er ein mächtiges, verteiltes und kollaboratives Werkzeug zur Versionsverwaltung von Quellcode. Das zuvor verwendete proprietäre Tool bot keine Möglichkeit der kostenlosen Verwendung und die kostenfreien Alternativen genügten den Anforderungen von Torvalds nicht. Die Idee ein eigenes, freies Softwareprodukt zu schreiben war geboren. Seitdem wurde Git von Jahr zu Jahr populärer und hat eine ganze Reihe auf Git aufsetzender Anwendungen (etwa *Sourcetree* und *GitHub Desktop*) und Webplattformen (etwa *GitHub* und *Bitbucket*) hervorgebracht. Doch warum wird Git so vielfach verwendet?

 - **Paralleles Arbeiten**: Git erlaubt es mehreren Entwicklern parallel und dezentral an einem Projekt (*repository*) in verschiedenen Entwicklungszweigen (*branches*) zu arbeiten. Der eigentliche Clou liegt dabei darin, dass Git eine ganze Reihe an Möglichkeiten (*merge*, *rebasing*, *cherry picking*, etc.) bietet diese
   Entwicklungszweige auch wieder zusammenzuführen.
   
 - **Flexibilität**: Es ist möglich verschiedenste Arbeitsweisen und Arbeitsmodelle (*workflows*) in Git zu realisieren. So eignet sich Git für die lokale Verwendung bei einem einzelnen Entwickler bis zur servergestützten Teamarbeit in einem internationalen Softwarekonzern. In gewisser Art und Weise baut man sich auf der
   Basis von Git seine eigene Versionsverwaltung auf.
   
 - **Einfache Beiträge**: Git macht es vergleichsweise einfach zu einem Projekt beizutragen bei dem man weder der Besitzer noch Teil des Kernteams ist. Bei zentralen Versionsverwaltungssystemen steht hier oft die Rechteverwaltung im Weg, doch erlaubt Git das einfache Kopieren (*clone*) des Quellcodes von einem gefolgten Änderungsvorschlag (*pull request*).
   
 - **Performance**: Selbst bei sehr großen Projekten bleibt Git schnell. Auf meinem *MacBook Air* (11 Zoll) konnte ich von einer aktuellen Version des Quellcodes des Linux-Kernels auf eine sechs Jahre alte Version
   von 2010 unter einer Minute wechseln. Das mag zunächst gar nicht so beeindruckend klingen, doch man sollte bedenken das hier etwa 40.000 Dateiänderungen vorlagen!
   
 - **Robustheit**: Aufgrund der Architektur von Git ist ein gravierender Datenverlust sehr unwahrscheinlich. Prüfsummen verhindern eine unbeabsichtigte Korruption von Daten, der dezentrale Aufbau sorgt
   dafür, dass der Code auf mehreren Rechnern vorliegt und die einfache Datenstruktur sorgt für die Interpretierbarkeit der Daten. Schlussendlich erlaubt die Versionierung und Verzweigung des
   Quellcodes wieder zu einem funktionierenden Stand zurückzukehren.
   
 - **Offsite und Offline**: Die dezentrale und zugleich verknüpfbare Struktur von Git erlaubt sowohl die Arbeit mit verteilten Entwicklungsteams als auch – zumindest eine gewisse Zeit lang – die Arbeit ohne Zugriff auf den Server.
   
 - **Erweiterbarkeit und Integrationsfähigkeit**: Git ist nahezu beliebig erweiterbar und integrierbar. Es ist offen für individuelle Anwendungen und Zusammenarbeit mit nahezu jeder belieben anderen Software.
   
 - **Gemeinschaft und Freiheit**: Git ist nicht nur kostenlose, sondern auch
   [freie Software](https://de.wikipedia.org/wiki/Freie_Software). Das heißt der Quellcode steht offen bereit und Mitarbeit ist sogar erwünscht. Verletzungen des Urheberrechts oder rechtliche Konflikte
   sind ausgeschlossen. Darüber hinaus existiert ein nahezu riesiges Ökosystem aus Dokumentationen und Erklärungen, Tools, Plattformen, Dienstleistern sowie Plug-Ins. Hinsichtlich des gemeinschaftlichen
   Aspekts sei GitHub hervorgehoben, welches sich in den letzten Jahren zum Code-Graphen entwickelt hat wie sich auch Facebook einige Jahr vorher zum (http://www.businessinsider.com/explainer-what-exactly-is-the-social-graph-2012-3)[Social-Graphen] entwickelt hatte. Hier findet man abertausende Entwickler und deren Softwareprojekte. Dies erlaubt die offene, kollaborative und kosmopolitische Entwicklung von Software sowie die Vernetzung der Entwickler.

Klingt gut? Aber wie anfangen? Die ersten Anlaufstellen sollten die offizielle Website von [Git](https://git-scm.com/) sowie die (kommerziellen) Implementationen [GitHub](https://github.com/) und [Atlassian](https://bitbucket.org/) sein. Dort findet ihr eigentlich alle Anleitungen und Tools, welche ihr benötigt, um loszulegen.

Wer eine etwas detaillierte und geführte Einleitung zu GitHub sucht, sollte ein Blick auf [den entsprechenden Kurs von Jan](http://www.lernmoment.de/einstieg-github/) werfen.
