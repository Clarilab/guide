---
layout: default
title: schnellstart
published: true
---

# Ermittlung des wirtschaftlich Berechtigten mit KYCnow

---

Ein wirtschaftlich Berechtigter gem. §3 GwG ist eine natürliche Person, in deren Eigentum ein Unternehmen liegt oder die dieses Unternehmen kontrolliert.
Außerdem kann ein wirtschaftlich Berechtigter auch die Person sein, die eine Transaktion oder die eine Begründung einer Geschäftsbeziehung veranlasst.

Zur Ermittlung von wirtschaftlich Berechtigten bezieht KYCnow die zugrundeliegenden Daten von verschiedenen Anbietern, derzeit SCHUFA und Dun & Bradstreet.
KYCnow ermittelt wirtschaftlich Berechtigte zunächst ausschließlich anhand deren Kapitel- bzw. Eigentümerstrukturen. Stimmrechtsanteile werden aktuell nicht berücksichtigt. In der Regel kann entsprechend der Kapitalanteile auf die Kontrollstrukturen geschlossen werden, die überwiegend mit den Eigentumsverhältnissen äquivalent sind (Vermutungsprinzip).  

Grundsätzlich wird der wirtschaftlich Berechtigte unabhängig des Anbieters auf Basis desselben Regelwerks ermittelt, immer entlang der Auslegungs- und Anwendungshinweise der Deutschen Kreditwirtschaft. Dies bedeutet eine voreingestellte Ermittlung nach Beherrschungsprinzip (Domination Approach) und 25%-Regel in KYCnow. Abweichende Berechnungsmethoden, wie (Accumulation Approach oder prozentuale Grenzwerte jenseits der 25%) sind derzeit individuell abzustimmen.
Der Ermittlungsnachweis ist seitens SCHUFA im bekannten GWG Design dargestellt und gestaltet sich seitens Dun & Bradstreet im reinen KYCnow Layout.

---

## Datenquellen

Die Rohdaten der Anbieter werden aktuell nicht vermischt, sondern isoliert je Ermittlung genutzt.

### Unternehmen ohne Auslandsbeziehungen

Für in Deutschland ansässige Unternehmen ohne Verflechtungen ins Ausland zieht KYCnow ausschließlich Daten der SCHUFA heran.

Für das Anfrageobjekt GmbH 1 aus Abb. 1, würden also, da es keinerlei Verflechtungen ins Ausland aufweist, die Daten der SCHUFA herangezogen werden

### Unternehmen mit Auslandsbeziehungen

Für Unternehmen mit Verflechtungen ins Ausland zieht KYCnow ausschließlich Rohdaten von Dun & Bradstreet heran.

Für das Anfrageobjekt GmbH 2 würden also die Daten von Dun & Bradstreet herangezogen werden, da das in Deutschland ansässige Unternehmen Verflechtungen in das Ausland aufweist, weil dessen Kapitalanteile von einem im Ausland ansässigen Unternehmen gehalten werden. 
Auch für das Anfrageobjekt GmbH 3 würden die Daten von Dun & Bradstreet herangezogen werden, da es vollständig im Ausland liegt.

![anfragelogik](/assets/wB/anfragelogik.png)

KYCnow entscheidet automatisch für den Anfragenden, welcher Partner in welcher Anfrage-Situation genutzt wird. Bei einer Anfrage nach einem Unternehmen mit Sitz in Deutschland wird zunächst immer Auf Basis der Informationen der SCHUFA geprüft. Wird im Zuge dieser Prüfung festgestellt, dass das angefragte Unternehmen Verflechtungen ins Ausland hat, wird die Ermittlung über SCHUFA verworfen und stattdessen anhand der Daten von Dun & Bradstreet weiter ermittelt. Die Unternehmens-Stammdaten werden in diesem Fall weiterhin von der SCHUFA genutzt.
Bei einer Anfrage nach einem Unternehmen mit Sitz im Ausland werden die Daten vollständig von Dun & Bradstreet herangezogen.

