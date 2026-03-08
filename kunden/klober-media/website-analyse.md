# Website-Analyse: klober-media.de
**Erstellt:** 08. März 2026 | **Aktualisiert mit Screaming Frog-Daten:** 08. März 2026
**Datenquellen:** Live-Crawl klober-media.de · Screaming Frog Export (265 URLs)
**Skills verwendet:** seo-audit · page-cro · site-architecture · copywriting · ai-seo

---

## 1. Executive Summary – Top 3 Quick Wins

> **Gesamtbewertung:** Starke Positionierung, überzeugende Case Studies, professionelle Seitenstruktur. Die technische Basis ist solide (alle 265 URLs liefern 200 OK, Canonicals korrekt gesetzt). Die größten unbenutzten Hebel sind fehlendes H1 auf allen Case Study Seiten, mangelnde Lesbarkeit im Fließtext und fehlender Content für organischen Traffic.

### Quick Win #1 — H1-Tags auf allen 7 Case-Study-Seiten ergänzen
**Befund (Screaming Frog):** Alle 7 Seiten unter `/unsere-arbeiten/` sowie die Übersichtsseite `/unsere-arbeiten/` haben **keinen H1-Tag**. Das ist der wichtigste On-Page-Rankingfaktor und fehlt komplett bei den Content-Seiten mit dem stärksten Trust-Signal.
**Maßnahme:** Keyword-haltigen H1 auf jeder Case-Study-Seite einfügen, z.B. `„Social Recruiting für WITTE Automotive – 78% Qualifikationsrate"`.
**Impact:** Hoch | **Aufwand:** Niedrig

### Quick Win #2 — Lesbarkeit aller Seiten verbessern (Flesch-Problem)
**Befund (Screaming Frog):** Keine einzige Seite erreicht den „Leicht"-Bereich. Die Hauptseiten liegen bei Flesch 40–47 (schwer), die Case-Study-Seiten sogar bei Flesch 13–32 (sehr schwer). Für eine Zielgruppe von Unternehmern ist das ein direktes Conversion-Hindernis.
**Maßnahme:** Case-Study-Texte kürzen, Sätze auf max. 15 Wörter, Fachbegriffe erklären oder ersetzen. Ziel: Flesch ≥ 60 auf allen Hauptseiten.
**Impact:** Mittel–Hoch | **Aufwand:** Mittel

### Quick Win #3 — Title-Tags für Datenschutz/Impressum kürzen + 2 Case Studies korrigieren
**Befund (Screaming Frog):** 4 Seiten haben Title-Tags über 60 Zeichen (Datenschutz: 82, Impressum: 80, Gebr. Pfeiffer: 65, Fuest: 64). Google kürzt diese automatisch ab — das verschlechtert CTR in den SERPs.
**Maßnahme:** Title-Tags auf 50–60 Zeichen kürzen, primäres Keyword nach vorne.
**Impact:** Mittel | **Aufwand:** Niedrig (30 Minuten Arbeit)

---

## 2. SEO-Analyse

### 2.1 Technische SEO — Gesamtübersicht (Screaming Frog, 265 URLs)

| Kriterium | Befund | Bewertung |
|-----------|--------|-----------|
| HTTPS | ✅ Aktiv auf allen URLs | Gut |
| HTTP-Status | ✅ 265/265 URLs → 200 OK | Sehr gut |
| Indexierbarkeit | ✅ 247 indexierbar, 18 nicht-indexierbar (korrekt canonicalized) | Gut |
| Duplicate Content | ⚠️ 10 URL-Gruppen mit Query-String-Duplikaten (?Home, ?Unsere%20Arbeiten) | Zu beobachten |
| Canonical-Tags | ✅ Query-String-Varianten korrekt auf kanonische URLs verwiesen | Gut |
| H1-Tags | ❌ 8 von 14 HTML-Seiten ohne H1 (alle Case Studies + /unsere-arbeiten/) | Kritisch |
| Title-Tag-Länge | ⚠️ 4 Title-Tags zu lang (>60 Zeichen) | Verbesserungsbedarf |
| Meta-Descriptions | ✅ Vorhanden auf 12/14 Seiten (Datenschutz + Impressum korrekt ohne) | Gut |
| Antwortzeiten | ✅ Ø 60–100ms (Ausreißer: Kontakt-Varianten bis 0,6s durch JS-Rendering) | Gut |
| Schema Markup | ❓ Nicht im Crawl verifizierbar | Prüfen |
| robots.txt / AI-Bots | ❓ Nicht im Crawl verifizierbar | Prüfen |
| Mobile-Friendliness | ✅ Responsives Design erkennbar | Gut |

