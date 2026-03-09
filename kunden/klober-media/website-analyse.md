# Website-Analyse: klober-media.de
**Erstellt:** 08. März 2026 | **Aktualisiert:** 08. März 2026 (+ Heading-Tiefenanalyse)
**Datenquellen:** Live-Crawl klober-media.de · Screaming Frog Export (265 URLs) · Heading-Audit alle Hauptseiten
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
| 1 | **Footer-Elemente aus H2 entfernen** (Newsletter, Follow us, Navi auf jeder Seite als H2 getaggt — siteweiter Hierarchiefehler) | SEO / Technik | 🔴 Kritisch | Niedrig | **Sofort** | Heading-Audit |
| 2 | **Fuest Case Study: 13 H1-Tags auf H2/H3 downgraden** — schwerster Einzelfehler im Crawl | SEO On-Page | 🔴 Kritisch | Niedrig | **Sofort** | Heading-Audit |
| 3 | **Alle Case Studies: Doppel-H1 beheben** (WITTE, Apleona: je 2×H1 „Case-Study" + Firmenname) | SEO On-Page | 🔴 Hoch | Niedrig | **Sofort** | Heading-Audit |
| 4 | **H1-Tags keyword-optimieren** auf allen Hauptseiten (/, /kontakt/, /unsere-arbeiten/) | SEO On-Page | 🔴 Hoch | Niedrig | **Sofort** | Heading-Audit |
| 5 | **Title-Tags kürzen** (Datenschutz 82→37, Impressum 80→42, Gebr. Pfeiffer 65→57, Fuest 64→57) | SEO On-Page | 🟠 Mittel | Niedrig | **Sofort** | Screaming Frog |
| 6 | **CTA vereinheitlichen** sitewide: Outcome-basiert, klarer Next Step | CRO | 🔴 Hoch | Niedrig | **Sofort** | Live-Analyse |
| 7 | **/neukundengewinnung/: H2-Überladung bereinigen** (16 H2s → max. 5, H2-Splitting beheben) | SEO On-Page | 🔴 Hoch | Niedrig | **KW 1** | Heading-Audit |
| 8 | **Optimierte Meta Titles** einpflegen (alle 8 Seiten laut Tabelle C.10) | SEO On-Page | 🟠 Mittel–Hoch | Mittel | **KW 1** | Heading-Audit |
| 9 | **Lesbarkeit Case Studies verbessern** (Flesch von 13–32 auf ≥50 heben) | Copy / CRO | 🟠 Mittel–Hoch | Mittel | **KW 1–2** | Screaming Frog |
| 10 | **Schema.org implementieren** (Organization, Review, FAQPage, HowTo) | SEO / AI-SEO | 🟠 Mittel–Hoch | Mittel | **KW 1–2** | Best Practice |
| 11 | **Kontaktseite erweitern** (106 → 300+ Wörter, Prozess nach Anfrage erklären) | CRO / SEO | 🟠 Mittel | Niedrig | **KW 1** | Screaming Frog |
| 12 | **/unsere-arbeiten/ Content ausbauen** (165 → 500+ Wörter, H3s mit Ergebniszahlen) | SEO / CRO | 🟠 Mittel | Mittel | **KW 2** | Screaming Frog |
| 13 | **Scarcity-Elemente dynamisch machen** oder entfernen | CRO | 🟠 Mittel | Niedrig | **KW 1** | Live-Analyse |
| 14 | **robots.txt prüfen** — AI-Bots (GPTBot, PerplexityBot, ClaudeBot) zulassen | AI-SEO | 🟠 Mittel | Niedrig | **KW 1** | Best Practice |
| 15 | **Testimonials mit Vorher/Nachher-Zahlen** anreichern | CRO / Copy | 🟠 Mittel | Niedrig | **KW 2–3** | Live-Analyse |
| 16 | **FAQ-Sektion** auf /mitarbeitergewinnung/ und /neukundengewinnung/ | AI-SEO / CRO | 🟡 Mittel | Mittel | **KW 3–4** | Best Practice |
| 17 | **Google Business Profile** optimieren & Bewertungen aufbauen | AI-SEO / Local | 🟠 Mittel | Niedrig | **KW 2** | Best Practice |
| 18 | **Hero-Bifurkation** Startseite (Recruiting vs. Neukunden klar trennen) | CRO / Copy | 🟠 Mittel | Mittel | **KW 3** | Live-Analyse |
| 19 | **Branchenspezifische Landingpages** (z.B. Recruiting Handwerk, Pflege, Industrie) | SEO | 🔴 Hoch | Hoch | **Q2** | Best Practice |
| 20 | **Content-Hub / Blog** für organischen Traffic | SEO | 🔴 Hoch | Hoch | **Q2** | Best Practice |
| 21 | **Team-/Über-uns-Seite** für E-E-A-T-Signale | SEO / Trust | 🟡 Mittel | Mittel | **Q2** | Best Practice |

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

## Anhang C: Tiefenanalyse Meta Title · Meta Description · H1–H4

> **Methode:** Live-Extraktion aller Heading-Tags von 10 Seiten (Startseite, 2 Leistungsseiten, Kontakt, Portfolio-Übersicht, 3 Case Studies). Bewertung je nach SEO-Relevanz (Keyword-Dichte, Hierarchie-Logik) und Conversion-Stärke (Klarheit, Nutzen, Handlungsimpuls).

---

### C.1 Bewertungssystem

| Kriterium | A — Sehr gut | B — Gut | C — Ausbaufähig | D — Kritisch |
|-----------|-------------|---------|-----------------|--------------|
| **SEO** | Primärkeyword im Tag, korrekte Länge, Hierarchie eingehalten | Keyword vorhanden, kleinere Abweichungen | Keyword schwach / fehlt | Kein Keyword, falsche Länge, Hierarchiebruch |
| **Conversion** | Spezifischer Nutzen, Zahlen, Dringlichkeit | Nutzen vorhanden, kein Trigger | Generisch, austauschbar | Keine Aussage / confusing |

---

### C.2 Startseite (`/`)

**Meta Title**
```
Ist:  "Online Marketing Agentur Klober Media in Bingen am Rhein"  [56 Zeichen]
```
| | SEO | Conversion |
|--|-----|------------|
| Bewertung | **B** | **C** |
| Begründung | Primärkeyword „Online Marketing Agentur" vorne ✅, Ortsnennung ✅, Länge ok | Kein Nutzenversprechen, keine Zahl, kein Differenzierungsmerkmal |
| Optimierung | „Online Marketing Agentur für Recruiting & Neukundengewinnung – Klober Media" [72 → kürzen auf 65: „Recruiting & Neukundengewinnung – Online Marketing Agentur Klober Media"] | |

