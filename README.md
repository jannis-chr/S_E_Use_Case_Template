## S_E_Use_Case_Template
**Anwendungafall: UC 1.01 (Probandin anlegen)**

### Name/Identifikationsnummer:
Name der Proband:innen wird abgefragt und eine ID Nummer vergeben
### Beschreibung:
Diagnosiker:in frägt den Namen der Probandinnen ab, trägt diesen ein und legt damit einen Testvorgang an die ID-Nummer wird automatisch vergeben 
### Beteiligte Akteure:
- Diagnostiker:in 
- Proband:in 

### Status:
in Arbeit
### Verwendete Anwendungsfälle:

### Auslöser:
Dringlichkeit eines standartisierten Leistungstests
### Vorbedingungen:
Start des Programms
### Invarianten:
Speicherung des Namens mit der vergebenen ID-Nummer
### Nachbedingungen/ Ergebnis:
Das Fenster zum Anlegen der Probanden wird nach der Bestätigung automatisch geschlossen
### Standardablauf:
1. Der Name wird eingetragen
2. Eine ID-Nummer wird vergeben 
3. Das Fenster wird automatisch geschlossen
### Alternative Ablaufschritte:
Falls kein Buchstabe eingegeben wird (Zahl,Sonderzeichen) kann das Fenster nicht geschlossen werden (Fehlermeldung)
### Hinweise:
Falls Proband:innen öffters zum Test kommen, könnte man parallel zur Namenseingabe eine Abfrage in der Bibliothek vornehmen und somit passend zum Namen und der schon vergebenen ID-Nummer mehrere Test unter demselben Namen/ID abspeichern. Dafür bräuchte man aber mehr Informationen wie z.B Testdatum oder Geburtsdatum der Proband:innen um Verwechslungen auszuschließen zudem müsste man auch ID-Nummer des Probanden und ID-Nummer des Tests dann unterteilen. 
### User Stories:
[Unter diesem Link](https://github.com/users/jannis-chr/projects/3/views/1)
### Änderungsgeschichte:
*0.1 , Jannis Pohl , 18.03.2024*