---

## Allgemeine Informationen über die Ermittlung

Als Basis für die Ermittlung der wirtschaftlichen Berechtigung werden die Eigentums- und Haftungsverhältnisse, welche durch die Rechtsform begründet sind, herangezogen. 
 
Die Ermittlungslogik unterscheidet dabei grundsätzlich zwischen einstöckigen und mehrstöckigen Strukturen.

Bei einstöckigen Strukturen, also direkter Beteiligung einer natürlichen Person am angefragten Unternehmen, führt das Überschreiten des „25%-Schwellwertes“ zu einer Stellung als wirtschaftlich berechtigte Person. (s. Abb. 2, Fälle A, B)

Bei mehrstöckigen Strukturen, also indirekter Beteiligung über eine zwischengeschaltete Gesellschaft, führt eine Beteiligung von >50% an der zwischengeschalteten Gesellschaft dazu, dass diese als beherrscht gilt. Überschreitet die zwischengeschaltete Gesellschaft ebenfalls 25% Direktbeteiligung am angefragten Unternehmen, gilt die indirekt beteiligte Person als wirtschaftlich berechtigte Person. (s. Abb. 2, Fall C, D)

Wurde eine tatsächlich wirtschaftlich berechtigte Person ermittelt, wird keine fiktive wirtschaftliche Berechtigung ausgegeben.

![ubo_szenario_a_d](/assets/wB/ubo_szenarien a_d.png)

A: Die natürliche Person A wird als wirtschaftlich berechtigte Person ausgegeben, da sie unmittelbar über 25% Kapitalanteile an der angefragten GmbH 1 hat.

B: Die natürliche Person B ist keine wirtschaftlich berechtigte Person. Dies liegt daran, dass sie unter 25% Kapitalanteile am angefragten Unternehmen hält.

C: Die AG 1 wird zu 70% von der GmbH 2 gehalten. Sie gilt von diesem Unternehmen daher als beherrscht. 
Die GmbH 2 wiederum wird zu 95% von der natürlichen Person C gehalten, somit von dieser beherrscht. Deshalb wird Person C als wirtschaftlich berechtigte Person angesehen, Person D hingegen, da diese nur 5% Kapitalanteil am Unternehmen hält, nicht.

D: Wie auch schon die Person D, beherrscht auch Person E mit nur 45% Kapitalanteil das Unternehmen AG 2 nicht. Sie beherrscht deshalb nicht die AG 2 und wird deshalb nicht als wirtschaftlich berechtigte Person angesehen, unabhängig davon, dass AG 2 an für sich über 25% am angefragten Unternehmen hält.

![ubo_szenario_e](/assets/wB/ubo_szenario e.png)

E: Die natürliche Person A ist sowohl direkt als auch indirekt an der GmbH 1 beteiligt. 
Die direkte Beteiligung liegt dabei für sich genommen unter der 25% Schwelle.
Im Fall der indirekten Beteiligung beherrscht A das zwischengelegene Unternehmen mit über 50%, weshalb ihm die 20% angerechnet werden.
A ist damit gemäß der Summenregel mit 30% an der GmbH 1 beteiligt und damit wirtschaftlich berechtigte Person.

### Fiktive wirtschaftlich Berechtigte
Erst wenn keine tatsächlich wirtschaftlich berechtigte Person ermittelt werden kann, werden die Personen der 1. Führungsebene als fiktive wirtschaftlich Berechtigte ausgegeben.

Es gibt verschiedene Gründe, weshalb keine wirtschaftlich berechtigten Personen ermittelt werden können. Diese Gründe werden aus den Ermittlungsabbrüchen ersichtlich.

![ubo_szenario_e](/assets/wB/ubo_szenario f.png)

---

## Ermittlungsschritte

Zur Ermittlung der wirtschaftlich Berechtigten sind zahlreiche Schritte notwendig. Damit diese nachvollziehbar dokumentiert werden können, werden die Ergebnisse aller einzelnen Schritte dokumentiert. 
Dafür wird zwischen Ermittlungsergebnissen (1) und Pfadergebnissen (2) unterschieden.