---

### 2.2 Seitenstruktur — Vollständige URL-Übersicht

| URL | Status | Title-Länge | H1 | Wörter | Flesch | Inlinks |
|-----|--------|-------------|-----|--------|--------|---------|
| `/` | ✅ 200, indexierbar | 56 ✅ | ✅ vorhanden | 753 🟡 | 40,9 🟡 | 121 |
| `/mitarbeitergewinnung/` | ✅ 200, indexierbar | 57 ✅ | ✅ vorhanden | 1.569 🟢 | 44,0 🟡 | 61 |
| `/neukundengewinnung/` | ✅ 200, indexierbar | 56 ✅ | ✅ vorhanden | 1.312 🟢 | 46,6 🟡 | 61 |
| `/kontakt/` | ✅ 200, indexierbar | 55 ✅ | ✅ vorhanden | 106 ⚠️ | 40,3 🟡 | 38 |
| `/unsere-arbeiten/` | ✅ 200, indexierbar | 50 ✅ | ❌ fehlt | 165 ⚠️ | 55,6 🟡 | 62 |
| `/unsere-arbeiten/apleona-wolfferts/` | ✅ 200, indexierbar | 54 ✅ | ❌ fehlt | 486 🟡 | 22,9 🔴 | 7 |
| `/unsere-arbeiten/witte-automotive-gmbh/` | ✅ 200, indexierbar | 54 ✅ | ❌ fehlt | 532 🟡 | 32,3 🔴 | 5 |
| `/unsere-arbeiten/fuest-social-recruiting/` | ✅ 200, indexierbar | 64 ⚠️ | ❌ fehlt | 482 🟡 | 25,8 🔴 | 6 |
| `/unsere-arbeiten/suffel-foerdertechnik/` | ✅ 200, indexierbar | 60 ✅ | ❌ fehlt | 407 🟡 | 13,3 🔴 | 5 |
| `/unsere-arbeiten/otto-junker/` | ✅ 200, indexierbar | 54 ✅ | ❌ fehlt | 371 🟡 | 27,7 🔴 | 5 |
| `/unsere-arbeiten/haustechnik-vrbanatz-gmbh-co-kg/` | ✅ 200, indexierbar | 55 ✅ | ❌ fehlt | 439 🟡 | 29,8 🔴 | 5 |
| `/unsere-arbeiten/gebr-pfeiffer/` | ✅ 200, indexierbar | 65 ⚠️ | ❌ fehlt | 420 🟡 | 27,7 🔴 | 7 |
| `/datenschutz/` | 200, **noindex** (korrekt) | 82 ⚠️ | ✅ | 4.099 | — | 31 |
| `/impressum/` | 200, **noindex** (korrekt) | 80 ⚠️ | ✅ | 80 | — | 31 |

**Legende Flesch:** 🟢 ≥60 (leicht) · 🟡 40–59 (schwer) · 🔴 <40 (sehr schwer)
**Legende Wörter:** 🟢 ≥800 · 🟡 300–799 · ⚠️ <300 (Thin Content)

---

### 2.3 H1-Problem — Detailbefund

**8 Seiten ohne H1** (Screaming Frog bestätigt):

```
❌ /unsere-arbeiten/
❌ /unsere-arbeiten/apleona-wolfferts/
❌ /unsere-arbeiten/witte-automotive-gmbh/
❌ /unsere-arbeiten/fuest-social-recruiting/
❌ /unsere-arbeiten/suffel-foerdertechnik/
❌ /unsere-arbeiten/otto-junker/
❌ /unsere-arbeiten/haustechnik-vrbanatz-gmbh-co-kg/
❌ /unsere-arbeiten/gebr-pfeiffer/
```

