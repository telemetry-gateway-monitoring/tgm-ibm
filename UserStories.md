## User-Stories

---

| Sprint 1 - 13.03-03.04                                      | Sprint 2 & 3 - 03.04-08.05                             |
| :---------------------------------------------------------- | ------------------------------------------------------ |
| IBM Cloud (IoT-Plattform, Cloudant, Git Repo/s) —> M + XS   | **Frontend** - API Calls —> M                          |
| **Frontend** - Wireframes —> M                              | **Backend** - DB Handler (Data from Cloudant) —> XL    |
| **Backend** - Setup (Swagger, Express, Ordnerstruktur) —> L | verschoben ... **Frontend** - Login —> M               |
| **Frontend** - Setup —> S                                   | **Frontend** - Device Liste —> L                       |
| **Backend** - Gateway-Cloud                                 | **Frontend** - Device Details —> L                     |
|                                                             | **Backend** - API DB —> XL                             |
|                                                             | **Backend** - Message Handler  —> XL                   |
|                                                             | verschoben ... **Frontend** - View: Registration —> XL |

## Sprint 1

### **IBM Cloud** - PSP: 2,5

- Anlegen einer IoT-Plattform

  ---

  Start Datum: 13.03.2019 | Abschlussdatum: 03.04.2019 |Zeitschätzung: 0,5 h

  Zugewiesen an: Maciej Dzialoszynski

  Beschreibung: Die IoT-Plattform bildet das Kernstück der benötigten Software. Hierdurch kommt eine Verbindung zwischen Gateway und unserer Applikation zu Stande.

  Akzeptanzkriterien: Die IoT-Plattform ist über die IBM-Cloud-Accounts der Teammitglieder zugänglich.

  ---

- Einrichten einer Frontend-Cloud-Foundary-App

  ---

  Start Datum: 13.03.2019 | Abschlussdatum: 03.04.2019 |Zeitschätzung: 0,5 h

  Zugewiesen an: Maciej Dzialoszynski

  Beschreibung: Eine Cloud-Foundary-App nimmt einiges an Arbeit ab. Hierzu gehört das Erstellen einer funktionierenden Arbeitsumgebung.

  Akzeptanzkriterien: Die Sample-App ist lauffähig.

  ---

- Einrichten einer Backend-Cloud-Foundary-App

  ---

  Start Datum: 13.03.2019 | Abschlussdatum: 03.04.2019 |Zeitschätzung: 0,5 h

  Zugewiesen an: Jordi Rieder

  Beschreibung: Eine Cloud-Foundary-App nimmt einiges an Arbeit ab. Hierzu gehört das Erstellen einer funktionierenden Arbeitsumgebung.

  Akzeptanzkriterien: Die Sample-App ist lauffähig.

  ---

- Anlegen von Git-Repository für Frontend

  ---

  Start Datum: 13.03.2019 | Abschlussdatum: 03.04.2019 |Zeitschätzung: 0,5 h

  Zugewiesen an: Maciej Dzialoszynski

  Beschreibung: Als Versionsverwaltungssystem wird ein Git-Repository erstellt.

  Akzeptanzkriterien: Git-Repository ist klonbar.

  ---

- Anlegen von Git-Repository für Backend

  ---

  Start Datum: 13.03.2019 | Abschlussdatum: 03.04.2019 |Zeitschätzung: 0,5 h

  Zugewiesen an: Jordi Rieder

  Beschreibung: Als Versionsverwaltungssystem wird ein Git-Repository erstellt.

  Akzeptanzkriterien: Git-Repository ist klonbar.

  ---

- Kommunikation zwischen Backend und Datenbank (Cloudant)

  ---

  Start Datum: 13.03.2019 | Abschlussdatum: 03.04.2019 |Zeitschätzung: 0,5 h

  Zugewiesen an: Jordi Rieder

  Beschreibung: Es muss eine Verknüpfung innerhalb der Cloud zwischen der Backend-App und der Datenbank erstellt werden. Weiters ist zu beachten, dass die korrekten API-Keys und Tokens benutzt werden.

  Akzeptanzkriterien: Verbindung ist hergestellt

  ---

