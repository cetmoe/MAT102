---
layout: default
title: Endelige Tilstandsmaskiner (FSM)
nav_order: 1
parent: Gersting
---

# Endelige Tilstandsmaskiner (FSM)
{: .no_toc}
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Nøkkelord
{: .text-green-000 }

- Maskina er synkronisert med klokkepulser.
- Maskina er deterministisk
- Endelig antall tilstander.

---

## Definisjon (Finite state machine)
{: .text-green-000 }

En endelig tilstandsmaskin består av

$$M = [S, I, O, fs, fo]$$

- $$S$$ - mengden av alle tilstander til maskina.
- $$I$$ - mengen av input symbol.
- $$O$$ - mengden av output symbol.
- $$fs: S \times I \rightarrow S$$, tilstands funksjon eller overgangsfunksjon.
- $$fo: S \rightarrow O$$, output funksjon.
- Vi har en basis tilstand : $$S_0$$.

---

## Eksempel
{: .text-green-000 }

Tilstander: $$S = \lbrace S_0, S_1, S_2 \rbrace$$
Input: $$I = \lbrace 0,1 \rbrace$$
Output: $$I = \lbrace 0,1 \rbrace$$

Tilstandstabell:

| Tilstand | 0 | 1 | Output |
| $$S_0$$ | $$S_1$$ | $$S_0$$ | 0 |
| $$S_1$$ | $$S_2$$ | $$S_1$$ | 1 |
| $$S_2$$ | $$S_2$$ | $$S_0$$ | 1 |

Finn output av input 0 1 1 0 1:

$$S_0 \rightarrow S_1 \rightarrow S_1 \rightarrow S_1 \rightarrow S_2 \rightarrow S_0$$

Output er altså: 0 1 1 1 1 0

[Tilstands graf](https://i.imgur.com/8gsbal5.png)

---

## Aksepterende tilstand
{: .text-green-000 }

En aksepterende tilstand er en eller flere tilstander som indikerer at input til tilstandsmaskinen er godkjent.

---

## Paritets test
{: .text-green-000 }

Formålet med en paritets test er å sjekke om informasjon er gått tapt. Det gjør en ved å bruke en bit til å representere at det er et partall antall enere i informasjonen.

Vi kan bruke en tilstandsmaskin for å sjekke om uttrykket inneholder partall enere.

| | 0 | 1 | Output |
| $$S_0$$ | $$S_0$$ | $$S_1$$ | 1 |
| $$S_1$$ | $$S_1$$ | $$S_0$$ | 0 |
