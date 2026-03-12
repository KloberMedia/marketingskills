# E-Mail Marketing Architektur -- Klober Media

**Erstellt:** 12. Marz 2026
**Unternehmen:** Klober Media -- Online Marketing Agentur, Bingen am Rhein
**Website:** klober-media.de
**Zielgruppe:** Mittelstandische Unternehmen (B2B), Geschaftsfuhrer, HR-Leiter, Marketing-Verantwortliche
**Kernleistungen:** Social Recruiting / Mitarbeitergewinnung, Neukundengewinnung via Social Media & Google Ads
**Skills verwendet:** email-sequence, content-strategy, copywriting, lead-magnet-strategy

---

## 1. Ubersicht -- Gesamtarchitektur

```
                        +---------------------------+
                        |     TRAFFIC-QUELLEN        |
                        +---------------------------+
                        | Website (organisch/paid)   |
                        | Social Media (Meta, LI)    |
                        | Google Ads                 |
                        | Empfehlungen / Netzwerk    |
                        +-------------+-------------+
                                      |
                    +-----------------+-----------------+
                    |                                   |
           +--------v--------+                 +--------v--------+
           |  LEAD MAGNET    |                 |   NEWSLETTER     |
           |  COV-Rechner    |                 |   Opt-in         |
           |  + Whitepaper   |                 |   (Website/      |
           |                 |                 |    Social Media)  |
           +--------+--------+                 +--------+---------+
                    |                                   |
                    v                                   v
           +------------------+                +------------------+
           | SEQUENZ 1:       |                | SEQUENZ 3:       |
           | Lead Magnet      |                | Newsletter       |
           | Nurture          |                | (regelmaszig)    |
           | (7 E-Mails,      |                |                  |
           |  21 Tage)        |                | Bi-weekly        |
           +--------+---------+                +--------+---------+
                    |                                   |
                    v                                   |
           +------------------+                        |
           | SEQUENZ 2:       |                        |
           | Sales Conversion |                        |
           | (4 E-Mails,      |                        |
           |  14 Tage)        |                        |
           +--------+---------+                        |
                    |                                   |
                    +------------------+----------------+
                                       |
                                       v
                              +------------------+
                              | SEQUENZ 4:       |
                              | Re-Engagement    |
                              | (4 E-Mails,      |
                              |  14 Tage)        |
                              +--------+---------+
                                       |
                              +--------v---------+
                              |  ERGEBNIS:       |
                              |  Erstgesprach /  |
                              |  Kontaktanfrage  |
                              |  / Langzeit-     |
                              |  Subscriber      |
                              +------------------+
```

---

## 2. Lead Magnets -- Einstiegspunkte

### 2.1 Primarer Lead Magnet: COV-Rechner + Whitepaper

**Landingpage:** `klober-media.de/cov-rechner/`
**Lead Magnet:** Whitepaper "Mitarbeiter mit Werten uberzeugen" (15 Seiten, PDF)

**Funnel-Ablauf:**
1. Besucher berechnet Cost of Vacancy (Kosten unbesetzter Stellen)
2. Ergebnis wird angezeigt mit Handlungsempfehlung
3. Opt-in: "Whitepaper kostenlos herunterladen -- Erfahre, wie du mit Werten die richtigen Mitarbeiter uberzeugst"
4. E-Mail-Adresse + Vorname + Unternehmen (Pflicht), Branche + Mitarbeiterzahl (optional)
5. Double Opt-in Bestatigung
6. Whitepaper-Zustellung per E-Mail
7. Start der Lead Magnet Nurture Sequenz

**Segmentierung bei Opt-in:**
- **Segment A:** Unternehmen mit 10-50 MA (KMU)
- **Segment B:** Unternehmen mit 50-250 MA (Mittelstand)
- **Segment C:** Unternehmen mit 250+ MA (Grossunternehmen)
- **Tag:** `lead-magnet:cov-rechner`, `interesse:recruiting`

### 2.2 Sekundare Lead Magnets (Empfehlung zur Erganzung)

| Lead Magnet | Zielgruppe | Einstiegspunkt | Tag |
|-------------|------------|----------------|-----|
| **Checkliste: Social Recruiting in 7 Schritten** | HR-Leiter, Geschaftsfuhrer | Blog, LinkedIn Ads | `lead-magnet:checkliste-recruiting` |
| **ROI-Rechner: Was bringt Social Media Marketing?** | Marketing-Verantwortliche | Website, Google Ads | `lead-magnet:roi-rechner` |
| **Case Study PDF: Apleona Wolfferts -- 92 Mitarbeiter in 8 Monaten** | Entscheider in der Industrie | LinkedIn, Cold E-Mail | `lead-magnet:case-study-apleona` |
| **Video-Kurs: 3 Fehler im Employer Branding** | HR & GF | Meta Ads, Instagram | `lead-magnet:video-kurs-eb` |

