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

- $\lim\limits_{b\to\infty}(-\frac5{\ln(b)} + \frac5{\ln(e)})$

- $0 + 5 = 5$

**Answer:**

- $\int_{e}^{\infty}\frac5{x*\ln(x)^2}\space dx \space \textrm{converges to 5}$

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

### 7. $\int_{3}^{\infty}\frac{1}{x-2}\space dx$

- $u = x-2$
- $du = 1$
- $\int (u)^{-1} du$
- $F(x) = \ln|x-2| +C$

- $\lim\limits_{b\to\infty}[\frac{1}{x-2}]\Big|_{3}^{b}$

- $\lim\limits_{b\to\infty}(\ln|b-2| - \ln|3-2|)$

- $\infty - 0 = \infty$

**Answer:**

- $\int_{0}^{\infty}\frac{1}{x-2}\space dx \space \textrm{diverges}$

---

### 8. $\int_{3}^{\infty}\frac{1}{(x-2)^2}\space dx$

- $u = x-2$
- $du = 1$
- $\int (u)^{-2} du$
- $F(x) = -(x-2)^{-1} +C$

- $\lim\limits_{b\to\infty}[\frac{1}{(x-2)^{2}}]\Big|_{3}^{b}$

- $\lim\limits_{b\to\infty}(-\frac1{b-2} + \frac1{3-2})$

- $0 + 1 = 1$

**Answer:**

- $\int_{3}^{\infty}\frac{1}{(x-2)^2}\space dx \space \textrm{converges to 1}$

---

### 9. $\int_{3}^{\infty}\frac{1}{(x-2)^3}\space dx$

- $u = x-2$
- $du = 1$
- $\int (u)^{-3} du$
- $F(x) = -\frac12(x-2)^{-2} +C$

- $\lim\limits_{b\to\infty}[\frac{1}{(x-2)^{3}}]\Big|_{3}^{b}$

- $\lim\limits_{b\to\infty}(-\frac12(b-2)^{-2} +\frac12(3-2)^{-2})$

- $0 + \frac12 = \frac12$

**Answer:**

- $\int_{3}^{\infty}\frac{1}{(x-2)^3}\space dx \space \textrm{converges to }\frac12$

---

### 13. $\int_{0}^{4}\frac{1}{\sqrt{x}}\space dx$

- $\int x^{-1/2} dx$
- $F(x) = 2x^{1/2} +C$

- $\lim\limits_{b\to0}[\frac{1}{\sqrt{x}}]\Big|_{0}^{4}$

- $\lim\limits_{b\to0}(2(4)^{1/2} - 2(0)^{1/2})$

- $4 - 0 = 4$

**Answer:**

- $\int_{0}^{4}\frac{1}{\sqrt{x}}\space dx \space \textrm{converges to 4}$

---

### 14. $\int_{0}^{8}\frac{1}{^3\sqrt{x}}\space dx$

- $\int x^{-1/3} dx$
- $F(x) = \frac32x^{2/3} +C$

- $\lim\limits_{b\to0}[\frac{1}{^3\sqrt{x}}]\Big|_{0}^{8}$

- $\lim\limits_{b\to0}(\frac32(8)^{2/3} - \frac32(0)^{2/3})$

- $6 - 0 = 6$

**Answer:**

- $\int_{0}^{8}\frac{1}{^3\sqrt{x}}\space dx \space \textrm{converges to 6}$

---

### 15. $\int_{0}^{16}\frac{1}{^4\sqrt{x}}\space dx$

- $\int x^{-1/4} dx$
- $F(x) = \frac43x^{3/4} +C$

- $\lim\limits_{b\to0}[\frac{1}{^4\sqrt{x}}]\Big|_{0}^{16}$

- $\lim\limits_{b\to0}(\frac43(16)^{3/4} - \frac43(0)^{3/4})$

- $\frac{32}3 - 0 = \frac{32}3$

**Answer:**

- $\int_{0}^{16}\frac{1}{^4\sqrt{x}}\space dx \space \textrm{converges to }\frac{32}3$

---

### 16. $\int_{0}^{2}\frac{1}{\sqrt{2-x}}\space dx$

- $\int (2-x)^{-1/2} dx$
- $u = 2-x$
- $du = -1$
- $-\int (u)^{-1/2} dx$
- $F(x) = -(2-x)^{1/2} +C$

- $\lim\limits_{b\to0}[\frac{1}{\sqrt{2-x}}]\Big|_{0}^{2}$

- $\lim\limits_{b\to0}(-(2-(2))^{1/2} +(2-(0))^{1/2})$

- $0 + \sqrt{2} = \sqrt{2}$

**Answer:**

- $\int_{0}^{2}\frac{1}{\sqrt{2-x}}\space dx \space \textrm{converges to }\sqrt{2}$

---

### 18. $\int_{0}^{2}\frac{3x^2}{\sqrt{8-x^3}}\space dx$

- $u = 8-x^3$
- $du = 3x^2$
- $\int (u)^{-1/2} du$
- $F(x) = -(8-x^3)^{1/2} +C$

- $\lim\limits_{b\to0}[\frac{3x^2}{\sqrt{8-x^3}}]\Big|_{0}^{2}$

- $\lim\limits_{b\to0}(-(8-(2)^3)^{1/2} + (8-(0)^3)^{1/2})$

- $0 + \sqrt{8} = \sqrt{8}$

**Answer:**

- $\int_{0}^{2}\frac{3x^2}{\sqrt{8-x^3}}\space dx \space \textrm{converges to }\sqrt{8}$

---

### 21. $\int_{0}^{\frac\pi2}\tan(x)\space dx$

- $\textrm{domain error}$

**Answer:**

- $\int_{0}^{\frac\pi2}\tan(x)\space dx \space \textrm{diverges}$

---

### 22. Trumpet with $f(x)=\frac1x ; x> 1$

- $\int \frac1x$
- $F(x) = \ln(x)$
- $V = \pi[\ln(C) - \ln(1)]^2$

**Answer:**

- $\textrm{Volumes is not finite thus contridictory}$

---
