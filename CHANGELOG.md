# Changelog — Pipple Chess

Alle noemenswaardige wijzigingen staan hier. De versie is altijd zichtbaar in de app
(rechts van de titel in de header, op het inlogscherm en in de footer).
Nummering volgens [semver](https://semver.org/lang/nl/): MAJOR.MINOR.PATCH.

## [1.2.0] — 2026-09-11

### Toegevoegd
- Inlogscherm: je vult je naam in voordat je speelt; eerdere spelers zijn met één klik te kiezen.
- Scorekaart met partijen, winst, remise, verlies, winstpercentage, huidige en beste reeks.
- Ranglijst van alle spelers op dit apparaat.
- Knop **Wissel speler** in de header.
- Versienummer zichtbaar in header, inlogscherm en footer.

### Technisch
- Scores worden lokaal bewaard in `localStorage` onder de sleutel `pipplechess.v1`.
- Uitslagen worden eenmalig per partij geregistreerd bij mat, pat, 50-zettenregel en onvoldoende materiaal.

## [1.1.1] — 2026-09-11

### Gewijzigd
- Keuze "Tegenstander" verwijderd: je speelt altijd tegen de computer.
- Witte stukken zijn duidelijk wit: tekstweergave afgedwongen (geen emoji-glyphs meer op iOS/Safari),
  witte vulling met donkerpaarse contour.

## [1.1.0] — 2026-09-11

### Toegevoegd
- Schaakcoach **Robin** in de chat: hints met uitleg, stellingsanalyse, dreigingsdetectie,
  regeluitleg en automatische waarschuwing bij hangende stukken.
- Speelstijl van de computer instelbaar van defensief tot offensief, met merkbaar effect op de zetkeuze.
- Niveau "Pittig" hernoemd naar "Robin".

## [1.0.0] — 2026-09-10

### Toegevoegd
- Volledige schaakapplicatie in Pipple-stijl: paars tegen wit, alle regels inclusief
  rokade, en-passant, promotie, pat en de 50-zettenregel.
- Computertegenstander (negamax met alfa-bèta, quiescence) op drie niveaus.
- Hintknop, stellingsbeoordeling, zettenlijst, zet-terug en bord draaien.
- Responsieve layout voor telefoon en publicatie via GitHub Pages.
