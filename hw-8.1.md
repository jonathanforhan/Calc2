# Section 8.1

### 1. $\int_{10}^{\infty}\frac1{x^3}\space dx$

- $\lim\limits_{b\to\infty}[-\frac12x^{-2}]\Big|_{10}^{b}$

- $\lim\limits_{b\to\infty}(-\frac1{2b^{2}}+\frac1{2(10)^2})$

- $0 + \frac{1}{200} = \frac{1}{200}$

**Answer:**

- $\int_{10}^{\infty}\frac1{x^3}\space dx \space\textrm{converges to }\frac{1}{200}$

---

### 2. $\int_{e}^{\infty}\frac5{x*\ln(x)^2}\space dx$

- $5\int_{e}^{\infty}u^{-2}du$
- $u = \ln(x)$
- $du = \frac1x$
- $F(x) = -5 \ln(x)^{-1}+C$

- $\lim\limits_{b\to\infty}[\frac5{x*\ln(x)^2}]\Big|_{e}^{b}$

- $\lim\limits_{b\to\infty}(-5\ln(b) + 5\ln(e))$

- $-\infty + 5 = -\infty$

**Answer:**

- $\int_{e}^{\infty}\frac5{x*\ln(x)^2}\space dx \space \textrm{diverges}$

---

### 4. $\int_{1}^{\infty}\frac2{e^x}\space dx$

- $2\int_{1}^{\infty}e^{-x} dx$
- $F(x) = -2 e^{-x}+C$

- $\lim\limits_{b\to\infty}[\frac2{e^x}]\Big|_{1}^{b}$

- $\lim\limits_{b\to\infty}(-2e^{-b} + 2e^{-1})$

- $0 + \frac2e = \frac2e$

**Answer:**

- $\int_{1}^{\infty}\frac2{e^x}\space dx \space \textrm{converges on }\frac2e$

---

### 5. $\int_{e}^{\infty}\frac5{x*\ln(x)}\space dx$

- $5\int_{e}^{\infty}u^{-1}du$
- $u = \ln(x)$
- $du = \frac1x$
- $F(x) = 5 \ln|\ln(x)|+C$

- $\lim\limits_{b\to\infty}[\frac5{x*\ln(x)}]\Big|_{e}^{b}$

- $\lim\limits_{b\to\infty}(5\ln|\ln(b)| - 5\ln|\ln(e)|)$

- $\infty - 0 = \infty$

**Answer:**

- $\int_{e}^{\infty}\frac5{x*\ln(x)}\space dx \space \textrm{diverges}$

---

### 6. $\int_{0}^{\infty}\frac{x}{1+x^2}\space dx$

- $u = 1+x^2$
- $du = 2x$
- $\frac12\int (u)^{-1} du$
- $F(x) = \frac12 \ln|1+x^2| +C$

- $\lim\limits_{b\to\infty}[\frac{x}{1+x^2}]\Big|_{0}^{b}$

- $\lim\limits_{b\to\infty}(\frac12 \ln|1+b^2| - \frac12 \ln|1+0^2|)$

- $\infty - 0 = \infty$

**Answer:**

- $\int_{0}^{\infty}\frac{x}{1+x^2}\space dx \space \textrm{diverges}$

---