**Meta Description**
```
Ist:  [138 Zeichen, Inhalt aus SF – exakter Text nicht extrahierbar]
```
| | SEO | Conversion |
|--|-----|------------|
| Bewertung | **B** (Länge ok) | **?** (Text unbekannt) |
| Empfehlung | „Mehr Mitarbeiter oder mehr Kunden? Klober Media liefert messbare Ergebnisse: 6.350+ Bewerbungen, 30+ Partner, 4,6–144x ROAS. Jetzt Erstgespräch anfragen." [148 Zeichen] | |

**Heading-Hierarchie Startseite — vollständige Bestandsaufnahme**

| Tag | Ist-Text | SEO | Conv. | Problem |
|-----|----------|-----|-------|---------|
| H1 | „Geiles Online Marketing, das funktioniert!" | **D** | **B** | Kein Keyword, nicht suchbar |
| H2 | „Starke Partner. Starke Ergebnisse." | **D** | **C** | Kein Keyword, zu generisch |
| H2 | „Ergebnisse statt Ausreden" | **D** | **B** | Positionierung ja, kein Keyword |
| H2 | „Klarer Plan. Klare Umsetzung. Klare Ergebnisse." | **D** | **C** | Repetitiv, kein Keyword |
| H2 | „Aus Projekten werden Partnerschaften." | **D** | **C** | Brand-Sprache ohne Keyword |
| H2 | „Kunden. Vertrauen. Ergebnisse." | **D** | **C** | Zu fragmentiert |
| H2 | „Bereit für geiles Online Marketing?" | **D** | **B** | Kein Keyword, aber Call-to-Action-Charakter |
| **H2** | **„Newsletter"** | **D** | **—** | ❌ KRITISCH: Footer-Element als H2 getaggt |
| **H2** | **„Follow us"** | **D** | **—** | ❌ KRITISCH: Footer-Element als H2 getaggt |
| **H2** | **„Navi"** | **D** | **—** | ❌ KRITISCH: Navigation als H2 getaggt |
| H3 | „135% mehr qualifizierte Bewerbungen" | **B** | **A** | ✅ Konkrete Zahl, starkes Trust-Signal |
| H3 | „6350+ Bewerbungen erfolgreich generiert" | **B** | **A** | ✅ Konkrete Zahl |
| H3 | „30+ Unternehmen vertrauen uns" | **C** | **B** | Social Proof, aber generisch |
| H3 | „7+ Jahre Erfahrung im Online Marketing" | **C** | **B** | Erfahrungs-Signal |
| H3 | „Zielsetzung", „Strategie", „Umsetzung", „Messung" | **C** | **C** | Prozess-Labels, zu kurz |
| H4 | „Ob Recruiting, Markenaufbau oder Sichtbarkeit" | **D** | **C** | Zu vage, kein Keyword |

