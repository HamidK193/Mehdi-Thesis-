---
name: thesis-recherche
description: Wissenschaftliche Literaturrecherche auf akademischem Niveau (Bachelor bis PhD) für die Thesis "KI im operativen Projektcontrolling eines Bauunternehmens". Verwende diesen Skill IMMER, wenn Quellen, Literatur, Studien, Paper, Bücher oder Belege gesucht, geprüft, zusammengefasst oder in die Quellenliste aufgenommen werden sollen — auch bei Formulierungen wie "recherchiere", "finde Quellen", "gibt es Studien zu", "belege das" oder wenn ein Kapitel Literaturbasis braucht.
---

# Thesis-Recherche

Systematische Literaturrecherche für die Bachelorarbeit. Ziel: mindestens 30 hochwertige Quellen, ca. 50 % Standardlehrbücher / 50 % aktuelle Fachliteratur (Zeitschriften, überregionale Zeitungen, seriöse Internetquellen).

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
