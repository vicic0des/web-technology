# Labo 2 - reflecties

Naam: Victoria Mazur

## 2. Selectors lezen

Welke elementen raakt elke selector? Eén zin per selector.

- a. `header nav ul li a`: elke a in een li in een ul in nav in de header zit
- b. `article > p`: elke p die kind is van article
- c. `.uren li:nth-child(3)`: elke li die derde kind is van zijn ouder ergens binnen een element met class uren zit
- d. `h2 ~ p`: elke p die na de h2 komt binenn dezelfde ouder als de h2
- e. `.rassen li:first-child`: het eerste li kind van zijn ouder die ergen in een element van de klas rassen zit 

## 3. Voorspel, dan kijk

Vul de eerste twee kolommen in vóór je de pagina opent. Trede: herkomst, specificiteit, volgorde of overerving (of iets anders, benoem het).

| vraag | mijn voorspelling (kleur) | beslissende trede | uitkomst in de browser | juist? |
|---|-----|---|---|---|
| 1 |groen| Herkomst: auteursCSS wint |groen|juist |
| 2 |blauw | Volgorde: zelfde spec. laatste selector wint |blauw |juist |
| 3 |rood |Specifiteit: selector .opvallend wint want heeft meer classes dan em| rood | juist |
| 4 |rood |Volgorde: laatste selector wint zelfde spec. |rood |juist |
| 5 |blauw |Specifiteit: selector #v5-tekst wint want meer ids dan .een.twee.drie  |blauw|juist |
| 6 |blauw |Volgorde: laatste selector wint zelfde spec. |blauw |juist |
| 7 |rood | Overerving |rood |juist |
| 8 |rood| Herkomst: auteursCSS wint  |rood| juist |
| 9 |blauw | Specifiteit: .v9-tekst heeft meer classes| blauw|juist|
| 10 |groen |puntkomma ontbreekt |groen |juist |

Bij welke vraag zat je fout, en wat was de reden? (Alles juist? Welke vraag duurde het langst, en waarom?)
Vraag 10 duurde het langst want er stond een fout in de code.
## 4. De nabouw

- Welke selector koos je voor de links in de navigatie, en waarom geen class?
- Welke regel kostte je het meeste tijd, en wat was uiteindelijk de oorzaak?

## 6. Je site

- Welke drie waarden staan in je tokenblok, en waarom die?
- Wat verandert er in je site als je één token wijzigt?

## Thuis: R2.3 (met AI)

Prompt en onbewerkte output staan in `review/`. Minstens vijf bevindingen, elk met een verwijzing naar de sectie of het foutnummer:

1. Pixel-soep: alle lettergroottes in px, ook 16px op body (2.8, F2.9).
2. Verweesde waarden: geen tokenblok, #b5451b staat zes keer letterlijk (2.9, F2.10).
3. Overspecifieke selectors: nav ul li a en main article p a, waar nav a en main a volstaan (2.5, F2.7).
4. Hover zonder focus bij alle links (2.5, F2.11).
5. Koppen blijven vet: geen font-weight: normal, de browserstijl wint (2.7).
6. Margins, padding, borders en flex die niet in het screenshot staan (hoofdstuk 3).