**Gesamtbefund Startseite:**
- **3 Footer-/Navigations-Elemente fälschlicherweise als H2** — das zerstört die Heading-Hierarchie aus Google-Perspektive
- H1 ohne jedes Keyword — Google kann Seite nicht thematisch einordnen
- Alle H2s sind Brand-Sprache statt SEO-Signale
- Stärkste Tags sind die H3-Zahlen — diese sollten ins H2-Level hochgezogen werden

**Empfohlene Korrektur-Hierarchie Startseite:**
```
H1: "Online Marketing Agentur für Recruiting und Neukundengewinnung"
H2: "135% mehr qualifizierte Bewerbungen – messbar und planbar"
H2: "Mitarbeitergewinnung via Social Recruiting"
H2: "Neukundengewinnung via Google & Meta Ads"
H2: "So arbeiten wir: Ziel → Strategie → Umsetzung → Messung"
H2: "30+ Unternehmen. 6.350+ Bewerbungen. 7+ Jahre."
H3: (Prozess-Details, Testimonials, einzelne Leistungen)
```

---

### C.3 `/mitarbeitergewinnung/`

**Meta Title**
```
Ist:  "Mitarbeitergewinnung durch Social Recruiting und Branding"  [57 Zeichen]
```
| | SEO | Conversion |
|--|-----|------------|
| Bewertung | **B** | **C** |
| Begründung | Primärkeyword ✅, Methode (Social Recruiting) ✅, Länge ok | Kein Nutzenversprechen, kein Ergebnis, keine Dringlichkeit |
| Optimierung | „Mitarbeitergewinnung mit Social Recruiting – 6.350+ Bewerbungen für KMU" [70 → auf 65 kürzen] | |

**Heading-Hierarchie `/mitarbeitergewinnung/`**

