---
layout: default
title: Chi-Kvadrat Test
nav_order: 2
parent: Kapittel 18
---

# $$\chi^2$$ test
{: .no_toc}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## En variabel
{: .text-green-000 }

Formålet med en $$\chi^2$$ test er å bestemme om det er en sammenheng mellom modell og observasjoner.

La

* $$O(i) = $$ observerte verdier.
* $$e(i) = $$ forventa verdier.

Da er:

* $$Q = \sum_i \frac{(o(i)-e(i))^2}{e(i)}$$.
* $$\alpha$$ er gitt
* $$m$$ er et utfall.

Hvis

* $$Q > Z_{\alpha,m-1}$$, er det liten sjanse for sammenheng.
* $$Q \leq Z_{\alpha,m-1}$$, er det stor sjanse for sammenheng.

---

## To variabel
{: .text-green-000 }

La $$X$$ og $$Y$$ være stokastiske variabler. $$X$$ kan har $$m$$ verdier, og $$Y$$ kan ha $$n$$ verdier.

La

* $$e(i,j) = $$ forventa utfall.
* $$o(i,j) = $$ observert utfall.

$$q = \sum_{i,j} \frac{\big( o(i,j) - e(i,j) \big)^2}{e(i,f)}$$

Hvis

* $$Q > Z_{\alpha,(m-1)(n-1)}$$ : behold $$H_0$$
* $$Q \leq Z_{\alpha,(m-1)(n-1)}$$ : velg $$H_1$$