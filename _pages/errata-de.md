---
permalink: /errata-de
title: "Errata der deutschen Ausgabe"
layout: single

---

![German Cover of book *Domain-Driven Transformation*](https://dpunkt.de/wp-content/uploads/2023/07/13698.jpg){: .align-right width="20%"}

## Errata – 1. Auflage

<!-- ### Vor dem 2. Druck -->

### Kapitel 7: »Fachlichkeit stärken«

*Seite 136:* In Listing 7–3 fehlt ein Cast. Die Implementierung der Methode `equals` muss deshalb‚ sein:

```java
    @Override
    public boolean equals(Object object) {
        var andererBetrag = (Amount) object;
        return _betrag == andererBetrag._betrag
            && _waehrung == andererBetrag._waehrung;
    }
```

*Seite 147.* Im Absatz hinter Listing 7–11 heißt es: »Im Gegensatz dazu kann das Konto nur die erste Auszahlung von 100 Euro durchführen.« Das muss erweitert werden zu: »Im Gegensatz dazu kann das Konto, das von `konto2` referenziert wird, nur die erste Auszahlung von 100 Euro durchführen.«

### Teil III: »Strategische Domain-Driven Transformation«

*Seite 171:* In der Abbildung III–1 muss es links unten statt »Poduct Owner« richtig »Product Owner« heißen.

*Seite 172:* In der Liste unter »Die Struktur in diesem Teil« muss es statt »Welche **Methoden** setzen wir ein?« besser »Welche **Teilschritte** gehören zu diesem Schritt?« heißen.

### Kapitel 12: »Schritt 4 – Priorisierung und Durchführung der Umbaumaßnahmen«

*Seite 248:* Im Einschub »Im Autoleasing-Beispiel: Entitiy duplizieren« muss es im zweiten Absatz statt »das strategische Refactoring 1.1« richtig »das taktische Refactoring 1.1« heißen.

### Kapitel 14: »Fazit«

*Seite 281:* In Abbildung 14–1 muss der Arbeitsgegenstand links oben nicht nur »Source« sondern »Source Code« heißen.

### Literaturverzeichnis

*Seite 289:* Statt »Jaskula« ist die richtige Schreibweise »Jaskuła«.
