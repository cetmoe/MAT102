---
layout: default
title: Kapittel 11
nav_order: 2
---

# Kapittel 11
{: .no_toc}
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Partiell derivasjon
{: .text-green-000 }

Partiell derivasjon er en måte å derivere en funksjon med to variabler. Vi deriverer med respekt til en variabel, altså vil en variabel bli sett på som en konstant. Dersom vi deriverer med respekt til $$x$$, blir $$y$$ en konstant og motsatt.

La $$f(x,y) = x^2y + \sin{y}$$. *(Obs. bruker ny notasjon $$\partial x$$ i stedet for $$dx$$.)*

$$\frac{\partial f}{\partial x} = (x^2y+\sin{y}) = 2xy$$

og

$$\frac{\partial f}{\partial y} = x^2 +\cos{y}$$

---

## Gradient vektor
{: .text-green-000 }

Gradient vektoren til en funksjon $$f(a,b)$$ kan finnes ved å kombinere de partielle derivasjonene av $$f(a,b)$$, $$f_a(a,b)$$ og $$f_b(a,b)$$.

$$\nabla f(a,b) = (\frac{\partial f}{\partial a}, \frac{\partial f}{\partial b}) = (f_a(a,b),f_b(a,b))$$

---

## Stasjonære punkt
{: .text-green-000 }

Et punkt $$(a,b)$$ er et stasjonært punkt dersom $$\nabla f(a,b) = \overrightarrow{0}$$. Altså er et punkt stasjonært dersom gradient vektoren i punktet er null.
