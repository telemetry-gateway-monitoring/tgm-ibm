## User-Stories

---

| Sprint 1 - 13.03-03.04                                      | Sprint 2 - 03.04-08.05                              |
| :---------------------------------------------------------- | --------------------------------------------------- |
| IBM Cloud (IoT-Plattform, Cloudant, Git Repo/s) —> M + XS   | **Frontend** - API Calls —> M                       |
| **Frontend** - Wireframes —> M                              | **Backend** - DB Handler (Data from Cloudant) —> XL |
| **Backend** - Setup (Swagger, Express, Ordnerstruktur) —> L | **Frontend** - Login —> M                           |
| **Frontend** - Setup —> S                                   | **Frontend** - Device Liste —> L                    |
| **Backend** - Gateway-Cloud                                 | **Frontend** - Device Details —> L                  |
|                                                             | **Backend** - API DB —> XL                          |
|                                                             | **Backend** - Message Handler  —> XL                |
|                                                             | **Frontend** - View: Registration —> XL             |

## Sprint 1

### **IBM Cloud** - PSP: 2,5

- **Anlegen einer IoT-Plattform**

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

  Beschreibung: 

  Akzeptanzkriterien:

  ---

- Kommunikation zwischen Backend und Frontend

  ---

  Start Datum: 13.03.2019 | Abschlussdatum: 03.04.2019 |Zeitschätzung: 0,5 h

  Zugewiesen an: Jordi Rieder

  Beschreibung: 

  Akzeptanzkriterien:

  ---

### **Frontend - Wireframes** - PSP: 3,1

- Login/Registrierung
- Gerät-Registrierung
- Gerät-Liste
- Gerät-Details

### **Backend - Setup **- PSP: 2,4

- Ordnerstruktur
- Node-Arbeitsumgebung aufsetzen

### **Frontend - Setup** - PSP: 3,2

- Ordnerstruktur
- React-App + Sass aufsetzen
- Routen festlegen

### **Backend - GW-Cloud** - PSP: 2,6

- GW-Daten über lokales Script empfangen
- Richtige Daten filtern
- Lokales Script auf Cloud übertragen