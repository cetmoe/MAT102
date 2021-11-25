---
layout: default
title: Konfidensintervall
nav_order: 2
parent: Kapittel 17
---

# Kapittel 17
{: .no_toc}
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Konfidensintervall
{: .text-green-000 }

Målet med et konfidensintervall er å finne et intervall $$[a,b]$$ der en med $$(1-\alpha)$$ % sikkerhet vet at gjennomsnittet ligger i intervallet.

### Hvilke faktorer påvirker resultatet?

- Antall målinger
- Hvor sikker en vil være, $$95$$ %? $$99%$$ %?

### Framgangsmåte

Bakgrunn:

- Anta at $$X_1,X_2,...,X_n$$ er et sett med normalfordelte stokastiske variabler. $$X_i \sim N(\mu,\sigma^2)$$.
- Anta at $$\mu$$ er ukjent.
- Anta at $$\sigma^2$$ er kjent.

La estimatoren $$\hat{\mu} = \frac{1}{n}\sum X_i$$, og er normalfordelt $$\hat{\mu}\sim N(\mu,(\frac{\sigma}{\sqrt{n}})^2)$$.

Da er $$(1-\alpha)$$ - konfidensintervallet for $$\mu$$ gitt ved

$$\hat{\mu} \pm u_{\alpha/2} \cdot \frac{\sigma}{\sqrt{n}}= \bigg[\hat{\mu}-u_{\alpha/2} \cdot \frac{\sigma}{\sqrt{n}},\hat{\mu}+u_{\alpha/2} \cdot \frac{\sigma}{\sqrt{n}}\bigg]$$

Hvor $$u_\alpha$$ er en konstant.

### Lengde av konfidensintervall

Formel for å finne antall forsøk som trengs for at lengden av intervallet skal være $$\leq k$$

$$\begin{align*}
\hat{\mu}+u_{\alpha/2} \cdot \frac{\sigma}{\sqrt{n}} - (\hat{\mu}-u_{\alpha/2} \cdot \frac{\sigma}{\sqrt{n}}) &\leq k\\
2u_{\alpha/2} \cdot \frac{\sigma}{\sqrt{n}} &\leq k \\
2u_{\alpha/2} \cdot \sigma &\leq k\sqrt{n} \\
\bigg(2\frac{u_{\alpha/2} \cdot \sigma}{k}\bigg)^2 &\leq n
\end{align*}$$

---

## $$u_\alpha$$ tabell.

| $$u_\alpha$$ | $$\alpha$$ | Sikkerhet |
|:-------------|:-----------|:----------|
| $$2.576$$ | $$0.01$$ | $$99$$ % konf. int.|
| $$1.960$$ | $$0.05$$ | $$95$$ % konf. int.|
| $$1.645$$ | $$0.1$$ | $$90$$ % konf. int.|
