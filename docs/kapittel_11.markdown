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


## 2. ordens partiell derivasjon
{: .text-green-000 }

$$f_{xx} = \frac{\partial^2 f}{\partial x^2}$$

$$f_{yy} = \frac{\partial^2 f}{\partial y^2}$$

$$f_{yx} = \frac{\partial^2 f}{\partial x \partial y} = \frac{f_y}{\partial x}$$

$$f_{xy} = \frac{\partial^2 f}{\partial y \partial x} = \frac{f_x}{\partial y}$$

Dersom $$f$$ og dei deriverte av f er kontinuerlige så er

$$f_{xy} = f_{yx}$$

### Hessematrise
{: .text-green-200 }

$$ H = \begin{bmatrix}
    f_{xx} && f_{xy} \\
    f_{yx} && f_{yy}
\end{bmatrix}$$

### Hessedeterminanten
{: .text-green-200 }

$$\triangle = det(H) = f_{xx} \cdot f_{yy} - f_{xy} \cdot f{yx}$$

---

## Gradient vektor
{: .text-green-000 }

Gradient vektoren til en funksjon $$f(a,b)$$ kan finnes ved å kombinere de partielle derivasjonene av $$f(a,b)$$, $$f_a(a,b)$$ og $$f_b(a,b)$$.

$$\nabla f(a,b) = \bigg(\frac{\partial f}{\partial a}, \frac{\partial f}{\partial b}\bigg) = \big(f_a(a,b),f_b(a,b)\big)$$

---

## Stasjonære punkt
{: .text-green-000 }

Et punkt $$(a,b)$$ er et stasjonært punkt dersom $$\nabla f(a,b) = \overrightarrow{0}$$. Altså er et punkt stasjonært dersom gradient vektoren i punktet er null.

For å klassifisere de kritiske punkta.

### Minimumspunkt
{: .text-green-200 }

$$\triangle > 0$$ og $$f_{xx} > 0$$

### Maksimumspunkt
{: .text-green-200 }

$$\triangle > 0$$ og $$f_{xx} < 0$$

### Salpunkt
{: .text-green-200 }

$$\triangle < 0$$

I tilfellet der $$\triangle = 0$$ er karakteristiske trekk ukjent.