| Tag | Ist-Text | SEO | Conv. | Problem |
|-----|----------|-----|-------|---------|
| H1 | „Mitarbeitergewinnung" | **C** | **D** | Keyword vorhanden, aber viel zu kurz — kein USP, keine Zahl, kein Differenzmerkmal |
| H2 | „Warum 95% aller Unternehmen beim Recruiting scheitern" | **C** | **A** | ✅ Stärkster Conversion-Hook der ganzen Seite — kein Keyword aber starker Pattern-Interrupt |
| H3 | „✅ Wie Apleona Wolfferts in nur 8 Monaten 92 neue Mitarbeiter einstellte" | **B** | **A** | ✅ Konkret, Zeitangabe, Zahl — perfektes Trust-Heading |
| H3 | „Messbares Recruiting" | **C** | **C** | Zu kurz, generisch |
| H3 | „Schnelle Umsetzung" | **D** | **D** | Jede Agentur behauptet das |
| H3 | „Zuverlässige Betreuung" | **D** | **D** | Jede Agentur behauptet das |
| H3 | „Ehrliche Kommunikation auf Augenhöhe" | **D** | **C** | Differenzierung ohne Beleg |

**Gesamtbefund `/mitarbeitergewinnung/`:**
- H1 „Mitarbeitergewinnung" — ein einzelnes Wort als H1 ist verschenktes Potenzial
- H2 ist der stärkste Conversion-Text — müsste keyword-optimiert sein
- H3-Differenzierungsversprechen sind alle austauschbar — keine einzige Zahl

**Empfohlene Korrektur-Hierarchie:**
```
H1: "Mitarbeitergewinnung mit Social Recruiting – planbar, messbar, effizient"
H2: "Warum 95% aller Unternehmen beim Recruiting scheitern"  [behalten]
H2: "Wie wir in 8 Monaten 92 Mitarbeiter für Apleona Wolfferts eingestellt haben"
H2: "Unser 4-Phasen-Recruiting-System"
H3: "Phase 1: Anforderungsanalyse & Zielgruppendefinition"
H3: "Phase 2: Kampagnenentwicklung & Anzeigengestaltung"
H3: "Ergebnis: 83% Qualifizierungsquote, Ø 24h Erstgespräch"
```

---

### C.4 `/neukundengewinnung/`

**Meta Title**
```
Ist:  "Digitale Neukundengewinnung: Mit Social Media zum Erfolg"  [56 Zeichen]
```
| | SEO | Conversion |
|--|-----|------------|
| Bewertung | **B** | **C** |
| Begründung | Keyword ✅, „Digital" ✅, Länge ok | „Zum Erfolg" ist zu vage — welcher Erfolg? Welche Zahl? |
| Optimierung | „Neukundengewinnung mit Social Media & Google Ads – bis 144x ROAS" [64 Zeichen] | |

**Heading-Hierarchie `/neukundengewinnung/` — 16 H2s (kritische Überladung)**

| Tag | Ist-Text | SEO | Conv. | Problem |
|-----|----------|-----|-------|---------|
| H1 | „Neukundengewinnung mit Social Media" | **B** | **C** | Keyword ✅ aber kein Nutzenversprechen |
| H2 | „Endlich wieder Zeit das Unternehmen strategisch weiterzuentwickeln" | **D** | **B** | Kein Keyword, zu lang als Heading |
| H2 | „schnell und effektiv!" | **D** | **D** | ❌ Nur 3 Wörter, kein Kontext, nicht als H2 geeignet |
| H2 | „Schluss mit schlaflosen Nächten wegen schwankender Umsätze" | **D** | **A** | ✅ Starker Pain-Trigger, kein Keyword |
| H2 | „Red Flags im Marketing" | **C** | **A** | Pattern-Interrupt, kein Keyword |
| H2 | „3 Quick Tipps, wie Du teure Fehlentscheidungen vermeidest" | **C** | **A** | Nutzenversprechen, kein Keyword |
| H2 | „BEI KLOBER MEDIA MACHEN WIR ES ANDERS:" | **D** | **B** | Differenzierung ja, GROSSSCHREIBUNG im H2 ❌ |
| H2 | „Qualifizierte Kundenanfragen" | **C** | **C** | Zu kurz |
| H2 | „So klappt's mit den neuen Kunden!" | **D** | **C** | Kein Keyword, umgangssprachlich |
| H2 | „Erfolg braucht Partnerschaft." | **D** | **C** | Brand-Sprache |
| H2 | „Unsere Leistung" | **C** | **D** | Keyword-Potenzial, aber zu generisch |
| H2 | „Das Ergebnis? Während die Konkurrenz noch rätselt," | **D** | **B** | Halber Satz als H2 ❌ |
| **H2** | **„warum funktioniert's?"** | **D** | **D** | ❌ Fortsetzung des vorherigen H2 — Heading-Splitting |
| **H2** | **„Weil wir's smart angehen!"** | **D** | **D** | ❌ Antwort als H2 — Heading-Splitting |
| H2 | „unsere Arbeitsweise" | **C** | **D** | Zu generisch |
| H2 | „Aus Projekten werden Partnerschaften." | **D** | **C** | Brand-Sprache |
| H2 | „Effizient, partnerschaftlich und immer auf Augenhöhe" | **D** | **C** | 3 Adjektive ohne Beleg |
| H3 | „#1", „#2", „#3" | **D** | **D** | ❌ Nummern ohne Kontext sind SEO-wertlos |
| H3 | „Google Ads", „Meta Ads", „Analytics" | **B** | **C** | Keywords ✅, aber zu kurz als Headings |
| H3 | „Positionierung", „Digitalisierung", „Targetierung", „Automatisierung" | **C** | **D** | Keyword-Potenzial ungenutzt |

