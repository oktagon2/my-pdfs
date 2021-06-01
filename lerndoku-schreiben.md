# Lerndoku schreiben
In diesem Dokument wird ein ganzer Prozess vorgestellt, der schliesslich zu einer guten Lerndokumentation führt.

## Ausgangslage
Lerndoku brauchen wir, um gelernte Theorie zu dokumentieren, schnell wieder zu finden und immer wieder sicher und ohne grossen Zeitverlust anwenden zu können. Dabei muss die Lerndokumentation der Quelle der Theorie angepasst werden.

## Wichtige Dokumente
### Glossar
Hier werden alle fachspezifischen Begriffe erklärt.

### Index
Wir brauchen einen Index, damit wir Rezepte, die wir benötigen, rasch wieder finden.

### Namespaces
Eine Liste aller Namespaces, für die Übersicht. Sonst passiert es leicht, dass wir für ein und denselben Namespace verschiedene Namen haben.

### Protokoll
Wir brauchen ein Protokoll, damit wir belegen können, was wir wann bearbeitet und gelernt haben. Das Protokoll macht man am besten hierachisch

Beispiel
* TicketXpert (Namespace)
  * Hilfe
    * Start
      * Inhalt  
        Kommentar zum Inhalt
      * Erste Schritte
      * Demonstrationssystem
      * Glossar
      * Werkzeuge
      * Kontakt

Wenn man z.B. so ein Protokoll in VS Code im md-Format schreibt, so kann man innerhalb VS Code Details einfach ein- und ausblenden, in dem man am linken Rand mit den v und > Symbolen arbeitet. Das ist sehr praktisch, weil man so das Protokoll übersichtlich oder detailliert anzeigen kann, wie es gearade am besten passt.

### Artefakte
Eine Liste aller Artefakte, die geschaffen wurden. Artefakte sind: Glossar Einträge, Rezepte. Am besten ist es, wenn man Artefakte über einen Link erreicht. Das Tolle ist, dass GitHub in einem MD File jedes Kapitel über einen Link referenzieren kann. Sol lautet z.B. der Link zu diesem Kapitel https://github.com/oktagon2/my-pdfs/blob/master/lerndoku-schreiben.md#artefakte. Klickt man auf diesen Link oder gibt man die URL im Browser ein, so wird sofort dieses Kapitel angezeigt.

### Installationen
Eine Lsite aller Produktio, die installiert wurden.

### Backlog
Eine Liste von Todos, die noch gemacht werden müssen.

## Lerndoku für PDFs
Am optimalsten ist es, wenn die Theorie als PDF vorliegt, weil
* Der Inhalt von PDFs ist stabil und ändert sich nicht, wie z.B. der Inhalt von Web Seiten
* PDFs können mit dem Acrobat Reader einfach markiert und kommentiert werden. Siehe dazu die Arcobat Reader Rezepte.

### Vorgehen
* Rezepte identifizieren
* Titel der Rezepte im Dokument identifizieren und markieren
* Markierung dokumentieren mit 
  *  etwas wie Rezept "GitHub: Clone a repository". Dabei gibt man zuerst den Namensraum vom Rezept an. D.h. für welches Tool oder für welche Programmiersprache oder Library das Rezept gilt. Danach folgt ein Doppelpunkt und ein Titel für das Rezept. Der Titel muss innerhalb vom angegebenen Namensraum verständlich sein. 
  *  u/o Ergänzungen: bla, bla ...
* Rezepte im Index aufnehmen. Bei Rezepten in PDFs gibt man neben dem Titel vom Rezept am besten
  *  entweder die Seite an, wo das Rezept gefunden werden kann
  *  oder noch besser ein Suchstring, mit welchem das Rezept im Dokument gefunden werden kann
