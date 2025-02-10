# Github-Tutorial
*Eine Einführung in Github - mit einem Schuss Website-Design*
Dieses Tutorial richtet sich an Mitarbeitende und Partner:innen des bologna.labs, die noch keine Erfahrung mit Github haben. Hoffentlich ist es in Ordnung, wenn wir uns für die Zwecke des Tutorials duzen!
In diesem Tutorial lernst du:
* was Github ist, was viele relevante Begriffe wie "Repository" und "Commit" heißen sowie einen Überblick, was man mithilfe von Github machen kann
* wie du mithilfe von Github und einen Quellcode-Editor ein Repository erstellen und bearbeiten kannst
* wie du kollaborativ an einem Repository arbeiten kannst
* wie du mithilfe von *Github Pages* eine öffentliche Webseite mit HTML erstellen und die Texte darin bearbeiten kannst.
* Ein Sneak-Preview, wie du mit CSS und HTML weitere Änderungen zur Struktur deiner Webseite vornehmen kannst.

Während des Tutorials wirst du die Formattierungssprache [Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) nutzen, womit auch dieser Text geschrieben wird. Das benötigt keine spezialisierte Software und ist einfach zu lernen (falls du noch nicht damit auskennst)

In diesem Tutorial lernst du nicht:
* neue, komplizierte Funktionen für deine Website zu programmieren
* Github-Funktionen mit dem Command Prompt (CMD) zu steuern.

### Was du für dieses Tutorial brauchst:
* Ein Konto auf [Github](https://github.com/signup) zu erstellen - vergiss nicht, Zwei-Faktor-Authentifizierung einzurichten.
* [Github for Desktop](https://github.com/apps/desktop) herunterzuladen und zu installieren.
* Den Quellcode-Editor [Visual Studio Code](https://code.visualstudio.com/) (VSCode) herunterzuladen und zu installieren.
* Die VSCode Erweiterung [LiveServer](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) zu installieren (für den Vorschau von Webseiten).

<hr>

## 1. Definitionen

### Was ist Github?
Github ist ein (grundsätzlich) kostenloser Dienst für die gemeinsame Entwicklung von Softwareprojekten. Seine Grundlage ist die Software [Git](https://de.wikipedia.org/wiki/Git), die nichts anderes als ein **Versionsverwaltungsystem** ist.

*Und was ist ein Versionsverwaltungsystem?*

Ein Versionsverwaltungssystem ist eine Herangehensweise, Änderungen in einem Dokument oder größerem Projekt nachzuverfolgen. Viele Software für gemeinsame Dokumentenbearbeitung (z.B. Word, Google Docs, Etherpad) bieten Wege an, Änderungen nachzuverfolgen, aber ein Versionsverwaltungssystem wie Git geht weit darüber hinaus, indem z.B.:
* Änderungen innerhalb von Projekten mit gesamten Ordnern und Unterordnern nachverfolgt werden können
* Änderungen (auch solche, die mehrere Schritte zuvor vorgenommen wurden) immer rückgängig gemacht werden können
* jemand an einer umfangreichen Änderung in einer parallelen „Version“ des Projekts arbeiten kann, während das Hauptprojekt unabhängig davon weiterbearbeitet werden kann. Wenn die Änderung bereit für die Implementierung ist, dann werden alle Änderungen (sowohl die im Hauptprojekt als auch die in der parallelen Version) automatisch (oder fast immer automatisch) miteinander in Einklang gebracht.

### Relevante Begriffe für die Arbeit mit Github
#### Repository
Ein _Repository_ ist ein Ordner, dessen Versionierung verwaltet wird. Das könnte die Quellcode einer Webseite oder Software sein aber auch ein Ordner mit experimentellen Daten, die mithilfe eines Softwares ausgewertet werden oder auch eine Masterarbeit, die mithilfe _LaTeX_ geschrieben wird. Ein Repository hat eine **remote**-Version (im "Cloud", auf der Github-Website), sowie mehrere **lokale** Versionen (z.B. auf deinem Computer). Ein Repository kann auch "gespiegelt" werden (z.B. zu einem Repository in einem anderen Dienst), aber das ist für dieses Tutorial nicht so interessant.

##### Datei-Typen in einem Repository
Das Repository könnte beliebige Unterordner und Dateitypen enthalten (Texte Dateien, Bilder, Videos, PDF, usw.) - aber von der Versionsverwaltung (die auf Zeilenebene der einzelnen Dateien funktioniert) profitieren am meisten **textbasierte Dateien**, z.B. ``.txt.``, ``.html``, ``.css``, ``.json`` usw. Andere Dateien wie z.B. Word-Dateien können nur als ganze Dateien betrachtet werden.

#### Klonen
Um an einem Projekt auf den eigenenen Rechner zu arbeiten musst du ein _remote_-Repository **klonen** - das erstellt eine lokales Repository sowie ein lokales Verzeichnis (local directory) auf deinem Rechner.
