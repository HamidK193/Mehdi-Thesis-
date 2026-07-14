# Kapitel 1: Einleitung (Entwurf v3, nach QS-Iteration 2)

Fußnoten in eckigen Klammern, werden bei Übertragung nach Word als echte Fußnoten gesetzt.

---

## 1.1 Problemstellung und Praxisrelevanz

Bauprojekte gehören zu den besonders komplexen Vorhaben der betrieblichen Praxis.[1] Viele Beteiligte, lange Laufzeiten, wechselnde Rahmenbedingungen und ein hoher Termin- und Kostendruck treffen auf eine Branche, deren Wertschöpfung stark von Unikaten geprägt ist. Jedes Bauwerk entsteht unter eigenen Bedingungen: mit eigenem Baugrund, eigener Baustellenlogistik und einem projektspezifischen Geflecht aus Auftraggebern, Planern, Nachunternehmern und Behörden.[2] Das operative Projektcontrolling soll in diesem Umfeld Transparenz über Termine, Kosten, Risiken und Leistungsfortschritt schaffen. Es legt damit die Grundlage für eine wirksame Projektsteuerung.[3]

In der Praxis stößt diese Aufgabe auf erhebliche Hindernisse. Daten werden vielfach manuell erfasst und ausgewertet, Berichte entstehen mit zeitlichem Verzug, und Abweichungen fallen oft erst auf, wenn ihre Ursachen bereits Wochen zurückliegen.[4] Die Möglichkeit, frühzeitig gegenzusteuern, sinkt entsprechend. Gerade im Bau führen kleine Störungen im Ablauf regelmäßig zu spürbaren Auswirkungen auf Kosten und Termine, weil Gewerke aufeinander aufbauen und sich Verzögerungen fortpflanzen.[5] Klassische Controllinginstrumente wie Soll-Ist-Vergleiche und Kennzahlenberichte geraten an ihre Grenzen, wenn Datenmengen groß und unstrukturiert sind oder Auswertungen unter Zeitdruck benötigt werden.[6]

Zugleich verfügen viele Bauunternehmen inzwischen über umfangreiche digitale Projektdaten aus Kalkulation, Bauzeitenplanung, Abrechnung und Bautagesberichten. Systematisch für Prognosen oder Frühwarnzwecke genutzt werden diese Bestände bislang selten.[7] Verfahren der Künstlichen Intelligenz (KI) versprechen hier einen Zugewinn. Sie können große Datenbestände auswerten, Muster erkennen und Prognosen unterstützen, etwa bei der Früherkennung von Termin- und Kostenabweichungen.[8] Dem stehen allerdings ernstzunehmende Hürden gegenüber: Die Qualität der Prognosen hängt von der Qualität und Verfügbarkeit der zugrunde liegenden Daten ab, der Aufbau entsprechender Kompetenzen bindet Ressourcen, und die Einbindung in gewachsene Prozesse wirft organisatorische Fragen auf.[9] Ob und wie sich das Potenzial der KI im operativen Projektcontrolling eines Bauunternehmens tatsächlich erschließen lässt, ist damit eine offene Frage von unmittelbarer praktischer Bedeutung. Sie stellt sich umso dringlicher, je stärker der Wettbewerbs- und Margendruck der Branche eine effiziente, datenbasierte Projektsteuerung verlangt.[10]

## 1.2 Zielsetzung, Forschungsfrage und Innovationsgehalt

Zu Projektcontrolling, Digitalisierung und KI liegt jeweils umfangreiche Literatur vor. Eine konkrete Verbindung dieser Themen im Baukontext fehlt jedoch häufig. Ein erheblicher Teil der Beiträge bleibt entweder technisch orientiert oder allgemein gehalten; praxisnahe Vorgehensmodelle, die organisatorische, datenbezogene und prozessuale Voraussetzungen der Einführung zusammenführen, sind rar.[11] Diese Lücke greift die vorliegende Arbeit auf.