**Gesamtbefund `/neukundengewinnung/`:**
- **16 H2-Tags** auf einer Seite zerstören die semantische Hierarchie
- Drei H2s bilden zusammen einen Satz (Splitting) — technisch fehlerhaft
- `#1`, `#2`, `#3` als H3 sind für Google und KI-Crawler vollständig wertlos
- Stärkste Conversion-Headlines (Schlaflose Nächte, Red Flags) haben keine Keywords

**Empfohlene Korrektur-Hierarchie:**
```
H1: "Neukundengewinnung mit Social Media & Google Ads – 4,6x bis 144x ROAS"
H2: "Schluss mit schwankenden Umsätzen – so gewinnst du planbar neue Kunden"
H2: "3 Red Flags: Woran du eine schlechte Marketing-Agentur erkennst"
H2: "Unsere Leistungen für planbare Neukundengewinnung"
  H3: "Google Ads – Suchkampagnen mit messbarem ROI"
  H3: "Meta Ads – Facebook & Instagram Leadgenerierung"
  H3: "Marketing Automation – Leads zu Kunden konvertieren"
H2: "Wie wir arbeiten: Von der Analyse zum ersten Kunden"
H2: "Referenzen: 4,63 ROAS für AIKON Skincare – 144 ROAS für DIV"
```

---

### C.5 `/kontakt/`

**Meta Title**
```
Ist:  "Klober Media Kontakt – individuell, verbindlich, direkt"  [55 Zeichen]
```
| | SEO | Conversion |
|--|-----|------------|
| Bewertung | **C** | **B** |
| Begründung | Kein Keyword, „Kontakt" allein rankt nicht | 3 Adjektive sind Differenzierung, aber kein Nutzen |
| Optimierung | „Kontakt – Klober Media Online Marketing Agentur Bingen am Rhein" [61 Zeichen] | |

**Heading-Hierarchie `/kontakt/`**

| Tag | Ist-Text | SEO | Conv. | Problem |
|-----|----------|-----|-------|---------|
| H1 | „Lass uns gemeinsam über dein Projekt sprechen." | **D** | **C** | Kein Keyword, kein Nutzenversprechen, kein konkretes Angebot |
| H2 | „Du bist auf der Suche nach einem Partner, der nicht nur redet, sondern liefert? Wir sind bereit. Und du?" | **D** | **B** | Viel zu lang als H2, kein Keyword — passt als Fließtext |
| H2 | „Erfolgreiche Unternehmen die uns bereits vertrauen:" | **C** | **B** | Social Proof ✅, kein Keyword |
| H2 | „Let's Talk" | **D** | **C** | Englisch, zu kurz, kein Keyword |
| **H2** | **„Newsletter"** | **D** | **—** | ❌ Footer-Element als H2 |
| **H2** | **„Follow us"** | **D** | **—** | ❌ Footer-Element als H2 |
| **H2** | **„Navi"** | **D** | **—** | ❌ Footer-Element als H2 |
| H3 | „Regelmäßig frische Impulse. In deinem Postfach." | **D** | **C** | Newsletter-Teaser |
| H4 | „Kein Spam. Versprochen." | **D** | **B** | Vertrauenssignal ok, aber fehl am Platz |

