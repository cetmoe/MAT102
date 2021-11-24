---
layout: default
title: Kapittel 17
nav_order: 4
---

# Kapittel 17
{: .no_toc}
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Normalfordelingen
{: .text-green-000 }

En stokastisk variabel $$X$$ er normalfordelt med gjennomsnitt $$\mu$$ og varians $$\sigma ^2$$

$$X\sim N(\mu,\sigma^2)$$

dersom tetthetsfunksjonen er

$$f(x) = \frac{1}{\sqrt{2\pi}\sigma}e^{-\dfrac{(x-\mu)^2}{2\sigma ^2}}$$

### Errorfunksjonen

$$\text{erf}(x) = \frac{2}{\sqrt{\pi}}\int_0^x e^{-t^2} dt$$

Errorfunksjonen er en hjelpefunksjon som blir brukt til å regne ut arealet mellom midtverdien $$\mu$$ og en variabel $$b$$ under grafen til normalfordelinga.

$$P(X \leq b) = \frac{1}{2} +\frac{1}{2}\text{erf}(\frac{b-\mu}{\sqrt{2}\sigma})$$

Graf representasjon av hvordan error funksjonen blir brukt.

![Alt text](./assets/svg/normal_fordeling.svg){: width="650px" .align-center}

---
