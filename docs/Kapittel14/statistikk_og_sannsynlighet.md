---
layout: default
title: Sannsynlighet og Statistikk
parent: Kapittel 14
nav_order: 1
---

# Statistikk og Sannsynlighet
{: .no_toc }
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Statistikk
{: .text-green-000 }

### Gjennomsnitt

En verdi som beskriver en mengde med tall.

$$ \overline{X} = \frac{1}{n} \sum_{i=1}^{n} x_i$$

### Generell Varians

$$S^2 = \frac{1}{n-1} \sum_{i=1}^{n} (\overline{X} - X_i)^2$$

### Generell Standardavvik

En verdi som beskriver forskjellen fra tallene in en mengde fra gjennomsnittet.

$$S = \sqrt{S^2}$$

---

## Sannsynlighet
{: .text-green-000 }

### Utfall

Et utfall et mulig resultat av et tilfeldig forsøk.

### Hendelse

Mengden av mulige utfall.

### Stokastisk Variabel

En variabel som er avhengig av et utfall av en tilfeldig hendelse.

$$P(X=x)$$

---

## Sannsynlighet kombinert med statistikk
{: .text-green-000 }

### Forventning

Den forventa verdien av en stokastisk variabel.

$$E(X) = \sum x \cdot P(X=x)$$

Nyttig omgjøring

$$E(aX+b) = aE(X)+b$$

### Varians

Varians av en stokastisk variabel.

$$Var(X) = \sum \big(x-E(X)\big)\cdot P(X=x)$$

Nyttig omgjøring

$$Var(aX+b) = a^2Var(X)$$

### Standardavvik

Standardavvik av en stokastik variabel.

$$Std(X) = \sqrt{Var(X)}$$
