# Requirements Engineering Process

## Wer ist an der Lösung interessiert? - Stakeholder

### Stakeholder Identifikation

* Wer hat Einfluss auf die an das Projekt gestellten Anforderungen? - Product Owner, Entwickler, Partner (DB, RNV/VRN, Plant-for-the-Planet), Nutzer
* Wer beeinflusst das Budget und den Zeitplan? - Partner, Investoren - Scrum Master, Product Owner
* Wer kümmert sich um die Geschäftsbeziehung zwischen unserem Team und dem Kunden? - Product Owner
* Wer entscheidet wann und ob überhaupt die Lösung an den Kunden ausgeliefert werden kann? - Product Owner
* Wer kann das Projekt politisch beeinflussen? (positiv wie negativ) - Politiker, Demonstranten
* Welche Partner hängen von unserem System ab? - keiner
* Von welchen Partnern sind wir abhängig? - Partner, Universitäten (Datenbereitstellung)
* Wer interessiert sich für den Prozess den wir nutzen um die Lösung zu entwickeln? -  Investoren
* Wer wird welche Teile der implementierten Lösung nutzen? - umweltbewusste Menschen -> Co2-Stempel ausrechnen, umweltinteressierte Menschen -> Informieren über Verbesserungsvorschläge

### Stakeholder Klassifizierung

![Klassifizierung](https://github.com/tjbnde/SE2Portfolio/blob/master/Abgabe%202/Requirements-Raw/Matrix.jpg)

## Warum wird Geld investiert? - Business Requirements

Durchschnittlichen CO2-Footprint der Nutzer ermitteln und möglichst reduzieren mit dem Ziel, den Planeten nachhaltiger zu gestalten

## Welche fachlichen Randbedingungen gibt es? - Business Rules

* Datenschutz (DSGVO)
* AGB der AppStores
* korrekte CO2-Messwerte
* spezifische Werbung

## Welche technischen Randbedingungen gibt es? - Constraints

* API der Partner
* Apple -> Swift, SwiftUI, ObjectiveC
* Android -> Java, Kotiln

## Was muss technisch noch zusätzlich gemacht werden? - Functional Requirements

* Key-Value Datenbank (Redis) für die einzelnen CO2-Werte
* Relationale Datenbank (MySQL) für die präsentierten Daten, sowie zur Nutzerverwaltung 
* Backend Server (REST-API)

## Welche Qualitätsmerkmale muss die Lösung erfüllen? - Non-functional Requirement

* Berechnung des CO2-Footprints dauert im schlechtesten Fall weniger als 1sec
* Gut nutzbar wenn Berechnung schneller als eine Sekunde
* Nicht mehr nutzbar wenn Berechnung länger als drei Sekunden dauert

* Intuitives Design um innerhalb max. 4 Klicks neue Aktivitäten hinzuzufügen
* Umweltwerbung (ausschaltbar)
* qualitativ hochwertige Verbesserungsvorschläge
* Freunde und Mitbewerber einfach hinzufügen (Nutzername, QR-Scan)

## Welche Systeme müssen integriert werden? - External Interface Requirements

* Universitäts-API für Daten
* RNV-API
* DB-API
* Bezahlung (In-App-Käufe, Spenden)

## Wer wird die Lösung verwenden? - Personas

![Umweltbewusste Persona](https://github.com/tjbnde/SE2Portfolio/blob/master/Abgabe%202/Requirements-Raw/Persona1.jpg)
![Umweltinteressierte Persona](https://github.com/tjbnde/SE2Portfolio/blob/master/Abgabe%202/Requirements-Raw/Persona2.jpg)

## Welche großen Blöcke gibt es? - Themes / Epics

### Epic:
**As** Ursula Umweltinteressiert  
**I want to** learn more about the environment, how I can reduce my footprint and compete with my friends
**so that** I can help to save the earth.  

Untergliedert:  
**As** Ursula Umweltinteressiert  
**I want to** learn more about the environment  
**so that** I'm aware of the impact of my actions .  

**As** Ursula Umweltinteressiert  
**I want to** know how I can reduce my footprint  
**so that** I can start living more sustainable.  

**As** Ursula Umweltinteressiert  
**I want to** compete with my friends  
**so that** it is attractive to reduce my footprint.  

Theme:	Eine Menge an User Stories, welche thematisch zusammengehören
* Technisch (Tech.): Sicherheit, UX
* Inhaltlich (Inh.): Tipps, Freunde 

## Was braucht / erwartet der Endanwender? - User Requirements

### Story

**As** Ursula Umweltinteressiert  
**I want to** learn more about environment apps  
**so that** I can share them with my friends. -> (Inh.)  

**As** Ursula Umweltinteressiert  
**I want to** have a good User Experience  
**so that** I won’t have any problems while using the app. -> (Tech.)  

**As** Ursula Umweltinteressiert  
**I want to** have a secure data storing  
**so that** my Internet-Footprint isn’t big as my CO2-Footprint. -> (Inh.)  

**As** Uli Umweltbewusst  
**I want to** see how much CO2 I produce  
**so that** I can compete to my friends who has the least CO2- Footprint. -> (Inh.)

**As** Uli Umweltbewusst  
**I want to** have a good User Experience  
**so that** I only need to use one app. -> (Tech.)  

**As** Uli Umweltbewusst  
**I want to** have a secure data storing  
**so that** I don’t need to be afraid that my data is used for other purpose. -> (Tech.)  

**As** Uli Umweltbewusst  
**I want to** help the world  
**so that** it can run better 😉. -> (Inh.)  

### Acceptance Criteria
### Use Case
### User Story Mapping
![Map](https://github.com/tjbnde/SE2Portfolio/blob/master/Abgabe%202/Requirements-Raw/Map.PNG)
