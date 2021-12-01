---
layout: default
title: Substitusjon i Rekker
nav_order: 2
parent: Kapittel 20
---

# Substitusjon i Rekker
{: .no_toc}
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Substitusjon
{: .text-green-000 }

La $$f(x)$$ være en Taylorrekke

$$f(x) = \sum_{n=0}^\infty a_n x^n$$

Da er rekka til $$f(u(x))$$ gitt ved

$$f(u(x)) = \sum_{n=0}^\infty a_n(u(x))^n$$

---

## Eksempel
{: .text-green-000 }

---

### Funksjon til rekke
{: .text-green-200 }

Finn Talorrekken til $$\frac{1}{1-2x}$$

$$\frac{1}{1-2x} = \frac{1}{1-u} = \sum_{n=0}^\infty u^n = \sum_{n=0}^\infty (2x)^n = \sum_{n=0}^\infty 2^nx^n$$

Vi kan også bruke substitusjon for å finne funksjonen til ei rekke.

---

### Rekke til funksjon
{: .text-green-200 }

$$\sum_{n=0}^\infty \frac{3^n}{n!}x^n = \sum_{n=0}^\infty \frac{(3x)^n}{n!} = \sum_{n=0}^\infty \frac{u^n}{n!} = e^u = e^{3x}$$