- Kommunikation zwischen Backend und Frontend

  ---

  Start Datum: 13.03.2019 | Abschlussdatum: 03.04.2019 |Zeitschätzung: 0,5 h

  Zugewiesen an: Jordi Rieder

  Beschreibung: 

  Akzeptanzkriterien:Verbindung ist hergestellt

  ---

### **Frontend - Wireframes** - PSP: 3,1

- Login/Registrierung

  ---

  Start Datum: 13.03.2019 | Abschlussdatum: 03.04.2019 |Zeitschätzung: 1 h

  Zugewiesen an: Maciej Dzialoszynski

  Beschreibung: Ein Benutzer muss sich registrieren und einloggen können. Das Wireframe behandelt eine Seite, die sich aus Registrierung und Login zusammensetzt.

  Akzeptanzkriterien: Das Wireframe wurde von Papier auf das Mockup-Tool Balsamiq übertragen.

  ---

- Gerät-Registrierung

  ---

  Start Datum: 13.03.2019 | Abschlussdatum: 03.04.2019 |Zeitschätzung: 3 h

  Zugewiesen an: Sebastian Grünewald

  Beschreibung: Hier wird die Geräte-Registrierungsseite, zu welcher man per Click auf den "Hinzufügen"-Button bei der Geräte-Liste, gelangt.

  Akzeptanzkriterien: Das Wireframe wurde von Papier auf das Mockup-Tool Balsamiq übertragen.

  ---

- Gerät-Liste

  ---

  Start Datum: 13.03.2019 | Abschlussdatum: 03.04.2019 |Zeitschätzung: 3 h

  Zugewiesen an: Sebastian Grünewald

  Beschreibung: Die Geräte-Liste ist, zusammen mit den Geräte-Details, das erste, was ein eingelogter User zu sehen bekommt. Hier werden die registrierten Geräte und ihre allerwichtigsten Daten angezeigt.

  Akzeptanzkriterien: - Das Wireframe wurde von Papier auf das Mockup-Tool Balsamiq übertragen.

  ​				  - Die Geräte-Liste enthält eine Darstellung der wichtigsten Daten.

  ---

- Gerät-Details

  ---

  Start Datum: 13.03.2019 | Abschlussdatum: 03.04.2019 |Zeitschätzung: 3 h

  Zugewiesen an: Maciej Dzialoszynski

  Beschreibung: Die Geräte-Details sind, zusammen mit der Geräte-Liste, das erste, was ein eingelogter User zu sehen bekommt. Hier werden alle verfügbaren Daten des Geräts angezeigt.

  Akzeptanzkriterien: - Das Wireframe wurde von Papier auf das Mockup-Tool Balsamiq übertragen

  ​				  - Die Geräte-Details werden als einzelne Karten dargestellt.

  ---
  
  
 ### **Backend - Setup **- PSP: 2,4

- Ordnerstruktur

  ---

  Start Datum: 13.03.2019 | Abschlussdatum: 03.04.2019 |Zeitschätzung: 1 h

  Zugewiesen an: David Jovanovic

  Beschreibung: Es muss für das Backend-Team, die entsprechende Ordnerstruktur aufgebaut werden, die notwendig ist für die Erfüllung der Aufgaben.

  Akzeptanzkriterien: Die umgesetzte Ordnerstruktur ist für die Leute die damit arbeiten werden verständlich und praktisch

  ---

- Node-Arbeitsumgebung aufsetzen

  ---

  Start Datum: 13.03.2019 | Abschlussdatum: 03.04.2019 |Zeitschätzung: 2 h

  Zugewiesen an: David Jovanovic

  Beschreibung: Es muss für das Backend-Team, die entsprechende Node.js Entwicklungsumgebung bereitgestellt werden. Dazu gehört die Einrichtung auf der Cloud und das hochladen einer Vorlage als App

  Akzeptanzkriterien: Die Mitglieder haben Zugriff auf die Node.js App auf der Cloud und können ihre Änderungen pushen. Die neuste Version sollte dann immer verfügbar sein über den Link auf der Cloud

  ---

