# Introducción
El curso está organizado en tres bloques principales, que se irán conectando de manera progresiva a lo largo del semestre.

En la primera parte se introducen las herramientas básicas del análisis dinámico. El énfasis está en ecuaciones diferenciales ordinarias, ecuaciones en diferencias y sistemas dinámicos, tanto en tiempo continuo como discreto. La idea es que obtengan herramientas, intuición y práctica en el análisis de trayectorias dinámicas, estabilidad, estados estacionarios y comportamiento de largo plazo, más allá de la mera solución mecánica de ecuaciones.

La segunda parte está dedicada a optimización dinámica. Se comienza con un repaso breve del cálculo de variaciones, que sirve como puente hacia el control óptimo en tiempo continuo (Hamiltoniano) y la programación dinámica en tiempo discreto (Bellman).

La tercera parte está dedicada a la aplicación de estas herramientas a modelos macroeconómicos. En particular, se trabajará el modelo clásico de ciclos económicos reales (RBC) al estilo de Hansen, para después introducir factores monetarios y concluir con fricciones nominales. En particular, el bloque termina con la formulación, calibración y análisis del modelo DSGE Nuevo Keynesiano canónico. Todo lo anterior con teoría y simulación en Dynare.

# Preparación previa recomendada
A continuación, una guía de preparación previa al curso. Recomiendo ampliamente llegar con familiaridad conceptual (no necesariamente dominio técnico completo) de los siguientes temas, ya que les facilitará mucho el ritmo del curso. La mayor parte de estos temas los abarcarán en las primeras dos semanas del semestre.

# Ecuaciones Diferenciales Ordinarias (EDO)
## Definiciones y Conceptos Básicos
- Definición de Ecuación Diferencial Ordinaria
- Solución general, solución particular y curvas solución
- Campos direccionales e isoclinas
- Problemas de valor inicial y de valor en la frontera
- Teorema de existencia y unicidad (opcional)
- Estados estacionarios, estabilidad local y estabilidad en el sentido de Lyapunov (opcional)
# Tipos de EDO de Primer Orden
- Ecuaciones de variables separables
- Ecuaciones homogéneas
- Ecuaciones exactas y cuasi-exactas
- Ecuaciones lineales homogéneas y no homogéneas
# EDO de Orden Superior
- Ecuaciones lineales homogéneas y no homogéneas con coeficientes constantes
- # Sistemas de Ecuaciones Lineales con Coeficientes Constantes
- Sistemas Homogéneos
- Sistemas No Homogéneos

## Bibliografía recomendada
- Boyce, W. E., DiPrima, R. C., & Meade, D. B. (2017). Elementary differential equations and boundary value problems. 11th ed. Wiley. **(Mi preferido)**
- Kiseliov, A., Krasnov, M., & Makarenko, G. (1984). Problemas de ecuaciones diferenciales ordinarias. 4th ed. Editorial MIR. **(Ejercicios y algo de teoría)**
- Zill, D. G., & Cullen, M. R. (2009). Differential equations with boundary-value problems. 7th ed. Cengage Learning. **(El que más usará Itza para esta parte del curso)**
- Hirsch, M. W., Smale, S., & Devaney, R. L. (2013). Differential equations, dynamical systems, and an introduction to chaos. 3th ed. Academic Press. **(Bueno para sistemas dinámicos)**
- V. I. Arnol’d (1992) Ordinary Differential Equations. Springer, 1992.
- Chicone, C. (2006). Ordinary differential equations with applications. Second Edition. Springer. **(Una introducción sin dolor a la teoría de ecuaciones diferenciales)**

## Bibliografía recomendada (Aplicaciones a Economía)
- B. Heijdra (2017), Foundations of Modern Macroeconomics, 3th ed., Oxford University Press.
-	Lomelí, H. y Rumbos, B. (2003). Métodos dinámicos en economía. Otra búsqueda del tiempo perdido. International Thomson Editores.
-	K. Sydsæter, P. Hammond, A. Seierstad, and A. Strøm (2008). Further Mathematics for Economic Analysis, 2nd ed. Prentice Hall.