Die Untersuchung folgt der Forschungsfrage: Wie kann Künstliche Intelligenz im operativen Projektcontrolling eines Bauunternehmens schrittweise und praxistauglich implementiert werden? Daraus leiten sich drei Teilfragen ab. Erstens: Welche Aufgaben und Instrumente prägen das operative Projektcontrolling im Bauunternehmen, und wo liegen die Grenzen der klassischen Vorgehensweise? Zweitens: Welche KI-Verfahren eignen sich für welche Controllingaufgaben, und welche Voraussetzungen verlangen sie? Drittens: Wie lässt sich die Einführung so gestalten, dass sie im Projektalltag eines Bauunternehmens trägt?

Ziel der Arbeit ist es, ein Vorgehensmodell zur Implementierung von KI im operativen Projektcontrolling eines Bauunternehmens zu entwickeln und anhand eines Fallbeispiels zu erproben. Dabei wird gezeigt, wie KI das Termin-, Kosten-, Risiko- und Fortschrittscontrolling unterstützen kann. Die Untersuchung arbeitet zudem heraus, unter welchen Bedingungen sich der Einsatz lohnt und wo seine Grenzen liegen. Am Ende steht eine praxisnahe Handlungsempfehlung, die aufzeigt, wie Bauunternehmen KI schrittweise und wirtschaftlich sinnvoll in bestehende Controllingprozesse integrieren können.

Der Innovationsgehalt liegt in der anwendungsbezogenen Verknüpfung zweier Themenfelder, die in der Literatur überwiegend getrennt behandelt werden. Die Arbeit entwickelt kein abstraktes KI-Modell, sondern ein Vorgehensmodell für den Projektalltag. Der Fokus liegt auf der praktischen Umsetzbarkeit, nicht allein auf der theoretischen Beschreibung. Nicht Gegenstand der Arbeit sind die technische Entwicklung eigener KI-Algorithmen sowie das strategische Controlling; die Untersuchung konzentriert sich auf die operative Ebene der Projektsteuerung.

## 1.3 Vorgehensweise und Aufbau der Arbeit

Methodisch ist die Untersuchung als Literaturarbeit mit Fallbeispiel angelegt. Die Literaturrecherche folgt dem Fünf-Phasen-Modell von vom Brocke et al., das eine nachvollziehbare Dokumentation des Suchprozesses verlangt.[12] Zunächst werden Umfang und Ziel des Reviews festgelegt und die zentralen Begriffe geklärt. Anschließend erfolgt die Suche in Datenbanken und Fachverlagen, ergänzt um Rückwärts- und Vorwärtssuche ausgehend von Schlüsselquellen. Die gefundene Literatur wird konzeptorientiert ausgewertet und in einer Konzeptmatrix geordnet, wie sie Webster und Watson für Literaturanalysen vorschlagen.[13] Sämtliche Suchläufe sind in einem Suchprotokoll dokumentiert, das im Anhang wiedergegeben wird. Für die Quellenauswahl gilt der Grundsatz, stets die aktuellste Auflage beziehungsweise den aktuellsten Jahrgang der Primärquelle heranzuziehen.

Der Gang der Untersuchung ergibt sich aus der Zielsetzung. Kapitel 2 legt die Grundlagen des operativen Projektcontrollings im Bauunternehmen dar und arbeitet die Besonderheiten von Bauprojekten sowie die Grenzen klassischer Instrumente heraus. Kapitel 3 führt in die Künstliche Intelligenz ein und zeigt ihre Einsatzfelder im Controlling sowie den Stand der Anwendung im Bauwesen. Kapitel 4 analysiert das Fallbeispiel, ein konkretes Bauprojekt mit typischen Controllingproblemen wie Terminverzug, Kostenabweichungen und unzureichender Transparenz. Auf dieser Basis entwickelt Kapitel 5 das Vorgehensmodell für die Implementierung. Kapitel 6 erprobt das Modell im Bauprojekt des Fallbeispiels. Kapitel 7 bewertet die Ergebnisse und benennt Nutzen, Grenzen und Erfolgsbedingungen des KI-Einsatzes. Kapitel 8 leitet daraus Handlungsempfehlungen für die Praxis ab, bevor Kapitel 9 die Arbeit mit einem Fazit und einem Ausblick abschließt.

---

## Fußnoten (Belegstand)