**Empfohlene H1-Tags (SEO-optimiert):**

| Seite | Empfohlener H1 |
|-------|----------------|
| `/unsere-arbeiten/` | „Erfolgreiche Recruiting-Kampagnen – unsere Referenzen" |
| `/unsere-arbeiten/apleona-wolfferts/` | „Social Recruiting Apleona Wolfferts: 83% Qualifikationsrate" |
| `/unsere-arbeiten/witte-automotive-gmbh/` | „Social Recruiting WITTE Automotive: 78% Qualifizierungsquote" |
| `/unsere-arbeiten/fuest-social-recruiting/` | „Fuest Familienstiftung: 350+ Einstellungen via Social Recruiting" |
| `/unsere-arbeiten/otto-junker/` | „Otto Junker: 78 Bewerbungen und 9 Einstellungen in 12 Wochen" |
| `/unsere-arbeiten/suffel-foerdertechnik/` | „Suffel Fördertechnik: Techniker-Recruiting mit Social Ads" |
| `/unsere-arbeiten/haustechnik-vrbanatz-gmbh-co-kg/` | „Haustechnik Vrbanatz: 4 Monteure und 3 Azubis eingestellt" |
| `/unsere-arbeiten/gebr-pfeiffer/` | „Gebr. Pfeiffer: Fachkräfte begeistern und gewinnen" |

---

### 2.4 Title-Tags — Korrekturbedarf

| Seite | Aktuell (Zeichen) | Empfehlung (Zeichen) |
|-------|-------------------|----------------------|
| `/datenschutz/` | „Datenschutz - Klober Media - Online Marketing Agentur für..." (82) | „Datenschutzerklärung – Klober Media" (37) |
| `/impressum/` | „Impressum - Klober Media - Online Marketing Agentur für..." (80) | „Impressum – Klober Media, Bingen am Rhein" (42) |
| `/unsere-arbeiten/gebr-pfeiffer/` | „Kundenreferenz: Gebr. Pfeiffer - Fachkräfte begeistern & gewinnen" (65) | „Gebr. Pfeiffer: Fachkräftegewinnung via Social Recruiting" (57) |
| `/unsere-arbeiten/fuest-social-recruiting/` | „Fuest Familienstiftung: Social Recruiting mit 350+ Einstellungen" (64) | „Fuest Familienstiftung: 350+ Einstellungen via Social Ads" (57) |

---

### 2.5 Lesbarkeit — Detailanalyse (Flesch Reading Ease)

Screaming Frog misst den Flesch-Score für alle Seiten. Ergebnis: **Kein einziger Content-Bereich erreicht „Leicht" (≥60).**

| Seite | Flesch | Bewertung | Wörter |
|-------|--------|-----------|--------|
| `/unsere-arbeiten/suffel-foerdertechnik/` | **13,3** | Extrem schwer | 407 |
| `/unsere-arbeiten/apleona-wolfferts/` | **22,9** | Sehr schwer | 486 |
| `/unsere-arbeiten/fuest-social-recruiting/` | **25,8** | Sehr schwer | 482 |
| `/unsere-arbeiten/gebr-pfeiffer/` | **27,7** | Sehr schwer | 420 |
| `/unsere-arbeiten/otto-junker/` | **27,7** | Sehr schwer | 371 |
| `/unsere-arbeiten/haustechnik-vrbanatz-gmbh-co-kg/` | **29,8** | Sehr schwer | 439 |
| `/unsere-arbeiten/witte-automotive-gmbh/` | **32,3** | Schwer | 532 |
| `/` | **40,9** | Schwer | 753 |
| `/kontakt/` | **40,3** | Schwer | 106 |
| `/mitarbeitergewinnung/` | **44,0** | Schwer | 1.569 |
| `/neukundengewinnung/` | **46,6** | Schwer | 1.312 |

**Ursache:** Case-Study-Texte enthalten viele Nominalisierungen, lange Schachtelsätze und Fachbegriffe (Qualifikationsrate, Conversion-Rate, ROAS-Werte ohne Erklärung).

