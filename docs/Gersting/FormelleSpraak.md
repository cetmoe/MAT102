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

## Gramatikk
{: .text-green-000 }

### Type 0 gramatikk
{: .text-green-200 }

$$G = (V,\ V_T,\ S,\ P)$$

- $$V$$ - alfabetet
- $$V_T \subseteq V$$ - mengda av terminalsymbol
- $$S$$ - startsymbolet
- $$P$$ - produksjonsregler i gramatikk på forma $$\alpha \rightarrow \beta$$.

La oss definere $$V$$, $$V_t$$ og $$P$$ for et språk.

- $$V = \lbrace 0, 1, S \rbrace$$.
- $$V_t = \lbrace 0,1 \rbrace$$.
- $$P=\lbrace S\rightarrow 0\ S, S \rightarrow 1\rbrace$$.

Språket generert av gramatikken er et vilkårlig antall nuller med en 1 til slutt. Regulært uttrykkt - $$0^*1$$.

### Type 1 Gramatikk
{: .text-green-200 }

Alle produksjonane $$\alpha \rightarrow \beta$$ er $$\beta$$ minst like langt som $$\alpha$$.

### Type 2 Gramatikk
{: .text-green-200 }

Alle produksjonane $$\alpha \rightarrow \beta$$ så er $$\alpha$$ et enkelt ikkje-terminalt symbol.

### Type 3/Regulær Gramatikk
{: .text-green-200 }

Alle produksjonanene $$\alpha \rightarrow \beta$$ er et enkelt ikkje-termineralt symbol, og $$\beta$$ er på forma $$t$$ eller $$tW$$

$$\text{Type 3} \subseteq \text{Type 2} \subseteq \text{Type 1} \subseteq \text{Type 0}$$

### Hovedresultat
{: .text-green-200 }

Hvis et språk er definert ved en regulær gramatikk så kan språket beskrivast som et regulært uttrykk og det finst en aksepterande tilstandsmaskin.

---

## Slettekonvensjonen
{: .text-green-000 }

- De eneste produksjonane som skal gi $$\lambda$$ skal være på formen $$S\rightarrow \lambda$$.
- Dersom $$S\rightarrow \lambda$$ så skal $$S$$ bare være på venstreside av produksjonane.