### **Backend - GW-Cloud** - PSP: 2,6
- GW-Datenempfang

  ---

  Start Datum: 13.03.2019 | Abschlussdatum: 03.04.2019 |Zeitschätzung: 5 h

  Zugewiesen an: David Jovanovic

  Beschreibung: Es muss ermöglicht werden Daten vom Gateway aus zur IoT-Plattform auf der Cloud zu senden und diese dort zu empfangen.

  Akzeptanzkriterien: Die korrekten Daten werden empfangen.

  ---

- Datenfilterung

  ---

  Start Datum: 13.03.2019 | Abschlussdatum: 03.04.2019 |Zeitschätzung: 5 h

  Zugewiesen an: Jordi Rieder

  Beschreibung: Es muss ermöglicht werden die empfangenen Daten mittels einer Node.js-App zu filtern, um anschließend für die nächsten Schritte der Datenverarbeitung, nur die nötigsten Daten zu bekommen.

  Akzeptanzkriterien: Man erhält nur die gewünschten Daten

  ---



### **Frontend - Setup** - PSP: 3,2

- Ordnerstruktur

  ---

  Start Datum: 13.03.2019 | Abschlussdatum: 03.04.2019 | Zeitschätzung: 1 h

  Zugewiesen an: Sebastian Grünewald

  Beschreibung: Um eine übersichtliche Einteilung der Frontend-Komponenten zu haben, muss eine passende Ordnerstruktur erstellt werden.

  Akzeptanzkriterien: Jede Komponente und jede zusätzliche Technologie hat einen eigenen Ordner.

  ---

- React-App mit der Node-App verbinden

  ---

  Start Datum: 13.03.2019 | Abschlussdatum: 03.04.2019 |Zeitschätzung: 1 h

  Zugewiesen an: Sebastian Grünewald

  Beschreibung: Mittels "Create-React-App" wird ein React-Projekt aufgesetzt. Dieses muss mit der Node-Applikation verbunden werden.

  Akzeptanzkriterien: Datenaustausch zwischen jenen Apps möglich.

  ---

- Routen festlegen

  ---

  Start Datum: 13.03.2019 | Abschlussdatum: 03.04.2019 |Zeitschätzung: 4 h

  Zugewiesen an: Maciej Dzialoszynski

  Beschreibung: Eine gut funktionierende Web-App benötigt eine fehlerlose Navigation zwischen einzelnen Komponenten und Subseiten.

  Akzeptanzkriterien: - Navigation zwischen Login/Reg-Seite und Hauptseite funktioniert.

  ​				- Navigation zwischen einzelnen Komponenten funktioniert.

  ---

- Sass aufsetzen

  ---

  Start Datum: 13.03.2019 | Abschlussdatum: 03.04.2019 |Zeitschätzung: 1 h

  Zugewiesen an: Maciej Dzialoszynski

  Beschreibung: Für eine erleichterte Design-Arbeit wird der Präprozessor "Sass" verwendet.

  Akzeptanzkriterien: Sass in Projekt eingebunden und funktionstüchtig.

  ---

## Sprint 2 - 03.04 bis 20.04

### Frontend - Setup - PSP: 3,2

- Continous Delivery - Build

  ---

  Start Datum: 03.04.2019 | Abschlussdatum: 20.04.2019 | Zeitschätzung: 0,5h | Zeit: 3,5 h

  Zugewiesen an: Maciej Dzialoszynski

  Beschreibung: Erste Phase der Continous Delivery Pipeline. Der "Build"- Prozess der App muss mit der Cloud abgestimmt werden.

  Akzeptanzkriterien: Build Stage auf IBM Cloud auf "Phase bestanden".

  ---