**Empfehlung:** Sätze auf max. 12–15 Wörter begrenzen, passive Konstruktionen auflösen, Fachbegriffe kurz erklären.

---

### 2.6 Duplicate URLs / Query-String-Problem

Screaming Frog hat **10 URL-Gruppen** mit Query-String-Varianten gefunden, die intern verlinkt sind:

| Basis-URL | Varianten | Canonical-Status |
|-----------|-----------|-----------------|
| `/kontakt/` | ?Home, ?cta-sektion-home, ?Neukundengewinnung | ✅ korrekt canonicalized |
| `/unsere-arbeiten/` | ?Home, ?Neukundengewinnung | ✅ korrekt canonicalized |
| Case-Study-Seiten | ?Home, ?Unsere%20Arbeiten | ✅ korrekt canonicalized |

**Bewertung:** Canonicals sind korrekt gesetzt — kein Duplicate-Content-Problem für Google. Die Query-Strings entstehen durch interne Tracking-Parameter in den Navigation-Links. **Empfehlung:** Diese Parameter sauber mit Google Tag Manager verwalten statt als URL-Parameter.

---

### 2.7 Thin Content

| Seite | Wörter | Problem |
|-------|--------|---------|
| `/impressum/` | 80 | Kein Problem (Pflichtseite) |
| `/kontakt/` | 106 | Zu wenig — Kontaktseiten mit 200+ Wörtern konvertieren besser |
| `/unsere-arbeiten/` | 165 | Thin Content — Portfolio-Übersicht braucht mehr Kontext |

---

### 2.8 On-Page SEO — Hauptseiten im Detail

**Startseite `/`:**
- Title: „Online Marketing Agentur Klober Media in Bingen am Rhein" (56 Zeichen) — ✅ gute Länge, Ortsnennung für Local SEO
- H1: „Geiles Online Marketing, das funktioniert!" — ✅ vorhanden, aber kein Keyword-Match
- Meta-Description: 138 Zeichen ✅ — Inhalt unbekannt, Optimierungspotenzial
- Wortanzahl: 753 — könnte höher sein
- **Keyword-Gap:** Kein Targeting auf „Social Recruiting Agentur", „Mitarbeitergewinnung Agentur", „Online Marketing Agentur Bingen"

**`/mitarbeitergewinnung/`:**
- Title: „Mitarbeitergewinnung durch Social Recruiting und Branding" (57 Zeichen) ✅
- H1: „Mitarbeitergewinnung" — zu kurz, kein Long-Tail-Keyword
- Wortanzahl: 1.569 🟢 — gute Content-Tiefe
- Flesch: 44,0 — Optimierungspotenzial

**`/neukundengewinnung/`:**
- Title: „Digitale Neukundengewinnung: Mit Social Media zum Erfolg" (56 Zeichen) ✅
- H1: „Neukundengewinnung mit Social Media" ✅
- Wortanzahl: 1.312 🟢
- Flesch: 46,6 — besser als Recruiting-Seite, noch Potenzial

---

### 2.9 AI-SEO — Sichtbarkeit in KI-Suchmaschinen

| Plattform | Sichtbarkeitsrisiko | Empfehlung |
|-----------|--------------------|-|
| Google AI Overviews | Mittel — abhängig von H1/Schema-Daten | H1s ergänzen, Schema implementieren |
| ChatGPT / Perplexity | Niedrig — wenig externe Erwähnungen erkennbar | Drittplattformen (ProvenExpert, Google Business) bespielen |
| ClaudeBot | ❓ robots.txt prüfen | Bot-Zugang sicherstellen |
| GPTBot | ❓ robots.txt prüfen | Bot-Zugang sicherstellen |

**Empfehlungen AI-SEO:**
1. `robots.txt` prüfen: GPTBot, PerplexityBot, ClaudeBot nicht blocken
2. FAQ-Sektionen auf `/mitarbeitergewinnung/` und `/neukundengewinnung/` hinzufügen
3. `Organization`, `LocalBusiness`, `Review`, `FAQPage`, `HowTo` Schema implementieren
4. Vergleichsartikel erstellen: „Social Recruiting Agentur vs. Stellenbörsen"
5. Auf Bewertungsplattformen aktiv werden (Google Business, ProvenExpert, Trustpilot)