**Gesamtbefund `/kontakt/`:**
- Footer-Tags (Newsletter, Follow us, Navi) erscheinen wieder als H2 — **siteweites Problem im Theme**
- H1 enthält kein einziges Keyword

**Empfehlung:**
```
H1: "Kontakt – Jetzt kostenfreies Erstgespräch anfragen"
H2: "In 3 Schritten zu deiner Marketingstrategie"
H2: "30+ Unternehmen vertrauen uns bereits – du auch?"
```

---

### C.6 `/unsere-arbeiten/`

**Meta Title**
```
Ist:  "Unsere Arbeiten – kreative Projekte, echte Wirkung"  [50 Zeichen]
```
| | SEO | Conversion |
|--|-----|------------|
| Bewertung | **C** | **C** |
| Begründung | Kein Keyword (weder „Social Recruiting" noch „Case Studies") | „Kreative Projekte" ist austauschbar |
| Optimierung | „Social Recruiting Referenzen – Unsere Arbeiten & Case Studies" [61 Zeichen] | |

**Heading-Hierarchie `/unsere-arbeiten/`**

| Tag | Ist-Text | SEO | Conv. | Problem |
|-----|----------|-----|-------|---------|
| **H1** | **„Unsere Arbeiten"** | **D** | **D** | ❌ Kein Keyword, kein USP, 2 Wörter ohne Mehrwert |
| H2 | „Jede Marke hat Potenzial. Wir helfen, es sichtbar zu machen." | **D** | **C** | Brand-Sprache, kein Keyword |
| H3 | Fuest, WITTE, Apleona... (Firmennamen) | **C** | **B** | Markennamen sind ok, aber kein Nutzen kommuniziert |

**Empfehlung:**
```
H1: "Social Recruiting Referenzen – 7 Fallstudien mit messbaren Ergebnissen"
H2: "Recruiting-Kampagnen: Ergebnisse unserer Kunden"
H3: "Fuest Familienstiftung – 350+ Einstellungen"  [statt nur Firmenname]
H3: "WITTE Automotive – 78% Qualifizierungsquote"
```

---

### C.7 Case-Study-Seiten (WITTE, Apleona, Fuest)

**Siteweites Problem: Doppelter H1**

Alle drei analysierten Case-Study-Seiten haben **zwei H1-Tags** — das ist ein direktes SEO-Problem:

```
WITTE:   H1: "Case-Study"  +  H1: "WITTE Automotive"
Apleona: H1: "Case-Study"  +  H1: "Apleona Wolfferts GmbH"
Fuest:   H1: "Case-Study"  +  H1: "Fuest Familienstiftung"  (+ weitere H1-Fehler)
```

**WITTE Automotive — Heading-Bewertung**

| Tag | Ist-Text | SEO | Conv. |
|-----|----------|-----|-------|
| H1 | „Case-Study" | **D** | **D** | Generisch, kein Keyword |
| H1 | „WITTE Automotive" | **D** | **C** | Firmenname ohne Kontext ❌ zweiter H1 |
| H2 | „Über das Unternehmen" | **C** | **C** | Standard |
| H2 | „Die Herausforderung" | **C** | **B** | Narrative Struktur ✅ |
| H2 | „Die Umsetzung" | **C** | **B** | Prozess-Transparenz ✅ |
| H2 | „Das Ergebnis" | **C** | **A** | ✅ High-Interest-Section |
| H2 | „Learnings" | **C** | **B** | Differenzierung durch Transparenz |
| H2 | „Du suchst das passende Personal?" | **D** | **B** | CTA-H2, kein Keyword |
| H3 | „Auslastung", „Konkurrenzdruck", „Arbeitgebermarke" | **C** | **B** | Problem-Kategorien ok |
| H4 | „Der steigende Projektbedarf brachte das bestehende Team an seine Grenzen." | **D** | **B** | Zu lang für H4, besser als Fließtext |

