# Introducción
El curso está organizado en tres bloques principales, que se irán conectando de manera progresiva a lo largo del semestre.

En la primera parte se introducen las herramientas básicas del análisis dinámico. El énfasis está en ecuaciones diferenciales ordinarias, ecuaciones en diferencias y sistemas dinámicos en tiempo continuo y discreto. La idea es que obtengan herramientas, intuición y práctica en el análisis de trayectorias, estados estacionarios y estabilidad (comportamiento de largo plazo), más allá de la mera solución mecánica de ecuaciones.

La segunda parte está dedicada a optimización dinámica. Se comienza con un breve repaso del cálculo de variaciones, que sirve como puente hacia el control óptimo en tiempo continuo (Hamiltoniano) y la programación dinámica en tiempo discreto (Bellman).

La tercera parte está dedicada a la aplicación de estas herramientas a modelos macroeconómicos. En particular, trabajarán el modelo clásico de ciclos económicos reales (RBC) al estilo de Hansen, para después introducir factores monetarios y concluir con fricciones nominales. En particular, el bloque termina con la formulación, calibración y análisis del modelo DSGE Nuevo Keynesiano canónico. Todo lo anterior con teoría y simulación en Dynare.

# Preparación previa recomendada
A continuación se presenta una guía de preparación previa al curso. Recomiendo ampliamente llegar con familiaridad conceptual (no necesariamente con dominio técnico completo) de los siguientes temas, ya que les facilitará mucho el ritmo del curso. En particular, las ecuaciones diferenciales de primer orden se cubrirán durante la primera semana del semestre; por ello, sugiero priorizar el repaso de EDOs de primer orden, especialmente las definiciones y conceptos básicos, así como los principales tipos y métodos de solución. Para esta parte, pueden apoyarse con videos de YouTube para ver los métodos de solución. Mi recomendación para esta sección es el [curso completo de ecuaciones diferenciales de MateFacil](https://www.youtube.com/playlist?app=desktop&list=PL9SnRnlzoyX0RE6_wcrTKaWj8cmQb3uO6).

Por otro lado, el curso hace un uso intensivo de varios conceptos de álgebra lineal. En particular, álgebra matricial, los operadores de determinante y traza, y la relación entre el polinomio característico, valores y vectores propios con el determinante y la traza. Si se sienten un poco oxidados con estos temas, les recomiendo darles un repaso previo, aunque sea de manera rápida. Pueden apoyarse en la referencia que les resulte más cómoda. Personalmente, recomiendo la siguiente:
- Axler, S. (2024). *Linear algebra done right*. 4th Edition. Springer.

De cualquier forma, conforme vayamos necesitando estas propiedades podrán consultarlas sin problema.

# Ecuaciones Diferenciales Ordinarias (EDO)
## Definiciones y Conceptos Básicos
- Definición de EDO
- Solución general, solución particular y curvas solución
- Campos direccionales e isoclinas
- Problemas de valor inicial y de valor en la frontera
- Teorema de existencia y unicidad (opcional)
- Estado estacionario, estabilidad local y estabilidad en el sentido de Lyapunov (opcional)
## EDO de Primer Orden
- Ecuaciones de variables separables
- Ecuaciones homogéneas
- Ecuaciones exactas y cuasi-exactas
- Ecuaciones lineales homogéneas y no homogéneas
## EDO de Orden Superior
- Ecuaciones lineales homogéneas y no homogéneas con coeficientes constantes
## Sistemas de Ecuaciones Lineales con Coeficientes Constantes
- Sistemas Homogéneos
- Método de valores propios
- Clasificación de Puntos de Equilibrio
- Plano Traza-Determinante
- Sistemas No Homogéneos
## Sistemas de Ecuaciones No Lineales
- Sistemas autónomos no lineales
- Linealización de puntos de equilibrio

## Bibliografía recomendada
- Boyce, W. E., DiPrima, R. C., & Meade, D. B. (2017). *Elementary differential equations and boundary value problems*. 11th Edition. Wiley. **(Favorito personal)**
- Kiseliov, A., Krasnov, M., & Makarenko, G. (1984). *Problemas de ecuaciones diferenciales ordinarias*. 4th Edition. Editorial MIR. **(Ejercicios y algo de teoría)**
- Zill, D. G., & Cullen, M. R. (2009). *Differential equations with boundary-value problems*. 7th Edition. Cengage Learning. **(El que más usará Itza para esta parte del curso)**
- Hirsch, M. W., Smale, S., & Devaney, R. L. (2013). *Differential equations, dynamical systems, and an introduction to chaos*. 3th Edition. Academic Press. **(Bueno para sistemas dinámicos)**
- V. I. Arnol’d (1992). *Ordinary Differential Equations*. Springer, 1992.
- Chicone, C. (2006). *Ordinary differential equations with applications*. 2nd Edition. Springer. **(Una introducción sin dolor a la teoría de ecuaciones diferenciales)**

## Bibliografía recomendada (Aplicaciones a Economía)
-	Lomelí, H. & Rumbos, B. (2003). *Métodos dinámicos en economía. Otra búsqueda del tiempo perdido*. International Thomson Editores.
-	Sydsæter, K., Hammond, p., Seierstad, A., & Strøm, A. (2008). *Further Mathematics for Economic Analysis*. 2nd Edition. Prentice Hall.
- Heijdra, B. (2017). *Foundations of Modern Macroeconomics*. 3th Edition. Oxford University Press.

# Ecuaciones en Diferencia
Para ecuaciones en diferencia no existe un libro verdaderamente canónico. Sin embargo, las siguientes referencias son, a mi parecer, las más útiles:
- Enders, W. (2015). *Applied Econometric Time Series*. 4th Edition. Wiley. **(Cap. 1)**
- Miao, J. (2014). *Economic Dynamics in Discrete Time*. 1st Edition. The MIT Press. **(Tratamiento formal, aunque medio enredado)**

# Optimización Dinámica
No hay mejor recomendación para introducirse y profundizar que la siguiente:
- Cerdá, E. (2001). *Optimización Dinámica*. Prentice Hall.

No obstante, la verdadera biblia es el Stokey & Lucas:
- Stokey, N. & Lucas, R. (1989). *Recursive Methods in Economic Dynamics*. Harvard University Press. (Stokey)

Una presentación moderna y aplicada de métodos recursivos en macroeconomía es:
- Ljungqvist, L., & Sargent, T. J. (2018). *Recursive Macroeconomic Theory*. 4th Edition. MIT Press.

# RBC/DSGEs
Posiblemente el mejor libro para los modelos RBC es:
- McCandless, G. (2008). *The ABCs of RBCs: An introduction to dynamic macroeconomic models*. Harvard University Press.

El siguiente tambien es bueno, principalmente para programar en Dynare:
- Chirichillo, G. (2021). *DSGE models for real business cycle and New Keynesian macroeconomics: Theoretical methods and numerical solutions with Dynare*. Springer.

Para NK-DSGEs:
- Galí, J. (2015). *Monetary Policy, Inflation, and the Business Cycle*. Princeton University Press. **(EL libro de texto de NK-DSGE)**
- Walsh, C. E. (2017). *Monetary Theory and Policy. 4th Edition*. MIT press. **(Otra referencia muy citada en la literatura)**
- Woodford, M. (2003). *Interest and Prices. Foundations of a Theory of Monetary Policy*. Princeton University Press. **(Un clásico en economía monetaria)**
- Obstfeld, M. & K. Rogoff (1996). *Foundations of International Macroeconomics*. MIT press. **(Principalmente el capítulo 10)**
