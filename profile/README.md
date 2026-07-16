# Projekt_ITA23
Projekt der ITA23 der Technischen Schulen in Steinfurt  
Neugestaltung der Webseite: https://www.nossaterrarestaurant.de/

## Überblick
Im Projekt wird eine moderne Website inkl. Reservierungs- und Bestellfunktionen konzipiert und umgesetzt.  
Die Anforderungen werden im Kick-off gesammelt, anschließend in **User Stories** überführt und im **Product Backlog** mit einem Handlungsplan (TO-DOs) konkretisiert.

---

## Kick-off: Schritt 1 (Notizen & Grundlagen)
### Stakeholder
- **Kunde / Auftraggeber**
- **Product Owner (Lehrer)**
- **Entwicklerteam (Schüler)**
- **Gäste / Endnutzer**

### SMARTes Projektziel: benötigte Informationen
- Kundenwünsche erfassen und priorisieren
- Anforderungen so formulieren, dass sie messbar und umsetzbar sind

## Anforderungen (Kundenwünsche)
- Modern gestaltete Website
- Reservierungsportal
- Speisekarte:
  - Darstellung auf der Website
  - Bearbeitung (Pflege)
  - Druckfunktion
- Bestellungen im Restaurant per Handy (am Tisch)
- Abholbestellungen über die Website
- Events:
  - Darstellung
  - Buchung
- Karteikarten (Feature/Anforderung nach Kundenvorgabe)

## Vorgehen
### 1) User Stories erstellen
- Aus Sicht **aller Stakeholder** User Stories formulieren
- Erst alleine/mit Partner erarbeiten, dann gesammelt ins **Product Backlog** übernehmen

### 2) Handlungsplan & TO-DOs ableiten
- Jede User Story im Product Backlog erhält einen kurzen Handlungsplan
- Daraus werden konkrete **TO-DOs** abgeleitet

## Ergebnisse / Artefakte
- Kick-off-Notizen (Stakeholder + Anforderungen)
- User Stories
- Product Backlog inkl. Handlungsplänen und TO-DOs

<br>
<br>

---


# Online Test Darstellung

Das Main-Repository wird über einen privaten Fork mit externen Einbindungen als Live-Website dargestellt.

**Website:**  
https://nossaterra-main.onrender.com/

> Hinweis:  
> Falls die Website länger als **60 Minuten** nicht aufgerufen wird, wird der dahinterliegende Server heruntergefahren.  
>  
> Um den Server wieder hochzufahren, muss die Website erneut aufgerufen werden.  
> Der Startvorgang kann **bis zu 5 Minuten dauern** – ein Neuladen der Website beschleunigt ihn nicht.  
>  
> Sobald der Server hochgefahren ist und die Website geladen ist, wird die Seite automatisch angezeigt.  
> Bis dahin wird eine **Animation des externen Anbieters Render** angezeigt. (Siehe Bild 1)

Die Seite aktualisiert sich automatisch in regelmäßigen Abständen und zeigt dann Informationen an. (Siehe Bild 1)
Das ist **normal und beabsichtigt**.



## Synchronisation der Website

Die Website stellt eine **1:1-Darstellung des Main-Branches des Original-Repositories** dar.

Damit Änderungen aus dem Original-Repository auf der Website erscheinen, muss der Fork synchronisiert werden.

Repository zum Synchronisieren:

https://github.com/NoahRoters/Projekt_ITA23

Der Fork muss **manuell nach Änderungen im Original-Repository synchronisiert werden**.

Dafür muss der **Fork** über das **Originale GitHub Repository** und dort über den **dropdown Pfeil neben "Fork"** oder über den **oberen Link** aufgerufen werden.
Folgende **Schritte** sind wichtig und müssen befolgt werden zur **Synchronisierung**:
- Es muss sichergestellt werden das der **Fork geöffnet ist und dort die Branch "main" angezeigt wird.**
- Es muss überprüft werden das **im geöffneten Fork** angezeigt wird das der **"branch" einen oder mehrere commits hinterher ist hinter "ITA-LK-Meier/Projekt_ITA23:main"** (Siehe Bild 2)
- Nun kann der **Dropdown Pfeil** neben dem Button **Sync fork** gedrückt werden (Bild 3)
- Im neu geöffneten Menü kann nun zwischen **"Compare"** und **"Update branch"** **ausgewählt werden.** **Hier MUSS "Updade branch" gedrückt werden.**
- Nachdem die Seite neu geladen ist muss der **Bereich** welcher den **Status zwischen den Repositorys anzeigt**, **anzeigen das der Fork aktuell ist.** (Bild 4)

Nach erfolgreicher Synchronisierung:

- werden die Änderungen auf der Website angezeigt  
- dies kann **bis zu ca. 3 Minuten dauern**

---

# Darstellung der Synchronisation

Die folgenden Bilder zeigen:

- (Bild 1) **Die Ladeansicht der Website während der Server gestartet wird**
<p align="left">
  <img src="https://github.com/user-attachments/assets/ef986a67-be54-4895-9a59-e50c2b5dc64a" width="80%">
</p>
<br>

- (Bild 2) **Anzeige des Status des Forks in bezug auf das Original Repository**
<p align="left">
  <img src="https://github.com/user-attachments/assets/bd45c7e7-397b-456d-b37c-f3b17695e40d" width="90%">
</p>
<br>

- (Bild 3) **Die GitHub-Buttons zum Synchronisieren des Forks, wenn dieser nicht aktuell ist**
<p align="left">
  <img src="https://github.com/user-attachments/assets/616b126d-865a-4d13-b434-79a318fb37c2" width="90%">
</p>
<br>

- (Bild 4) **Darstellung bei Synchronisiertem Fork**
<p align="left">
  <img src="https://github.com/user-attachments/assets/f835ed0b-6ac6-43b4-be59-61ce4cdc899d" width="90%">
</p>

<p align="center">
  <sub>
  Bild 1: Ladeansicht der Website während der Server gestartet wird (Render).  
  Bild 2: GitHub-Anzeige zum Synchronisieren eines nicht aktuellen Forks.
  </sub>
</p>