---

## 3. E-Mail-Sequenzen im Detail

---

### SEQUENZ 1: Lead Magnet Nurture (COV-Rechner / Whitepaper)

```
Sequenz Name:     Lead Magnet Nurture -- COV-Rechner & Whitepaper
Trigger:          Whitepaper-Download nach COV-Rechner Nutzung
Ziel:             Vertrauen aufbauen, Expertise demonstrieren, Erstgesprach buchen
Lange:            7 E-Mails uber 21 Tage
Exit-Bedingungen: Erstgesprach gebucht ODER Kontaktformular ausgefullt
```

#### E-Mail 1: Whitepaper-Zustellung + Kontext
```
Versand:     Sofort nach Double Opt-in
Betreff:     Dein Whitepaper: So uberzeugst du Mitarbeiter mit Werten
Preview:     Plus: Was dein COV-Ergebnis wirklich bedeutet
---
Hallo [Vorname],

danke fur dein Interesse am Thema Mitarbeitergewinnung.

Hier ist dein Whitepaper: [Button: Whitepaper herunterladen]

Du hast mit dem COV-Rechner bereits gesehen, was unbesetzte Stellen
dein Unternehmen kosten. Das Whitepaper zeigt dir den nachsten Schritt:
Wie du mit klaren Werten die richtigen Menschen anziehst -- nicht nur
die nachstbesten.

Uber die nachsten Wochen bekommst du von mir weitere Impulse zum Thema
Recruiting und Online Marketing. Alles praxisnah, keine Theorie.

Beste Grusse
Patrik Klober
Klober Media

P.S. Falls du direkt uber deine Recruiting-Situation sprechen mochtest:
[Link: Kostenloses Erstgesprach buchen]
---
CTA:         [Whitepaper herunterladen] -> PDF-Download-Link
Sekundar:    [Erstgesprach buchen] -> klober-media.de/kontakt/
```

#### E-Mail 2: Quick Win -- Die #1 Erkenntnis aus dem Whitepaper
```
Versand:     Tag 2 (1 Tag nach E-Mail 1)
Betreff:     Die eine Sache, die 95% beim Recruiting falsch machen
Preview:     Und wie du es ab morgen anders machst
---
Hallo [Vorname],

kurze Frage: Hast du schon ins Whitepaper reingeschaut?

Falls ja -- dann ist dir aufgefallen, dass wir nicht uber
Stellenanzeigen oder Jobborsen reden. Warum?

Weil 95% der qualifizierten Fachkrafte gar nicht aktiv suchen.

Die sitzen zufrieden bei ihrem aktuellen Arbeitgeber. Sie scrollen
abends durch Instagram oder LinkedIn. Sie denken nicht an einen
Jobwechsel -- bis sie etwas sehen, das sie anspricht.

Genau hier setzt Social Recruiting an.

Das bedeutet fur dich:
- Keine Abhangigkeit von Indeed, StepStone & Co.
- Zugang zu 95% des Marktes, den deine Konkurrenz nicht erreicht
- Bewerbungen von Menschen, die zu deinem Unternehmen passen

In der nachsten E-Mail zeige ich dir ein konkretes Beispiel --
mit Zahlen.

Beste Grusse
Patrik
---
CTA:         Kein harter CTA -- Vertrauensaufbau
```

#### E-Mail 3: Case Study / Social Proof
```
Versand:     Tag 5 (3 Tage nach E-Mail 2)
Betreff:     92 neue Mitarbeiter in 8 Monaten -- so hat Apleona es geschafft
Preview:     83% Qualifizierungsquote. Kein Headhunter, keine Jobborse.
---
Hallo [Vorname],

ich hab dir ein konkretes Beispiel versprochen. Hier ist es.

Apleona Wolfferts -- ein Facility-Management-Unternehmen mit uber
2.000 Mitarbeitern -- stand vor dem gleichen Problem wie viele
unserer Partner: Zu wenige qualifizierte Bewerbungen.

Was wir gemacht haben:
1. Zielgruppen-Analyse: Wer sind die idealen Kandidaten?
2. Kampagnen auf Meta (Facebook & Instagram): Dort, wo die Leute sind
3. Bewerbungsprozess vereinfacht: Unter 60 Sekunden statt 20 Minuten

Das Ergebnis nach 8 Monaten:
- 92 neue Mitarbeiter eingestellt
- 83% der Bewerber waren qualifiziert
- Kosten pro Einstellung deutlich unter Headhunter-Niveau

Die komplette Case Study findest du hier:
[Button: Case Study lesen]

Beste Grusse
Patrik

P.S. Wenn du ahnliche Ergebnisse fur dein Unternehmen willst,
lass uns 20 Minuten telefonieren:
[Link: Termin buchen]
---
CTA:         [Case Study lesen] -> klober-media.de/unsere-arbeiten/apleona-wolfferts/
Sekundar:    [Termin buchen] -> klober-media.de/kontakt/
```