**Fuest Familienstiftung — Heading-Bewertung (besonders kritisch)**

Die Fuest-Seite hat **die meisten H1-Fehler** aller analysierten Seiten:

```
H1: "Case-Study"
H1: "Fuest Familienstiftung"
H1: "Über das Unternehmen"       ← sollte H2 sein
H1: "Fuest Familienstiftung"     ← Wiederholung
H1: "Die Herausforderung"        ← sollte H2 sein
H1: "Gesucht wurden u. a.:"      ← sollte H3 sein
H1: "Recruiting mit Weitblick"   ← sollte H2 sein
H1: "Die Umsetzung:"             ← sollte H2 sein
H1: "Mix aus Strategie, Content und Technologie"  ← sollte H2 sein
H1: "Das Ergebnis"               ← sollte H2 sein
H1: "Sichtbarkeit, Bewerbungen, Entlastung"  ← sollte H3 sein
H1: "Was wir gelernt haben"      ← sollte H2 sein
H1: "Und jetzt?"                 ← sollte H2 sein
```

**→ Die Fuest-Seite hat 13 H1-Tags.** Das ist der schwerste Heading-Fehler im gesamten Crawl.

---

### C.8 Gesamtauswertung: SEO-Relevanz & Conversion-Stärke

**Aggregierte Bewertung aller Seiten (Skala A–D)**

| Seite | Meta Title SEO | Meta Title Conv. | H1 SEO | H1 Conv. | H-Hierarchie | Gesamtnote |
|-------|----------------|-----------------|--------|----------|--------------|------------|
| `/` | B | C | D | B | D (Footer als H2) | **D+** |
| `/mitarbeitergewinnung/` | B | C | C | D | C | **C** |
| `/neukundengewinnung/` | B | C | B | C | D (16 H2s, Splitting) | **C–** |
| `/kontakt/` | C | B | D | C | D (Footer als H2) | **D+** |
| `/unsere-arbeiten/` | C | C | D | D | C | **D+** |
| Case Studies (WITTE, Apleona) | B | C | D (2×H1) | D | B | **C–** |
| Fuest Case Study | C | C | D (13×H1!) | D | D | **D** |

---

### C.9 Die 5 kritischsten strukturellen Fehler (Handlungsbedarf sofort)

**Fehler 1 — Footer/Navigation als H2 getaggt (siteweites Problem)**
`Newsletter`, `Follow us`, `Navi` erscheinen auf jeder Seite als H2. Das vergiftet die Heading-Hierarchie seitenübergreifend.
```
Fix: In CMS/Theme die Footer-Elemente auf <p> oder <span> umstellen
```

**Fehler 2 — Fuest Case Study: 13 H1-Tags**
Die komplette Seitenstruktur der Fuest-Seite ist als H1 ausgezeichnet. Google sieht keine Hierarchie.
```
Fix: 1 H1 behalten → alle anderen auf H2/H3 downgraden
```

**Fehler 3 — Alle anderen Case Studies: 2 H1-Tags**
„Case-Study" + Firmenname beide als H1.
```
Fix: "Case-Study" → <p class="label"> oder <span>, nur Firmenname als H1
     Besser: H1 = "[Firmenname]: [Kernergebnis]"
```

**Fehler 4 — `/neukundengewinnung/`: H2-Splitting (3 H2s bilden einen Satz)**
```
Ist:  H2: "Das Ergebnis? Während die Konkurrenz noch rätselt,"
      H2: "warum funktioniert's?"
      H2: "Weil wir's smart angehen!"

Fix:  Diese 3 Tags zu einem einzigen H2 zusammenführen oder als Fließtext
```

