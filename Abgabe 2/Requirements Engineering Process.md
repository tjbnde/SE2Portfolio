# Requirements Engineering Process
Durchgeführter Requirements Engineering Prozess und Dokumentation aller gefundenen Requirements. Fokus sollte hierbei auf den User Requirements liegen

## Wer ist an der Lösung interessiert? - Stakeholder

### Stakeholder Klassifizierung

viel Macht/positiv -> eng managen:
viel Macht/negativ -> zufriedenstellen:
wenig Macht/positiv -> informieren:
wenig Macht/negativ -> überwachen:

### Stakeholder Identifikation

Wer hat Einfluss auf die an das Projekt gestellten Anforderungen?
Wer beeinflusst das Budget und den Zeitplan?
Wer kümmert sich um die Geschäftsbeziehung zwischen unserem Team und dem Kunden?
Wer entscheidet wann und ob überhaupt die Lösung an den Kunden ausgeliefert werden kann?
Wer kann das Projekt politisch beeinflussen? (positiv wie negativ)
Welche Partner hängen von unserem System ab?
Von welchen Partnern sind wir abhängig?
Wer interessiert sich für den Prozess den wir nutzen um die Lösung zu entwickeln?
Wer wird welche Teile der implementierten Lösung nutzen?

## Warum wird Geld investiert? - Business Requirements

Business Metriken
Product Vision

## Welche fachlichen Randbedingungen gibt es? - Business Rules

Vorhandene Regeln
Unabhängig von Software existent

Beispiele:
Bilanzierungsregeln
Steuerberechnung
Regeln zur Genehmigung bestimmter Anfragen (Urlaubsanträge, Bestellungen von Büromaterial, oder ähnlichem)

## Welche technischen randbedingungen gibt es? - Constraints

Beispiele:
Die Lösung soll auf einem bestimmten Hyperscaler laufen
Die Lösung soll einen bestimmten Service nutzen
Die Lösung soll in einer bestimmten Programmiersprache entwickelt werden

## Was muss technisch noch zusätzlich gemacht werden? - Functional Requirements

Rein Funktionale Anforderungen, ohne direkten Mehrwert für den Nutzer.
Werden aus technischen Gründen benötigt

Beispiele:
Konkrete Anforderungen an ein Datenbanschema
Anforderung eine Lösung als Framework umzusetezen

## Welche Qualitätsmerkmale muss die Lösung erfüllen? - Non-functional Requirement

Formulieren Konkrete Anforderungen an die Produktqualität und machen diese explizit
Häufig können Zielbereiche definiert werden

Beispiele:
Berechnung des Gesamtwertes
Dauert im Besten Fall 100ms
Gut nutzbar wenn Berechnung schneller als eine Sekunde
Nicht mehr nutzbar wenn Berechnung länger als zwei Sekunden dauert

## Welche Systeme müssen integriert werden? - External Interface Requirements

Definieren von Anforderungen bezüglich externer Schnittstellen (APIs)Kann von Nennung der Notwendigkeit bis hin zu detaillierter Formatbeschreibung gehen

## Wer wird die Lösung verwenden? - User Classes / Personas

## Welche großen Blöcke gibt es? - Themes / Epics

Epic:	Große und grob beschriebene User Story. Sollte in kleinere User Stories geteilt werden, bevor es bearbeitet wird

Theme:	Eine Menge an User Stories, welche thematisch zusammengehören

## Was braucht / erwartet der Endanwender? - User Requirements /

### Story
### Acceptance Criteria
### Use Case
### User Story Mapping