#### E-Mail 4: Tiefere Problemanalyse -- Kosten des Nichts-Tuns
```
Versand:     Tag 8 (3 Tage nach E-Mail 3)
Betreff:     Was dich eine unbesetzte Stelle wirklich kostet (pro Monat)
Preview:     Spoiler: Es ist mehr als du denkst
---
Hallo [Vorname],

erinnerst du dich an deinen COV-Rechner-Ergebnis?

Die meisten Unternehmer unterschatzen die Kosten unbesetzter Stellen
dramatisch. Hier ist, was viele vergessen:

Die versteckten Kosten:
- Uberstunden und Mehrbelastung im bestehenden Team
- Sinkende Qualitat und langsamere Lieferzeiten
- Verlorene Auftrage, weil Kapazitat fehlt
- Know-how-Verlust, wenn erfahrene Mitarbeiter ausbrennen

Laut Studien kostet eine unbesetzte Stelle im Durchschnitt
das 1- bis 3-fache des Jahresgehalts -- pro Jahr.

Die Frage ist nicht, ob du dir Recruiting leisten kannst.
Die Frage ist: Kannst du es dir leisten, nichts zu tun?

In meiner nachsten E-Mail zeige ich dir, wie unser
Recruiting-Prozess funktioniert -- Schritt fur Schritt.

Beste Grusse
Patrik
---
CTA:         [COV nochmal berechnen] -> klober-media.de/cov-rechner/
```

#### E-Mail 5: Losung -- So arbeitet Klober Media
```
Versand:     Tag 11 (3 Tage nach E-Mail 4)
Betreff:     Unser 4-Phasen-System fur planbare Mitarbeitergewinnung
Preview:     Kein Hokuspokus, keine leeren Versprechen. Nur Ergebnisse.
---
Hallo [Vorname],

viele Agenturen versprechen "mehr Bewerbungen" -- und liefern
Klicks ohne Qualitat. Das ist nicht unser Ansatz.

Unser 4-Phasen-System:

Phase 1 -- Analyse
Wir verstehen dein Unternehmen, deine Wunschkandidaten und
deinen Arbeitsmarkt. Kein Template, keine 08/15-Kampagne.

Phase 2 -- Strategie
Wir entwickeln Kampagnen, die deine Arbeitgebermarke authentisch
positionieren -- dort, wo deine Zielgruppe ist.

Phase 3 -- Umsetzung
Professionelle Anzeigen auf Meta, LinkedIn oder Google.
Optimierter Bewerbungsprozess in unter 60 Sekunden.

Phase 4 -- Messung & Optimierung
Wochentliche Reports. Transparente Zahlen. Kontinuierliche
Verbesserung. Keine Uberraschungen.

Das Ergebnis: 6.350+ generierte Bewerbungen fur 30+ Unternehmen
seit 2017.

Mochtest du wissen, wie das fur dein Unternehmen aussehen konnte?
[Button: Kostenloses Erstgesprach buchen]

Beste Grusze
Patrik
---
CTA:         [Kostenloses Erstgesprach buchen] -> klober-media.de/kontakt/
```

#### E-Mail 6: Einwandbehandlung
```
Versand:     Tag 15 (4 Tage nach E-Mail 5)
Betreff:     "Wir haben schon alles probiert" -- das horen wir oft
Preview:     Und warum es trotzdem funktioniert
---
Hallo [Vorname],

die drei haufigsten Bedenken, die wir von Unternehmen horen:

"Wir haben schon eine Agentur ausprobiert -- hat nicht funktioniert."
-> Deshalb arbeiten wir mit individuellen Strategien statt Templates.
Jedes Unternehmen ist anders, jede Kampagne auch. Und wir optimieren
woechentlich, nicht monatlich.

"Social Recruiting funktioniert nicht in unserer Branche."
-> Wir haben Ergebnisse in Pflege, Automotive, Industrie,
Haustechnik, Logistik und Fordertechnik. Die Branche ist nicht
das Problem -- die Ansprache ist es.

"Das konnen wir uns gerade nicht leisten."
-> Was kostet dich eine unbesetzte Stelle pro Monat? (Du hast es
im COV-Rechner gesehen.) Social Recruiting ist keine Ausgabe --
es ist eine Investition mit messbarem ROI.

Noch Fragen? Lass uns reden. 20 Minuten, unverbindlich.
[Button: Termin vereinbaren]

Beste Grusze
Patrik
---
CTA:         [Termin vereinbaren] -> klober-media.de/kontakt/
```