# Ecuaciones en Diferencia
Para ecuaciones en diferencia, no existe un libro canónico. Sin embargo, las mejores recomendaciones son:
- Enders, W. (2015). Applied econometric time series, 4th ed. Wiley. **(Cap. 1)**
- J. Miao (2014), Economic Dynamics in Discrete Time, 1a Ed. The MIT Press.

# Optimización Dinámica
No hay mejor recomendación para introducirse a este tema y profundizar que la siguiente:
- Cerdá, E. (2001). Optimización Dinámica. Prentice Hall.
No obstante, la verdadera biblia es el Stokey & Lucas:
- Stokey, N. & Lucas, R. (1989). Recursive Methods in Economic Dynamics. Harvard University Press. (Stokey)
Una versión moderna de las aplicaciones de métodos recursivos en macroeconomía (i.e. programación dinámica), es decir de toda la teoría desarrollada en Stokey y Lucas, es el Sargent:
- Ljungqvist, L., & Sargent, T. J. (2018). Recursive macroeconomic theory, 4th ed. MIT Press.

# RBC/DSGEs
Posiblemente el mejor libro para introducirse a este tema:
- McCandless, G. (2008). The ABCs of RBCs: An introduction to dynamic macroeconomic models. Harvard University Press.
Para NK-DSGEs:
- Galí, J. (2015). Monetary Policy, Inflation, and the Business Cycle. Princeton University Press. **(EL libro de texto de NK-DSGE)**
- Walsh, C. E. (2017). *Monetary Theory and Policy, 4ed. MIT press. **(Otra referencia muy citada en la literatura)**
- Woodford, M. (2003).Interest and Prices. Foundations of a Theory of Monetary Policy. Princeton University Press. **(Un clásico en economía monetaria)**
- Obstfeld, M. and K. Rogoff (1996). Foundations of International Macroeconomics. MIT press. **(Principalmente el capítulo 10)**




# Ecuaciones en Diferencia
Para ecuaciones en diferencia no existe un libro verdaderamente canónico. Sin embargo, las siguientes referencias son, a mi parecer, las más útiles:
- Enders, W. (2015). *Applied Econometric Time Series*, 4th ed. Wiley. **(Cap. 1)**
- Miao, J. (2014). *Economic Dynamics in Discrete Time*, 1st ed. The MIT Press. **(Tratamiento formal, aunque medio enredado)**

# Optimización Dinámica
La mejor recomendación es:
- Cerdá, E. (2001). *Optimización Dinámica*. Prentice Hall.

No obstante, la verdadera biblia de los métodos dinámicos en economía es el Stokey & Lucas:
- Stokey, N. & Lucas, R. (1989). *Recursive Methods in Economic Dynamics*. Harvard University Press.

Una presentación moderna y aplicada de métodos recursivos en macroeconomía es:
- Ljungqvist, L., & Sargent, T. J. (2018). *Recursive Macroeconomic Theory*, 4th ed. MIT Press.

# RBC / DSGEs
Posiblemente el mejor libro para los modelos RBC es:
- McCandless, G. (2008). *The ABCs of RBCs: An Introduction to Dynamic Macroeconomic Models*. Harvard University Press.
El siguiente tambien es bueno, principalmente para programar en Dynare:
- Chirichillo, G. (2021). *DSGE models for real business cycle and New Keynesian macroeconomics: Theoretical methods and numerical solutions with Dynare*. Springer.

Para modelos DSGEs Nuevo Keynesianos:
- Galí, J. (2015). *Monetary Policy, Inflation, and the Business Cycle*. Princeton University Press. **(El libro de texto por excelencia en NK-DSGE)**
- Chirichillo, G. (2021). *DSGE models for real business cycle and New Keynesian macroeconomics: Theoretical methods and numerical solutions with Dynare*. Springer.
- Walsh, C. E. (2017). *Monetary Theory and Policy*, 4th ed. MIT Press. **(Referencia central en economía monetaria moderna)**
- Woodford, M. (2003). *Interest and Prices: Foundations of a Theory of Monetary Policy*. Princeton University Press. **(Clásico fundamental)**
- Obstfeld, M., & Rogoff, K. (1996). *Foundations of International Macroeconomics*. MIT Press. **(Especialmente el Capítulo 10)**

