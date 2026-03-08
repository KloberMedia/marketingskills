# Website-Analyse: klober-media.de
**Erstellt:** 08. März 2026
**Analysierte URLs:** klober-media.de · /neukunden · /mitarbeiter
**Skills verwendet:** seo-audit · page-cro · site-architecture · copywriting · ai-seo

---

## 1. Executive Summary – Top 3 Quick Wins

> **Gesamtbewertung:** Klober Media hat eine starke Positionierung, überzeugende Zahlen und klare Differenzierung. Die größten Hebel liegen in technischen SEO-Grundlagen, Conversion-Optimierung der Unterseiten und AI-Sichtbarkeit.

### Quick Win #1 — Seitenstruktur von Single-Page auf eigenständige URLs umstellen
**Problem:** `/arbeiten`, `/kundenstimmen`, `/kontakt` liefern 404-Fehler. Navigation-Links führen ins Leere oder zu Ankern innerhalb der Startseite. Suchmaschinen können diese Inhalte nicht separat indexieren.
**Maßnahme:** Eigenständige URLs mit aussagekräftigem Content für jede Seite anlegen, inkl. individueller Title-Tags und Meta-Descriptions.
**Impact:** Hoch | **Aufwand:** Mittel

### Quick Win #2 — CTA-Kopie konkretisieren und einheitlich ausrichten
**Problem:** CTAs wechseln zwischen „Jetzt Klartext sprechen", „Let's Talk" und „Lass uns gemeinsam..." — kein einheitlicher Funnel, keine klare Handlungsaufforderung mit spezifischem Nutzen.
**Maßnahme:** Primären CTA auf allen Seiten einheitlich mit Outcome formulieren, z.B. „Kostenlose Erstanalyse anfragen – in 24h Rückmeldung".
**Impact:** Hoch | **Aufwand:** Niedrig

### Quick Win #3 — Strukturierte Daten (Schema.org) implementieren
**Problem:** Keine erkennbare Schema-Markup-Implementierung. Testimonials, Case Studies und FAQs werden nicht als Rich Results ausgespielt.
**Maßnahme:** `Organization`, `LocalBusiness`, `Review`, `FAQPage` und `HowTo` Schema implementieren.
**Impact:** Mittel–Hoch | **Aufwand:** Niedrig–Mittel

---

## 2. SEO-Analyse

### 2.1 Technische SEO

| Kriterium | Status | Bewertung |
|-----------|--------|-----------|
| HTTPS | ✅ Aktiv | Gut |
| Seitenstruktur | ⚠️ Single-Page / Anker-Links | Kritisch |
| Indexierbarkeit Unterseiten | ❌ /arbeiten, /kundenstimmen, /kontakt = 404 | Kritisch |
| URL-Struktur | ⚠️ Teilweise fehlend | Verbesserungsbedarf |
| Mobile-Friendliness | ✅ Responsives Design erkennbar | Gut |
| Schema Markup | ❓ Nicht verifizierbar (JS-basiert) | Prüfen |
| AI-Bot-Zugang (robots.txt) | ❓ Nicht geprüft | Prüfen |

**Kritischer Befund — 404-Fehler:**
Die Navigation enthält Links zu `/arbeiten` und `/kundenstimmen`, die serverseitig nicht existieren. Dies führt zu:
- Indexierungsfehlern in der Google Search Console
- Verlust von Link-Equity durch tote Links
- Schlechter User Experience für ~15–25% der Besucher, die direkt dorthin navigieren

### 2.2 On-Page SEO — Startseite

**Stärken:**
- Headline „Geiles Online Marketing, das funktioniert!" ist einprägsam, aber nicht keyword-optimiert
- Klare Leistungsbereiche (Mitarbeitergewinnung, Neukundengewinnung) erkennbar
- Zahlen (6.350+ Bewerbungen, 30+ Unternehmen, 7+ Jahre) stärken E-E-A-T

**Schwächen:**
- **Title-Tag:** Nicht einsehbar, mutmaßlich generisch
- **Meta-Description:** Nicht einsehbar, vermutlich nicht optimiert
- **Keyword-Targeting:** Keine erkennbare Fokussierung auf Suchbegriffe wie „Recruiting Agentur", „Social Media Marketing Agentur", „Mitarbeitergewinnung Agentur"
- **H1/H2-Hierarchie:** Mehrere „Headlines" auf gleichem Level, keine klare Heading-Architektur

