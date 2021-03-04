# Athanasius Alexandrinus, Contra gentes und De incarnatione

## Transkriptionen und Edition

Die Transkriptionen und die Edition sind im Ordner `data`.

### Transkriptionsregeln

Die aktuellen Transkriptionsregeln sind am besten hier einzusehen: https://pta.bbaw.de/pta/project/encoding-guidelines.

## Preview-Funktion

- Python3: Mit Hilfe des Skriptes `server.py` kann ein Webserver gestartet werden:

> Programm `Terminal` starten. Dort dann eingeben: `python server.py`. 
> Ein Webserver startet, der im Browser unter der Adresse `localhost:8080` zu erreichen ist.

Im Browser erscheint nun (nach Klicken auf `preview.html`) die Transkription der aktuell geladenen Datei. 

- Python2

> Programm `Terminal` starten. Dort dann eingeben: `python -m SimpleHTTPServer`. 
> Ein Webserver startet, der im Browser unter der Adresse `localhost:8080` zu erreichen ist.

Im Browser erscheint nun (nach Klicken auf `preview.html`) die Transkription der aktuell geladenen Datei. 

- VS Code

Mit Hilfe der Extension »Live Server Preview« (negokaz.live-server-preview) kann die Datei `preview.html` im Editor angezeigt werden: 

*Command Palette* (Taste: `F1`) -> `Show Live Server Preview` 

Zum Aufrufen einer anderen Datei bitte mit einem Texteditor die Datei `preview.html` öffnen und dort in Z. 10

```  let selectedFile = "data/pta0022.pta001.pta-ms44.xml" ```

den entsprechenden Dateinamen ändern. Die Browserseite anschließend neu laden.

In der Preview werden die Nomina sacra in der abgekürzten Form angezeigt; die Auflösung kann per *mouseover* angezeigt (und wieder versteckt) werden. Bei Textersetzungen werden sowohl der gelöschte als auch der eingefügte Text angezeigt; durch Klicken kann der gelöschte Text ausgeblendet werden.