- Continous Delivery - Deploy

  ------

  Start Datum: 03.04.2019 | Abschlussdatum: 20.04.2019 | Zeitschätzung: 0,5h | Zeit: 3,5 h

  Zugewiesen an: Maciej Dzialoszynski

  Beschreibung: Zweite Phase der Continous Delivery Pipeline. Der "Deploy"- Prozess der App muss mit der Cloud abgestimmt werden.

  Akzeptanzkriterien: Deploy Stage auf IBM Cloud auf "Phase bestanden".

  ------
  
- ReactJS und Node-Server verknüpfen

  ---

  Start Datum: 03.04.2019 | Abschlussdatum: 20.04.2019 | Zeitschätzung: 2h | Zeit: 3 h

  Zugewiesen an: Sebastian Grünewald

  Beschreibung: Auf der Cloud laufen ein Node- und ein ReactJS-Server bzw. Anwendungen. Ziel dieses Arbeitspakets ist es, diese beiden zu verknüpfen.

  Akzeptanzkriterien: Verknüpfte Anwendung kann in die Delivery-Pipeline eingebunden werden
  
  ---
  
- Webpack - File Loader

  ------

  Start Datum: 03.04.2019 | Abschlussdatum: 20.04.2019 | Zeitschätzung: 0.5 | Zeit: 0.5

  Zugewiesen an: Sebastian Grünewald

  Beschreibung: Um den require() Befehl in React anwenden zu können, muss ein File Loader installiert werden. Der File-Loader löst `import/require()` einer Datei in eine URL auf und gibt die Datei in das Ausgabeverzeichnis aus.

  Akzeptanzkriterien: npm run build erfolgreich

  ------

- Webpack - Image Loader

  ------

  Start Datum: 03.04.2019 | Abschlussdatum: 20.04.2019 | Zeitschätzung: 0.5 | Zeit: 0.5

  Zugewiesen an: Sebastian Grünewald

  Beschreibung: Um Bilder aller Arten (png, jpg, jpeg, svg, ...) in die React-App einbinden zu können, muss in Webpack ein Image Loader eingebaut werden.

  Akzeptanzkriterien: File Loader vorhanden + npm run build erfolgreich + Bilder werden angezeigt

  ------

- Webpack - SASS/CSS Loader

  ------

  Start Datum: 03.04.2019 | Abschlussdatum: 20.04.2019 | Zeitschätzung: 0.5 | Zeit: 0.5

  Zugewiesen an: Sebastian Grünewald

  Beschreibung: Damit SASS-Files und dessen untergeordneten CSS-Files gültig von der React-App geladen werden, muss in Webpack ein geeigneter Loader eingebaut werden. 

  Akzeptanzkriterien: npm run build erfolgreich +Style-Änderungen werden übernommen 

  ------

  

## Sprint 3 - 20.04 bis 08.05

**Arbeitspaket - Template - Sprint 3**

------

- Titel

  ------

  Start Datum: 20.04.2019 | Abschlussdatum: 08.05.2019 | Zeitschätzung: | Zeit:

  Zugewiesen an: 

  Beschreibung: 

  Akzeptanzkriterien: 

  ------

---

### Frontend - Api Calls - PSP: 3,7

- Daten-Fetch von REST

  ---

  Start Datum: 20.04.2019 | Abschlussdatum: 08.05.2019 | Zeitschätzung: 1h | Zeit: 1h

  Zugewiesen an: Maciej Dzialoszynski

  Beschreibung: Es werden die, vom Backend bereitgestellten, Daten von einer REST-Schnittstelle geholt und ausgegeben.

  Akzeptanzkriterien: Gerätedaten werden korrekt heruntergeladen und in die hierfür vorgesehenen Komponenten hineingesetzt.

  ---

### Frontend - Device Liste - PSP: 3,4

---



- Device-Liste-Komponente Version 0.1

  ---

  Start Datum: 20.04.2019 | Abschlussdatum: 08.05.2019 | Zeitschätzung: 9h | Zeit: 7h

  Zugewiesen an: Maciej Dzialoszynski

  Beschreibung: Im Vorprojekt ist das registrierte Gateway innerhalb einer Tabellen-Komponente einsehbar. Hierbei handelt es sich um eine reine Text-Ausgabe.

  Akzeptanzkriterien: Die Komponente ist verwendbar und nimmt alle nötigen Props entgegen.

  ---

