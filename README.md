# Athanasius Alexandrinus, Contra gentes und De incarnatione

## Edition

Die Transkriptionen und die beiden Edition befinden sich im Ordner `data`. 

**Stand 31.8.2023** ist die Edition von **„Contra gentes“** abgeschlossen und liegt in der Datei `pta0022.pta001.pta-grc1.xml` vor, die Transkriptionen aller Handschriften liegen in den Dateien `pta0022.pta001.pta-MsXX.xml` (wobei `XX` die jeweilige Handschriftensigle ist) vor. Diese Dateien werden nach kleineren, noch durchzuführenden technischen Korrekturen ins [Patristische Textarchiv (PTA)](https://pta.bbaw.de) überführt und sind dann unter der URL <https://pta.bbaw.de/text/urn:cts:pta:pta0022.pta001> zu erreichen.

Die Transkriptionen `pta0022.pta002.pta-MsXX.xml` (wobei `XX` die jeweilige Handschriftensigle ist) und die Edition `pta0022.pta002.pta-grc1.xml` von **„De incarnatione“** stellen einen noch sehr vorläufigen Arbeitsstand dar. Die Weiterbearbeitung ist projektiert. 

Alle vorliegende Transkriptionen und Editionen wurden von Kyriakos Savvidis erstellt.

Dieser Stand hat die [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8377009.svg)](https://doi.org/10.5281/zenodo.8377009).

## Technisches
### Transkriptionsregeln

Die aktuellen Transkriptionsregeln sind am besten hier einzusehen: https://pta.bbaw.de/project/encoding-guidelines.

### Preview-Funktion (für Transkriptionen)

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
