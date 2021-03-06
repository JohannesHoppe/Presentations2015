# Vorträge 2015 von Johannes Hoppe

Mehrere Vorträge und Begleitmaterial für das laufende Jahr 2015.

## Inhalt

1. [Hybride Apps mit Cordova, AngularJS und Ionic](#ionic)
2. [JS Unit- und Oberflächentests mit Karma & Protractor](#tests)
3. [Hypermedia-REST-APIs mit der ASP.NET Web API und OData](#odata)
4. [Internet der Dinge mit dem Galileo Board und JavaScript](#iot)
5. [Microservices am Beispiel von Seneca](#seneca)
6. [Workshop: Einstieg in AngularJS](#angular)
7. [Angular 2.0 – Einführung & Schnellstart](#angular2)
 
<hr>

<a name="ionic"></a>
## Hybride Apps mit Cordova, AngularJS und Ionic

* [.NET Day Franken: 13.06.2015 11:30-12:40][0]

Dank Apache Cordova ist es möglich, Ihr bestehendes Wissen zu HTML5, JavaScript und CSS3 auf mobile Apps anzuwenden. Nutzen Sie AngularJS von Google um Techniken wie MVC und Data Binding in den Browser zu bringen. Erfahren Sie in diesem Vortrag, wie Sie in durch den jüngsten Spross, dem Ionic Framework, ansprechende Oberflächen für iOS, Android und Windows Phone gestalten können. Statt PowerPoint erwartet Sie viel Live Coding. Johannes Hoppe wird zusammen mit Ihnen eine erste Ionic -Anwendung entwickeln.

[» Präsentation Starten](http://johanneshoppe.github.io/IonicPresentation/Slides/)  
[» Präsentation als PDF](http://johanneshoppe.github.io/IonicPresentation/Vortrag%20-%20Hybride%20Apps%20mit%20Cordova,%20AngularJS%20und%20Ionic%20-%20Franken.pdf)  
[» Beispiel-Anwendung](http://plnkr.co/edit/MrCCas?p=preview)

<hr>

<a name="tests"></a>
## JS Unit- und Oberflächentests mit Karma & Protractor

* [DWX: 15.06.2015 16:30-17:30 Uhr / Track: JavaScript][1]
* [enterJS: 19.06.2015 10:45-11:30 Uhr / Raum Spectrum A][2]

Sauber Code und Test Driven Development (TDD) sind die Grundlage für eine gute Architektur. Durch automatisierte Tests lässt sich sicherstellen, dass die Software fehlerfrei funktioniert und die fachlichen Spezifikationen erfüllt sind. In diesem Vortrag wird der Test-Runner Karma vorgestellt, mit welchem Unit-Test für JavaScript Anwendungen erstellt werden können. Zum Einsatz wird das BDD-Framework Jasmine kommen. Oberflächentests sind eine gute Ergänzung zu Unit-Tests, denn mit ihnen lässt sich die Anwendung aus der Sicht des Anwenders überprüfen. Hierfür wird Protractor beleuchtet, welcher auf Basis von Selenium End-To-End-Tests von JavaScript-Anwendungen und speziell von AngularJS-Anwendungen ermöglicht.

[» Präsentation Starten](http://johanneshoppe.github.io/presentations/2015/Tests-Karma-Protractor/Slides)  
[» Präsentation als PDF](http://johanneshoppe.github.io/presentations/2015/Tests-Karma-Protractor/Vortrag%20-%20JavaScript%20Unit-%20und%20Oberflächentests%20mit%20Karma%20&%20Protractor.pdf)  
[» Beispiel-Anwendungen](https://github.com/JohannesHoppe/presentations/2015/tree/gh-pages/Tests-Karma-Protractor/examples)  
 

<hr>

<a name="odata"></a>
## Hypermedia-REST-APIs mit der ASP.NET Web API und OData

* [DWX: 16.06.2015 16:30-17:30 Uhr / Track: Web][3]

Bei einer modernen Web-Anwendung ist Kommunikation per REST die erste Wahl. Doch hinsichtlich der einzusetzenden Protokolle, Formate und Konventionen bleiben diverse Fragen für die praktische Umsetzung offen. Microsoft gibt hier mit dem Open Data Protocol (OData) eine ausführliche und standardisierte Antwort.
Erfahren Sie in diesem Vortrag, wie das OData Protokoll aufgebaut ist und wie Metadaten den Entwicklungsalltag erleichtern. Ohne zusätzlichen Aufwand wird Ihre ASP.NET Web API seitenweise Ausgabe, Sortierung, Filterung und Navigation innerhalb der Daten unterstützen. Weiterhin wird eine Reihe von kompatiblen JavaScript-Frameworks beleuchtet, unter anderen Breeze.js, JayData und Kendo UI.

[» Präsentation Starten](http://johanneshoppe.github.io/presentations/2015/Rest-WebAPI-OData/Slides)   
[» Beispiel-Anwendung](https://github.com/JohannesHoppe/presentations/2015/tree/gh-pages/Rest-WebAPI-OData/ODataDemo)   
[» Artikel PDF](http://johanneshoppe.github.io/presentations/2015/Rest-WebAPI-OData/Doc/Hypermedia-REST-APIs%20mit%20der%20ASP.NET%20Web%20API%20und%20OData.pdf)   
[» Artikel Online](https://github.com/JohannesHoppe/presentations/2015/blob/gh-pages/Rest-WebAPI-OData/Doc/index.md)      

<hr>

<a name="iot"></a>
## Internet der Dinge mit dem Galileo Board und JavaScript

* [Karlsruher Entwicklertag: 20.05.2015][4]
* [DWX: 17.06.2015 11:45-12:45 Uhr / Track: IoT][5] _(zusammen mit Gregor Biswanger)_

Das Intel Galileo Board ist ein Einplatinencomputer, mit dem Sie das Internet der Dinge erforschen und innovative Projekte erstellen können. Dieser Vortrag zeigt alles, was Sie brauchen um loszulegen: Das kostenfreie Intel XDK und wie dadurch mit JavaScript die Logik für den Zugriff auf Sensoren programmiert wird. Sie steigen mit den Grundlagen ein und werden dann mit den wichtigsten Frameworks und Vorgehensweisen vertraut gemacht. 

[» Github-Repository mit vielen Anleitungen](https://github.com/JohannesHoppe/Workshop_Javascript_Internet-of-Things/)  
[» Beispiel-Anwendungen "Intel IoT on Galileo with mobile companion app"](https://github.com/JohannesHoppe/Workshop_Javascript_Internet-of-Things/tree/gh-pages/examples)  
[» Präsentation Starten](http://johanneshoppe.github.io/Workshop_Javascript_Internet-of-Things/Slides/index_short.html)

<hr>

<a name="seneca"></a>
## Microservices am Beispiel von Seneca

* [DWX: 17.06.2015 15:00-16:00 Uhr / Track: Azure][6]
* [Node.js Meetup MA: 30.06.2015][8]

Geschäftsanwendungen neigen dazu, über die Jahre zu einem gigantischen Monolithen anzuwachsen. Microservices sind ein alternatives Architekturparadigma, bei der die Anwendung in kleine dezentrale Services aufgeteilt wird. Dieser Vortrag zeigt, wie eine Architektur mit diesem Ansatz aufgebaut werden kann.
Zur Erläuterung wird das Node.js-Framework Seneca eingesetzt, welches die Kommunikation der Services über HTTP und JSON realisiert. Docker wird anschließend verwendet, um die einzelnen Services unabhängig voneinander zu deployen. Der Einsatz von Node.js ist nicht vorgeschrieben, denn der Architekturansatz ist auf alle Programmiersprachen und Frameworks anwendbar.

[» Präsentation Starten](http://johanneshoppe.github.io/presentations/2015/Microservices-Seneca/Slides)  
ENGLISH: [» Start presentation](http://johanneshoppe.github.io/presentations/2015/Microservices-Seneca/Slides/index_en.html)  

<hr>

<a name="angular"></a>
## Einstieg in AngularJS

* [DWX: 18.06.2015 09:00-17:00 Uhr][7]

Sie planen ein neues Webprojekt? Stellen Sie sicher, dass AngularJS das richtige Framework für Ihren Einsatzzweck ist. In diesem intensiven eintägigen Workshop wird AngularJS anhand von praktischen Beispielen erläutert. Sie erfahren wertvolle Tipps und bekommen Best Practices für die Entwicklung einer Single-Page-Application auf Basis von AngularJS vermittelt.

Es werden unter anderem folgende Themen behandelt:
- MVC und Routing
- MVVM & Two-Way Binding
- Dependendy-Injection und Module
- Controller, Services und Direktiven
- Fehleranalyse und Debugging
- Zusätzliche Frameworks wie Bootstrap und Kendo UI
- Ausblick auf Angular 2.0


&nbsp;
<hr>

<a name="angular2"></a>
## Angular 2.0 – Einführung & Schnellstart

* [Developer Open Space: 17.10.2015 15:00-16:00 Uhr][8]

Per Live-Coding mit Pair-Programming haben Gregor und ich einen Schnellstart in das neue Framework gegeben: TypeScript, Komponenten, Dekoratoren, Bindings, Events, Formularverarbeitung und Datenfluss in einer NG2-App. In 45 Minuten stand die erste Single-Page-App. Im Anschluss an die tolle Session möchte ich hier noch einmal alle Infos zusammen tragen.

[» Präsentation Starten](https://angular2buch.de/presentations/book-rating/)  
[» Beispiel-Anwendung](https://github.com/Angular2Buch/angular-2-book-rating-app)    

<hr>

# [&laquo; zurück](../)

<hr>

_&copy; 2015, Johannes Hoppe_



[0]: http://dotnet-day-franken.de/
[1]: http://www.developer-week.de/Programm/Veranstaltung/(event)/18498
[2]: http://www.enterjs.de/abstracts#unit-und-oberflaechentests
[3]: http://www.developer-week.de/Programm/Veranstaltung/(event)/18404
[4]: https://entwicklertag.de/karlsruhe/2015/internet-things-mit
[5]: http://www.developer-week.de/Programm/Veranstaltung/(event)/18488
[6]: http://www.developer-week.de/Programm/Veranstaltung/(event)/18454
[7]: http://www.developer-week.de/Programm/Veranstaltung/(event)/18986
[8]: http://www.meetup.com/node-js-Mannheim/events/222685767/
[9]: http://blog.johanneshoppe.de/2015/10/angular2-einfuehrung-schnellstart/

