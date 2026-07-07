---
name: thesis-recherche
description: Wissenschaftliche Literaturrecherche auf akademischem Niveau (Bachelor bis PhD) für die Thesis "KI im operativen Projektcontrolling eines Bauunternehmens". Verwende diesen Skill IMMER, wenn Quellen, Literatur, Studien, Paper, Bücher oder Belege gesucht, geprüft, zusammengefasst oder in die Quellenliste aufgenommen werden sollen — auch bei Formulierungen wie "recherchiere", "finde Quellen", "gibt es Studien zu", "belege das" oder wenn ein Kapitel Literaturbasis braucht.
---

# Thesis-Recherche

Systematische Literaturrecherche für die Bachelorarbeit. Ziel: mindestens 30 hochwertige Quellen, ca. 50 % Standardlehrbücher / 50 % aktuelle Fachliteratur (Zeitschriften, überregionale Zeitungen, seriöse Internetquellen).

## Methodischer Rahmen: vom Brocke et al. (2009)

Die gesamte Literaturrecherche folgt dem Fünf-Phasen-Modell von vom Brocke et al. (2009), "Reconstructing the Giant", ECIS 2009, S. 2206–2217 (verifiziert):

1. **Review-Umfang definieren** (nach Coopers Taxonomie: Fokus, Ziel, Perspektive, Abdeckung, Organisation, Zielgruppe) — pro Kapitel kurz festhalten.
2. **Thema konzeptualisieren:** zentrale Begriffe und Synonyme klären, bevor gesucht wird (z.B. Projektcontrolling / project controls / cost engineering).
3. **Literatursuche:** Kombination aus Datenbank-/Schlagwortsuche, Zeitschriftensuche sowie Rückwärtssuche (Quellen der gefundenen Quellen) und Vorwärtssuche (wer zitiert die Quelle, z.B. via Google Scholar "cited by").
4. **Analyse und Synthese:** Ergebnisse in einer Konzeptmatrix ordnen (Konzepte × Quellen, nach Webster/Watson 2002), abgelegt in `02_Recherche/Konzeptmatrix.md`.
5. **Forschungslücke ableiten:** aus der Matrix begründen, was fehlt (speist Kap. 1 und Fazit).

**Dokumentationspflicht (Kernaussage von vom Brocke et al.):** Jeder Suchlauf wird im `02_Recherche/Suchprotokoll.md` protokolliert: Datum, Datenbank/Suchmaschine, Suchstring, Trefferzahl, übernommene Treffer mit Begründung. Ohne Protokolleintrag gilt eine Suche als nicht durchgeführt.

## Rechercheprozess (pro Thema/Kapitel)

1. **Suchbegriffe definieren** — deutsch UND englisch (z.B. "Projektcontrolling Bauwesen", "AI construction project controlling", "machine learning cost forecasting construction").
2. **Breit suchen, dann filtern.** Nutze Websuche/Deep-Research-Tools. Bevorzugte Quellenarten:
   - Standardlehrbücher (Controlling: z.B. Horváth, Weber/Schäffer; Bauprojektmanagement; KI-Grundlagen)
   - Peer-reviewte Zeitschriften (Controlling, ZfbF, Harvard Business Review, Automation in Construction, IEEE)
   - Aktuelle Fachbeiträge (Handelsblatt, FAZ; Branchenstudien von z.B. McKinsey, PwC, Fraunhofer — als solche kennzeichnen)
3. **Qualitätsprüfung jeder Quelle:**
   - Aktuellste Auflage / aktuellster Jahrgang? (Vorgabe Prof. Binder: immer aktuellste Primärquelle)
   - Primärquelle? Wenn Sekundärzitat: Original suchen und dieses zitieren.
   - Wissenschaftlich zitierfähig? (keine Blogs, keine Werbetexte; Wikipedia nur als Einstieg — nie zitieren)
   - Bei Internetquellen: vollständige URL + Abrufdatum festhalten.
4. **Dokumentieren** — sofort, nicht später (siehe unten).
5. **Kernaussagen exzerpieren** mit exakter Seitenzahl in `02_Recherche/` (eine Datei pro Kapitel, z.B. `Kap2_Notizen.md`). Warum sofort mit Seitenzahl: Fußnoten verlangen später exakte Seitenangaben, Nachrecherche kostet Stunden.

## Verifikation (Pflicht, vor Aufnahme in die Quellenliste)

Recherchierte Quellen enthalten oft Fehler oder existieren gar nicht (KI-Halluzinationen, veraltete Angaben, falsche Seitenzahlen). Deshalb wird JEDE Quelle vor Verwendung verifiziert:

1. **Existenz belegen:** Quelle über eine zweite, unabhängige Suche bestätigen (Verlagsseite, DOI, Bibliothekskatalog wie DNB/WorldCat, Zeitschriftenarchiv). Die Seite tatsächlich öffnen, nicht nur das Suchergebnis lesen.
2. **Bibliografische Daten abgleichen:** Autor, Jahr, Auflage, Titel, Verlagsort, Jahrgang/Heft, Seitenzahlen exakt gegen die Originalquelle prüfen.
3. **Aussage-Beleg prüfen:** Die Aussage, die belegt werden soll, muss in der Quelle tatsächlich auffindbar sein (Volltext oder Leseprobe öffnen). Nie aus dem Gedächtnis oder aus Zusammenfassungen Dritter zitieren.
4. **Unabhängige Zweitprüfung:** Bei zentralen oder überraschenden Aussagen ein zweites Recherche-Tool (z.B. perplexity-web-research oder Tavily) als unabhängigen Prüfer nutzen.
5. **Markierung:** Erst nach bestandener Prüfung mit ✓ in die Quellenliste; ungeprüfte Kandidaten separat unter "Unverifiziert" führen.

## Pflicht: Quellenliste pflegen

Jede verwendbare Quelle sofort in `01_Literatur/Quellenliste.md` eintragen, bereits im Format des Literaturverzeichnisses (Jahreszahl-Methode nach Prof. Binder):

```
Kirsch W. (1987), Einführung in die Theorie der Entscheidungsprozesse (3 Bände), Wiesbaden 1987
Mintzberg H. (1994a), The Managers Job, in: Harvard Business Review, H 7/1994, Jg. 72, 1994, S. 49-61
o.V. (2025), Titel des Artikels, https://... (abgerufen am TT.MM.JJJJ)
```

Zusätzlich je Quelle vermerken: Typ (Lehrbuch/Zeitschrift/Internet/…), Kapitel-Zuordnung, 1-Satz-Relevanz. Mehrere Werke eines Autors im selben Jahr mit a, b, c unterscheiden.

## Statistik im Blick behalten

Nach jeder Recherche-Session kurz bilanzieren: Anzahl Quellen gesamt, Verhältnis Lehrbuch/Fachliteratur, Lücken je Kapitel. Ergebnis in `THESIS_PLAN.md` (Kapitel-Tracker, Notizen) aktualisieren.

## Warnzeichen

- Quelle ohne Autor, Jahr oder Verlag → nur mit o.V./o.J./o.O. verwenden, sparsam einsetzen.
- KI-generierte oder SEO-Texte als "Studie" getarnt → verwerfen.
- Nur eine Quelle für eine zentrale Behauptung → zweite unabhängige Quelle suchen.