**Fehler 5 — H1s ohne Keyword auf Hauptseiten**
`/` → „Geiles Online Marketing, das funktioniert!" — kein indexierbares Keyword
`/kontakt/` → „Lass uns gemeinsam über dein Projekt sprechen." — kein Keyword
`/unsere-arbeiten/` → „Unsere Arbeiten" — kein Keyword

---

### C.10 Optimierte Meta Titles & H1s — Zusammenfassung (copy-ready)

| Seite | Aktueller Title | Optimierter Title | Aktueller H1 | Optimierter H1 |
|-------|-----------------|------------------|--------------|----------------|
| `/` | „Online Marketing Agentur Klober Media in Bingen am Rhein" | „Online Marketing Agentur für Recruiting & Neukundengewinnung – Klober Media" | „Geiles Online Marketing, das funktioniert!" | „Online Marketing Agentur für Recruiting und Neukundengewinnung" *(H1 technisch, Display-Headline bleibt)* |
| `/mitarbeitergewinnung/` | „Mitarbeitergewinnung durch Social Recruiting und Branding" | „Mitarbeitergewinnung mit Social Recruiting – 6.350+ Bewerbungen für KMU" | „Mitarbeitergewinnung" | „Mitarbeitergewinnung mit Social Recruiting – planbar, messbar, effizient" |
| `/neukundengewinnung/` | „Digitale Neukundengewinnung: Mit Social Media zum Erfolg" | „Neukundengewinnung mit Social Media & Google Ads – bis 144x ROAS" | „Neukundengewinnung mit Social Media" | „Neukundengewinnung mit Social Media & Google Ads – 4,6x bis 144x ROAS" |
| `/kontakt/` | „Klober Media Kontakt – individuell, verbindlich, direkt" | „Kontakt – Klober Media Online Marketing Agentur Bingen am Rhein" | „Lass uns gemeinsam über dein Projekt sprechen." | „Kontakt – Jetzt kostenfreies Erstgespräch anfragen" |
| `/unsere-arbeiten/` | „Unsere Arbeiten – kreative Projekte, echte Wirkung" | „Social Recruiting Referenzen – Fallstudien & Case Studies" | „Unsere Arbeiten" | „Social Recruiting Referenzen – 7 Fallstudien mit messbaren Ergebnissen" |
| `/unsere-arbeiten/witte-automotive-gmbh/` | „Kundenreferenz: Social Recruiting für WITTE Automotive" | „WITTE Automotive: Social Recruiting – 78% Qualifizierungsquote" | „Case-Study" + „WITTE Automotive" (2×H1) | „Social Recruiting WITTE Automotive – 78% Qualifizierungsquote, 6% CVR" |
| `/unsere-arbeiten/apleona-wolfferts/` | „Recruiting für Apleona Wolfferts – konkret & effizient" | „Apleona Wolfferts: 83% Qualifizierungsquote via Social Recruiting" | „Case-Study" + „Apleona Wolfferts GmbH" (2×H1) | „Social Recruiting Apleona Wolfferts – 92 Mitarbeiter in 8 Monaten" |
| `/unsere-arbeiten/fuest-social-recruiting/` | „Fuest Familienstiftung: Social Recruiting mit 350+ Einstellungen" | „Fuest Familienstiftung: 350+ Einstellungen via Social Recruiting" | 13×H1 (komplette Seite) | „Social Recruiting Fuest Familienstiftung – 350+ Einstellungen" |

---

*Report erstellt mit: seo-audit · page-cro · site-architecture · copywriting · ai-seo Skills*
*Skills-Quelle: github.com/KloberMedia/marketingskills/tree/main/skills*
*Datengrundlage: Live-Crawl + Screaming Frog Export (265 URLs) + Heading-Tiefenanalyse (10 Seiten), Stand März 2026*