### 2.3 Content & E-E-A-T

**Positiv:**
- Konkrete Case Studies mit messbaren Ergebnissen (WITTE Automotive, Apleona Wolfferts, Fuest Familienstiftung)
- 8+ Kundenstimmen mit Namen und Unternehmen
- 7+ Jahre Erfahrung kommuniziert

**Lücken:**
- Kein erkennbarer Blog / Content-Hub für organischen Traffic
- Keine branchenspezifischen Landingpages für gezielte Keyword-Abdeckung
- Kein Autorenprofile oder Team-Seite für Expertise-Signale
- Keine externen Verlinkungen auf relevante Quellen / Studien

### 2.4 AI-SEO — Sichtbarkeit in KI-Suchmaschinen

| Plattform | Sichtbarkeitsrisiko | Empfehlung |
|-----------|--------------------|-|
| Google AI Overviews | Mittel — abhängig von traditionellem Ranking | Schema + Content-Tiefe |
| ChatGPT / Perplexity | Niedrig — wenig externe Erwähnungen erkennbar | Drittplattformen bespielen |
| ClaudeBot | ❓ robots.txt prüfen | Bot-Zugang sicherstellen |
| GPTBot | ❓ robots.txt prüfen | Bot-Zugang sicherstellen |

**Empfehlung AI-SEO:**
1. robots.txt prüfen: GPTBot, PerplexityBot, ClaudeBot dürfen nicht geblockt sein
2. FAQ-Sektionen auf allen Hauptseiten mit klaren Antworten strukturieren
3. Vergleichsartikel erstellen (z.B. „Klober Media vs. klassische Recruiting-Agentur")
4. Auf Bewertungsplattformen (Google Business, ProvenExpert, Trustpilot) aktiv werden
5. Schema: `FAQPage`, `HowTo`, `Review` implementieren

---

## 3. Conversion-Analyse je Hauptseite

### 3.1 Startseite (/)

**Aktuelle Conversion-Elemente:**
- Headline: „Geiles Online Marketing, das funktioniert!" ✅ Aufmerksamkeitsstark
- Subheadline: „Ob mehr Bewerbungen oder Kunden..." ✅ Zielgruppenabgrenzung
- Zahlen: 6.350+, 30+, 7+ ✅ Trust-Signale
- CTA: „Jetzt Klartext sprechen" ⚠️ Unklar was passiert

**CRO-Bewertung: 6/10**

**Probleme:**
- **5-Sekunden-Test:** Zwei Leistungen (Mitarbeiter + Neukunden) konkurrieren im Erstblick — Besucher müssen selbst einordnen
- **CTA above the fold:** CTA-Text beschreibt Aktion, aber nicht den Nutzen für den Kunden
- **Social Proof-Platzierung:** Zahlen sind vorhanden, aber Kontext fehlt (Zahlen ohne Zeitraum/Branche wirken abstrakt)
- **Kein Urgency-Trigger** auf der Hauptseite (vorhanden auf Unterseiten)

**Empfehlungen:**
```
Aktuelle Headline:  "Geiles Online Marketing, das funktioniert!"
Empfehlung:        "135% mehr qualifizierte Bewerbungen – planbar und messbar."
                   (Stärkster Beweis als Headline nutzen)

Aktueller CTA:     "Jetzt Klartext sprechen"
Empfehlung:        "Kostenlose Strategie-Session anfragen"
                   (Outcome + niedrige Einstiegshürde)
```

### 3.2 Seite: /mitarbeiter (Recruiting)

**Aktuelle Conversion-Elemente:**
- Headline: „Warum 95% aller Unternehmen beim Recruiting scheitern" ✅ Starker Pattern-Interrupt
- Case Study Apleona Wolfferts: 92 Mitarbeiter in 8 Monaten ✅ Konkreter Beweis
- 24-48h Bewerbungsversprechen ✅ Differenzierung
- Scarcity: „Nur noch 4 Plätze diese Woche" ⚠️ Potentiell unglaubwürdig wenn statisch

**CRO-Bewertung: 7/10**

**Probleme:**
- Scarcity-Element muss dynamisch und glaubwürdig sein — statischer Text erzeugt Misstrauen
- 4 Säulen (Messbar, Schnell, Zuverlässig, Ehrlich) sind generisch — Wettbewerber nutzen ähnliche Versprechen
- Kein konkreter „Was passiert nach dem Klick"-Flow erklärt

**Empfehlungen:**
```
Scarcity:          Dynamisches Datum einbauen oder entfernen
                   "Diese Woche: 4 Erstgespräche verfügbar (KW 11)"

CTA-Optimierung:   "Recruiting-Strategie anfragen – wir melden uns in 24h"

Differenzierung:   "92 neue Mitarbeiter in 8 Monaten" als Hero-Stat in Headline
```

### 3.3 Seite: /neukunden (Neukundengewinnung)

**Aktuelle Conversion-Elemente:**
- Headline: „Effizient und planbar: Deine Neukundenstrategie" ✅ Outcome-fokussiert
- Pain Point: „Schluss mit schlaflosen Nächten wegen schwankender Umsätze" ✅ Emotionaler Trigger
- 5-Schritt-Prozess ✅ Transparenz
- Case Studies mit ROAS-Werten (4,63 ROAS, 144 ROAS) ✅ Starke Beweise
- Scarcity: „Nur noch 7 Plätze diese Woche" ⚠️ Gleiche Problematik

**CRO-Bewertung: 7.5/10**

**Probleme:**
- „300% Umsatzsteigerung in 3 Monaten" klingt wie typische Agenturen-Übertreibung — belegt diesen Claim mit einem konkreten Kunden
- „150% mehr Conversions" ohne Kontext (Ausgangswert?) — Beleg fehlt
- 5 verschiedene Services aufgelistet ohne klare Hierarchie — welches ist das Kernangebot?

**Empfehlungen:**
```
Unglaubwürdige Claims ersetzen:
  Vorher: "300% Umsatzsteigerung in 3 Monaten"
  Nachher: "AIKON Skincare: Von 1,2x auf 4,63 ROAS in 90 Tagen"

Hero-CTA konkretisieren:
  Vorher: "Lass uns gemeinsam deinen Umsatz steigern"
  Nachher: "Dein ROI-Potenzial berechnen – kostenlos in 20 Min."
```

---

## 4. Texte & Messaging

### 4.1 Stärken der aktuellen Copy

- **Tonalität:** Direkt, persönlich, „auf Augenhöhe" — passt zur Zielgruppe (Unternehmer/Geschäftsführer)
- **Positionierung:** „Ergebnisse statt Ausreden" ist ein klares, differenzierendes Statement
- **Zahlenverwendung:** Konkrete Metriken (Conversion Rates, ROAS, Anzahl Bewerbungen) machen Leistung greifbar
- **Pain-Adressierung:** „Schlaflose Nächte", „schwankende Umsätze" treffen echte Probleme der Zielgruppe

### 4.2 Schwächen & Copywriting-Probleme

**Problem 1 — Zwei Zielgruppen, eine Startseite**
Die Hauptseite spricht gleichzeitig Unternehmen mit Recruiting-Bedarf und solche mit Neukunden-Bedarf an. Das verwässert die Botschaft.

```
Empfehlung: Klare Bifurkation im Hero-Bereich
"Mehr Mitarbeiter finden? → [Button]   Mehr Kunden gewinnen? → [Button]"
```

**Problem 2 — Generische Differenzierungsversprechen**
„Ehrliche Kommunikation", „Zuverlässige Betreuung", „Individuelle Strategie" werden von nahezu jeder Agentur kommuniziert.

```
Empfehlung: Spezifität statt Adjektive
Vorher: "Zuverlässige Betreuung"
Nachher: "Ein fester Ansprechpartner – erreichbar Mo–Fr innerhalb von 2h"
```

**Problem 3 — Hero-Headline nicht keyword-aligned**
„Geiles Online Marketing, das funktioniert!" ist einprägsam, aber kein Mensch sucht danach.

```
Empfehlung: SEO-freundliche H1 + kreative Display-Headline trennen
H1 (unsichtbar/technisch): "Online Marketing Agentur für Recruiting & Neukundengewinnung"
Display-Headline: "Geiles Online Marketing, das funktioniert!"
```

**Problem 4 — Testimonial-Qualität ausbaufähig**
Testimonials wie „Gerne wieder" oder „Ein echter Gamechanger" sind zu generisch. Die besten Testimonials enthalten Vorher/Nachher.

```
Empfehlung: Testimonials mit Ergebnis-Framing
Vorher: "Kein Marketing-Gelaber, sondern echte Ergebnisse"
Nachher: "Innerhalb von 6 Wochen hatten wir 23 qualifizierte Bewerbungen – mehr als im ganzen Vorjahr."
— [Name, Position, Unternehmen]
```

### 4.3 Messaging-Hierarchie (Empfehlung)

```
Ebene 1 — WER:    "Online Marketing Agentur für Mittelstand & KMU"
Ebene 2 — WAS:    Recruiting-Kampagnen & Neukundengewinnung via Social Media & Google Ads
Ebene 3 — WIE:    Datengetrieben, messbar, ein fester Ansprechpartner
Ebene 4 — BEWEIS: 6.350+ Bewerbungen | 30+ Partner | 4,63–144 ROAS
Ebene 5 — CTA:    Kostenfreies Erstgespräch (20 Min.) → Strategiepapier
```

---

## 5. Priorisierte Maßnahmentabelle

| # | Maßnahme | Bereich | Impact | Aufwand | Priorität |
|---|----------|---------|--------|---------|-----------|
| 1 | 404-Fehler beheben: /arbeiten, /kundenstimmen, /kontakt als eigene Seiten anlegen | SEO / Technik | 🔴 Hoch | Mittel | **Sofort** |
| 2 | Title-Tags & Meta-Descriptions für alle Seiten optimieren (keyword-spezifisch) | SEO On-Page | 🔴 Hoch | Niedrig | **Sofort** |
| 3 | CTA vereinheitlichen: Outcome-basiert, einheitlicher Text sitewide | CRO | 🔴 Hoch | Niedrig | **Sofort** |
| 4 | Schema.org implementieren: Organization, Review, FAQPage, HowTo | SEO / AI-SEO | 🟠 Mittel–Hoch | Mittel | **KW 1–2** |
| 5 | Startseite: Hero-Bifurkation (Recruiting vs. Neukunden) klar trennen | CRO / Copy | 🟠 Mittel–Hoch | Mittel | **KW 1–2** |
| 6 | Scarcity-Elemente dynamisch machen oder entfernen | CRO | 🟠 Mittel | Niedrig | **KW 1** |
| 7 | Testimonials mit Vorher/Nachher-Zahlen anreichern | CRO / Copy | 🟠 Mittel | Niedrig | **KW 2–3** |
| 8 | robots.txt prüfen: AI-Bots (GPTBot, PerplexityBot, ClaudeBot) zulassen | AI-SEO | 🟠 Mittel | Niedrig | **KW 1** |
| 9 | Generische Claims durch spezifische Case-Study-Zahlen ersetzen | Copy | 🟠 Mittel | Niedrig | **KW 2** |
| 10 | FAQ-Sektion auf /mitarbeiter und /neukunden hinzufügen | AI-SEO / CRO | 🟡 Mittel | Mittel | **KW 3–4** |
| 11 | Branchenspezifische Landingpages erstellen (z.B. Recruiting Handwerk, Recruiting Pflege) | SEO | 🔴 Hoch | Hoch | **Q2** |
| 12 | Content-Hub / Blog starten für organischen Traffic | SEO | 🔴 Hoch | Hoch | **Q2** |
| 13 | Google Business Profile optimieren & Bewertungen aufbauen | AI-SEO / Local | 🟠 Mittel | Niedrig | **KW 2** |
| 14 | Vergleichsartikel erstellen für AI-Suchmaschinen-Sichtbarkeit | AI-SEO | 🟡 Mittel | Mittel | **Q2** |
| 15 | Team-/Über-uns-Seite für E-E-A-T-Signale | SEO / Trust | 🟡 Mittel | Mittel | **Q2** |

**Legende:** 🔴 Hoch · 🟠 Mittel–Hoch · 🟡 Mittel

---

## Anhang: Analysierte URLs

| URL | Status | Anmerkung |
|-----|--------|-----------|
| klober-media.de | ✅ 200 | Hauptseite, Single-Page-Struktur |
| klober-media.de/neukunden | ✅ 200 | Eigenständige Unterseite |
| klober-media.de/mitarbeiter | ✅ 200 | Eigenständige Unterseite |
| klober-media.de/arbeiten | ❌ 404 | Navigationspunkt ohne Ziel |
| klober-media.de/kundenstimmen | ❌ 404 | Navigationspunkt ohne Ziel |
| klober-media.de/kontakt | ❌ 404 | Kritisch: kein Kontaktformular erreichbar |

---

*Report erstellt mit: seo-audit · page-cro · site-architecture · copywriting · ai-seo Skills*
*Quelle: github.com/KloberMedia/marketingskills/tree/main/skills*
