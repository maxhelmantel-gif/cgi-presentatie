# Tekeningen die jij aanlevert

Leg je **handgetekende plaatjes** in de map `assets/` met **exact** deze
bestandsnamen (kleine letters). Zodra een bestand er staat, verschijnt het
automatisch op de juiste plek; tot die tijd zie je een nette "plak hier"-placeholder.

**Formaat:** vierkant (1:1), bij voorkeur **PNG met transparante achtergrond**
(anders wit). Ongeveer **600 x 600 px of groter**, tekening goed gecentreerd.

## Volgorde / lijst

| # | bestand | waar | wat erop staat (vrij in te vullen) |
|---|---------|------|-------------------------------------|
| 1 | `assets/pop.png` | POP & rol | je leerdoelen + beroepsrol "creative in the loop" |
| 2 | `assets/leerdoel1.png` | Leerdoel 1 | creative in the loop / je Kaires-muziekproduct |
| 3 | `assets/leerdoel2.png` | Leerdoel 2 | rust, focus & zichtbaarheid (podium, groei, balans) |
| 4 | `assets/reflectie.png` | Reflectie | terugkijken op jezelf (spiegel, denkwolk) |
| 5 | `assets/ethisch.png` | Ethisch dilemma | AI & makers (weegschaal, mens vs. machine) |
| 6 | `assets/visie.png` | Visie | jouw blik als mediamaker (oog, horizon, mens + AI) |
| 7 | `assets/gesprek.png` | Gespreksstarter *(optioneel)* | een tekstballon / vraagteken |

Plus het midden (dat ben jij):

| # | bestand | waar | wat |
|---|---------|------|-----|
| 0 | `assets/kind.jpg` | About me (de cirkel) | een **foto** (of tekening) van jezelf; vult automatisch de cirkel |

> De **inhoud** (teksten, bewijs, LV-indicatoren) staat al ingevuld in `index.html`
> (in het JS-object `DATA`). Je hoeft alleen nog de tekeningen toe te voegen.
> De **gespreksstarter** heeft geen eigen vak in de tekening nodig; hij staat wel
> in de legenda en in de presentatiemodus. Geef je toch `gesprek.png` mee, dan
> verschijnt die in de presentatiemodus.

## Toevoegen en online zetten
Leg de bestanden in `assets/`, en dan:
```
git add assets/
git commit -m "Tekeningen toegevoegd"
git push
```
Binnen ~1 minuut staan ze live op de GitHub Pages-link.
