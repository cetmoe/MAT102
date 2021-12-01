---
layout: default
title: Formelle Språk
nav_order: 3
parent: Gersting
---

# Formelle Språk
{: .no_toc}
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Notasjon
{: .text-green-000 }

- Alfabet $$V$$ = mengde av symbol.
- ord - streng med symbol fra $$V$$.
- $$V*$$, mengda av alle ord over $$V$$.
- Et språk er en delmengde av $$V*$$.

---

## Type 0 Gramatikk
{: .text-green-000 }

$$G = (V,\ V_T,\ S,\ P)$$

- $$V$$ - alfabetet
- $$V_T \subset V$$ - mengda av terminalsymbol
- $$S$$ - startsymbolet
- $$P$$ - produksjonsregler i gramatikk på forma $$\alpha \rightarrow \beta$$.

La oss definere $$V$$, $$V_t$$ og $$P$$ for et språk.

- $$V = \lbrace 0, 1, S \rbrace$$.
- $$V_t = \lbrace 0,1 \rbrace$$.
- $$P=\lbrace S\rightarrow 0\ S, S \rightarrow 1\rbrace$$.

Språket generert av gramatikken er et vilkårlig antall nuller med en 1 til slutt. Regulært uttrykkt - $$0^*1$$.

---

## Slettekonvensjonen
{: .text-green-000 }

- De eneste produksjonane som skal gi $$\lamba$$ skal være på formen $$S\rightarrow \lambda$$.
- Dersom $$S\rightarrow \lambda$$ så skal $$S$$ bare være på venstreside av produksjonane.
