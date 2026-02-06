# Kartenspiele

## Was brauchen wir?

### Datentyp für Farben

- `int`: 0: Kreuz, 1: Pik, ...

### Datentyp für Werte

- `int`: 2: Zwei, ..., 11: Bube, 12: Dame, 13: König, 14: Ass

### Datentyp für Karten

- Ein Paar von Farbe und Wert (ein `struct`)

### Datentyp für Kartenstapel

- Liste von Karten
- Methoden zum Mischen, Ziehen, ...

### Datentyp für Handkarten

- Liste von Karten
- Anzeige aufgefächert, ...

### Datentyp für Spieler

- `struct` mit Name und Handkarten, Kontostand

### Datentyp für das Spiel

#### Mau Mau

- `struct`:
  - Liste von Spielern
  - Kartenstapel
  - Ablagestapel

#### Poker (Texas Hold'em)

- `struct`
  - Liste von Spielern
  - Kartenstapel
  - Ein Satz Handkarten für das Board
  - Pot?

#### Black Jack

- `struct`
  - Liste von Spielern
  - Kartenstapel

## Spielvorbereitung

### Mau Mau

- Jeder Spieler bekommt 5 Karten.
- Eine Karte wird aufgedeckt

### Poker

- ...

### Black Jack

- ...

## Spielablauf

- ...