#### E-Mail 7: Direktes Angebot + Dringlichkeit
```
Versand:     Tag 21 (6 Tage nach E-Mail 6)
Betreff:     [Vorname], eine Frage
Preview:     Sollen wir gemeinsam draufschauen?
---
Hallo [Vorname],

in den letzten 3 Wochen hast du einiges zum Thema
Mitarbeitergewinnung erfahren:

- Warum klassische Jobborsen nur 5% des Marktes erreichen
- Wie Apleona Wolfferts 92 Mitarbeiter in 8 Monaten gewonnen hat
- Was unbesetzte Stellen dein Unternehmen wirklich kosten
- Wie unser 4-Phasen-System funktioniert

Jetzt liegt die Entscheidung bei dir.

Ich biete dir ein kostenloses 20-Minuten-Erstgesprach an.
Kein Verkaufsdruck, kein Smalltalk. Wir schauen gemeinsam auf
deine Situation und ich sage dir ehrlich, ob und wie wir
helfen konnen.

[Button: Jetzt Erstgesprach buchen]

Falls der Zeitpunkt gerade nicht passt -- kein Problem.
Du bleibst in unserem Newsletter und bekommst weiterhin
wertvolle Impulse.

Beste Grusze
Patrik Klober
Klober Media

P.S. Wir arbeiten mit maximal 5 neuen Partnern pro Quartal,
damit jeder Kunde unsere volle Aufmerksamkeit bekommt.
---
CTA:         [Jetzt Erstgesprach buchen] -> klober-media.de/kontakt/
Bedingung:   Nach dieser E-Mail -> Verschiebe in Newsletter-Liste
             (Tag: nurture-abgeschlossen)
```

---

### SEQUENZ 2: Sales Conversion (fur warme Leads)

```
Sequenz Name:     Sales Conversion Follow-up
Trigger:          Lead hat mind. 3 E-Mails aus Sequenz 1 geoffnet
                  ABER kein Erstgesprach gebucht
Ziel:             Erstgesprach-Buchung
Lange:            4 E-Mails uber 14 Tage
Exit-Bedingungen: Erstgesprach gebucht
```

#### E-Mail 1: Personalisierte Branchenreferenz
```
Versand:     Tag 1 nach Sequenz-Eintritt
Betreff:     [Branche des Leads]: So gewinnen andere Unternehmen Mitarbeiter
Preview:     Ein Beispiel aus deiner Branche
---
Hallo [Vorname],

ich hab gesehen, dass du dich intensiv mit dem Thema
Mitarbeitergewinnung beschaftigst -- das freut mich.

Weil du aus [Branche/Region] kommst, wollte ich dir ein
besonders relevantes Beispiel zeigen:

[Dynamisch: Passende Case Study basierend auf Branche/Segment]

Das Spannende: Die Ausgangslage war ahnlich wie bei vielen
Unternehmen in deiner Branche.

Sollen wir mal schauen, ob das auch fur [Unternehmen] passen konnte?
[Button: 20 Min. Erstgesprach buchen]

Beste Grusze
Patrik
---
Segment/Bedingung: Dynamische Case Study basierend auf Branchen-Tag
```

#### E-Mail 2: Video/Audio-Testimonial
```
Versand:     Tag 5
Betreff:     "In 6 Wochen mehr Bewerbungen als im ganzen Vorjahr"
Preview:     Was unsere Partner uber die Zusammenarbeit sagen
---
[Kundenstimmen mit konkreten Ergebnissen]
[CTA: Erstgesprach buchen]
```

#### E-Mail 3: Exklusives Angebot
```
Versand:     Tag 9
Betreff:     Deine kostenlose Recruiting-Potenzialanalyse
Preview:     Wir schauen 20 Min. auf deine Situation -- komplett unverbindlich
---
[Angebot einer kostenlosen Potenzialanalyse als Einstieg]
[CTA: Analyse anfragen]
```

#### E-Mail 4: Letzter Impuls
```
Versand:     Tag 14
Betreff:     Kurze Frage, [Vorname]
Preview:     Ist Mitarbeitergewinnung gerade noch ein Thema?
---
[Kurze, direkte E-Mail: Interesse noch da? Falls ja -> Termin.
Falls nein -> kein Problem, Newsletter weiterlaufen lassen.]
---
Bedingung:   Nach E-Mail 4 -> Verschiebe in Newsletter-Liste
             ODER Tag: "sales-follow-up-needed" fur manuellen Kontakt
```

