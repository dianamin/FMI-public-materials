
Ecuatii Diferentiale si cu Derivate Partiale
============================================

[TOC]


> **NU SE GARANETAZA CORECTITUDINEA SAU COMPLETITUDINEA INFORMATIILOR DE AICI**

> Ai descoperit o greseala? Ai facut o tema si vrei sa o dai si colegilor? Stii cum sa faci ceva sa arate mai bine? Contribuie [direct pe GitHub](https://github.com/Vlaaaaaaad/FMI-public-materials/tree/master/EcuatiiDiferentialeSiCuDerivatePartiale) sau trimite un mail la <mailto:stiu-chestii@vladionescu.me>

#Ecuatii diferentiale de tip primitiva( in $\mathbb{R}$)

Se da o functie $f : I \subset \mathbb{R} \to \mathbb{R}$ continua si se cere sa se determine multimea functiilor $F : I \to \mathbb{R}$ care verifica conditiile:
 - $F$ sa fie derivabila pe $I$
 - verifica ecuatia diferentiala $F'(x) = f(x)$, $\forall x \in I$ sau $\frac{\operatorname{d}\!F}{ \operatorname{d}\!x} (x) = f(x)$, $\forall x \in I$
Problema e echivalenta cu a determina primitivele lui $f(x)$.

$F(x) = \int f(x) \operatorname{d}\!x$
$C$ este multimea functiilor constante
$C + C = C$
$\alpha C = C$

**Exerctiu**: Sa se determine multimea solutiilor ecuatiei $\frac {\operatorname{d}\!F} { \operatorname{d}\!x} = f(x)$ pentru urmatoarele functii $f$.

1. $f(x) = 3 x^2 + \frac {1}{x} - 2 \sqrt{x} + \sqrt[3]{x^2}$, cu $x \in (0, \infty)$
2. $f(x) = 2^x - 2 \frac{1}{3^x} $, cu $x \in \mathbb{R}$
3. $f(x) = 4 \sin(x) - \cos(x)$, cu $x \in \mathbb{R}$
4. $f(x) = \frac{1}{\sin^2{x}} + \frac{1}{\cos^2{x}}$, cu $x \in (0, \frac{\pi}{2})$
5. $f(x) = \frac{1}{sin^2{x} \cos^2{x}}$, cu $x \in (0, \frac{\pi}{2})$
6. $f(x) = \tan{x} + \cot{x}$, cu $x \in (0, \frac{\pi}{2})$
7. $f(x) = \frac{1}{x^2 + 9} + \frac{1}{x^2 - 9}$, cu $x \in ( - 3, 3)$
8. $f(x) = \frac{1}{\sqrt{x^2 + 9}} + \frac{2}{\sqrt{x^2 - 9}} - \frac{1}{\sqrt{36 - x^2}}$, cu $x \in (3,6)$
9. $f(x) = \frac{2x^2}{(x^2 + 2)(x^2 - 2)}$, cu $x \in( - 2,2)$
10. $f(x) = x \ln x$, cu $x > 0$
11. $f(x) = x e^x$, cu $x \in \mathbb{R}$
12. $f(x) = \sqrt{1 - x^2}$, cu $x \in ( - 1,1)$
13. $f(x) = \frac{x}{\sqrt{x^2 + 1}}$, cu $x \in \mathbb{R}$
14. $f(x) = e^{3x} \sin(x)$, cu $x \in \mathbb{R}$
15. $f(x) = \frac {e^{2 \sin{x}}}{\sqrt{1 - x^2}}$, cu $x \in ( - 1, 1)$
16. $f(x) = \frac{1}{x \sqrt{x^2 - 1}}$, cu $x \in (1, \infty)$
17. $f(x) = \sqrt{x^2 - 3x + 2}$, cu $x \in (2, + \infty)$
18. $f(x) = \frac{2 \cos{x}}{\sin{x} + \cos{x}}$, cu $x \in (0, \frac{\pi}{2})$
19. $f(x) = {1}{x \sqrt{x^2 + x + 1}} $, cu $x > 0$
20. $f(x) = \frac{1}{x \sqrt{x^4 - x^2 + 1}}$, cu $x < 0$

*Rezolvari*:

1. $$ F(x) = \int \left(3 x^2 + \frac{1}{x} - 2\sqrt{x} + \sqrt[3]{x^2}\right) \operatorname{d}\!x \\
 F(x) = \int 3 x^2 \operatorname{d}\!x + \int \frac{1}{x} \operatorname{d}\!x - \int 2 \frac{1}{x^2} \operatorname{d}\!x + \int x^{\frac{2}{3}} \operatorname{d}\!x \\
 = 3 \frac{x^3}{3} + \ln|x| - 2 \frac{2x^{\frac{3}{2}}}{3} + \frac{3 x^{\frac{5}{3}}}{5} + C \\
 = x^3 + \ln x - \frac{4}{3} \sqrt{x^3} + \frac{3}{5}\sqrt[3]{x^5} + C $$

2. $$F(x) = \int(2^x - 2 \frac{1}{3^x}) \operatorname{d}\!x \\
 = \int 2^x \operatorname{d}\!x - 2 \int (\frac{1}{3})^x \operatorname{d}\!x \\
 = \frac{2^x}{\ln2} - 2 \frac{(\frac{1}{3})^x}{\ln\frac{1}{3}} + C $$

3. $$ F(x) = \int(4 \sin{x} - \cos{x}) \operatorname{d}\!x = \\
 = 4 \int \sin{x} \operatorname{d}\!x - \int \cos{x} \operatorname{d}\!x \\
 = 4 \cos{x} - \sin{x} + C$$

4. $$F(x) = \int\left(\frac{1}{\sin^2 x} + \frac{1}{\cos^2 x}\right) \operatorname{d}\!x = \\
 - \cot x + \tan x + C$$

5. $$F(x) = \int \frac{1}{\sin^2 x \cos^2 x} \operatorname{d}\!x = \\
 = \int \frac{\sin^2 x + \cos^2 x}{\sin^2 x \cos^2 x} \operatorname{d}\!x \\
 = \tan x - \cot x + C$$

6. $$F(x) = \int(\tan x \cot x) \operatorname{d}\!x = \\
 = - \ln|\cos x| + \ln| \sin x| + C$$

7. $$F(x) = \int \left(\frac{1}{x^2 + 9} + \frac{1}{x^2 - 9}\right) \operatorname{d}\!x \\
 = \frac{1}{3} \arctan \frac{x}{3} + \frac{1}{6} \left|\frac{x - 3}{x + 3}\right| \\
 = \frac{1}{3} \arctan \frac{x}{3} + \frac{1}{6} \ln\left(\frac{3 - x}{x - 3}\right) + C$$

8. $$F(x) = \int \left(\frac{1}{\sqrt{x^2 + 9}} \frac{2}{\sqrt{x^2 - 9}} - \frac{1}{\sqrt{36 - x}}\right) \operatorname{d}\!x \\
 = \ln (x + \sqrt{x^2 + 9} + \ln \left|x + \sqrt{x^2 - 9}\right|) - \arcsin \frac{x}{6} + C$$

9. $$F(x) = \int \frac{(x^2 + 2) + (x^2 - 2)}{(x^2 + 2)(x^2 - 2)} \operatorname{d}\!x \\
 = \int \frac{1}{x^2 - 2} \operatorname{d}\!x + \int \frac{1}{x^2 - 2} \operatorname{d}\!x \\
 = \frac{1}{2\sqrt{2}} \ln \left|\frac{x - \sqrt{2}}{x + \sqrt{2}}\right| + \frac{1}{\sqrt{2}} \arctan \frac{x}{\sqrt{2}} + C$$

10. **tema**

11. **tema**

12. $$F(x) = \int \sqrt{1 - x^2} \operatorname{d}\!x \\
 = \int x' \sqrt{1 - x^2} \operatorname{d}\!x \\
 = x \sqrt{1 - x^2} - \int x\left(\sqrt{1 - x^2}\right)' \operatorname{d}\!x \\
 = x \sqrt{1 - x^2} - \int x \frac{ - 2x}{2 \sqrt{1 - x^2}} \operatorname{d}\!x = x \sqrt{1 - x^2} - \int \frac{1 - x^2 - 1}{\sqrt{1 - x^2}} \operatorname{d}\!x \\
 = x \sqrt{1 - x^2} - \int \frac{1 - x^2}{\sqrt{1 - x^2}} \operatorname{d}\!x + \int \frac{1}{\sqrt{1 - x^2}} \operatorname{d}\!x \\
 = x \sqrt{1 - x^2} - \int \sqrt{1 - x^2} \operatorname{d}\!x + \arcsin x \\
 \\
 \implies 2\int\sqrt{1 - x^2} \operatorname{d}\!x = x \sqrt{1 - x^2} + \arcsin x + C$$

13. **tema**

14. **tema**

15. $$ F(x) = \int \frac{e}{\sqrt{1 - x^2}} \operatorname{d}\!x \\
 \\
 \text{Notam } t = 2 \arcsin x \\
 \frac{1}{2}\operatorname{d}\!t = \frac{1}{\sqrt{1 - x^2}} \operatorname{d}\!x \\
\frac{1}{2} \int e^t \operatorname{d}\!t = \frac{1}{2} e^t + C \\
 \implies F(x) = \frac{1}{2} e^{\arcsin x} + C$$

16. $$F(x) = \int \frac{1}{x \sqrt{x^2 - 1}} \\
 = \int \frac{1}{x^2 \sqrt{1 - \frac{1}{c^2}}}\operatorname{d}\!x \\
 \text{Notam } \frac{1}{x} = t \text{ si } - \frac{1}{x^2}\operatorname{d}\!x = \operatorname{d}\!t \\
 = - \int \frac{1}{\sqrt{1 - t^2}}\operatorname{d}\!t = \\
 - \arcsin t + C = \\
 - \arcsin \frac{1}{x} + C $$

17. **tema**

18. **tema**

19. **tema**

20. **tema**


#Ecuatii diferentiale cu variabile separabile

**Exercitiu**: Sa se determine multimea solutiilor ecuatiilor urmatoare:
1. $\frac{\operatorname{d}\!x}{\operatorname{d}\!t} = \frac{x^2 - 2x - 8}{t^2 - 4}$, cu $x \in \mathbb{R} \text{ si } t \in (2, \infty)$
2. $\frac{\operatorname{d}\!x}{\operatorname{d}\!t} = (1 + \tan^2 t)(1 + \cot^2 x)$, cu $x, t \in (0, \frac{\pi}{2})$
3. $\frac{\operatorname{d}\!x}{\operatorname{d}\!t} = \frac{\sqrt{x^2 + 1}}{t^2 + 1}$, cu $x, t \in \mathbb{R}$
4. $\frac{\operatorname{d}\!x}{\operatorname{d}\!t} = \frac{2t(x^2 - 9)}{t^2 + 1}$, cu $x \in (0, \infty) \text{ si } t \in \mathbb{R}$
5. $\frac{\operatorname{d}\!x}{\operatorname{d}\!t} = \frac{1}{t^2 + 9} (x^2 + 4x + 5)$, cu $x, t \in \mathbb{R}$

*Rezolvari*:
1. $$ \text{ Identificam } a(t) = \frac{1}{t^2 - 4} \text { si } b(x) = x^2 - 2x - 8 \\
 \text{ Rezolvam } b(x) = 0 \implies x^2 - 2x - 8 = 0 \implies x_1 = 4 \text{ si } x_2 = - 2 \text{ care sunt in domeniu }\\
 \implies \text{ avem solutiile } \varphi_1, \varphi_2 : (2, + \infty) \to \mathbb{R} \text{ cu } \varphi_1(t) = 4 \text{ si }\varphi_2(t) = - 2 \\
 \text{ Pentru } x \in \mathbb{R} - \{ - 2, 4\} \text{ separam variabilele } \frac{\operatorname{d}\!x}{x^2 - 2x - 8} = \frac{\operatorname{d}\!t}{t^2 - 4} \\
 \int \frac{1}{x^2 - 2x - 8}\operatorname{d}\!x = \int \frac{1}{(x - 4)(x + 2)}\operatorname{d}\!x \\
 \text{Luam } \frac{1}{(x - 4)(x + 2)} = \frac{A}{x - 4} + \frac{B}{x + 2} \implies A = \frac{1}{6} \text{ si } B = - \frac{1}{6} \\
 \implies = \frac{1}{6} \int \frac{1}{x - 4}\operatorname{d}\!x - \frac{1}{6} \int \frac{1}{x + 2}\operatorname{d}\!x \\
 = \frac{1}{6} \ln|x - 4| - \frac{1}{6} \ln(x + 2) = \\
 \frac{1}{6} \ln \left|\frac{x - 4}{x + 2}\right| + c \implies B(x) = \frac{1}{6} \ln\frac{x - 4}{x + 2} \\
 \\
 \int\frac{1}{t^2 - 4}\operatorname{d}\!t = \frac{1}{4} \ln \left|\frac{t - 2}{t + 2}\right| + c \\
 A(t) = \frac{1}{4} \ln \left|\frac{t - 2}{t + 2}\right| \\
 B(x) = A(t) + C \\
 \frac{1}{6} \ln \left|\frac{x - 4}{x + 2}\right| = \frac{1}{4} \ln \left|\frac{t - 2}{t + 2}\right| \\
 \ln\left|\frac{x - 4}{x + 2}\right| + C = \ln\left|\frac{t - 2}{t + x}\right|^{\frac{3}{2}} + 6C \\
 = \frac{x - 4}{x + 2} = \pm \left(\frac{t - 2}{t + 2}\right)^{\frac{3}{2}} e^{6C} = \pm e^{6C}\sqrt{\frac{t - 2}{t + 2}^3} \implies x - 4 = (x - 2) e^{6C} \sqrt{\frac{t - 2}{t + 2}^3} \\
 \implies x\left(1 - e^{6C} \sqrt{\frac{t - 2}{t + 2}^3}\right) = 2 e^{6C} \sqrt{\frac{t - 2}{t + 2}^3} + 4 \\
 \implies x = \frac{2 e^{6C} \sqrt{\frac{t - 2}{t + 2}^3} + 4}{1 - e^{6C} \sqrt{\frac{t - 2}{t + 2}^3}} \\
\text{ Deci avem multimea solutiilor formata din } x = \frac{2 e^{6C} \sqrt{\frac{t - 2}{t + 2}^3} + 4}{1 - e^{6C} \sqrt{\frac{t - 2}{t + 2}^3}} \\
\text{ si } \varphi_1, \varphi_2 : (2, + \infty) \to \mathbb{R} \text{ cu } \varphi_1(t) = 4 \text{ si }\varphi_2(t) = - 2$$
2. **tema**
3. **tema**
4. **tema**
5. **tema**

#Ecuatii diferentiale omogene

**Exercitiu**: Sa se determine multimea solutiilor ecuatiilor urmatoare:
1. $\frac{\operatorname{d}\!x}{\operatorname{d}\!t} = \frac{2xt}{x^2 - t^2}$ cu $ x \in ( - 1,1) \text{ si } t \in(2, 10)$
2. $\frac{\operatorname{d}\!x}{\operatorname{d}\!t} = \frac{x}{t} - e^{\frac{x}{t}}$ cu $, t > 0, x \in \mathbb{R}$
3. $\frac{\operatorname{d}\!x}{\operatorname{d}\!t} = \frac{t^2x + x^3}{t^3}$ cu $, t > 0, x \in \mathbb{R}$
4. $\frac{\operatorname{d}\!x}{\operatorname{d}\!t} = \frac{x^2}{t^2} = \frac{t}{x}$, cu $t,x > 0$

*Rezolvari*:
1. $$ f(t,x) = \frac{2xt}{x^2 - t^2} \\
 f(\alpha t, \alpha x) = \frac{2\alpha^2xt}{\alpha^2x^2 - \alpha^2t^2} = \frac{2xt}{x^2 - t^2} = f(x, t) \implies \text{ ecuatia este omogena} \\
\text{Facem schimbarea de variabila } y(t) = \frac{x(t)}{t} \implies x = ty \\
 \text{Ecuatia devine, deci } \frac{\operatorname{d}}{\operatorname{d}\!t}(ty) = \frac{2t^2y}{t^2y^2 - t^2} \\
 \implies y + t \frac{\operatorname{d}\!y}{\operatorname{d}\!t} = \frac{2y}{y - 1} \implies \frac{\operatorname{d}\!y}{\operatorname{d}\!t} = \left(\frac{2y}{y^2 - 1} - y\right)\frac{1}{t} \text{ care este ecuatie cu variabile separabile} \\
 = \frac{\operatorname{d}\!y}{\operatorname{d}\!t} = \left(\frac{3y - y^3}{y^2 - 1}\right)\frac{1}{t} \\
 \text{Avem } a(t) = \frac{1}{t} \text{ si } b(y) = \frac{3y - y^3}{y^2 - 1} \text{ unde } y \in \left( - \frac{1}{2}, \frac{1}{2}\right) \text{ si } t \in (2, 10) \\
\frac{3y - y^3}{y^2 - 1} = 0 \implies y(3 - y^2) = 0 \implies \text{ Solutia stationara } y = 0 \\
\implies \varphi_1 :(2, 10) \to \mathbb{R}, \varphi_1(t) = 0 \text{ solutie stationara pentru ecuatia in } y \implies x_1(t) = 0 \implies t = 0 \\
\text{Pentru } y \neq 0 \frac{y^2 - 1}{y(3 - y^2)}\operatorname{d}\!y = \frac{1}{t}\operatorname{d}\!t \\
 \int\frac{y^2 - 1}{ - y^3 + 3y}\operatorname{d}\!y \text{ integrala care o rezolvam prin schimbare de variabila } \\
 z = - y^3 + 3y \implies \operatorname{d}\!z = - 3(z^2 - 1)\operatorname{d}\!y \\
 - \frac{1}{3} \int \frac{1}{z} \operatorname{d}\!z = - \frac{1}{3} \ln |z| + C \\
 \int\frac{y^2 - 1}{ - y^3 + 3y}\operatorname{d}\!y = - \frac{1}{3} \ln | - y^3 + 3y| + C \\
 \implies B(y) = - \frac{1}{3} \ln | - y^3 + 3y| \text{ si } A(t) = \ln|t| \\
 B(y) = A(t) + C \\
 - \frac{1}{3} \ln | - y^3 + 3y| = \ln t + C \\
 - \frac{1}{3} \ln \left| - \frac{x^3}{t^3} + 3\frac{x}{t}\right| = \ln t + C$$
2. **tema**
3. **tema**
4. **tema**

#Ecuatii diferentiale liniare

**Exercitiu**: Sa se determine multimea solutiilor ecuatiilor:
1. $\frac{\operatorname{d}\!x}{\operatorname{d}\!t} = \frac{2t}{t^2 + 1}x + 2t - 1$, cu $t,x \in \mathbb{R}$
2. $\frac{\operatorname{d}\!x}{\operatorname{d}\!t} = (1 + \tan^2 t)x + \frac{1}{\cos^2 t}$, cu $t \in (0, \frac{\pi}{2})$
3. $\frac{\operatorname{d}\!x}{\operatorname{d}\!t} = 2xt - te^{t^2}$, cu $t \in \mathbb{R}$
4. $\frac{\operatorname{d}\!x}{\operatorname{d}\!t} = \frac{1}{\sqrt{t^2 + 1}}x + t(t + \sqrt{t^2 + 1})$, cu $t \in \mathbb{R}$

*Rezolvari*:
1. $$a(t) = \frac{2t}{t^2 + 1} \text{ si } b(t) = 2t - 1 \\
 \frac{d \bar{x}}{\operatorname{d}\!t} = \frac{2t}{t^2 + 1}\bar{x} \implies \bar{x}(t) = C e^{A(t)}\\
 \int \frac{2t}{t^2 + 1}\operatorname{d}\!t = \int \frac{(t^2 + 1)'}{t^2 + 1}\operatorname{d}\!t = \ln( t^2 + 1) + C \implies A(t) = \ln (t^2 + 1) \\
 \implies \bar{x} = C e^{\ln( t^2 + 1)} = C (t^2 + 1) \\
 \text{Aplicam metoda variatiei constantelor.} \\
 \text{Determinam } C: \mathbb{R} \to \mathbb{R} \text{ astfel incat } x(t) = C(t) (t^2 + 1) \text{ sa verifice ecuatia data initial} \\
 \frac{\operatorname{d}\ !C(t)(t^2 + 1)}{\operatorname{d}\!t} = \frac{2t}{t^2 + 1} (C(t)(t^2 + 1)) + 2t - 1 \\
 \implies C(t)' (t^2 + 1) + C(t)(t^2 + 1)' = 2tC(t) = 2t - 1 \implies C(t)' = \frac{2t - 1}{t^2 - 1} \\
 \implies C(t) = \int \frac{2t - 1}{t^2 - 1}\operatorname{d}\!t = \ln(t^2 + 1) - \arctan(t) + C_1 \\
 \implies x(t) = \left(\ln(t^2 + 1) - \arctan(t) + C_1\right) (t^2 + 1)$$
2. **tema**
3. **tema**
4. **tema**

#Ecuatii de tipul $\frac{\operatorname{d}\!x}{\operatorname{d}\!t} = f\left(\frac{at + bx + c}{a_1t + b_1t + c_1}\right)$

**Exercitii**: Sa se determine multimea solutiilor ecuatiilor:
1. $\frac{\operatorname{d}\!x}{\operatorname{d}\!t} = \frac{2t + x}{t + x}$
2. $\frac{\operatorname{d}\!x}{\operatorname{d}\!t} = \frac{2t + x - 1}{4t + 2x - 4}$
3. $\frac{\operatorname{d}\!x}{\operatorname{d}\!t} = \frac{t - 2x + 4}{ - t + 2x + 3} $
4. $\frac{\operatorname{d}\!x}{\operatorname{d}\!t} = \frac{t - 2x - 3}{t + x}$
5. $\frac{\operatorname{d}\!x}{\operatorname{d}\!t} = \frac{2t + x - 5}{t - x + 2}$

*Rezolvari*:
1. **tema**
2. $$\text{Suntem in cazul } d = 0 \implies \text{ alegem una din cele doua optiuni de schimbare de variabila.} \\
\text{Am ales } 2t + x = y \text{ si } x = y - 2t \\
 \frac{\operatorname{d}}{\operatorname{d}\!t}(y - 2t) = \frac{2t + y - 2t - 1}{4t + 2y - 4t - 4} \\
 \frac{\operatorname{d}\!y}{\operatorname{d}\!t} - 2 = \frac{y - 1}{2y - 4} \\
 \frac{\operatorname{d}\!y}{\operatorname{d}\!t} = \frac{y - 1 + 4y - 8}{2y - 4}\\
\frac{\operatorname{d}\!y}{\operatorname{d}\!t} = \frac{5y - 9}{2y - 4} \text{ care este ecuatie cu variabile separabile } \\
 a_2(t) = 1 \text{ si } b_2(y) = \frac{5y - 9}{2y - 4} \\
 \text{Cautam solutii stationare } b2(y) = 0 \implies t = \frac{9}{5} \\
 \text{ Deci rezulta solutia stationara } y_1(t) = \frac{9}{5} x_1(t) = \frac{9}{5} - 2t \\
 \text{Daca } y \neq \frac{9}{5} \text{ separam variabilele } \implies \frac{2y - 4}{5y - 9}\operatorname{d}\!y = 1 \operatorname{d}\!t \\
 \int \frac{2y - 4}{5y - 9}\operatorname{d}\!y = \frac{2}{5} \int \frac{y - 2}{y - \frac{9}{5}}\operatorname{d}\!y = \frac{2}{5} \int \frac{y - \frac{9}{5} + \frac{9}{5} - 2}{y - \frac{9}{5}} \operatorname{d}\!y = \\\frac{2}{5}\left( \int 1 \operatorname{d}\!y - \frac{1}{5}\int \frac{1}{y - \frac{9}{5}}\operatorname{d}\!y\right) = \frac{2}{5}y - \frac{2}{25} \ln \left|y - \frac{9}{5}\right| + C \\
 B_2 = \frac{2}{5} y - \frac{2}{25} \ln \left|y - \frac{9}{5}\right|, A_2(t) = t \\
 \implies \text{Solutia implicita a ecuatiei in } y \text{ este } B_2(y) = A_2(t) + C = \frac{2}{5} y - \frac{2}{25} \ln \left|y - \frac{9}{5}\right| = t + C \\
 \frac{2}{5} (x + 2t) - \frac{2}{25} \ln \left|x + 2t - \frac{9}{5}\right| = t + C$$
3. $$\text{Suntem in cazul } d \neq 0 \implies \text{ trebuie sa rezolvam sistemul }\\
 t - 2x - 3 = 0, t + x = 0 \implies t = 1 \text{ si } x = - 1 \text{ care sunt } t_0 si x_0. \\
 \implies s = t - t_0 = t - 1 \text{ si }y = x - x_0 = x + 1 \\
 (t,x) \xrightarrow{s = t - 1 \text{ si } y = x + 1} (s,y)\\
 \frac{\operatorname{d}\!x}{\operatorname{d}\!t} = \frac{\operatorname{d}\!y}{\operatorname{d}\!s} \frac{\operatorname{d}\!s}{\operatorname{d}\!t} = \frac{\operatorname{d}\!y}{\operatorname{d}\!s} \\
 \implies \text{Ecuatia devine } \frac{\operatorname{d}\!y}{\operatorname{d}\!s} = \frac{s + 1 - 2(y - 1) - 3}{s + 1 + y - 1} \\
 \frac{\operatorname{d}\!y}{\operatorname{d}\!s} = \frac{s - 2y}{s + y} \text{ care este ecuatie omogena.} \\
 \frac{\operatorname{d}\!y}{\operatorname{d}\!s} = \frac{1 - 2 \frac{y}{s}}{1 + \frac{y}{s}} \\
 \text{Facem schimbarea de variabila } z = \frac{y}{s} \\
 (t,x)\xrightarrow{s = t - 1 \text{ si }y = x + 1} (s,y) \xrightarrow{\frac{y}{s} = z} (s,z) \\
 \frac{d (s z)}{\operatorname{d}\!s} = \frac{1 - 2z}{1 + z} \\
 \ z + s\frac{\operatorname{d}\!z}{\operatorname{d}\!s} = \frac{1 - 2z}{1 + z} \\
 \implies \frac{\operatorname{d}\!z}{\operatorname{d}\!s} = \left(\frac{1 - 2z}{1 + z} - z\right) \frac{1}{s} \\
 \frac{\operatorname{d}\!z}{\operatorname{d}\!s} = \frac{1 - 3z - z^2}{1 + z} \frac{1}{s} \\
 a_2(s) = \frac{1}{s} \text{ si } b_2(s) = \frac{1 - 3z - z^2}{1 + z} \\
b_2(z) = 0 \implies z_{1,2} = \frac{3 \pm \sqrt{13}}{ - 2} \\
 z(t) = z_1 \text{ solutie stationara pentru ecuatia in } z \implies y_1(t) = s z_1 \\
 x_1(t) = (t - 1) z_1 - 1 \text{. Analog } x_2(t) = (t - 1) z_2 - 1 \\
 \frac{1 + z}{1 - 3z - z^2} \operatorname{d}\!z = \frac{1}{s} \operatorname{d}\!s \\
 \int \frac{1}{s} \operatorname{d}\!s = \ln |s| + C \\
 A_2(s) = \ln|s| \\
 \int \frac{1 + z}{1 - 3z - z^2} \operatorname{d}\!z = - \int \frac{1 + z}{z^2 - 3z - 1}\operatorname{d}\!z = \\
 \text{Vrem sa scriem forma canonica a ecuatiei de gradul doi de la numitor } z^2 - 3z - 1 = \left(z + \frac{3}{2}\right)^2 - \frac{13}{4} \\
 \implies - \int \frac{1 + z}{\left(z + \frac{3}{2}\right)^2 - \frac{13}{4}}\operatorname{d}\!z \\
 k = z + \frac{3}{2} \text{ si } dk = \operatorname{d}\!z \\
 \implies - \int \frac{k - \frac{1}{2}}{k^2 - \frac{13}{4}} = - \frac{1}{2} \ln\left|k^2 - \frac{13}{4}\right| + \frac{1}{2} \frac{1}{\sqrt{13}} - \ln \left| \frac{k - \frac{\sqrt{13}}{2}}{k + \frac{\sqrt{13}}{2}}\right| \\
 B_2(z) = - \frac{1}{2} \ln \left|\left(z + \frac{3}{2}\right)^2 - \frac{13}{4}\right| + \frac{1}{2} \frac{1}{\sqrt{13}} \ln \left|\frac{z + \frac{3}{2} - \frac{\sqrt{13}}{2}}{z + \frac{3}{2} + \frac{\sqrt{13}}{2}}\right| \\
 B_2(z) = A_2(s) + C \text{ solutie implicita a ecuatiei in } z \\
 B_2\left(\frac{y}{s}\right) = A_2(s) + C \text{ solutie implicita a ecuatiei in } y \\
B_2\left(\frac{x + 1}{t - 1}\right) = A_2(t - 1) + C \text{ solutie implicita a ecuatiei in } x $$
4. **tema**
5. **tema**

#Ecuatia Bernoulli

**Exercitii**:
1. $x' - \frac{x}{t} = \frac{1}{t^2x^2}$ cu $t,x > 0$
2. $x' = 2xt + tx^2$ cu $t,x \in \mathbb{R}$
3. $x' = xt + t\sqrt{x}$ cu $t \in \mathbb{R}, x \geq 0$
4. $x' - \frac{xt}{t^2 + 1} = (t + 1)x^2$ cu $t,x \in \mathbb{R}$

> $x' = \frac{\operatorname{d}\!x}{\operatorname{d}\!t}$

*Rezolvari*:
1. $$\frac{\operatorname{d}\!x}{\operatorname{d}\!t} = \frac{1}{t^2x^2} + \frac{x}{t} \\
 a(t) = \frac{1}{t}, b(t) = \frac{1}{t^2}, \alpha = - 2 \\
 \frac{\operatorname{d}\!x}{\operatorname{d}\!t} = \frac{1}{t}x + \frac{1}{t^2}x^2 \\
 \frac{\operatorname{d}\ \bar{x}}{\operatorname{d}\!t} = \frac{1}{t} \bar{x} \implies \bar{x}(t) = C e^{A(t)} \\
 \int \frac{1}{t} = \ln t + C \\
 A(t) = \ln t \\
 \bar{x} = C e^{\ln t} = C t \\
 \text{Determinam functia } C : (0, + \infty) \to \mathbb{R} \text{ astfel incat } x(t) = C(t) t \text{ sa verifice ecuatia. } \frac{\operatorname{d}\!x}{\operatorname{d}\!t} = \frac{1}{t^2x^2} + \frac{x}{t} \\
 \frac{\operatorname{d}}{\operatorname{d}\!t}(C(t)t) = \frac{1}{t^2C^2(t)t^2} + \frac{1}{t}C(t)t \\
 C'(t) t + C(t) = \frac{1}{t^4 C^2(t)} + C(t) \\
 \frac{\operatorname{d}\ !C}{\operatorname{d}\!t} = \frac{t}{t^5}\frac{1}{C^2} \\
 a_1(t) = \frac{1}{t^5} , b_1(C) = \frac{1}{C^2} \\
 \frac{1}{C^2} = 0 \text{ nu are solutii} \\
 C^2\operatorname{d}\ !C = \frac{1}{t^5}\operatorname{d}\!t \\
 C^2\operatorname{d}\ !C = \frac{C^3}{3} + C_1 \\
 B_1(c) = \frac{C^3}{3} \\
 \int\frac{1}{t^5}\operatorname{d}\!t = \frac{t^ - 4}{ - 4} + C_1 \\
 A_1(t) = \frac{1}{4t^4} \\
 \frac{C^3}{3} = - \frac{1}{4t^4} + C_1 \\
 C^3 = - \frac{3}{4t^4} + 3 C_1 \\
 C(t) = \sqrt[3]{\frac{ - 3}{4t^4} + 3 C_1}, C_1 \in \mathbb{R} \\
 x(t) = t \sqrt[3]{\frac{ - 3}{4t^4} + 3 C_1}$$

#Ecuatia Riccati

**Exemplu**: Fie ecuatia $\frac{\operatorname{d}\!x}{\operatorname{d}\!t} = \frac{1}{t}x^2 - \frac{2}{t^2}x - \frac{2}{t^2}$, cu $t > 0$.
a. Determinati $\alpha \in \mathbb{R}$ astfel incat ecuatia sa aiba o solutie particulara de forma $\varphi_0(t) = \frac{\alpha}{t}$.
b. Determiati multimea solutiilor ecuatiei si apoi solutia care verifica conditia $x(1) = 2$, daca exista.

a. $$
\frac{\operatorname{d}}{\operatorname{d}\!t}\left(\frac{\alpha}{t}\right) = \frac{1}{t} \left(\frac{\alpha}{t}\right)^2 - \frac{2}{t^2}\left(\frac{\alpha}{t}\right) - \frac{2}{t^2} \\
\implies \alpha \frac{-1}{t^2} = \frac{\alpha^2}{t^3} - \frac{2 \alpha}{t^3} - \frac{2}{t^2} \\
\implies- \alpha t = \alpha^2 -2\alpha -2t
\\ \text{ Identificam coeficientii } \alpha^2 - 2\alpha = 0 \text{ si } -\alpha = -2 \text{ si identificam solutia nenula } \alpha = 2
\\ \implies \text{Solutia particulara este } \varphi_0(t) = \frac{2}{t}
$$

b. $$
x = y + \frac{2}{t} \implies \frac{\operatorname{d}}{\operatorname{d}\!t}\left(y + \frac{2}{t}\right) = \frac{1}{t}\left( y + \frac{2}{t}\right)^2 - \frac{2}{t^2}\left(y + \frac{2}{t}\right) - \frac{2}{t} \\
\frac{\operatorname{d}\!y}{\operatorname{d}\!t} + \frac{-2}{t^2} = \frac{1}{t}\left(y^2 + \frac{4t}{t} + \frac{4}{t^2}\right) - \frac{2y}{t^2} - \frac{4}{t^3} - \frac{2}{t^2} \\
\frac{\operatorname{d}\!y}{\operatorname{d}\!t} = \frac{2}{t^2}y + \frac{1}{t}y^2 \text{ care este ecuatie Bernoulli} \\
\\\text{Rezolvam ecuatia Bernoulli. In cazul nostru avem } a_1(t) = \frac{2}{t^2} \text{ si }  b_1(t) = \frac{1}{t} \text{ si } \alpha = 2 \\
\text{Se rezolva ecuatia liniara omogena atasata } \frac{\operatorname{d}\!\bar{y}}{\operatorname{d}\!t} = \frac{2}{t^2} \bar{y} \\
y(t) = C e^{A_1(t)} \\
\int \frac{2}{t^2} \operatorname{d}\!t = \frac{-2}{t} \implies A_1(t) = \frac{-2}{t} \\
\implies \bar{y}(t) = C e^{\frac{-2}{t}} \\
\text{Aplicam metoda variatiei constantelor}. \\
\text{Determinam functia } C : (0, +\infty) \to \mathbb{R} \text{ astfel incat } y(t) = C(t)e^{\frac{-2}{t}} \text{ sa fie solutie a ecuatiei Bernoulli.} \\
C'(t) e^{\frac{-2}{t}} + C(t) e^{\frac{-2}{t}} \left(\frac{-2}{t}\right)' = \frac{2}{t}C(t) e^{\frac{-2}{t}} + \frac{1}{t}C^2(t) e^{\frac{-4}{t}} \\
C' e^{\frac{-2}{t}} = \frac{1}{t}C^2 e^{\frac{-4}{t}} \\
C'(t) = \frac{1}{t}C^2(t) e^{\frac{2}{t}} \text{ care este ecuatie cu variabile separabile}\\
\frac{dC}{\operatorname{d}\!t} = \frac{e^{\frac{-2}{t}}}{t}C^2 \\
C^2 = 0 \implies C = 0 \implies y = 0 \implies x=\frac{2}{t} \\
\text{Pentru } C \neq 0 \text{ separam variabilele} \frac{dC}{c^2} = \frac{e^{\frac{-2}{t}}}{t}\operatorname{d}\!t \\
\int \frac{dC}{C^2} = \frac{-1}{C} + C_1 \implies B_2(C) = \frac{-1}{C} \\
\int \frac{e^{\frac{-2}{t}}}{t} \text{ care nu se poate integra.} \\
B_2(C) = A_2(t) + K \\
\frac{-1}{C} = \int_1^t\frac{e^{\frac{-2}{s}}}{s}\operatorname{d}\!s + K, K \in \mathbb{R} \\
C(t) = \frac{1}{\int_1^t\frac{e^{\frac{-2}{s}}}{s}\operatorname{d}\!s + K} \\
y(t) = \frac{1}{\int_1^t\frac{e^{\frac{-2}{s}}}{s}\operatorname{d}\!s + K} e^{\frac{-2}{t}} \\
x = \frac{1}{\int_1^t\frac{e^{\frac{-2}{s}}}{s}\operatorname{d}\!s + K} e^{\frac{-2}{t}} + \frac{2}{t} \\
\text{Din conditia } x(1) = 2 \implies x_1 \frac{1}{\int_1^1\frac{e^{\frac{-2}{s}}}{s}\operatorname{d}\!s + K} e^{\frac{-2}{t}} + \frac{2}{1} = 2 \\
\implies \nexists K \\
\text{Dar avem solutia partiala } \varphi_0(t) = \frac{2}{t} \text{ care verifica conditia } \varphi_0(1) = 2 \\
\text{Solutia } \varphi_0(t) = \frac{2}{t}
$$

**Tema**: Sa se determine multimea solutiilor ecuatiilor:
1. $x' = x^2 + 1 - t^2$ stiind ca admite ca solutie $\varphi_0(t) = \alpha t + \beta$, cu $\alpha, \beta \in \mathbb{R}$
2. $2\left(t-t^2\sqrt{t}\right)x' + 2\sqrt{t}x^2 -x -t = 0$ stiind ca admite ca solutie $\varphi_0(t) = \alpha t + \beta$, cu $\alpha, \beta \in \mathbb{R}$
3. $x' = -\frac{2t}{t^5-1}x^2 + \frac{t^4}{t^5-1}x + \frac{3t^2}{t^5-1}$, stiind ca admite solutie particulara de forma $\varphi_0(t) = \alpha x^m$, cu $\alpha, m \in \mathbb{R}$

#Ecuatia implicita

**Exercitii**:
1. $t+x = \left(\frac{x'+1}{x'-1}\right)^2$.
            a. Precizati in cate moduri poate fi rezolvata ecuatia.
        b. Determinati multimea solutilor considerand ecuatia ca fiind de forma $t = h\left(x, x'\right)$.
        c. Determinati solutia ecuatiei care verifica $x(1) = -1$.
2. $x = 2tx' - \left(x'\right)^2$
3. $x = t\left(1 + x'\right) + \left(x'\right)^2$
4. $x = \left(x'\right)^2 - x't + \frac{t^2}{2}$
5. $\left(x'\right)^3 - 4t x x' + 8x^2 =0 $

*Rezolvari*:
1.
a. $$
\text{Avem doua moduri de rezolvare: } \\
t = \left(\frac{x'+1}{x'-1}\right)^2 - x  \text{ care se rezolva prin derivare in raport cu } x \\
\text{sau} \\
x = \left(\frac{x'+1}{x'-1}\right)^2 -t \text{ care se rezolva prin derivare in raport cu } t
$$
b. $$
t = \left(\frac{x'+1}{x'-1}\right)^2 - x \\
t = h\left(x, x'\right) \text{ unde } h\left(x, x'\right) = \left(\frac{x'+1}{x'-1}\right)^2 -x \\
\frac{\operatorname{d}\!t}{\operatorname{d}\!x} = \frac{\operatorname{d}}{\operatorname{d}\!x}\left(h\left(x,x'\right)\right) \\
\frac{\operatorname{d}\!t}{\operatorname{d}\!x} = \frac{\partial h}{\partial x} + \frac{\partial h}{\partial x'} \frac{\operatorname{d}\!x'}{\operatorname{d}\!x} \\
\implies \frac{\operatorname{d}\!x}{\operatorname{d}\!t} = 2\left(\frac{x'+1}{x'-1}\right) \frac{\left(x'-1\right)\left(x'+1\right)}{\left(x'-1\right)^2} \frac{\operatorname{d}\!x'}{\operatorname{d}\!x} - 1 \\
\frac{\operatorname{d}\!t}{\operatorname{d}\!x} = \frac{1}{\frac{\operatorname{d}\!x}{\operatorname{d}\!t}} \text{Notam } x' = \frac{\operatorname{d}\!x}{\operatorname{d}\!t} = p \\
\implies \frac{1}{p} = 2\left(\frac{p+1}{p-1}\right) \frac{-2}{(p-1)^2} \frac{\operatorname{d}\!p}{\operatorname{d}\!x} - 1 \\
\frac{1}{p} + 1 = \frac{-4 (p+1)}{(p-1)^2} \frac{\operatorname{d}\!p}{\operatorname{d}\!x} \\
\frac{p+1}{p} = \frac{-4(p+1)}{(p-1)^3} \frac{\operatorname{d}\!p}{\operatorname{d}\!x} \\
\text{Daca } p+1 = 0 \text{ atunci ecuatia este adevarata pentru ca imi da } 0 = 0 \implies x' = -1 \implies x = -t + C  \\
\implies t = \left(\frac{-1+1}{-1-1}\right)^2 +t - C \implies C = 0 \implies x(t) = -t\\
\text{Daca } p+1 \neq 0 \text{ simplificam } \implies \frac{1}{p} = \frac{-4}{(p-1)^3} \frac{\operatorname{d}\!p}{\operatorname{d}\!x} \\
\implies \frac{\operatorname{d}\!p}{\operatorname{d}\!x} = \frac{(p-1)^3}{-4p} \text{ care este ecuatie cu variabile separabile in necunoscuta } p(x) \\
\text{Rasturnam ecuatia } \frac{\operatorname{d}\!x}{\operatorname{d}\!p} = \frac{-4p}{(p-1)^3} \text{ care este ecuatie de tip primitiva } \\
x(p) = \int \frac{-4p}{(p-1)^3} \operatorname{d}\!p \\
\text{Notam } p - 1 = u \implies \operatorname{d}\!p = \operatorname{d}\!u \\
\implies -4 \int \frac{u+1}{u^3} \operatorname{d}\!u \\
= -4 \int \frac{u}{u^3}\operatorname{d}\!u - 4 \int \frac{1}{u^3}\operatorname{d}\!u \\
\\ = 4 u^{-1} + 2 u^{-2}
\\ = \frac{4}{u} + \frac{2}{u^2} \\
\implies x(p) = \frac{4}{p-1} + \frac{2}{(p-1)^2} + C_1 \\
\implies \text{Solutia parametrica este } x(p) = \frac{4}{p-1} + \frac{2}{(p-1)^2} + C_1 \text{ si } t = \left(\frac{p+1}{p-1}\right)^2 \\ \text{Deci multimea solutiilor este }x(t) = -t \text{ si } \\
\text{ solutia parametrica formata din } x(p) = \frac{4}{p-1} + \frac{2}{(p-1)^2} + C_1 \text{ si } t = \left(\frac{p+1}{p-1}\right)^2
-x
$$
c.
$$
\text{Daca } t = 1 \text{ si } x = -1 \implies -1 = \frac{4}{p-1} + \frac{2}{(p-1)^2} + C_1 \text{ si } 1 = \left(\frac{p + 1}{p-1}\right)^2 + 1 \\
\implies p = -1 \implies -1 = \frac{4}{-2} + \frac{2}{4} + C_1 \\
\implies C_1 = \frac{1}{2} \\
\implies \text{Mai avem si solutia parametrica } x = \frac{4}{p-1} + \frac{2}{(p-1)^2} + \frac{1}{2} \implies t = \left(\frac{p+1}{p-1}\right)^2 -x
$$

2. $$
x = 2tx' - \left(x'\right)^2 \text{ care este ecuatie de tip Lagrange} \\
\text{Derivam ecuatia in raport cu } t \text{: } 2x' + 2t\left(x'\right)' - 2\left(x'\right)\left(x'\right)' = x' \\
\text{Notam } x' = p \implies p = 2p+2tp' -2pp' \\
\implies p'(2t-2p) = -p \implies p' - \frac{p}{2(p-t)} \\
\frac{\operatorname{d}\!p}{\operatorname{d}\!t} = \frac{p}{2(p-t)} \\
\implies \frac{\operatorname{d}\!t}{\operatorname{d}\!p} = \frac{2(p-t)}{p} \\
\frac{\operatorname{d}\!t}{\operatorname{d}\!p} = 2 - \frac{2}{p}t \text{ care este ecuatie liniara in } t \text{ si }p \\
\implies \frac{\operatorname{d}\!t}{\operatorname{d}\!p} = a(t) + b(p) \implies a(p) = \frac{-2}{p} \text{ si } b(p) = 2 \\
\text{Verificam } \varphi_0(p) = \alpha p \text{ este solutie pentru } \alpha \text{ convenabil determinat} \\
\implies \frac{\operatorname{d}}{\operatorname{d}\!p}(\alpha p) = 2 - \frac{2}{p}\alpha p\\
\implies \alpha = \frac{2}{3} \implies \varphi_0(p) = \frac{2}{3}p \text{ este solutie} \\
\text{Facem schimbare de variabila } t = s + \varphi_0 \implies t = s + \frac{2}{3} p \\
\implies \frac{\operatorname{d}}{\operatorname{d}\!p}\left(s + \frac{2}{3}p\right) = 2 - \frac{2}{p}\left(s + \frac{2}{3} p\right) \\
\implies \frac{\operatorname{d}\!s}{\operatorname{d}\!p} = \frac{-2}{p}s\\
\implies s = C e^{A(p)} \text{ unde } A \text{ este primitiva pentru } a(p) = \frac{-2}{p} \\
\int \frac{-2}{p} \operatorname{d}\!p = -2 \ln |p| + C = \ln |p^{-2}|+ C = \ln \frac{1}{p^2} + C \\
\implies s = C e^{ \ln \frac{1}{p^2} } \\
\implies t = C \frac{1}{p^2} + \frac{2}{3}p \\
\text{Solutia parametrica } t = C \frac{1}{p} + \frac{2}{3}p \\ x = 2tp-p^2 , C \in \mathbb{R}, p \text{ parametru}
$$
3. **tema**
4. **tema**
5. **tema**



#Aplicatii la Teorema de existenta si unicitate a solutiei problemei Cauchy(TEU)

1. Fie problema Cauchy $\begin{cases} x' = 2 t \sin{x} \\ x(0) = \frac{\pi}{4} \end{cases}$, cu $(t,x) \in \mathbb{R}^2$.
        a. Stabiliti daca problema data verifica ipotezele TEU.
        b. Determinati primele 3 aproximatii din sirul aproximatiilor succesive.
        c. Determinati solutia problemei.

a.
$$
\begin{cases} \frac{\operatorname{d}\!x}{\operatorname{d}\!t} = f(t,x)\\ x(t_0) = x_0 \end{cases} \\
f: \Omega \subset \mathbb{R}^2 \to \mathbb{R}, (t_0, x_0) \in \Omega \\
\text{Sa scriem intai ipotezele: } \\
\text{1. } \exists a,b > 0 \text{ astfel incat } D = \left[t_0-a, t_0+a\right] \times \left[t_0-b, t_0+b]\right] \subset \mathbb{R} \\
\text{2. } f \text{ este continua in ambele variabile pe } D \\
M = \sup \left\{\left|f(t,x)\right|, (t,x) \in D\right\} \\
\text{3. } f \text{ este Lipschitz in a doua variabila AKA in } x \text{ adica este suficient ca } \frac{\partial f}{\partial x} \text{ sa fie continua pe } D \\
\text{Avem } \\
f(t,x) = 2 t \sin x \text{ cu } t_0 = 0, x_0 = \frac{\pi}{4}, \Omega = \mathbb{R}^2 \\
\exists a,b > 0 \text{ astfel incat } D \subset \mathbb{R}^2 \\
\text{Alegem } b = \frac{\pi}{4} \text{ si } a = 1 \\
\implies D = \left[-1,1\right] \times \left[0,\frac{\pi}{2}\right]  \\
\text{2. } f \text{ este continua in ambele argumete ca produs de functii elementare } \\
M = \sup \left\{\left|2 t \sin x\right|, |t| \leq 1, x \in \left[0,\frac{\pi}{2}\right]\right\} \implies M = 2 \\
\text{3. } \frac{\partial f}{\partial x} = \frac{\partial(2 t \sin x)}{\partial x} = 2 t \cos \text{ care este continua pe } D \\
\text{Observatie: constanta din definitia formulei Lipschitz este } L = \sup \left\{\left|\frac{\partial f}{\partial x}(t,x)\right| | (t,x) \in D\right\} \\
\implies \text{Sunt indeplinite conditiile TEU } \\
\implies \forall \alpha \leq \min\left(a, \frac{b}{m}\right) \text{ care in cazul nostru } = \frac{\pi}{4} \\
\exists! \varphi: \left[0 - \alpha, 0 + \alpha\right] \to \left[0, \frac{\pi}{2}\right] \text{ solutia problemei Cauchy date}
$$

b.
$$
\text{In general sirul aproximatiilor succesive este } \varphi_0(t) = x_0 \text{ si } \varphi_{(i+1)} = x_0 + \int_{t_0}^t\left(f\left(s, \varphi_i(s)\right)\right) \operatorname{d}\!s \\
\text{In cazul nostru } \varphi_0(t) = \frac{\pi}{4} \\
\varphi_1(t) = \frac{\pi}{4} + \int_0^t f\left(s, \frac{\pi}{4}\right) \operatorname{d}\!s \\
= \frac{\pi}{4} + \int_0^t 2s \sin \frac{\pi}{4}\operatorname{d}\!s \\
= \frac{\pi}{4} + \frac{\sqrt{2}}{2} \left[t^2 - 0^2\right] \\
\implies \varphi_1(t) = \frac{\pi}{4} + \frac{\sqrt{2}}{2} t^2 \\
\varphi_2(t) = \frac{\pi}{4} \int_0^t f\left(s, \varphi_1(s)\right)\operatorname{d}\!s \\
= \frac{\pi}{4} + \int_0^t 2s \sin\left(\frac{\pi}{4} + \frac{\sqrt{2}}{2} s^2\right)\operatorname{d}\!s \\
\text{Notam } \frac{\pi}{4} + \frac{\sqrt{2}}{2} s^2 = u \implies \operatorname{d}\!u = \sqrt{2} s \operatorname{d}\!s \\
s = 0 \implies u = \frac{\pi}{4}; s = t \implies u =  \frac{\pi}{4} + \frac{\sqrt{2}}{2} t^2 \\
=  \frac{\pi}{4} + \sqrt{2} \int_{ \frac{\pi}{4}}^{ \frac{\pi}{4} + \frac{\sqrt{2}}{2} t^2} \sin{u} \operatorname{d}\!u \\
= \frac{\pi}{4} + \text{ chestia de mai sus rezolvata care e lunga }
$$

c. **tema**

2. Fie problema Cauchy $\begin{cases} x' = 3 \sqrt[3]{x^2} \\ x(t_0) = x_0 \end{cases}$, cu $(t,x) \in \mathbb{R}^2$.
        a. Stabiliti daca problema data verifica ipotezele TEU.
        b. Determinati cateva aproximatii din sirul aproximatiilor succesive pentru $x_0 \neq 0$.
        c. Aratati ca pentru $x_0 = 0 $ problema are mai multe solutii.



3. Fie problema Cauchy $\begin{cases} x' = 3 \sqrt[3]{x^2} \\ x(2) = 1 \end{cases}$.
                a. Solutia $\varphi$ a problemei.
                b. Determinati aproximarile $x_0, x_1, x_2$ pentru $N = 2$, folosind metoda Euler explicita, pe intervalul $[2, 4]$.
                    Calculati $\left|\varphi(t_2) - x_2\right|$ si comparati cu majorarea din teorema de aproximare.

*Rezolvare*:

a.
$$
\text{Ecuatia este cu variabile separabile.} \\
x' = 3 \sqrt[3]{x^2} \\
a(t) = 1 \\
b(x) = 0 \implies x = 0  \text{ solutie stationara a ecuatiei} \\
\frac{\operatorname{d}\!x}{\operatorname{d}\!t} = 3 \sqrt[3]{x^2} \iff \frac{1}{ 3 \sqrt[3]{x^2}}\operatorname{d}\!x = 1 \operatorname{d}\!t \\
\int \frac{1}{ 3 \sqrt[3]{x^2}} \operatorname{d}\!x = \frac{1}{3} \int x^{\frac{-2}{3}} = \\
= x^{\frac{1}{3}} + C \\
B(x) = \sqrt[3]{x^2} \\
A(t) = t \\
B(x) = A(t) + C \\
\iff  \sqrt[3]{x^2} = t + C \implies x = (t + C)^3 \\
x(2) = 1 \\
x(2) = (2 + C)^3 = 1 \implies C = -1 \\
\varphi(t) = (t-1)^3
$$

b.
$$
f(t,x) = 3 \sqrt[3]{x^2} \\
[t_0, t_0 + \alpha] = [2,4] \\
N = 2 \\
\implies t_0 = 2, h = 1, \\
t_1 = t_0 + h \implies t_1 = 2. \\
t_2 = t_0 + 2h \implies t_2 = 4 \\
x_0 = 1 \\
x_1 = x_0 + h f(t_0, x_0) \implies x_1 = 4 \\
x_2 = x_1 + h f(t_1, x_1) \implies x_2 = 4 + 6 \sqrt[3]{2} \\
\varphi(t_1) = \varphi(3) = (3-1)^3 = 8 \\
\varphi(t_2) = \varphi(4) = (4-1)^3 = 27 \\
\left|\varphi(t_1) - x_1\right| = 4 \\
\left|\varphi(t_2) - x_2\right| = 23 - 6 \sqrt[3]{2} \\
\text{ Din teorema de aproximare avem ca } \varphi(t_n) < Ah \text{ unde } A > 0 \text{ si } \\
A = \frac{e^{\alpha L_2} -1}{L_2} B \\
\text{ unde } B = M L_2 + L_1 \\
\text{ unde } L_1 \text{ este constanta Lipschitz a functiei } f \text{ in raport cu } t \\
\text{ si } L_2 \text{ este constanta Lipschitz a functiei } f \text{ in raport cu } x \\
\text{iar } M \text{ este marginea superioara pentru } f(t,x) \text{ pe intervalul pe care construim solutia} \\
\\
f(t,x) = 3 \sqrt[3]{x^2} \text{ cu } t \in [2, 4] \\
\implies M = \sup \left|f(t,x)\right|, t \in [2, 4], x \in [1, 27] \\
\implies M = 3 \sqrt[3]{27^2} = 27  \\
\text{ Lipschitz in raport cu prima variabila inseamna ca } \left|f(t_1,x) - f(t_2,x)\right| \leq L_1 \left|t_1-t_2\right| \forall (t_1,x), (t_2,x) \in [2,4] \times [1,27] \\
\implies 0 \leq L_1 \left|t_1-t_2\right| \implies L_1 \text{ poate fi ales orice constanta pozitiva. Sa zicem ca alegem } L_1 = \frac{1}{2} \\
\text{ Lipschitz in raport cu a doua variabila inseamna ca } \left|f(t, a) - f(t, b)\right| \leq L_2 \left|a - b\right| \forall (t,a), (t,b) \in [2,4] \times [1,27] \\
\left|3 \sqrt[3]{a^2} - 3 \sqrt[3]{b^2}\right| = 3 \left| \frac{a^2 - b^2}{\sqrt[3]{a^4} + \sqrt[3]{b^4} + \sqrt[3]{a^2 b^2}}\right| \leq 3 \left|\frac{(a-b)(a+b)}{1+1+1}\right| = 54 \left|a-b\right| \\
L_1 = \frac{1}{2}
L_2 = 54 \\
M = 27 \\
\implies B = 27 \cdot 54 + \frac{1}{2}\\
A = \frac{e^{54 \cdot 2}-1}{54}\left(27 \cdot 54 + \frac{1}{2}\right) \approx 2.16 \cdot 10^{48} \text{ conform Wolfram Alpha}
$$

#Sisteme de ecuatii diferentiale

1. Fie sistemul $\begin{cases} x_1' = f_1(t,(x_1, x_2))\\ x_2'= f_2(t, (x_1, x_2))\end{cases}$, x = $ \begin{pmatrix} x_1 \\ x_2 \end{pmatrix}$, $\begin{cases} f_1(t,(x_1, x_2)) = 2tx_1 + x_2 \\ f_2(t,(x_1, x_2)) = x_1 + 2tx_2\end{cases}$.
                a. Stabiliti daca sistemul dat verifica conditiile teoremei de existenta si unicitate daca adaugam sistemului conditia $x(t_0) = x_0 = \begin{pmatrix} x_{01} \\ x_{02} \end{pmatrix} \in \mathbb{R}^2$
                b. Demonstrati ca $F (t, (x_1, x_2)) = (x_1-x_2)e^{t-t^2}$ este integrala prima a sistemului.
                c. Determinati multimea solutiilor sistemului dat folosind integrala prima.

*Rezolvare*:

a.
$$
i) \exists a, b_1, b_2 > 0 \text{ astfel incat } D = [t_0-a, t_0 +a] \times [x_{01}-b_1, x_{01}+b_1] \times [x_{02}-b_2, x_{02}+b_2] \in \Omega \\
ii) f \text{ continua in } t \text{ si } x \\
M = \sup \left|f(t,x)\right|, (t,x) \in D \\
iii) \frac{Df}{\operatorname{d}\!x} = \frac{D(f_1,f_2)}{D(x_1,x_2)} = \left(\begin{array}{nume1} \frac{\partial f_1}{\partial x_1} & \frac{\partial f_2}{\partial x_1} \\ \frac{\partial f_1}{\partial x_2} & \frac{\partial f_2}{\partial x_2} \end{array} \right)= \left(\begin{array}{nume2} 2t & 1 \\ 1 & 2t\end{array} \right) \text{ continua pe } D \\
\implies \forall \alpha \leq \min\left\{1, \frac{b_1}{M},\frac{b_2}{M}\right\} \exists! \varphi : [t_0-\alpha, t_0 + \alpha] \to D_1 \subseteq \mathbb{R}^3 \text{ solutie pentru problema Cauchy}
$$

b.
$$
\text{O functie } F : \Omega \to \mathbb{R} \text{ este integrala prima pentru } x' = f(t,x) \text{ daca } \\
\forall \varphi:I_\varphi \to \mathbb{R}^n \text{ solutie pentru } x' = f(t,x), \\
\exists C_\varphi \in \mathbb{R} \text{ astfel incat } F\left(t, \varphi(t)\right) = C_\varphi, \forall t \in I_\varphi \\
\text{Criteriu de recunoastere a integralelor prime: }
F \text{ este integrala prima pentru } x' = f(t,x) \iff \\
\iff \frac{\partial F}{\partial t} (t,x) + \sum_{i = 0}^n \frac{\partial F}{\partial x_i}(t,x) f_i(t,x) = 0, \forall(t,x) \in \mathbb{R} \\
\frac{\partial F}{\partial t}(t,x) + \frac{dF}{\partial x_1} (t,x) f_1(t,x)+ \frac{\partial F}{\partial x_2} (t,x) f_2(t,x) =\\
=(x_1 -x_2) e^{t-t^2}(1-2t) +  e^{t-t^2} (2tx_1 + x_2) -  e^{t-t^2} (x_1 -2tx_1 -x_2 =2tx_2 +2tx_1 +x_2 -x_1 -2tx_2) =\\
= 0 \implies F \text{ este integrala prima a sistemului.}
$$

c.
$$
F \text{ este integrala prima } \implies F(t,x) = C_1, C_1 \in \mathbb{R} \\
\implies (x_1 - x_2) e^{t-t^2} = C_1 \\
\implies x_1 = \frac{C_1}{e^{t-t^2}} + x_2 = C_1 e^{t-t^2} + x_2 \\
x_2' = x_2 + C_1 e^{t-t^2} + 2 t x_2 \\
\implies x_2' = x_2(1+2t) + C_1 e^{t-t^2} \text{ care este o ecuatie liniara ne-omogena in } x_2 \\
\overline{x_2'} = \overline{x_2}(1+2t) \\
x_2 = C e^{A(t)}\\
\int (1+2t)\operatorname{d}\!t = t + t^2 \implies \overline{x_2} = C e^{t^2 + t} \\
x_2(t) = C(t) e^{t^2 + t} \text{ solutia ecuatiei liniare ne-omogene} \\
C' e^{t^2 + t} + C (2t+1) e^{t^2 + t} = C e^{t^2 + t}(1 + 2t) + C e^{t^2 + t} \\
C' = C_1 e^{-2t} \text{ care este ecuatie de tip primitiva} \\
\implies C = \int C_1 e^{-2t} \operatorname{d}\!t = C_1 \frac{e^{-2t}}{-2} + C_2 \\
\implies \begin{cases}x_2(t) = C_1 \frac{e^{-2t}}{-2} + C_2 \\
x_1(t) = C_1 e^{t^2-t} + C_1 \frac{e^{-2t}}{-2} + C_2 e^{t^2 + t} \end{cases} C_1, C_2 \in \mathbb{R}
$$

**Tema**:
2. Fie sistemul $\begin{cases} x_1' = f_1(t,(x_1, x_2))\\ x_2'= f_2(t, (x_1, x_2))\end{cases}$, x = $ \begin{pmatrix} x_1 \\ x_2 \end{pmatrix}$, $\begin{cases} f_1(t,(x_1, x_2)) = -x_1(x_1^2 + x_2^2) \\ f_2(t,(x_1, x_2)) = -x_2(x_1^2 + x_2^2)\end{cases}$.
        a. Stabiliti daca sistemul dat verifica conditiile teoremei de existenta si unicitate daca adaugam sistemului conditia $x(t_0) = x_0 = \begin{pmatrix} x_{01} \\ x_{02} \end{pmatrix} \in \mathbb{R}^2$
        b. Demonstrati ca $F (t, (x_1, x_2)) = 2t - \left(x_1^2 + x_2^2\right)$ este integrala prima a sistemului.
        c. Determinati multimea solutiilor sistemului dat folosind integrala prima.

#Sisteme liniare de ecuatii diferentiale

##Cazul omogen

$x' = A(t) x$ unde $A: I \subset \mathbb{R} \to \mathscr{M}_n(\mathbb{R})$ si $x = $

Multimea solutiilor sistemului este spatiu vectorial real de dimensiune $n$, notat $S_A$. Se numeste sistem fundamental de solutii o baza in $S_A$. Adica $S_A = <\varphi_1, \dots, \varphi_n>$

###Cazul omogen cu coeficienti constanti
 Adica cazul in care $A(t) = \text{ constant } = A \in \mathscr{M}_n(\mathbb{R})$.
 $x' = Ax$

 Pasi de determinare a unui sistem fundamental de solutii:
 1. Se determina valorile proprii ale matricei $A$ si multiplicitatile lor.
 $\sigma(A) = \{\lambda_1, \dots, \lambda_p\}$ cu $1 \leq p \leq n$,
$m_1 + \dots + m_p = n$,
$\det(A - \lambda I_n) = 0$
 2. Pentru fiecare $\lambda_k \in \sigma(A)$ se determina $m_p$ solutii ale sistemului $x' = A x$ care sunt introduse in sistemul fundamental de solutii.

**Exercitiu**: Pentru urmatoarele sisteme scrieti forma matriceala si apoi determinati un sistem fundamental de solutii.
1. $\begin{cases}x_1' = 2x_1 + 2x_2 \\ x_2' = 8x_1 + 2x_2\end{cases}$
2. $\begin{cases}x_1'=2x_1 + 2x_2 \\ x_2' = -x_1 + 2x_2\end{cases}$
3. $\begin{cases}x_1' = 3x_1 -2 x_2\\ x_2' = 2x_1 -x_2\end{cases}$
4. $\begin{cases}x_1' = x_2 + x_3 \\ x_2' = x_1 + x_3 \\ x_3' = x_1 + x_2\end{cases}$
5. $\begin{cases}x_1' = 2x_1 - x_2 - x_3 \\ x_2' = 2x_1 - x_2 - 2x_3 \\ x_3' = 2x_3 - x_1 + x_2\end{cases}$
6. $\begin{cases}x_1' = 2x_1 + 2x_3 - x_2 \\ x_2' = x_1 + 2x_3 \\ x_3' = x_2 -2x_1 -x_3\end{cases}$

*Rezolvari*:
1. $$
A = \left(\begin{array}{nume1}2 & 2 \\ 8 & 2\end{array}\right) \\
A - \lambda I_2 =  \left(\begin{array}{nume1}2 & 2 \\ 8 & 2\end{array}\right) - \left(\begin{array}{nume1} \lambda & 0 \\ 0 & \lambda \end{array}\right) = \left(\begin{array}{nume1} 2 - \lambda & 2 \\ 8 & 2 - \lambda \end{array}\right) \\
\det(A - \lambda I_2 ) = (2 - \lambda)^2 - 16 \implies \lambda_1 = -2 \text{ si } \lambda_2 = 6 \\
m_1 = 1, m_2 = 1 \\
\\
\lambda_1 = -2 \text{ cu multiplicitatea } m_1 = 1 \\
\text{ Se determina } u \in \mathbb{R}^2 \neq 0_{\mathbb{R}^2} \text{ astfel incat } (A - \lambda_1 I_2) u = 0_{\mathbb{R}^2} \\
(A - \lambda_1 I_2) u = \left(\begin{array}{nume}0 \\ 0 \end{array}\right) = \left(\begin{array}{nume}4 & 2 \\ 8 & 4\end{array} \right) \left(\begin{array}{nume}u_1 \\ u_2\end{array}\right) = \left(\begin{array}{nume}0 \\ 0\end{array}\right) \\
\begin{cases}4 u_1 + 2u_2 = 0 \\ 8u_1 +4u_2 = 0\end{cases} \implies u_2 = -2u_1 \implies u = \left(\begin{array}{nume}u_1 \\ -2u_1\end{array}\right) = \left(\begin{array}{nume}1 \\ -2\end{array}\right) u_1, \text{ cu } u_1 \in \mathbb{R}\\
\text{Pentru } u = \left(\begin{array}{nume}1 \\ -2\end{array}\right) \implies \varphi_1(t) = u e^{\lambda_1 t} = \left(\begin{array}{nume}1 \\ -2\end{array}\right) e^{-2t} \implies \varphi_1 = \left(\begin{array}{nume}e^{-2t} \\ -2e^{-2t}\end{array}\right) \\
\\
\lambda_2 = 6 \text{ cu multiplicitatea } m_2 = 1 \\
u \in \mathbb{R}^2 \neq 0_{\mathbb{R}^2} \\
(A - \lambda_2 I_2) u = \left(\begin{array}{nume}0 \\ 0\end{array}\right)\\
\left(\begin{array}{nume}-4 & 2 \\ 8 & -4\end{array}\right) \left(\begin{array}{nume}u_1 \\ u_2\end{array}\right) = \left(\begin{array}{nume}0 \\ 0 \end{array}\right) \\
\begin{cases}-4 u_1 + 2u_2 = 0 \\ 8 u_1-4u_2 = 0 \end{cases} \implies u_2 = 2u_2 \implies u = \left(\begin{array}{nume}1 \\ 2\end{array}\right) u_1 \\
u = \left(\begin{array}{nume}1 \\ 2\end{array}\right) \implies \varphi_2(t) = \left(\begin{array}{nume}1 \\ 2\end{array} \right) e^{\lambda_2 t} = \left(\begin{array}{nume}1 \\ 2\end{array}\right) e^{6 \lambda} \implies \varphi_2(t) = \left(\begin{array}{nume}e^{6t} \\ 2e^{6t}\end{array}\right) \\
S_A = \left\{\varphi(t) = C_1 \varphi_1(t) + C_2 \varphi_2(t) | C_1, C_2 \in \mathbb{R}\right\} \\
\text{ sau } \\
S_A = \left\{x_1(t) = C_1 e^{-2t} + C_2 e^{6t}, x_2(t) = C_1 (-2e^{-2t}) + C_2 2e^{6t} | C_1, C_2 \in \mathbb{R}\right\} \\
\text{ sau } \\
\Phi(t) = \left(\begin{array}{nume}e^{-2t} & e^{6t} \\ -2e^{-2t} & 2e^{6t}\end{array}\right) \implies S_A= \left\{\varphi(t) = \Phi(t) C | C = \left(\begin{array}{nume}C_1 \\ C_2 \end{array}\right) \in \mathbb{R}^2\right\}
$$
2. **tema**
3. **tema**
4. $$ \left(\begin{array}{nume}   \end{array}\right)
A = \left(\begin{array}{nume} 0 & 1 & 1 \\ 1 & 0 & 1 \\ 1 & 1 & 0 \end{array}\right) \\
\det(A - \lambda I_3) = -\lambda^3 + 3 \lambda + 2 \\
-\lambda^3 + 3 \lambda + 2 = 0 \\
\implies \lambda_1 = \lambda_3 = -1 \text{ cu multiplicitatea } m_1 = 2 \\
\implies \lambda_2 = 2 \text{ cu multiplicitatea } m_2 = 1 \\
\implies \sigma(A) = \{-1, 2\} \\
\lambda_1 = -1, m_1 = 2 > 1 \\
\text{ Se determina} m \text{ vectori } (v_0, \dots, v_{m_1-1}) \text{, nu toti nuli, in } \mathbb{R}^3 \text{astfel incat } \\
\varphi(t) = (v_0 + v_1 t + v_2 t^2 + \dots + v_{m_1-1} t^{m_1-1}) \text{ sa fie solutie a sistemului } x'=Ax \\
\text{Pentru } m_1 = 2 \implies \text{ determinam } v_0 \text{ si } v_1 \in \mathbb{R}^3 \text{ nu amandoi nuli, astfel incat } \\
\varphi(t) = (v_0 + v_1 t)e^{-t} \text{ sa fie solutie a sistemului } x' = Ax \\
((v_0 + v_1t)e^{-t}) = A (v_0 + v_1 t) e^{-t} \iff \\
v_1 e^{-t} -(v_0 + v_1 t)e^{-t} = A (v_0 v_1t)e^{-t} \iff \\
v_1 - v_0 - v_1 t = A v_0 + A v_2 t \\
\begin{cases}-v_1 = A v_1 \\ v_1 -v_0 = A v_0 \end{cases} \iff \begin{cases} A v_1 + v_1 = 0 \\ A v_0 + v_0 = v_1\end{cases} \iff \begin{cases} (A + I_3)v_1 = 0 \\ (A + I_3)v_0 = v_1\end{cases} \implies \\
\implies (A+ I_3)^2 v_0 = 0 \implies
(A + I_3)^2 = \left(\begin{array}{nume} 3 & 3 & 3 \\ 3 & 3 & 3 \\ 3 & 3 & 3\end{array}\right) \implies v_0 \in \ker\left((A+I_3)^2\right) \subseteq \mathbb{R}^3 \\
\text{Pentru } v_0 \text{ este suficient sa consideram valorile unei baze din } \ker\left((A+I_3)^2\right) \\
(A + I_3)^2 u = \left(\begin{array}{nume} 0 \\ 0 \\ 0  \end{array}\right) \iff \left(\begin{array}{nume}  3 & 3 & 3 \\ 3 & 3 & 3 \\ 3 & 3 & 3 \end{array}\right) \left(\begin{array}{nume}  u_1 \\ u_2 \\ u_3 \\ \end{array}\right) = \left(\begin{array}{nume}   0 \\0 \\ 0 \end{array}\right) \\
\implies u_1 = -u_2 -u_3 \\
\implies \forall u \in \ker\left((A+I_3)^2\right) \implies u = \left(\begin{array}{nume} -u_2 -u_3 \\ u_2 \\ u_3  \end{array}\right) \\
\implies u = \left(\begin{array}{nume}  -1 \\ 1 \\ 0  \end{array}\right) u_2 + \left(\begin{array}{nume}  -1 \\ 0 \\ 1 \end{array}\right) u_3 \implies \text{ o baza in } \ker\left((A+I_3)^2\right) \text{ este } \left(\begin{array}{nume}  -1 \\ 1 \\ 0  \end{array}\right), \left(\begin{array}{nume}  -1 \\ 0 \\ 1 \end{array}\right) \\
v_0 = \left(\begin{array}{nume}  -1 \\ 1 \\ 0  \end{array}\right) \implies v_1 = (A + I_3) v_0 \implies v_1 = \left(\begin{array}{nume} 0 \\ 0 \\ 0  \end{array}\right) \implies \varphi_1(t) =\left( \left(\begin{array}{nume}  -1 \\ 1 \\ 0 \end{array}\right) + \left(\begin{array}{nume}  0 \\ 0 \\ 0\end{array}\right) t\right)e^{-t} = \left(\begin{array}{nume}  -e^{-t} \\ e^{-t} \\ 0 \end{array}\right) \\
v_0 = \left(\begin{array}{nume}  -1 \\ 0 \\ 1 \end{array}\right) \implies v_1 = \left(\begin{array}{nume}  0 \\ 0 \\0\end{array}\right) \implies \varphi_2(t) = \left(\begin{array}{nume} -e^{-t} \\ 0 \\ e^{-t}  \end{array}\right) \\
\\
\lambda_2 = 2 \text{ cu multiplicitatea } m_2 = 1 \\
\text{Determinam } u \in \mathbb{R}^3 \neq \left(\begin{array}{nume} 0 \\ 0 \\ 0  \end{array}\right) \text{ astfel incat } \left(A - \lambda_2 I_3\right) u = \left(\begin{array}{nume} 0 \\ 0 \\ 0  \end{array}\right) \\
\left(\begin{array}{nume} -2 & 1 & 1 \\ 1 & -2 & 1 \\ 1 & 1 & -2  \end{array}\right) \left(\begin{array}{nume} u_1 \\ u_2 \\ u_3    \end{array}\right) = \left(\begin{array}{nume} 0 \\ 0 \\ 0  \end{array}\right) \\
\implies u_2 = u_3 \text{ si } u_1 = u_3 \\
\implies u = \left(\begin{array}{nume}  1 \\ 1 \\ 1 \end{array}\right) u_3 \\
\implies \varphi_3(t) = u e^{\lambda_2 t} = \left(\begin{array}{nume}  1 \\ 1 \\ 1 \end{array}\right) e^{2t} \implies \varphi_3(t) = \left(\begin{array}{nume} e^{2t} \\ e^{2t} \\ e^{2t}   \end{array}\right) \\
S_A = \{\varphi(t) = C_1 \varphi_1(t +  C_2 \varphi_2(t) +  C_3 \varphi_3(t)) | C_1, C_2, C_3 \in \mathbb{R}\} \\
\text{ sau } \\
S_A = \begin{cases}x_1(t) = -C_1 e^{-t} + C_2 e^{-t} + C_3 e^{2t} \\ x_2(t) = C_1 e^{-t} + C_3 e^{2t} \\ x_3(t) = C_2 e^{-t} + C_3 e^{2t}  \end{cases} \\
\text{ sau } \\
\phi(t) = \left(\begin{array}{nume} e^{-t} & e^{-t} & e^{2t} \\ e^{-t} & 0 & e^{2t} \\ 0 & e^{-t} & e^{2t}  \end{array}\right) S_A = \left\{\varphi(t) = \phi(t) C | C \in \mathbb{R}^3\right\}
$$
5. **tema**
6. **tema**

> **NU SE GARANETAZA CORECTITUDINEA SAU COMPLETITUDINEA INFORMATIILOR DE AICI**

> Ai descoperit o greseala? Ai facut o tema si vrei sa o dai si colegilor? Stii cum sa faci ceva sa arate mai bine? Contribuie [direct pe GitHub](https://github.com/Vlaaaaaaad/FMI-public-materials/tree/master/EcuatiiDiferentialeSiCuDerivatePartiale) sau trimite un mail la <mailto:stiu-chestii@vladionescu.me>



> Written with [StackEdit](https://stackedit.io/).
