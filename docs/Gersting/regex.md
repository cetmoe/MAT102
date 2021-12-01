---
layout: default
title: Regulære Uttrykk
nav_order: 2
parent: Gersting
---

# Regulære Uttrykk
{: .no_toc}
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Notasjon
{: .text-green-000 }

- $$ I = \lbrace a,b,c,d,...\rbrace$$, alfabetet til språket.
- $$\lambda = $$ tom streng.
- $$\emptyset = $$ tomme mengden.
- $$(ab)(bca) = abbca$$, konkatenering.
- $$(ab)^\star = \lbrace (ab)^0, (ab)^1, (ab)^2, ... \rbrace = \lbrace \lambda, ab, abab, ... \rbrace$$, uendlig konkatenering.

---

## Kleene's Teorem
{: .text-green-000 }

I følge Kleene's teorem finnes det for alle regulære uttrykk en endelig tilstandsmaskin som aksepterer uttrykket.

Som følge av det finnes det også altid et regulært uttryk for en endelig tilstandsmaskin.

---

## Minimering av Tilstandsmaskiner
{: .text-green-000 }

Målet er å finne en enklere måte å bygge opp tilstandsmaskinen.

Vi begynner med å teste hvilke verdier som er ekvivalente for strenger av lengde 0.

La oss si at vi får en oppdeling:

$$\lbrace S_0, S_2, S_5 \rbrace, \lbrace S_1, S_3, S_4 \rbrace$$

Vi sjekker nå verdiene i mengdene vi har om de er ekvivalente for strenger av lengde 1. Vi tester om $$S_0, S_2, S_5$$ er ekvivalente og om $$S_1, S_3, S_4$$ er ekvivalente.

Da får vi kanskje en slik oppdeling og ser at $$S_0, S_2$$ er ekvivalent, men ikke $$S_5$$:

$$\lbrace S_0, S_2 \rbrace, \lbrace S_5 \rbrace, \lbrace S_1, S_3, S_4 \rbrace$$

Nå sjekker vi for verdier som er ekvivalente for streng med lengde 2. Vi skjekker bare de leddene som forandret seg fra forrige iterasjon, altså $$S_0$$ og $$S_2$$.

Vi får kanskje samme resultat som før:

$$\lbrace S_0, S_2 \rbrace, \lbrace S_5 \rbrace, \lbrace S_1, S_3, S_4 \rbrace$$

Dette vil da si at det er den minste tilstandsmaskinen som representerer uttrykket vårt.

---

## Eksempel
{: .text-green-000 }

Et regulært uttrykk $$1^*0(01)*$$ har uendelig mange utfall.

Eksempel på uttrykk som er i mengda:

- $$0$$.
- $$111100101$$.
- $$1001$$.

Eksempel på uttrykk som *ikkje* er i mengda:

- $$01$$, middelleddet er ikkje oppfyllt.
- $$101$$, igjen er ikke middelleddet oppfyllt.
- $$10011$$, endar på $11$.