---

### SEQUENZ 3: Newsletter (laufend, bi-weekly)

```
Sequenz Name:     Klober Media Newsletter
Trigger:          Newsletter Opt-in (Website-Footer, Popup, Social Media)
                  ODER Abschluss von Sequenz 1/2
Ziel:             Top-of-Mind bleiben, Expertise demonstrieren, Erstgesprach-Buchungen
Frequenz:         Alle 2 Wochen (Dienstag, 09:00 Uhr)
Format:           1 Hauptthema + 2-3 kurze Impulse + CTA
```

**Content-Kategorien (Rotation):**

| Woche | Kategorie | Beispiel-Themen |
|-------|-----------|-----------------|
| 1 | **Online Marketing Insights** | Neue Meta-Ads-Features, Google-Updates, Trends |
| 2 | **Personalmarketing & Recruiting** | Employer Branding, Social Recruiting Tipps, Arbeitsmarkt-Daten |
| 3 | **Forderungen & Zuschuse** | Digitalbonus, Forderung Mittelstand, neue Programme |
| 4 | **Arbeitswelt im Wandel** | Gen Z Erwartungen, Remote Work, KI im HR |
| 5 | **Case Study / Erfolgsgeschichte** | Kunden-Ergebnis im Detail |
| 6 | **Praxis-Tipp / How-To** | "3 Schritte zu besseren Stellenanzeigen" |

**Newsletter-Template:**

```
Betreff:     [Thema-spezifisch, 40-60 Zeichen]
Preview:     [Erganzung zum Betreff, 90-140 Zeichen]
---
Hallo [Vorname],

[Einstieg: 2-3 Satze, die das Hauptthema einleiten -- mit Relevanz
fur den Leser. Warum ist das jetzt wichtig?]

## [Hauptthema-Uberschrift]

[3-5 Absatze zum Hauptthema. Praxisnah, mit konkreten Zahlen
oder Handlungsempfehlungen. Maximal 300 Worter.]

[Button: Mehr erfahren / Zum Blogartikel / Case Study lesen]

---

Kurz & knapp:

- [Impuls 1: Online Marketing News in 1-2 Satzen]
- [Impuls 2: Arbeitsmarkt-Update in 1-2 Satzen]
- [Impuls 3: Tool-Tipp oder Quick Win]

---

Du mochtest uber deine Marketing- oder Recruiting-Strategie sprechen?
[Link: Kostenloses Erstgesprach buchen]

Beste Grusze
Patrik Klober
Klober Media
---
```

**Beispiel-Newsletter #1:**
```
Betreff:     Forderung 2026: Bis zu 50% Zuschuss fur digitales Marketing
Preview:     Neue Programme fur KMU -- jetzt beantragen, bevor das Budget weg ist
---
Hallo [Vorname],

wusstest du, dass es aktuell mehrere Forderprogramme gibt, die bis zu
50% deiner Marketing-Investitionen bezuschussen?

Viele Unternehmer kennen diese Programme nicht -- oder denken, der
Aufwand lohnt sich nicht. Das Gegenteil ist der Fall.

## Welche Forderungen gibt es 2026 fur Online Marketing?

1. **Digitalbonus (landerabhangig):** Bis zu 10.000 EUR Zuschuss fur
   Website, Online Marketing und Digitalisierung.

2. **go-digital (BMWK):** Forderung fur Beratung und Umsetzung im
   Bereich Digitale Marktstrategie. 50% Zuschuss, max. 16.500 EUR.

3. **Regionale Forderprogramme:** Je nach Bundesland gibt es zusatzliche
   Programme (z.B. Innovationsgutscheine, Wirtschaftsforderung).

Was bedeutet das fur dich?
Du kannst Social Recruiting oder Neukundengewinnung mit deutlich
reduziertem Budget starten -- und trotzdem volle Qualitat bekommen.

[Button: Fordermoglichkeiten prufern lassen]

---

Kurz & knapp:

- Meta hat die Mindestbudgets fur Lead-Ads gesenkt -- gut fur KMU
- Gen Z erwartet Antwort auf Bewerbungen innerhalb von 48h (Studie XING)
- Tool-Tipp: Canva fur Employer Branding Visuals -- kostenlos starten

---

Fragen zu Forderungen oder deinem Recruiting?
[Link: Erstgesprach buchen]

Beste Grusze
Patrik
---
```

---

