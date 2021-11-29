---
layout: default
title: Rekker
nav_order: 1
parent: Kapittel 20
---

# Rekker
{: .no_toc}
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Geometrisk Rekke
{: .text-green-000 }

Den geometriske rekka er gitt ved

$$\frac{1}{1-x} = \sum_{n=0}^\inf x^n$$

Hvis

$$|x| < 1$$

## Taylor Rekke
{: .text-green-000 }

En taylor rekke er en rekke som tilnærmer en funksjon $$f(x)$$.

$$f(x) = \sum^{\infty}_{n=0} \frac{f^{n}(a)}{n!}(x-a)^n$$

## Konvergensintervall
{: .text-green-000 }

Intervallet av x-verdier der

$$f(x) = \sum a_nx^n$$

er gitt ved

$$L = \lim_{n\rightarrow \infty} \bigg| \frac{a_{n+1} x^{n+1}}{a_{n} x^{n}}\bigg| = \begin{cases}
    < 1, && \text{konvergent} \\
    > 1, && \text{divergent} \\
    = 1, && \text{ukjent}
\end{cases}$$

## Referansetabell
{: .text-green-000 }

| Funksjon | Rekke | Følge |
| $$\frac{1}{1-x}$$ | $$\sum_{n=0}^\infty 1 \cdot x^n = 1 + x + x^2 +...$$ | $$\lbrace 1 \rbrace_{n=0}^\infty$$ |
| $$\frac{1}{(1-x)^2}$$ | $$\sum_{n=0}^\infty (n+1) x^n = 1 + 2x + 3x^2 +...$$ | $$\lbrace n+1 \rbrace_{n=0}^\infty$$ |
| $$-\ln(1-x)$$ | $$\sum_{n=1}^\infty \frac{1}{n} x^n = x + \frac{x^2}{2} +...$$ | $$\lbrace \frac{1}{n} \rbrace_{n=1}^\infty$$ |
| $$e^x$$ | $$\sum_{n=0}^\infty \frac{x^n}{n!} = 1 + x + \frac{x^2}{2!} +...$$ | $$\lbrace \frac{1}{n!} \rbrace_{n=0}^\infty$$ |
