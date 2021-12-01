---
layout: default
title: Hypotesetest
nav_order: 3
parent: Kapittel 17
---

# Hypotesetest
{: .no_toc}
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Hypotesetest
{: .text-green-000 }

Formålet med hypotesetest er å sjekke om en hypotese blir reflektert av det datasetttet vi har.

La

- $$X \sim N\big(\mu,\sigma^2\big)$$
- Anta at $$\mu$$ er ukjent.
- Anta hypotese $$H_0 : \mu = \mu_0$$.
- Alternative hypotese $$H_1 : \mu > \mu_0$$.
- Signifikantsnivå $$\alpha$$
- Vi har datasett med $$n$$ antall forsøk.

Estimatoren for forventningsverdien er $$\hat{\mu} = \frac{1}{n} \sum X_i$$, og er normalfordelt $$\hat{\mu} \sim N\bigg(\mu, \frac{\sigma^2}{n}\bigg)$$.

Vi har da noen utfall.

### $$H_1 : \mu > \mu_0$$ velg $$H_1$$ hvis:
{: .text-green-200 }

$$\hat{\mu} > \mu_0 + u_\alpha \frac{\sigma}{\sqrt{n}}$$

### $$H_1 : \mu < \mu_0$$ velg $$H_1$$ hvis:
{: .text-green-200 }

$$\hat{\mu} < \mu_0 - u_\alpha \frac{\sigma}{\sqrt{n}}$$

### $$H_1 : \mu \neq \mu_0$$ velg $$H_1$$ hvis:
{: .text-green-200 }

$$|\hat{\mu} - \mu_0 | > u_{\alpha / 2} \frac{\sigma}{\sqrt{n}}$$
