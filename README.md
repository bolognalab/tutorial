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

<hr>

## 1.Fragen und Definitionen

#### *Was ist Github?*
Github ist ein (grundsätzlich) kostenloser Dienst für die gemeinsame Entwicklung von Softwareprojekten. Seine Grundlage ist die Software [Git](https://de.wikipedia.org/wiki/Git), die nichts anderes als ein **Versionsverwaltungsystem** ist.

#### *Und was ist ein Versionsverwaltungsystem?*
Stell dir vor, Anna A. hat den ersten Entwurf eines langen Dokuments entworfen (z.B. eines wissenschaftlichen Artikels) und möchte Feedback von ihren Kollegen Max und Moritz holen. Es gibt drei Möglichkeiten, wie Anna damit umgehen könnte:
1. Anna schickt eine Datei ``dokument_v1.docx`` erstmal an Max, wartet auf seine Änderungen, bekommt von ihm die ``dokument_v1_max.docx`` bereitet danach eventuell eine neue ``dokument_v2.docx`` und schickt sie danach an Moritz weiter. Das könnte viel Zeit in Anspruch nehmen, besonders wenn es mehrere Revisionsrunden gibt.
2. Anna teilt die ``dokument_v1.docx`` gleichzeitig mit Max und Moritz. Nach einiger Zeit bekommt sie zwei Dokumente ``dokument_v1_max.docx`` und ``dokument_v1_moritz.docx``. Anna muss danach die Änderungen selbst in einer dritten Datei in Einklang bringen - was umständlich für sie ist, 