[1] Vgl. Girmscheid G. (2016). [BELEG PRÜFEN: Seitenzahl nach PDF-Eingang — Komplexität von Bauprojekten]
[2] Ebenda. [BELEG PRÜFEN: Seitenzahl — Unikatcharakter/Projektbeteiligte; ebenda-Regel: unmittelbar auf FN1 (Girmscheid 2016) folgend]
[3] Vgl. Fiedler R. (2020). [BELEG PRÜFEN: Seitenzahl — Aufgaben des Projektcontrollings]
[4] Vgl. Langmann C. (2019). [BELEG PRÜFEN: Seitenzahl — manuelle Prozesse/Berichtsverzug im Controlling; falls dort nicht gedeckt: Branchenstudie Bau-Digitalisierung ergänzen]
[5] Vgl. Kochendörfer B./Liebchen J.H./Viering M.G. (2021). [BELEG PRÜFEN: Seitenzahl — Gewerkeabhängigkeiten/Terminrisiken]
[6] Vgl. Weber J./Schäffer U. (2022). [BELEG PRÜFEN: Seitenzahl — Grenzen klassischer Instrumente bei großen Datenmengen]
[7] [BELEG PRÜFEN: Beleg erforderlich — geringe systematische Datennutzung im Bau; Kandidaten: Branchenstudie (McKinsey/PwC/Fraunhofer) oder Abioye et al. (2021); bis dahin Aussage als Beobachtung der Fallstudienpraxis kennzeichnen oder abschwächen]
[8] Vgl. Abioye S.O. et al. (2021). [BELEG PRÜFEN: genaue Fundstelle im OA-PDF]
[9] Vgl. Schneider T. (2025). [BELEG PRÜFEN: Seitenzahl — Voraussetzungen/Hürden KI im Controlling; alternativ Ertel W. (2025) für Datenabhängigkeit]
[10] Vgl. Kochendörfer B./Liebchen J.H./Viering M.G. (2021). [BELEG PRÜFEN: Seitenzahl — Wettbewerbs-/Kostendruck Bauwirtschaft]
[11] Vgl. Haghsheno S. et al. (Hrsg., 2024). [BELEG PRÜFEN: Fundstelle im PDF — Einleitungs-/Grundlagenkapitel zur Lücke praxisnaher Implementierung; ggf. Abioye et al. (2021), Future Challenges, ergänzen. Geändert 13.07.2026 wegen Sprachregel: Pan/Zhang gestrichen]
[12] Vgl. vom Brocke J. et al. (2009), S. 2206-2217. [Präzisierung der Fundstelle (Framework-Abschnitt) nach PDF-Eingang]
[13] Vgl. Webster J./Watson R.T. (2002), S. xiii-xxiii. [Präzisierung der Fundstelle (Konzeptmatrix) nach PDF-Eingang]

## Notizen für QS/Übertragung

- Umfang Entwurf v3: ca. 790 Wörter Fließtext ≈ 2,5 Word-Seiten (Arial 12, 1,5-zeilig, inkl. Fußnotenapparat knapp 3). Bewusste Entscheidung (Entscheidungslog): nicht künstlich strecken. 1.3 wächst planmäßig um einen Methodikabsatz zum Fallbeispiel (und ggf. Experteninterview WBL), sobald Kap. 4 steht; Zielgröße 3,5 bis 4 Seiten wird damit erreicht.
- Änderungen ggü. v1 (QS-Mängel 1-8): Superlativ abgeschwächt + Fußnote an Satz 1 [M3]; unbelegte Praxis-Behauptungen jetzt belegt bzw. markiert [M1, M2, M7-Fußnote]; Fußnote 4 auf eine Quelle festgelegt [M5]; Forschungslücken-Beleg mit Prüfvermerk und Abschwächungsoption [M6]; explizite Forschungsfrage + drei Teilfragen + Abgrenzung ergänzt [M7]; Grenzen/Hürden der KI substanziell in 1.1 aufgenommen [Ausgewogenheit]; Tripel reduziert und wörtliche Doppelung „Chancen, Grenzen und Voraussetzungen" beseitigt [M4]; Umfangsangabe korrigiert [M8].
- Weber/Schäffer: vor Abgabe prüfen, ob 18. Aufl. (2026) erschienen ist (Beschaffungsliste).
