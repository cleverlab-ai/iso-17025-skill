# DIN EN ISO/IEC 17025:2018 — Leitfaden zur Methodenvalidierung

## Wann ist eine Validierung erforderlich (7.2.2.1)

Eine Validierung ist erforderlich fuer:
- Nicht-standardisierte Verfahren
- Laborintern entwickelte Verfahren
- Normverfahren, die ausserhalb ihres vorgesehenen Anwendungsbereichs eingesetzt werden
- Modifizierte Normverfahren (Erweiterungen/Abwandlungen)

Eine Verifizierung (keine vollstaendige Validierung) ist ausreichend fuer:
- Normverfahren, die innerhalb ihres Anwendungsbereichs eingesetzt werden, um zu bestaetigen, dass das Laboratorium das Verfahren ordnungsgemaess durchfuehren kann

## Validierungsparameter (7.2.2.3)

### Zu bewertende Kenngrössen

| Parameter | Beschreibung | Wann erforderlich |
|-----------|-------------|-------------------|
| **Selektivitaet/Spezifitaet** | Faehigkeit, den Analyten ohne Stoerung durch Matrixbestandteile zu messen | Immer |
| **Linearitaet** | Bereich, in dem das Messsignal proportional zur Konzentration ist | Quantitative Verfahren |
| **Arbeitsbereich** | Konzentrations-Intervall des Analyten, fuer das das Verfahren akzeptable Ergebnisse liefert | Quantitative Verfahren |
| **Richtigkeit** | Uebereinstimmung des Mittelwerts mit dem wahren/akzeptierten Wert (Bias/Wiederfindung) | Immer bei quantitativen Verfahren |
| **Praezision — Wiederholbarkeit** | Streuung unter gleichen Bedingungen (gleicher Pruefer, gleiche Geraete, kurzer Zeitraum) | Immer |
| **Praezision — Laborinterne Vergleichbarkeit** | Streuung innerhalb des Laboratoriums (verschiedene Pruefer, Geraete, Tage) | Empfohlen |
| **Praezision — Vergleichbarkeit** | Streuung zwischen Laboratorien (aus Ringversuchen) | Wenn verfuegbar |
| **Nachweisgrenze (NWG)** | Kleinste Menge, die nachgewiesen werden kann (nicht notwendigerweise quantifiziert) | Wenn Ergebnisse nahe der NWG erwartet werden |
| **Bestimmungsgrenze (BG)** | Kleinste Menge, die mit akzeptabler Praezision/Richtigkeit quantifiziert werden kann | Spurenanalytische Verfahren |
| **Robustheit** | Widerstandsfaehigkeit gegenueber kleinen, absichtlichen Aenderungen der Verfahrensparameter | Empfohlen |
| **Messunsicherheit** | Kenngrösse, die die Streuung der dem Messobjekt zugeschriebenen Werte charakterisiert | Immer |
| **Empfindlichkeit** | Aenderung des Messsignals pro Einheit der Konzentrationsaenderung | Beim Vergleich von Verfahren |
| **Matrixeffekte** | Einfluss der Probenmatrix auf die Messung | Wenn verschiedene Matrices analysiert werden |

### Validierung mikrobiologischer Verfahren — Spezifische Parameter

| Parameter | Beschreibung |
|-----------|-------------|
| **Relative Richtigkeit** | Vergleich mit dem Referenzverfahren unter Verwendung natuerlich kontaminierter oder dotierter Proben |
| **Relative Empfindlichkeit** | Verhaeltnis der durch das Alternativverfahren im Vergleich zum Referenzverfahren erkannten positiven Ergebnisse |
| **Relative Spezifitaet** | Verhaeltnis der durch das Alternativverfahren im Vergleich zum Referenzverfahren bestaetigten negativen Ergebnisse |
| **Relative Richtigkeit (Uebereinstimmung)** | Grad der Uebereinstimmung zwischen Alternativ- und Referenzverfahren |
| **Relative NWG** | Niedrigste Kontaminationsstufe, die zuverlaessig nachgewiesen wird |
| **Inklusivitaet** | Faehigkeit, Zielorganismen aus verschiedenen Quellen nachzuweisen |
| **Exklusivitaet** | Abwesenheit falsch-positiver Ergebnisse durch Nicht-Zielorganismen |

