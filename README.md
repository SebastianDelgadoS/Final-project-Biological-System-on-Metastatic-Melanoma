[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=SebastianDelgadoS/Final-project-Biological-System-on-Metastatic-Melanoma)
# Gemelos Digitales. Project Final: Biological System on Metastatic Melanoma [DelgadoC20212281]

## Autor
Delgado Soto Jose Sebastian

Ingeniería Biomédica, Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México/IT Tijuana. Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México. Email: l20212281@tectijuana.edu.mx

## Resumen de la práctica
Esta práctica modela la evolución del melanoma metastásico mediante un sistema de ecuaciones diferenciales que simula la interacción entre células tumorales, tejido sano y células del sistema inmune. Se utilizan datos experimentales para simular y ajustar el modelo matemático, aplicando técnicas de suavizado y normalización. A través de regresión no lineal, se estiman parámetros que permiten representar con precisión el comportamiento biológico del sistema. El análisis de estabilidad revela que no existe un equilibrio biológico donde coexistan las tres poblaciones, predominando el crecimiento tumoral. Se identifican dos puntos de equilibrio: uno trivial y otro con dominio del tumor. Las simulaciones muestran una rápida proliferación del cáncer, supresión inmune y destrucción del tejido sano. El modelo ofrece una base útil para estudiar terapias como la inmunoterapia.

## Objetivos específicos
1.Implementar el método de Heun para resolver numéricamente el sistema de ecuaciones diferenciales que describe la interacción entre células tumorales, tejido sano y células inmunes, utilizando datos experimentales como base.

2.Representar gráficamente la curva ajustada del modelo, con el fin de comparar visualmente los resultados simulados frente a los datos reales y evaluar la precisión del ajuste.

3.Determinar los principales parámetros estadísticos del modelo, como el coeficiente de determinación (R²), el error estándar y el AIC corregido, para validar cuantitativamente el desempeño del sistema.

4.Estimar las tasas de crecimiento 𝜌 y 𝛾 de las poblaciones celulares mediante técnicas de regresión no lineal aplicadas a datos suavizados y normalizados.

5.Analizar la estabilidad del sistema dinámico a través del cálculo de la matriz Jacobiana, la obtención de puntos de equilibrio y la evaluación de sus valores propios.

## Docente
Dr. Paul A. Valle

Posgrado en Ciencias de la Ingeniería [PCI] y Departamento de Ingeniería Eléctrica y Electrónica [DIEE], Tecnológico Nacional de México/IT Tijuana. Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México. Email: paul.valle@tectijuana.edu.mx

## Lecturas
[1] Paul. A. Valle, Syllabus de Biomatemáticas para la asignatura de Gemelos Digitales, Tecnológico Nacional de México/IT Tijuana, Tijuana, B.C., México, 2025. Permalink: https://www.dropbox.com/s/6yf9afxzih9y458/Biomatematicas.pdf

[2] Dominik Wordaz & Natalia L. Komarova, Dynamics of Cancer: Mathematical Foundations of Oncology, University of California, Irvine, USA, 2014.