---

## 3. Conversion-Analyse je Hauptseite

### 3.1 Startseite (`/`)
**Wörter:** 753 | **Flesch:** 40,9 | **Inlinks:** 121 | **Antwortzeit:** 60ms

**Aktuelle Conversion-Elemente:**
- Headline: „Geiles Online Marketing, das funktioniert!" ✅ Aufmerksamkeitsstark, bleibt im Gedächtnis
- Subheadline: „Ob mehr Bewerbungen oder Kunden..." ✅ Zielgruppenabgrenzung
- Zahlen: 6.350+, 30+, 7+ ✅ Trust-Signale
- CTA: „Jetzt Klartext sprechen" ⚠️ Unklar was danach passiert

**CRO-Bewertung: 6/10**

**Probleme:**
- **5-Sekunden-Test:** Zwei Leistungen (Mitarbeiter + Neukunden) konkurrieren im Erstblick
- **CTA without outcome:** CTA-Text beschreibt Aktion, nicht den Nutzen
- **Kein Urgency-Trigger** auf der Hauptseite

```
Aktueller CTA:   "Jetzt Klartext sprechen"
Empfehlung:      "Kostenlose Strategie-Session anfragen – Antwort in 24h"

Aktuelle Headline (Display): "Geiles Online Marketing, das funktioniert!"
→ behalten (Markenstimme)

H1 (technisch/SEO): aktuell "Geiles Online Marketing, das funktioniert!"
→ separaten SEO-H1 einbauen: "Online Marketing Agentur für Recruiting & Neukundengewinnung"
→ Display-Headline als visuelle Überschrift drüber (kein H1)
```

---

### 3.2 Seite: `/mitarbeitergewinnung/`
**Wörter:** 1.569 🟢 | **Flesch:** 44,0 🟡 | **Inlinks:** 61 | **Antwortzeit:** 88ms

**Aktuelle Conversion-Elemente:**
- Headline: „Warum 95% aller Unternehmen beim Recruiting scheitern" ✅ Starker Pattern-Interrupt
- H1: „Mitarbeitergewinnung" — zu kurz, kein Differenzierungsmerkmal
- Case Study Apleona Wolfferts: 92 Mitarbeiter in 8 Monaten ✅
- Scarcity: „Nur noch 4 Plätze diese Woche" ⚠️ Wahrscheinlich statischer Text

**CRO-Bewertung: 7/10**

**Probleme:**
- H1 „Mitarbeitergewinnung" ist keyword-richtig aber nicht überzeugend als Headline
- Scarcity ohne Dynamik wirkt unglaubwürdig
- Flesch 44 — Fließtexte zu schwer für schnelle Überzeugung

```
H1-Empfehlung:   "Mitarbeitergewinnung via Social Recruiting – 6.350+ Bewerbungen seit 2017"

CTA-Optimierung: "Recruiting-Strategie anfragen – Rückmeldung in 24h"

Flesch-Fix:      Sätze über 20 Wörter aufteilen, Nominalstil reduzieren
```

---

### 3.3 Seite: `/neukundengewinnung/`
**Wörter:** 1.312 🟢 | **Flesch:** 46,6 🟡 | **Inlinks:** 61 | **Antwortzeit:** 79ms

**Aktuelle Conversion-Elemente:**
- H1: „Neukundengewinnung mit Social Media" ✅ Keyword-haltig
- Headline: „Effizient und planbar: Deine Neukundenstrategie" ✅ Outcome-fokussiert
- Pain Point: „Schluss mit schlaflosen Nächten wegen schwankender Umsätze" ✅ Emotionaler Trigger
- Case Studies mit ROAS-Werten (4,63 ROAS, 144 ROAS) ✅
- Scarcity: „Nur noch 7 Plätze diese Woche" ⚠️

**CRO-Bewertung: 7,5/10**

