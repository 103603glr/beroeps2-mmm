# Testrapport

Dit rapport bevat de resultaten van **Testronde 1** (Figma-prototype, week 1) en **Testronde 2**
(live app op Plesk, week 7). Test met **externe proefpersonen**, dus niet met je eigen groepsleden,
en altijd op een **telefoon**.

## Testprotocol

- Leg het doel uit: je test de app, niet de proefpersoon.
- Vraag de proefpersoon **hardop te denken**.
- **Niet voorzeggen** en niet helpen: noteer waar iemand vastloopt.
- Eén teamlid begeleidt, een ander noteert.
- Vraag toestemming voor eventuele opnames en bewaar geen namen als dat niet nodig is (AVG).

## Testscenario's

| Code | Scenario | Bijbehorende eis |
| --- | --- | --- |
| T1 | Ga naar het hiphopkanaal | Je kunt naar het hiphopkanaal navigeren |
| T2 | Open een artikel, lees het en speel het bijbehorende nummer af | Je kunt artikelen lezen en muziek afspelen |
| T3 | Ga naar een ander artikel en zet daarna de muziek op pauze | Je kunt naar andere artikelen gaan en muziek pauzeren |
| T4 | Doe T2 opnieuw op een laptop | De website werkt ook op een laptop |

---

## Testronde 1: Figma-prototype

**Datum:** 25-11-2026
**Afgenomen door:** Sem de Jongste - @sem103434

### Proefpersonen

| # | Leeftijd / achtergrond | Apparaat | Extern? |
| --- | --- | --- | --- |
| P1 - Thomas Blok | 17 - Nederlands | iMac | ja |
| P2 | Nog niet ingevuld | Nog niet ingevuld | ja |
| P3 | Nog niet ingevuld | Nog niet ingevuld | ja |

### Resultaten per scenario

| Scenario | Geslaagd? P1 | Tijd | Observaties |
| --- | --- | --- | --- |
| T1 | Geslaagd | 2 sec | Het navigeren naar het hiphopkanaal ging zonder problemen. |
| T2 | Niet geslaagd | Niet voltooid | Het artikel lezen werkt, maar het afspelen van muziek loopt vast. Ook werkt het bekijken van YouTube-clips niet. |
| T3 | Niet geslaagd | Niet voltooid | Naar een ander artikel gaan werkt niet. Ook kan de muziek niet worden afgespeeld en gepauzeerd. |
| T4 | Niet geslaagd | Niet voltooid | De functies werken niet goed op de laptop. |

### Bevindingen en vervolgacties

| Bevinding | Ernst (hoog/laag) | Actie of ontwerpbesluit | Issue / PR |
| --- | --- | --- | --- |
| Naar het hiphopkanaal gaan werkt goed. | Laag | Niets aanpassen. | - |
| Muziek afspelen werkt niet. | Hoog | De muziekspeler verbeteren en controleren. | Nog aanmaken |
| YouTube-clips werken niet. | Gemiddeld | Controleren waarom de video's niet afspelen. | Nog aanmaken |
| Naar andere artikelen navigeren werkt niet. | Hoog | De navigatie verbeteren. | Nog aanmaken |
| Muziek pauzeren werkt niet. | Hoog | De pauzeknop verbeteren. | Nog aanmaken |
| De website werkt niet goed op een laptop. | Hoog | Het ontwerp en de functies verbeteren voor laptops. | Nog aanmaken |

### Conclusie en gemaakte keuzes

Uit de eerste test blijkt dat het prototype nog niet helemaal goed werkt. Het navigeren naar het hiphopkanaal ging goed, maar bij de andere scenario's kwamen verschillende problemen naar voren.

Het lezen van artikelen werkt, maar muziek afspelen lukt niet. Ook werken de YouTube-video's en het navigeren naar andere artikelen nog niet goed. Daarnaast werkt het prototype niet goed op een laptop.

We gaan deze problemen verbeteren voordat we de volgende testronde uitvoeren. Vooral de muziekspeler, de navigatie tussen artikelen en de werking op een laptop krijgen extra aandacht.

Ons doel is om ervoor te zorgen dat alle scenario's bij de volgende test goed uitgevoerd kunnen worden.

---

## Testronde 2: live app op echte telefoons

**Datum:** <!-- -->
**URL:** <!-- live Plesk-URL -->
**Afgenomen door:** <!-- -->
**Netwerk-throttling gecontroleerd in Chrome DevTools:** ja / nee

### Proefpersonen (5–6, extern)

| # | Leeftijd / achtergrond | Telefoon + browser | Extern? |
| --- | --- | --- | --- |
| P1 |  |  | ja |

### Resultaten per scenario

| Scenario | Geslaagd? | Tijd | Observaties |
| --- | --- | --- | --- |
| T1 |  |  |  |

### Bevindingen, triage en verbeteringen

| Bevinding | Prioriteit | Verbetering in code | Issue / PR |
| --- | --- | --- | --- |
|  |  |  |  |

### Conclusie

<!-- Wat is er aantoonbaar beter geworden tussen Testronde 1 en 2? -->