### SEQUENZ 4: Re-Engagement

```
Sequenz Name:     Re-Engagement Sequenz
Trigger:          45 Tage keine E-Mail geoffnet UND kein Website-Besuch
Ziel:             Reaktivierung oder saubere Listen-Bereinigung
Lange:            4 E-Mails uber 14 Tage
Exit-Bedingungen: E-Mail geoffnet -> Zuruck in Newsletter
                  Keine Reaktion nach E-Mail 4 -> Abmelden
```

#### E-Mail 1: Ehrlicher Check-in
```
Versand:     Tag 1
Betreff:     Noch Interesse, [Vorname]?
Preview:     Wir raumen auf -- und mochten wissen, ob du dabei bleibst
---
Hallo [Vorname],

wir haben gemerkt, dass du unsere E-Mails in letzter Zeit
nicht mehr geoffnet hast.

Das ist vollig okay -- vielleicht hat sich dein Fokus verschoben
oder dein Postfach ist voll.

Kurze Frage: Mochtest du weiterhin Impulse zu Online Marketing,
Recruiting und Arbeitswelt bekommen?

[Button: Ja, ich bleibe dabei]
[Link: Nein, bitte abmelden]

Keine harten Gefuhle, versprochen.

Beste Grusze
Patrik
```

#### E-Mail 2: Werterinnerung -- Was du verpasst hast
```
Versand:     Tag 5
Betreff:     Das Beste aus den letzten 6 Wochen
Preview:     3 Artikel, die andere Unternehmer weitergebracht haben
---
[Zusammenfassung der besten Newsletter-Inhalte der letzten 6 Wochen]
[CTA: Weiterlesen]
```

#### E-Mail 3: Exklusiver Anreiz
```
Versand:     Tag 9
Betreff:     Exklusiv fur dich: Kostenlose Kurzanalyse deines Recruitings
Preview:     15 Minuten, die sich lohnen konnten
---
[Angebot einer kostenlosen Mini-Analyse als Reaktivierung]
[CTA: Analyse anfordern]
```

#### E-Mail 4: Letzte Chance
```
Versand:     Tag 14
Betreff:     Wir melden uns ab -- es sei denn...
Preview:     Letzte E-Mail, bevor wir dich aus der Liste nehmen
---
Hallo [Vorname],

dies ist unsere letzte E-Mail an dich.

Wenn du weiterhin Impulse zu Recruiting und Online Marketing
mochtest, klicke auf den Button unten. Dann bleibst du dabei.

[Button: Ja, ich mochte dabei bleiben]

Falls wir nichts von dir horen, nehmen wir dich in den nachsten
Tagen automatisch aus unserer Liste. Kein Spam, kein Nachhaken.

Alles Gute fur dein Unternehmen!

Patrik
---
Bedingung:   Kein Klick nach 7 Tagen -> Automatisch abmelden
             + Tag: "re-engagement-failed"
```

---

## 4. Segmentierung & Tags

### Tag-System

| Tag | Beschreibung | Trigger |
|-----|-------------|---------|
| `quelle:cov-rechner` | Einstieg uber COV-Rechner | Formular-Submit |
| `quelle:newsletter-optin` | Direkter Newsletter Opt-in | Footer/Popup |
| `quelle:social-media` | Einstieg uber Social Ad | UTM-Parameter |
| `interesse:recruiting` | Interesse an Mitarbeitergewinnung | COV-Rechner oder Seitenbesuch /mitarbeitergewinnung/ |
| `interesse:neukunden` | Interesse an Neukundengewinnung | Seitenbesuch /neukundengewinnung/ |
| `lead-score:warm` | Hat 3+ E-Mails geoffnet | Automatisch |
| `lead-score:hot` | Hat CTA geklickt oder Kontaktseite besucht | Automatisch |
| `nurture-abgeschlossen` | Sequenz 1 durchlaufen | Automatisch nach E-Mail 7 |
| `sales-bereit` | Erstgesprach-Anfrage | Formular-Submit |
| `segment:kmu` | 10-50 Mitarbeiter | Opt-in Formular |
| `segment:mittelstand` | 50-250 Mitarbeiter | Opt-in Formular |
| `segment:gross` | 250+ Mitarbeiter | Opt-in Formular |
| `branche:[name]` | Branchen-Zuordnung | Opt-in oder manuell |

### Automatisierungsregeln

