# Integration Review

### 1. Write and evaluate two integrals that involve only basic antiderivative rules. You may copy problems from the Calculus I Review HW or create your own problems.

- $F(x)=\int\cos(x)dx$

  - $f(x)=\sin(x)+C$

- $F(x)=\int e^x dx$
  - $f(x)=e^x+C$

---

### 2. Write and evaluate two integrals that require u-substitution. You may copy problems from the Section 4.6 Problems or create your own problems.

- $F(x)=\int \cos(4x) dx$

  - $u=4x$
  - $du=4dx$
  - $f(x)=\frac14\sin(4x)+C$

- $F(x)=\int e^{3x} dx$
  - $u=3x$
  - $du=3dx$
  - $f(x)=\frac13 e^{3x}+C$

---

### 3. Write and evaluate two integrals that require integration by parts. You may copy problems from the Section 8.3 Problems or create your own problems.

$\int udv=uv-\int vdu$

- $xe^{-x}dx$

  - $u=x$
  - $du=dx$
  - $v=-e^{x}$
  - $dv=e^{-x}dx$
  - $x(-e^{-x})-\int -e^{-x}dx$
  - $-xe^{-x}+\int e^{-x}dx$
  - $-xe^{-x}-e^{-x}+C$

- $\int x^4\ln(x)dx$
  - $u=\ln(x)$
  - $du=\frac1x dx$
  - $v=\frac15x^5$
  - $dv=x^4dx$
  - $\ln(x)*\frac15x^5 - \int \frac15x^5 \frac1x dx$
  - $\ln(x)*\frac15x^5 - \int \frac15x^4 dx$
  - $\ln(x)*\frac15x^5 - \frac1{25}x^5+C$

---

### 4. Write and evaluate two integrals that require partial fraction decomposition. You may copy problems from the Section 8.4 Problems or create your own problems.

- $\frac{7x+2}{x(x+1)}$

  - $7x+2=A(x+1)+Bx$
  - $7(0)+2=A(1)+B(0)$
  - $A=2$
  - $7(-1)+2=A(-1+1)+B(-1)$
  - $B=5$
  - $f(x)=\frac2x + \frac5{x+1}$

- $\frac{7x+9}{(x+3)(x-1)}$
  - $7x+9 = A(x-1) + B(x+3)$
  - $7(-3)+9 = A(-4) + B(0)$
  - $A=3$
  - $7(1)+9 = A(0) + B(4)$
  - $B=4$

---

### 5. When faced with an integral on the final exam, explain how you will decide with integration technique (basic antiderivative rules, u-substitution, integration by parts, or partial fraction decomposition) to use to evaluate the integral.

If I see that the problem looks to be resultant from a chain rule derivative I will try
u-substitution, if not and it has two things multiplied together I will try integration by parts,
lastly if it is a fraction I will try fraction decomposition.
