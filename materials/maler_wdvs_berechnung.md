<!--

author:   DiAgnostiK-Coach
email:    info@gkz-ev.de
version:  0.1.0
language: de
narrator: Deutsch Male

edit: true
date: 2026-04-27

icon: ../assets/img/Logo_234px.png
logo: ../assets/img/haus_klimaqualitaet.jpg

attribute: Logo-Bild: Pixabay

comment:  Lerneinheit – WDVS Materialbedarf: Flächenberechnung, Abzüge für Fenster und Türen, Materialbedarf nach Herstellerangaben

title: WDVS Materialbedarf berechnen – Flächen, Abzüge und Mengen ermitteln

tags:   Maler,
        Lackierer,
        WDVS,
        Fassade,
        Mengenermittlung,
        Flächenberechnung,
        Materialbedarf,
        MGI,
        Mathe

link: ./style.css

import: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Piktogramme/refs/heads/main/makros.md
        https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Bildersammlung/refs/heads/main/makros.md

-->

# WDVS – Materialbedarf berechnen 🔢

Ein WDVS richtig anzubringen reicht nicht — man muss auch wissen, wie viel Material man braucht.
Zu wenig bestellen kostet Zeit, zu viel kostet Geld.
Die Kalkulation beginnt mit der Fläche — und endet mit dem Gewicht des Materials.

<!-- class="highlight" -->
In dieser Lerneinheit lernen Sie: Wie berechnet man die Nettofläche einer Fassade? Wie viel Kleber und Oberputz werden benötigt? Und wie berücksichtigt man Fenster- und Türöffnungen?

<br>

<center>

![Haus mit Wärmedämmung](../assets/img/haus_klimaqualitaet.jpg "[_Quelle: Pixabay_]")<!-- style="max-width: 550px; width: 100%" -->

</center>

## Die Formeln

    --{{0}}--
Alle Berechnungen beginnen mit denselben drei Grundformeln. Diese sollten Sie auswendig kennen — sie sind die Basis für jede Aufgabe zur Mengenermittlung.

<div>

### Die 3 Grundformeln

| Formel | Beschreibung |
|--------|-------------|
| **Bruttofläche** = Breite × Höhe | Gesamtfläche der Fassade — ohne Abzüge |
| **Nettofläche** = Bruttofläche − Abzüge | Tatsächliche Arbeitsfläche — Fenster und Türen werden abgezogen |
| **Materialbedarf** = Nettofläche × Verbrauch (kg/m²) | Menge des benötigten Materials in Kilogramm |

</div>

<!-- class="box" -->
**Merksatz:** Brutto = alles. Netto = alles minus Öffnungen. Materialbedarf = Netto × Verbrauch. Drei Formeln — immer in dieser Reihenfolge.

    --{{1}}--
In der Praxis arbeiten viele Aufgaben mit Bruttoflächen, ohne Abzüge anzugeben — weil kleinere Öffnungen in der Praxis als Verschnittreserve akzeptiert werden. In der Prüfung gilt: Wenn Abzüge angegeben sind, rechnen Sie mit Nettofläche. Wenn keine angegeben sind, rechnen Sie mit Bruttofläche.

      {{1}}
> **Merkhilfe:** „Abzüge gegeben? → Netto rechnen. Keine Abzüge? → Brutto rechnen." Nie ohne Grund Abzüge erfinden.

## Herstellerangaben: Verbrauchswerte

    --{{0}}--
Jedes Produkt hat einen vom Hersteller angegebenen Verbrauchswert in Kilogramm pro Quadratmeter. Diese Angabe steht auf der Verpackung oder im technischen Merkblatt. Für die Übungsaufgaben verwenden wir die Sto-Systemprodukte.

<div>

### Verbrauchswerte für Sto-Systemprodukte

| Produkt | Verbrauch |
|---------|-----------|
| **StoLevell Duo plus** (Klebe- und Armierungsmasse) | 5,0 kg/m² |
| **Strukturputz K 2,0** (Oberputz) | 2,5 kg/m² |

</div>

<!-- class="box" -->
**Merksatz:** Kleber/Armierung: 5,0 kg/m². Strukturputz: 2,5 kg/m². Diese Werte stehen so in den Prüfungsaufgaben.

## Beispielrechnung 1: Nur Bruttofläche (kein Abzug)

    --{{0}}--
Schauen wir uns eine typische Prüfungsaufgabe an. Die Fassade hat eine Breite von 12 Metern und eine Höhe von 7 Metern. Es gibt keine angegebenen Abzüge. Wie viel Material wird benötigt?

<div>

### Aufgabe 1: Ohne Abzüge

**Gegeben:**
- Breite: 12 m
- Höhe: 7 m
- Keine Abzüge angegeben

**Lösung:**