**Probleme:**
- „300% Umsatzsteigerung in 3 Monaten" — ohne Kundenbeleg unglaubwürdig
- Scarcity ohne Dynamik schadet Vertrauen

```
Unglaubwürdige Claims ersetzen:
  Vorher: "300% Umsatzsteigerung in 3 Monaten"
  Nachher: "AIKON Skincare: Von 1,2x auf 4,63 ROAS in 90 Tagen"

Hero-CTA:
  Vorher: "Lass uns gemeinsam deinen Umsatz steigern"
  Nachher: "ROI-Potenzial berechnen – kostenlos in 20 Min."
```

---

### 3.4 Seite: `/kontakt/`
**Wörter:** 106 ⚠️ | **Flesch:** 40,3 | **Inlinks:** 38 | **Antwortzeit:** 43ms

Die Kontaktseite hat nur 106 Wörter — das ist zu wenig um Vertrauen aufzubauen und für SEO zu ranken. Kontaktseiten mit Zusatz-Content (was passiert nach dem Absenden? Wer meldet sich? In welchem Zeitraum?) konvertieren nachweislich besser.

```
Empfehlung — Erweitere die Kontaktseite um:
- "Was passiert nach deiner Anfrage?" (3-Schritt-Prozess)
- Foto des Ansprechpartners + Name
- "Wir melden uns innerhalb von 24 Stunden"
- Alternativkontakt (Telefon, LinkedIn)
```

---

### 3.5 Case-Study-Seiten (`/unsere-arbeiten/*`)
**Wörter:** 371–532 🟡 | **Flesch:** 13–32 🔴 | **H1:** ❌ alle fehlend

**Strukturproblem:** Keine der 7 Case-Study-Seiten hat einen H1-Tag. Das macht sie unsichtbar für Suchmaschinen-Ranking auf Case-Study-Suchbegriffe wie „Social Recruiting Ergebnisse Beispiel".

**Lesbarkeits-Problem:** Flesch 13–32 ist auf Niveau von wissenschaftlichen Fachartikeln. Für Entscheider, die in 2–3 Minuten entscheiden ob sie Kontakt aufnehmen, ist das ein Conversion-Killer.

**Empfehlung für jede Case-Study-Seite:**
```
Struktur-Template:
1. H1: "[Kundenname]: [Kernergebnis in Zahlen]"
2. Vorher-Situation (3–4 Sätze)
3. Unsere Lösung (Aufzählung, kein Fließtext)
4. Ergebnisse (Zahlen prominent hervorheben)
5. Kundenzitat (Vorher/Nachher-Framing)
6. CTA: "Ähnliche Ergebnisse für dein Unternehmen?"
```

---

## 4. Texte & Messaging

### 4.1 Stärken der aktuellen Copy

- **Tonalität:** Direkt, persönlich, „auf Augenhöhe" — passt zur Zielgruppe
- **Positionierung:** „Ergebnisse statt Ausreden" ist ein klares, differenzierendes Statement
- **Zahlenverwendung:** Konkrete Metriken (Conversion Rates, ROAS, Bewerbungszahlen) machen Leistung greifbar
- **Pain-Adressierung:** „Schlaflose Nächte", „schwankende Umsätze" treffen echte Probleme der Zielgruppe
- **Case-Study-Dichte:** 7 ausführliche Referenzen mit Messwerten — starkes Trust-Signal

### 4.2 Schwächen & Copywriting-Probleme

**Problem 1 — Lesbarkeit der Case Studies (Flesch 13–32)**
Case-Study-Seiten lesen sich wie Berichte statt Erfolgsgeschichten. Fachbegriffe ohne Erklärung (Qualifizierungsquote, ROAS, Conversion-Rate) schließen Teile der Zielgruppe aus.

```
Vorher: "Die implementierte Social-Recruiting-Strategie erzielte eine
         Qualifizierungsquote von 78% bei einer Conversion-Rate von 6%."
Nachher: "Von 100 Bewerbern waren 78 wirklich qualifiziert.
          6 von 100 wurden letztendlich eingestellt. Im Branchendurchschnitt
          sind es 2."
```

