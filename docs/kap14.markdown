---
layout: default
title: Kapittel 14
nav_order: 3
---

# Kapittel 11
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

### Varians

$$S^2 = \frac{1}{n-1} \sum_{i=1}^{n} (\overline{X} - X_i)^2$$

### Standardavvik

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

### Varians

Varians av en stokastisk variabel.

$$Var(X) = \sum (x-E(X))\cdot P(X=x)$$

### Standardavvik

Standardavvik av en stokastik variabel.

$$Std(X) = \sqrt{Var(X)}$$

---

## Binomial fordeling
{: .text-green-000 }

Binomialfordelingen er en fordeling av tilfeldige forsøk med tilbakelegging, hvor $$n$$ er antall trekk, og $$p$$ er sjansen for trekk.

$$X \sim Bin(n,p)$$

### Forventing

$$E(X) = n\cdot p$$

### Varians

$$Var(X) = n\cdot p \cdot (1-p)$$

---

## Hypergeometrisk fordeling
{: .text-green-000 }

Hypergeometriskfordelingen er en fordeling av tilfeldige forsøk uten tilbakelegging, hvor $$N$$ er totalt antall element, $$M$$ er antall positive forsøk, og $$n$$ er antall forsøk.

$$X \sim hypergeom(N,M,n)$$

### Forventning

$$E(X) = n \cdot \frac{M}{N}$$
### Varians

$$Var(X) = n \cdot \frac{M}{N}(1-\frac{M}{N})\cdot\frac{N-n}{N-1}$$

<script type="text/javascript" id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<script>
  MathJax = {
      options: {
        enableMenu: false
      }
    }
</script>