![ermittlungsschritte](/assets/wB/pfad_vs_ermittlungsergebnis.png)

---

## Pfadergebnisse

Pfadergebnisse können ermittelte wirtschaftlich berechtigte Personen sein. Es kann aber auch vorkommen, dass aus einem Pfad kein Rückschluss auf eine wirtschaftlich berechtigte Stellung getroffen werden kann. In diesem Fall kommt es zu einem Ermittlungsabbruch. Ein Ermittlungsabbruch ist ein üblicher Vorgang in der Erarbeitung eines Ermittlungsergebnisses und kann verschiedene Gründe haben. Im Status Quo werden hinsichtlich Benennung und Informationstiefe leicht abweichende Pfadergebnisse zwischen den Datenquellen SCHUFA und Dun & Bradstreet ausgegeben. Diese sind im folgenden Bild visualisiert.

![pfadergebnisse](/assets/wB/pfadergebnisse.png)

### Pfadergebnisse - SCHUFA

SCHUFA unterscheidet zwischen verschiedenen Abbruchsgründen, welche im Folgenden aufgezählt und erläutert werden. 

1. Wirtschaftliche Berechtigung
Konnte einer natürlichen Person eine wirtschaftliche Berechtigung zugeordnet werden, sei es durch die Summenregel oder unmittelbar, wird dies als Pfadergebnis festgehalten.

2. Ermittlungsende
Ein Ermittlungsende wird beispielsweise dann ausgegeben, wenn Streubesitz ermittelt wird oder auch wenn Kommunen oder Landkreise ermittelt werden.

3. Keine wirtschaftliche Berechtigung
Wird eine einzelne natürliche Person ermittelt, welche das Regelwerk für die UBO-Ermittlung nicht erfüllt, also bspw. nicht die notwendigen Kapitalanteile hält, wird dies so wiedergegeben.

4. Auslandsabbruch
Befindet sich entweder die Muttergesellschaft oder eine natürliche Person im Ausland, wird ein Auslandsabbruch ausgegeben, da dem Pfad nicht weiternachgegangen wird. 
Es kann also weitere UBOs im Ausland geben, die Daten liegen jedoch (noch) nicht vor.

5. Im Register Gelöscht
Das Unternehmen wurde aus dem Handelsregister gelöscht.

6. Gesperrt
Ein beteiligtes Unternehmen ist gesperrt, weshalb keine weitere Ermittlung erfolgen kann.

7. Zirkelbezug
In diesem Fall liegt eine Eigenbeteiligung vor – entweder des angefragten Unternehmens selbst oder eines beteiligten Unternehmens.

8. Sonstige
Dieser Ermittlungsabbruch wird ausgegeben, wenn ein Unternehmen keine Kapitalanteile hat. Dies wäre bspw. bei einer Stiftung oder einem Verein der Fall.

---

## Ermittlungsergebnisse
Die Ermittlungsergebnisse resultieren aus den Pfadergebnissen. Wenn Pfadergebnisse ausschließlich auf Informationen der SCHUFA basieren, werden auch die Ermittlungsergebnisse durch die SCHUFA ausgegeben. Sobald die Pfadergebnisse auf Informationen von Dun & Bradstreet beruhen, werden auch die Ermittlungsergebnisse basierend auf diesen Informationen ausgegeben.

### Ermittlungsergebnisse - SCHUFA 
SCHUFA unterscheidet zwischen vier Ermittlungsergebnissen.

![ermittlungsergebnisse_schufa](/assets/wB/ermittlungsergebnisse_schufa.png)

### Ermittlungsergebnisse - Dun & Bradstreet
Dun & Bradstreet unterscheidet zwischen fünf Ermittlungsergebnissen.

![ermittlungsergebnisse_d&b](/assets/wB/ermittlungsergebnisse_dnb.png)