**Problem 2 — Zwei Zielgruppen, eine Startseite**
Hauptseite spricht Recruiting-Kunden und Neukunden-Kunden gleichzeitig an — verwässert die Botschaft.

```
Empfehlung: Klare Bifurkation im Hero-Bereich
"Mehr Mitarbeiter finden? → [Button]   Mehr Kunden gewinnen? → [Button]"
```

**Problem 3 — Generische Differenzierungsversprechen**
„Ehrliche Kommunikation", „Individuelle Strategie" werden von jeder Agentur kommuniziert.

```
Vorher: "Zuverlässige Betreuung"
Nachher: "Ein fester Ansprechpartner – erreichbar Mo–Fr, Antwort in 2h"
```

**Problem 4 — Testimonial-Qualität ausbaufähig**
„Gerne wieder" und „Ein echter Gamechanger" sind zu generisch — Ergebnis fehlt.

```
Vorher: "Kein Marketing-Gelaber, sondern echte Ergebnisse"
Nachher: "In 6 Wochen hatten wir 23 qualifizierte Bewerbungen –
          mehr als im gesamten Vorjahr zusammen."
— [Name, Position, Unternehmen]
```

### 4.3 Messaging-Hierarchie (Empfehlung)

```
Ebene 1 — WER:    "Online Marketing Agentur für Mittelstand & KMU"
Ebene 2 — WAS:    Recruiting-Kampagnen & Neukundengewinnung via Social Media & Google Ads
Ebene 3 — WIE:    Datengetrieben, messbar, ein fester Ansprechpartner
Ebene 4 — BEWEIS: 6.350+ Bewerbungen | 30+ Partner | 4,63–144 ROAS | 7+ Jahre
Ebene 5 — CTA:    Kostenfreies Erstgespräch (20 Min.) → konkretes Strategiepapier
```

---

## 5. Priorisierte Maßnahmentabelle

| # | Maßnahme | Bereich | Impact | Aufwand | Priorität | Datenquelle |
|---|----------|---------|--------|---------|-----------|-------------|
| 1 | **H1-Tags auf allen 8 Seiten ergänzen** (7 Case Studies + /unsere-arbeiten/) | SEO On-Page | 🔴 Hoch | Niedrig | **Sofort** | Screaming Frog |
| 2 | **Title-Tags kürzen** (Datenschutz 82→37, Impressum 80→42, Gebr. Pfeiffer 65→57, Fuest 64→57) | SEO On-Page | 🟠 Mittel | Niedrig | **Sofort** | Screaming Frog |
| 3 | **CTA vereinheitlichen** sitewide: Outcome-basiert, klarer Next Step | CRO | 🔴 Hoch | Niedrig | **Sofort** | Live-Analyse |
| 4 | **Lesbarkeit Case Studies verbessern** (Flesch von 13–32 auf ≥50 heben) | Copy / CRO | 🟠 Mittel–Hoch | Mittel | **KW 1–2** | Screaming Frog |
| 5 | **Schema.org implementieren** (Organization, Review, FAQPage, HowTo) | SEO / AI-SEO | 🟠 Mittel–Hoch | Mittel | **KW 1–2** | Best Practice |
| 6 | **Kontaktseite erweitern** (106 → 300+ Wörter, Prozess nach Anfrage erklären) | CRO / SEO | 🟠 Mittel | Niedrig | **KW 1** | Screaming Frog |
| 7 | **/unsere-arbeiten/ Content ausbauen** (165 → 500+ Wörter, Überblick + Filter) | SEO / CRO | 🟠 Mittel | Mittel | **KW 2** | Screaming Frog |
| 8 | **Scarcity-Elemente dynamisch machen** oder entfernen | CRO | 🟠 Mittel | Niedrig | **KW 1** | Live-Analyse |
| 9 | **robots.txt prüfen** — AI-Bots (GPTBot, PerplexityBot, ClaudeBot) zulassen | AI-SEO | 🟠 Mittel | Niedrig | **KW 1** | Best Practice |
| 10 | **Testimonials mit Vorher/Nachher-Zahlen** anreichern | CRO / Copy | 🟠 Mittel | Niedrig | **KW 2–3** | Live-Analyse |
| 11 | **Generische Claims ersetzen** durch spezifische Case-Study-Zahlen | Copy | 🟠 Mittel | Niedrig | **KW 2** | Live-Analyse |
| 12 | **FAQ-Sektion** auf /mitarbeitergewinnung/ und /neukundengewinnung/ | AI-SEO / CRO | 🟡 Mittel | Mittel | **KW 3–4** | Best Practice |
| 13 | **Google Business Profile** optimieren & Bewertungen aufbauen | AI-SEO / Local | 🟠 Mittel | Niedrig | **KW 2** | Best Practice |
| 14 | **Hero-Bifurkation** Startseite (Recruiting vs. Neukunden klar trennen) | CRO / Copy | 🟠 Mittel | Mittel | **KW 3** | Live-Analyse |
| 15 | **Branchenspezifische Landingpages** (z.B. Recruiting Handwerk, Pflege, Industrie) | SEO | 🔴 Hoch | Hoch | **Q2** | Best Practice |
| 16 | **Content-Hub / Blog** für organischen Traffic | SEO | 🔴 Hoch | Hoch | **Q2** | Best Practice |
| 17 | **Team-/Über-uns-Seite** für E-E-A-T-Signale | SEO / Trust | 🟡 Mittel | Mittel | **Q2** | Best Practice |