| Schritt | Rechnung | Ergebnis |
|---------|----------|----------|
| Bruttofläche | 12 m × 7 m | = **84 m²** |
| Nettofläche | = Bruttofläche (kein Abzug) | = **84 m²** |
| Kleber (StoLevell Duo plus) | 84 m² × 5,0 kg/m² | = **420 kg** |
| Strukturputz (K 2,0) | 84 m² × 2,5 kg/m² | = **210 kg** |

</div>

<!-- class="box" -->
**Ergebnis:** 420 kg Kleber/Armierung und 210 kg Strukturputz.

## Beispielrechnung 2: Mit Abzug für Fenster und Türen

    --{{0}}--
Dieselbe Fassade — aber diesmal sind Öffnungen angegeben: Fenster und Türen belegen zusammen 6 Quadratmeter. Die Nettofläche ist jetzt kleiner.

<div>

### Aufgabe 2: Mit Abzug (6 m² Öffnungen)

**Gegeben:**
- Breite: 12 m
- Höhe: 7 m
- Öffnungen (Fenster + Türen): 6 m²

**Lösung:**

| Schritt | Rechnung | Ergebnis |
|---------|----------|----------|
| Bruttofläche | 12 m × 7 m | = 84 m² |
| Nettofläche | 84 m² − 6 m² | = **78 m²** |
| Kleber (StoLevell Duo plus) | 78 m² × 5,0 kg/m² | = **390 kg** |
| Strukturputz (K 2,0) | 78 m² × 2,5 kg/m² | = **195 kg** |

</div>

<!-- class="box" -->
**Ergebnis:** 390 kg Kleber/Armierung und 195 kg Strukturputz — 30 kg bzw. 15 kg weniger als ohne Abzug.

## Übungsaufgaben

    --{{0}}--
Rechnen Sie die folgenden Aufgaben selbst durch — bevor Sie die Lösung aufklappen.

<div>

### Aufgabe 3: Selbst berechnen

**Gegeben:**
- Breite: 10 m
- Höhe: 8 m
- Öffnungen: 4 m²
- Produkte: StoLevell Duo plus (5,0 kg/m²) und Strukturputz K 2,0 (2,5 kg/m²)

**Gesucht:** Nettofläche, Kleber-Menge, Strukturputz-Menge

</div>

      {{1}}
<div>

### Lösung Aufgabe 3

| Schritt | Rechnung | Ergebnis |
|---------|----------|----------|
| Bruttofläche | 10 m × 8 m | = 80 m² |
| Nettofläche | 80 m² − 4 m² | = **76 m²** |
| Kleber | 76 m² × 5,0 kg/m² | = **380 kg** |
| Strukturputz | 76 m² × 2,5 kg/m² | = **190 kg** |

</div>

    --{{1}}--
Haben Sie dasselbe Ergebnis? Gut. Falls nicht: Prüfen Sie, ob Sie Brutto- oder Nettofläche als Ausgangsbasis für den Materialbedarf verwendet haben. Der Materialbedarf wird immer auf Basis der Nettofläche berechnet — wenn Abzüge angegeben sind.

## Typische Fehler in der Prüfung

    --{{0}}--
Drei Fehler tauchen bei dieser Aufgabenstellung besonders häufig auf. Vermeiden Sie sie.

<div>

### Häufige Rechenfehler — und wie man sie vermeidet

| Fehler | Problem | Lösung |
|--------|---------|--------|
| Bruttofläche statt Nettofläche verwenden | Materialbedarf wird zu hoch berechnet | Wenn Abzüge gegeben: immer Nettofläche berechnen |
| Abzüge vergessen | Materialbedarf wird zu hoch berechnet | Öffnungen aus der Aufgabenstellung lesen und abziehen |
| Falschen Verbrauchswert verwenden | Ergebnis stimmt nicht | Verbrauchswerte aus der Aufgabe ablesen — nicht schätzen |
| Einheiten verwechseln | m² × kg/m² = kg — nicht m² | Einheit immer mitrechnen: m² × kg/m² = kg |

</div>

<!-- class="box" -->
**Merksatz:** Einheiten mitrechnen. m² × kg/m² ergibt kg. Das ist keine Kleinigkeit — Einheitenfehler kosten in der Prüfung Punkte.

## Zusammenfassung – Materialbedarf WDVS

<div>

### Auf einen Blick

| Schritt | Formel / Wert |
|---------|--------------|
| Bruttofläche | Breite × Höhe |
| Nettofläche | Brutto − Abzüge (Fenster + Türen) |
| Verbrauch StoLevell Duo plus | 5,0 kg/m² |
| Verbrauch Strukturputz K 2,0 | 2,5 kg/m² |
| Materialbedarf | Nettofläche × Verbrauch (kg/m²) |

</div>

<!-- class="highlight" -->
**Nächster Schritt:** Testen Sie Ihr Wissen im Übungsmodul „MGI 1-04 – WDVS" — insbesondere den Mathe-Abschnitt zur Flächenberechnung.

<br>

<center>

![Jubel](../assets/img/colorfull_jumping.jpg "_Quelle: Pixabay, geralt_")<!-- style="max-width: 400px; width: 100%" -->

</center>
