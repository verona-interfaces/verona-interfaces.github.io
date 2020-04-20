English version [see below](#english)

# Einführung zu Verona Interfaces
In Deutschland gibt es für internationale (z. B. PISA) und einheitliche nationale 
Erhebungen (z. B. Bildungstrend) jeweils zentrale Einrichtungen oder Firmen zur 
Durchführung. Da für die Bildungspolitik aber jedes Bundesland einzeln zuständig ist, 
werden Kompetenzerhebungen oft in Länderregie durchgeführt. Entsprechend ist die 
Vielfalt an Anforderungen an ein technisches System zum computerbasierten Testen.    

Erhebungen zum Bildungsmonitoring erfordern nicht nur die eigentliche 
Computeranwendung zur unmittelbaren Durchführung des Tests, sondern auch komplexe Portale 
zur Vorbereitung (Eingabe der Daten der Testgruppen bzw. -personen, Festlegungen zum 
Inhalt und Ablauf der Tests) und zur Auswertung (anschauliche Präsentation der 
Ergebnisse, Anregungen zur Interpretation und zur Weiterarbeit). Die erhebliche Vielfalt 
und Komplexität der Anwendungen führt dazu, dass es keine einheitliche Software geben 
kann, die von allen genutzt wird. Statt dessen entwickeln die Länder gemeinsam eine 
offene und schrittweise wachsende Landschaft von Software-Modulen, die über 
wohldefinierte Schnittstellen durch alle Beteiligten genutzt werden können.

Lernstandserhebungen in den Ländern gibt es papierbasiert seit 2003. Diese 
Vergleichsarbeiten werden mit der Abkürzung VERA bezeichnet. Aus der Verbindung mit 
"Online" wurde dann die Bezeichnung "Verona" für VERA Online. Die nötigen Schnittstellen 
(engl. Interfaces) sind in diesem Dokumenten- bzw. Codeverwaltungssystem GitHub 
beschrieben.

Sämtliche Einführungstexte, erläuternde Dokumente und allgemeinen Diskussionen finden 
sich in diesem Repository "verona-interfaces/introduction". Konkrete Schnittstellen 
sind dann in separaten Repositorys geführt, z. B. "verona-interfaces/player". Als 
Einstieg ist das Wiki gedacht. Hier finden Sie auch Verweise zu anderen Quellen.

# <a name="english"></a>Introduction to Verona Interfaces
The repositories located at /verona-interfaces consist of API specifications for 
assessment applications. In Germany, every state / Bundesland conducts assessments 
in schools. These are separate applications with complex management overhead. In order
to exchange some code modules and to be able to use the same tasks, we specify
applications interfaces. For example, if one application implements the player interface, 
it will be able to load and run player code. Every assessment unit requiring a verona 
player can be loaded afterwards.   

Providing a number of documents and a wiki, this repository supports the understanding 
of the basic concepts. Although the language of the api specification is English, we 
document and discuss in German language.