**Legende:** 🔴 Hoch · 🟠 Mittel–Hoch · 🟡 Mittel

---

## Anhang A: Vollständige URL-Übersicht (Screaming Frog, 265 URLs)

| Kategorie | Anzahl |
|-----------|--------|
| Gesamt gecrawlt | 265 |
| Status 200 OK | 265 |
| Indexierbar | 247 |
| Nicht-indexierbar (noindex) | 2 (Datenschutz, Impressum — korrekt) |
| Nicht-indexierbar (Canonical) | 16 (Query-String-Varianten — korrekt) |
| HTML-Seiten gesamt | 30 (inkl. Query-String-Varianten) |
| Einzigartige HTML-Seiten | 14 |
| Seiten ohne H1 | 8 |
| Title-Tags >60 Zeichen | 4 |
| Seiten ohne Meta-Description | 2 (Datenschutz, Impressum — akzeptabel) |

## Anhang B: Response-Zeiten aller HTML-Seiten

| URL | Antwortzeit | Bewertung |
|-----|-------------|-----------|
| `/datenschutz/` | 0,100s | 🟡 akzeptabel |
| `/mitarbeitergewinnung/` | 0,088s | ✅ gut |
| `/unsere-arbeiten/otto-junker/` | 0,084s | ✅ gut |
| `/unsere-arbeiten/apleona-wolfferts/` | 0,082s | ✅ gut |
| `/neukundengewinnung/` | 0,079s | ✅ gut |
| `/unsere-arbeiten/suffel-foerdertechnik/` | 0,078s | ✅ gut |
| `/unsere-arbeiten/gebr-pfeiffer/` | 0,077s | ✅ gut |
| `/unsere-arbeiten/witte-automotive-gmbh/` | 0,074s | ✅ gut |
| `/unsere-arbeiten/haustechnik-vrbanatz-gmbh-co-kg/` | 0,073s | ✅ gut |
| `/` | 0,060s | ✅ sehr gut |
| `/unsere-arbeiten/fuest-social-recruiting/` | 0,041s | ✅ sehr gut |
| `/kontakt/` | 0,043s | ✅ sehr gut |
| `/impressum/` | 0,049s | ✅ sehr gut |
| `/unsere-arbeiten/` | 0,044s | ✅ sehr gut |

> **Hinweis:** Query-String-Varianten der Seiten zeigen höhere Ladezeiten (0,3–0,6s) — das liegt am JS-Rendering beim direkten Linkaufruf mit Parametern, nicht am Server.

---

*Report erstellt mit: seo-audit · page-cro · site-architecture · copywriting · ai-seo Skills*
*Skills-Quelle: github.com/KloberMedia/marketingskills/tree/main/skills*
*Datengrundlage: Live-Crawl + Screaming Frog Export (265 URLs, Stand März 2026)*
