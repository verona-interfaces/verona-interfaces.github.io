English version [see below](#english)

In Deutschland werden viele Erhebungen des Bildungsmonitorings dezentral durchgeführt, d. h. jedes Bundesland folgt eigenen Traditionen und Prioritäten. Auch zentral auf Ebene der KMK abgestimmte Lernstandserhebungen (VERA) benutzen zwar gleiche Aufgaben und methodische Verfahren, technisch und organisatorisch laufen aber auch diese Erhebungen getrennt in den Ländern. Eine zentrale technische Lösung würde in Deutschland den heterogenen Anforderungen nicht gerecht werden können.

Daraus resultieren sehr hohe Anforderungen an die Modularität und Interoperabilität von technischen Lösungen im computerbasierten Testen. Sämtliche Programmierungen müssen über wohldokumentierte Schnittstellen verfügen. Die Initiative "Verona" hat das Ziel, diese Schnittstellendefinitionen zu erarbeiten und zu pflegen. An dieser Stelle finden Sie Verweise auf den Arbeitsstand.

## [Wiki](https://github.com/verona-interfaces/verona-interfaces.github.io/wiki)

Bitte nutzen Sie das [Wiki](https://github.com/verona-interfaces/verona-interfaces.github.io/wiki) für eine Einführung in die Initiative und in die Schnittstellen. Sie finden dort auch Präsentationen und Videos. Hier ist alles in deutscher Sprache verfasst.

## Spezifikationen
Folgende Spezifikationen liegen vor und werden in englischer Sprache gesondert in Repositorien geführt:

| Modul | Beschreibung | Direkte Links |
| ------ | ------ | ----- |
| [Player](https://github.com/verona-interfaces/player#readme) | Komponente, die eine Aufgabe in einer Testanwendung abspielt | [Spezifikation (Html)](https://verona-interfaces.github.io/player/), [Modell (UML)](https://github.com/verona-interfaces/player/blob/master/model/model.md) |
| [Editor](https://github.com/verona-interfaces/editor#readme) | Komponente, mit der man Aufgaben gestaltet | [Spezifikation (Html)](https://verona-interfaces.github.io/editor/) |
| [Schemer](https://github.com/verona-interfaces/schemer#readme) | Komponente, mit der man die Kodieranweisungen für die Antwortverarbeitung festlegt | [Spezifikation (Html)](https://verona-interfaces.github.io/schemer/) |
| [Metadaten](https://github.com/verona-interfaces/metadata#readme) | Alle o. g. Komponenten enthalten Metadaten auf einheitliche Art, die hier beschrieben ist. | [Schema Editor](https://skohub.io/editor/?schema=https://raw.githubusercontent.com/verona-interfaces/metadata/master/verona-module-metadata.json) |

# <a name="english"></a>Verona Interface Specifications
The repositories located at /verona-interfaces consist of API specifications for assessment applications. In Germany, every state / Bundesland conducts assessments in schools and uses different technical solutions. In order to exchange assessment units or to share code modules, the data formats and interfaces need to be specified. The initiative 'Verona' works on these specifications.

This is an early stage of this endeavour, we did some first steps. To support this process, we publish several documents as [Wiki](https://github.com/verona-interfaces/verona-interfaces.github.io/introduction/wiki) in German language. Here you find a general introduction and clarifying of terms etc.

Besides, the specifications come in separate repositories in English language: [Player](https://github.com/verona-interfaces/player#readme), [Editor](https://github.com/verona-interfaces/editor#readme), [Schemer](https://github.com/verona-interfaces/schemer#readme) and [Metadata](https://github.com/verona-interfaces/metadata#readme).

Contact: [Institute for Educational Quality Improvement](mailto:iqb-tbadev@hu-berlin.de).