| Regel | Bedingung | Aktion |
|-------|-----------|--------|
| Nurture -> Sales | 3+ E-Mails geoffnet, kein Erstgesprach | Start Sequenz 2 |
| Nurture -> Newsletter | Sequenz 1 abgeschlossen | Aufnahme in Newsletter-Liste |
| Inaktiv -> Re-Engagement | 45 Tage keine Offnung | Start Sequenz 4 |
| Re-Engagement -> Abmelden | Keine Reaktion auf 4 E-Mails | Automatische Abmeldung |
| Hot Lead -> Benachrichtigung | CTA-Klick auf "Erstgesprach" | Slack/E-Mail an Patrik |

---

## 5. Newsletter Content-Kalender (Template fur 3 Monate)

### Monat 1

| KW | Datum | Hauptthema | Kategorie | CTA |
|----|-------|-----------|-----------|-----|
| KW 13 | Di 24.03. | Forderungen 2026: Zuschuss fur digitales Marketing | Forderungen | Fordermoglichkeiten prufen |
| KW 15 | Di 07.04. | Warum 95% der Fachkrafte nicht auf Jobborsen suchen | Personalmarketing | Case Study lesen |
| KW 17 | Di 21.04. | Google Ads vs. Meta Ads: Wann welcher Kanal? | Online Marketing | Erstgesprach buchen |

### Monat 2

| KW | Datum | Hauptthema | Kategorie | CTA |
|----|-------|-----------|-----------|-----|
| KW 19 | Di 05.05. | Gen Z im Recruiting: Was junge Fachkrafte wirklich wollen | Arbeitswelt | Whitepaper laden |
| KW 21 | Di 19.05. | Case Study: Fuest Familienstiftung -- 350+ Einstellungen | Case Study | Erstgesprach buchen |
| KW 23 | Di 02.06. | 5 Fehler im Employer Branding, die Bewerber abschrecken | Personalmarketing | Checkliste laden |

### Monat 3

| KW | Datum | Hauptthema | Kategorie | CTA |
|----|-------|-----------|-----------|-----|
| KW 25 | Di 16.06. | KI im Recruiting: Chancen und Grenzen fur den Mittelstand | Arbeitswelt | Erstgesprach buchen |
| KW 27 | Di 30.06. | Halbjahres-Recap: Die 3 wichtigsten Marketing-Trends 2026 | Online Marketing | Newsletter empfehlen |
| KW 29 | Di 14.07. | Sommerloch nutzen: Jetzt Recruiting-Kampagnen vorbereiten | Personalmarketing | Erstgesprach buchen |

---

## 6. KPIs & Erfolgsmessung

### E-Mail-Metriken (Benchmarks B2B Deutschland)

| Metrik | Zielwert | Branchenschnitt |
|--------|----------|-----------------|
| **Offnungsrate** | > 30% | 22-25% |
| **Klickrate (CTR)** | > 4% | 2-3% |
| **Click-to-Open-Rate (CTOR)** | > 12% | 8-10% |
| **Abmelderate** | < 0,3% pro E-Mail | 0,5% |
| **Bounce Rate** | < 2% | 2-3% |
| **Spam-Beschwerderate** | < 0,05% | 0,1% |

### Conversion-Metriken

| Metrik | Zielwert | Messung |
|--------|----------|---------|
| **Lead Magnet Conversion** | > 25% (Besucher -> Download) | COV-Rechner Landingpage |
| **Nurture -> Erstgesprach** | > 8% der Leads | Sequenz 1+2 abgeschlossen |
| **Newsletter -> Erstgesprach** | > 1% pro Aussendung | Newsletter CTA-Klicks |
| **E-Mail -> Website-Besuche** | > 10% CTR | UTM-Tracking |
| **Gesamte E-Mail-Pipeline** | 3-5 Erstgesprache/Monat | CRM/Kalender |

### Reporting-Rhythmus

| Intervall | Report | Inhalt |
|-----------|--------|--------|
| Wochentlich | Quick-Check | Offnungsraten, Klickraten, Abmeldungen |
| Monatlich | Performance Report | Alle Metriken, Trends, Sequenz-Performance |
| Quartal | Strategie-Review | Content-Kalender Anpassung, Segmentierung, A/B-Test Ergebnisse |

---

## 7. Technische Empfehlungen

### Tool-Empfehlung

| Anforderung | Empfehlung | Alternative |
|-------------|-----------|-------------|
| **E-Mail-Marketing-Plattform** | **ActiveCampaign** (Automation, CRM, Tags) | Mailchimp (gunstiger, weniger Automation) |
| **Landingpage COV-Rechner** | Bestehend (klober-media.de/cov-rechner/) | Erganzung: Typeform/Tally fur Opt-in |
| **Tracking** | Google Analytics 4 + UTM-Parameter | Segment (wenn Budget vorhanden) |
| **Kalender-Buchung** | Calendly oder Cal.com | In Kontaktformular integrieren |
| **CRM** | ActiveCampaign CRM oder HubSpot Free | Pipedrive |