## Aufbau des Validierungsplans

```
1. Zielsetzung
   - Welches Verfahren wird validiert
   - Vorgesehener Verwendungszweck/Anwendungsbereich (Analyten, Matrices, Konzentrationsbereiche)
   - Verweis auf Norm oder Verfahrensanweisung

2. Validierungsparameter
   - Welche Parameter bewertet werden (begruendet auf Basis des vorgesehenen Verwendungszwecks)
   - Akzeptanzkriterien fuer jeden Parameter (VOR der Validierung festgelegt)

3. Versuchsplanung
   - Anzahl der Messungen/Wiederholungen
   - Konzentrationsniveaus
   - Zu untersuchende Matrices
   - Zu verwendende Referenzmaterialien/Standards
   - Statistische Methoden zur Datenauswertung

4. Erforderliche Ressourcen
   - Personal (mit Kompetenzanforderungen)
   - Geraete und Reagenzien
   - Referenzmaterialien/Standards
   - Zeitplan

5. Akzeptanzkriterien
   - Fuer jeden Parameter VOR Beginn der Versuche festgelegt
   - Basierend auf: Kundenanforderungen, gesetzliche Grenzwerte, Leistungsziele des Verfahrens
```

## Aufbau des Validierungsberichts (7.2.2.4)

Der Validierungsbericht muss enthalten:

1. **Verfahrensidentifikation** — Titel, Version, Referenz
2. **Anwendungsbereich** — Analyt(en), Matrix/Matrices, Bereich
3. **Validierungsverfahren** — Versuchsplanung, verwendete Materialien
4. **Spezifikation der Anforderungen** — Akzeptanzkriterien
5. **Ergebnisse fuer jeden Parameter** — Daten, statistische Auswertung
6. **Erklaerung zur Eignung fuer den beabsichtigten Zweck** — Schlussfolgerung, ob das Verfahren die Anforderungen erfuellt
7. **Festgestellte Einschraenkungen oder Bedingungen** waehrend der Validierung
8. **Freigabe** — Datum, verantwortliche Person, Genehmigung

## Typische Akzeptanzkriterien — Beispiele

### Chemische Pruefung
| Parameter | Typische Kriterien |
|-----------|-------------------|
| Wiederfindung | 80-120 % (variiert je nach Konzentration und Matrix) |
| Wiederholbarkeit (RSD) | <5-10 % (abhaengig vom Konzentrationsniveau) |
| Laborinterne Vergleichbarkeit (RSD) | <10-15 % |
| Linearitaet (R^2) | >0,995 (typischerweise >0,999) |
| NWG | < 1/10 des gesetzlichen Grenzwerts |
| BG | < 1/3 des gesetzlichen Grenzwerts |

### Mikrobiologische Pruefung
| Parameter | Typische Kriterien |
|-----------|-------------------|
| Relative Richtigkeit | >90 % Uebereinstimmung mit dem Referenzverfahren |
| Relative Empfindlichkeit | >90 % |
| Relative Spezifitaet | >90 % |
| Falsch-positiv-Rate | <5 % |
| Falsch-negativ-Rate | <5 % |

## Wichtige Hinweise

- Die Validierung muss so umfangreich sein, wie es zur Erfuellung der Anforderungen des vorgesehenen Verwendungszwecks erforderlich ist (7.2.2.1)
- Wenn Aenderungen an einem validierten Verfahren vorgenommen werden, muss deren Einfluss bestimmt werden; ist dieser signifikant, muss eine erneute Validierung durchgefuehrt werden (7.2.2.2)
- Validierungsergebnisse, einschliesslich der Erklaerung zur Eignung fuer den beabsichtigten Zweck, muessen aufgezeichnet und aufbewahrt werden (7.2.2.4)
- Akzeptanzkriterien muessen VOR der Validierung festgelegt werden, nicht nachdem die Ergebnisse vorliegen