- Verwendung der Listen-Komponente

  ---

  Start Datum: 20.04.2019 | Abschlussdatum: 08.05.2019 | Zeitschätzung: 1h | Zeit: 1h

  Zugewiesen an: Maciej Dzialoszynski

  Beschreibung: Die Komponente muss in den Aufbau des Web-Interfaces integriert werden.

  Akzeptanzkriterien: Die Komponente wird von der Eltern-Komponente angenommen und fehlerfrei angezeigt.

### Frontend - Device Details - PSP: 3,6

- Konzept entwickeln 	

  ------

  Start Datum: 20.04.2019 | Abschlussdatum: 08.05.2019 | Zeitschätzung: 1h| Zeit: 1h

​		Zugewiesen an: Sebastian Grünewald

​		Beschreibung: Erstellen eines Konzepts, zur Entwicklung und Umsetzung der Device Details

​		Akzeptanzkriterien: Nach Rücksprache 'OK' innerhalb des Teams

---



- Device-Details-Prototyp-Komponente

  ---

  Start Datum: 20.04.2019 | Abschlussdatum: 08.05.2019 | Zeitschätzung: 3h | Zeit: 3,5h

  Zugewiesen an: Maciej Dzialoszynski

  Beschreibung: Im Vorprojekt werden alle Daten innerhalb einer tabellenartigen Komponente ausgegeben.

  Akzeptanzkriterien: Die Komponente ist verwendbar und nimmt alle nötigen Props entgegen.

  ---

- Verwendung der Prototyp-Komponente

  ---

  Start Datum: 20.04.2019 | Abschlussdatum: 08.05.2019 | Zeitschätzung: 0,5h | Zeit: 0,5h

  Zugewiesen an: Maciej Dzialoszynski

  Beschreibung: Die Komponente muss in den Aufbau des Web-Interfaces integriert werden.

  Akzeptanzkriterien: Die Komponente wird von der Eltern-Komponente angenommen und fehlerfrei angezeigt.

  ---

- Grid-Implementierung

  ---

  Start Datum: 20.04.2019 | Abschlussdatum: 08.05.2019 | Zeitschätzung: 2h | Zeit: 1,5h

  Zugewiesen an: Maciej Dzialoszynski

  Beschreibung: Die GUI wird in Form eines Grids (Rasters) angezeigt.

  Akzeptanzkriterien: Grid-Layout adaptiert und für alle wesentlichen Bildschirmgrößen einsehbar.

  ---

### Frontend - Navbar - PSP: 3,8

- Navbar-Komponente

------

Start Datum: 20.04.2019 | Abschlussdatum: 08.05.2019 | Zeitschätzung: 2h| Zeit: 3h

Zugewiesen an: Sebastian Grünewald

Beschreibung: Es wird mit React und MaterialUI eine Navbar-Komponente aufgesetzt

Akzeptanzkriterien: Die Komponente ist verwendbar und nimmt alle nötigen Props entgegen.

------



- Verwendung der Navbar-Komponente

------

Start Datum: 20.04.2019 | Abschlussdatum: 08.05.2019 | Zeitschätzung: 1h | Zeit: 1h

Zugewiesen an: Sebastian Grünewald

Beschreibung: Die Komponente muss in den Aufbau des Web-Interfaces integriert werden.

Akzeptanzkriterien: Die Komponente wird von der Eltern-Komponente angenommen und fehlerfrei angezeigt.

---



- Gestalten der Navbar-Komponente

------

Start Datum: 20.04.2019 | Abschlussdatum: 08.05.2019 | Zeitschätzung: 2h | Zeit: 2,5

Zugewiesen an: Sebastian Grünewald

Beschreibung: Die Navbar-Komponente wird so gestaltet, dass sie responsiv ist und alle Inhalte ideal lädt und positioniert.

Akzeptanzkriterien: Komponente ist auf allen Geräten responsiv