### Technische Setup-Checkliste

- [ ] E-Mail-Domain authentifizieren (SPF, DKIM, DMARC fur klober-media.de)
- [ ] Double Opt-in Prozess einrichten (DSGVO-konform)
- [ ] Opt-in Formular auf COV-Rechner-Seite integrieren
- [ ] Newsletter Opt-in im Website-Footer einbauen
- [ ] UTM-Parameter fur alle E-Mail-Links definieren
- [ ] Automatisierungsworkflows aufsetzen (4 Sequenzen)
- [ ] Tag-System konfigurieren
- [ ] Abmelde-Link in jeder E-Mail (DSGVO)
- [ ] Impressum in jeder E-Mail (TMG)
- [ ] Test-Versand aller Sequenzen vor Go-Live
- [ ] Mobile-Responsiveness testen (70%+ offnen mobil)

### DSGVO-Compliance

- Double Opt-in fur jeden neuen Kontakt
- Abmelde-Link in jeder E-Mail
- Impressum und Datenschutzhinweis in jeder E-Mail
- Verarbeitungsverzeichnis aktualisieren
- Auftragsverarbeitung (AV-Vertrag) mit E-Mail-Tool abschliessen
- Einwilligung dokumentieren und speichern
- Loschkonzept: Inaktive Kontakte nach Re-Engagement-Sequenz loschen

---

## 8. Umsetzungsplan

### Phase 1 -- Grundlagen (Woche 1-2)

- [ ] E-Mail-Tool auswahlen und einrichten
- [ ] Domain-Authentifizierung (SPF, DKIM, DMARC)
- [ ] Opt-in Formulare erstellen (COV-Rechner + Newsletter)
- [ ] Double Opt-in E-Mail gestalten
- [ ] E-Mail-Templates im Marken-Design erstellen

### Phase 2 -- Lead Magnet Funnel (Woche 2-3)

- [ ] Opt-in auf COV-Rechner-Seite integrieren
- [ ] Whitepaper-Zustellungs-E-Mail einrichten
- [ ] Sequenz 1 (Lead Magnet Nurture, 7 E-Mails) aufsetzen
- [ ] Sequenz 2 (Sales Conversion, 4 E-Mails) aufsetzen
- [ ] Automatisierungsregeln konfigurieren
- [ ] Testlauf mit internen Adressen

### Phase 3 -- Newsletter (Woche 3-4)

- [ ] Newsletter-Template finalisieren
- [ ] Content-Kalender fur 3 Monate erstellen
- [ ] Ersten Newsletter schreiben und versenden
- [ ] Newsletter Opt-in auf Website prominent platzieren

### Phase 4 -- Optimierung (ab Woche 5)

- [ ] Re-Engagement Sequenz (Sequenz 4) aufsetzen
- [ ] Erste A/B-Tests starten (Betreffzeilen)
- [ ] Wochentliches Reporting einrichten
- [ ] Lead Scoring verfeinern basierend auf Daten
- [ ] Weitere Lead Magnets entwickeln (s. Abschnitt 2.2)

---

## 9. A/B-Test-Plan

### Prioritat 1: Betreffzeilen

| Test | Variante A | Variante B |
|------|-----------|-----------|
| Zahlen vs. Frage | "92 Mitarbeiter in 8 Monaten" | "Wie gewinnt man 92 Mitarbeiter in 8 Monaten?" |
| Direkt vs. Neugier | "Dein COV-Ergebnis und was es bedeutet" | "Was dein COV-Ergebnis uber dein Unternehmen verrat" |
| Personalisiert vs. Generisch | "[Vorname], eine Frage" | "Kurze Frage an dich" |

### Prioritat 2: CTA-Texte

| Test | Variante A | Variante B |
|------|-----------|-----------|
| Konkret vs. Allgemein | "20 Min. Erstgesprach buchen" | "Jetzt Kontakt aufnehmen" |
| Nutzen vs. Aktion | "Recruiting-Potenzial entdecken" | "Erstgesprach anfragen" |

### Prioritat 3: Versandzeit

| Test | Variante A | Variante B |
|------|-----------|-----------|
| Morgens vs. Mittags | Dienstag 09:00 | Dienstag 12:00 |
| Dienstag vs. Donnerstag | Dienstag 09:00 | Donnerstag 09:00 |

---

*Architektur erstellt mit: email-sequence, content-strategy, copywriting Skills*
*Skills-Quelle: github.com/KloberMedia/marketingskills/tree/main/skills*
*Stand: Marz 2026*
