<div align="center">
    <h1>Fundamentos de Estadística y Análisis de Datos con Python</h1>
    
</div>
-----------------------
# Estadistica-con-Python
En este repositorio muestro las distintas herramientas que he aprendido a lo largo de estos años en el ambito de la Ciencia de Datos, 
como matemático mi interes es el de desarrollar e implementar modelos que permitan resolver las problematicas planteadas por la empresa,
institución o en donde sean requeridos estos conocimientos.

Python es ampliamente utilizado en el campo de la estadística por varias razones:

1. Facilidad de uso: Python es un lenguaje de programación de alto nivel y fácil de aprender. Tiene una sintaxis clara y legible, lo que facilita el desarrollo y la comprensión de código en comparación con otros lenguajes de programación estadística más complejos.

2. Gran cantidad de bibliotecas: Python cuenta con una amplia gama de bibliotecas especializadas en estadística y análisis de datos, como NumPy, pandas, SciPy y scikit-learn. Estas bibliotecas proporcionan herramientas y funciones eficientes para realizar cálculos estadísticos, manipular datos, realizar análisis exploratorio y aplicar algoritmos de aprendizaje automático.

3. Comunidad y soporte activo: Python tiene una comunidad de usuarios y desarrolladores muy activa que contribuye al desarrollo y mantenimiento de bibliotecas estadísticas. Esto significa que hay una gran cantidad de recursos, tutoriales, ejemplos y documentación disponibles en línea. Además, puedes encontrar ayuda y soporte fácilmente a través de foros y comunidades en línea.

4. Integración con otras áreas: Python es un lenguaje versátil que se puede utilizar en una amplia gama de aplicaciones y disciplinas. Se integra fácilmente con otras áreas, como visualización de datos (matplotlib, Seaborn), ciencia de datos (Jupyter Notebook), desarrollo web (Django, Flask) y mucho más. Esto permite un flujo de trabajo fluido y la capacidad de combinar análisis estadísticos con otras tareas o proyectos.

5. Flexibilidad: Python es un lenguaje flexible que permite abordar una amplia variedad de problemas estadísticos. Puedes adaptar y personalizar tus análisis según tus necesidades específicas. Además, puedes combinar código Python con otros lenguajes o herramientas según sea necesario.

En resumen, Python es elegido en el campo de la estadística debido a su facilidad de uso, la disponibilidad de bibliotecas especializadas, la comunidad activa de usuarios y desarrolladores, la capacidad de integración con otras áreas y su flexibilidad en el abordaje de problemas estadísticos. Estas características hacen de Python una opción popular y poderosa para trabajar con datos y realizar análisis estadísticos.

Personalmente recomiendo el libro [An Introduction to Statistics with Python](https://link.springer.com/book/10.1007/978-3-319-28316-6) es bastante accesible y permite comenzar desde un nivel bajo tanto de python y de estadística.

----------------
## Objetivos del documento

- Utilizar Python en estadistica.
- Introducir conceptos básicos de estadística.
- Caracterizar información a través del análisis exploratorio.
- Aplicar conceptos de probabilidad a eventos aleatorios.
- Construir conceptos estadísticos analíticos.
- Realizar inferencias estadisticas a partir de una muestra.
- Usar modelos estadísticos para exploración y predicción.
- Introducir conceptos de analítica avanzada.

------------

## Plan de estudio 

Si deseas aprender estadística desde los fundamentos hasta un nivel de doctorado, te recomendaría seguir un plan de estudio que abarque los siguientes temas:

1. Matemáticas básicas: Comienza por reforzar tus conocimientos en matemáticas básicas, incluyendo álgebra, cálculo diferencial e integral, y probabilidad. Estos conceptos son fundamentales para comprender la estadística.

2. Estadística descriptiva: Aprende los conceptos básicos de estadística descriptiva, que incluyen medidas de centralidad, dispersión, distribuciones de frecuencia, gráficos estadísticos y análisis exploratorio de datos.

3. Probabilidad: Profundiza en los conceptos de probabilidad, incluyendo eventos, espacio muestral, reglas de probabilidad, variables aleatorias y distribuciones de probabilidad (binomial, normal, Poisson, etc.).

4. Inferencia estadística: Aprende los fundamentos de la inferencia estadística, que incluyen estimación puntual y por intervalos, pruebas de hipótesis, intervalos de confianza, análisis de varianza (ANOVA) y regresión lineal.

5. Diseño de experimentos: Familiarízate con los principios y técnicas de diseño experimental, incluyendo el diseño de experimentos completamente aleatorizados, en bloques y factoriales.

6. Modelos de regresión avanzados: Estudia modelos de regresión más avanzados, como regresión múltiple, regresión logística, regresión no lineal y modelos de series temporales.

7. Análisis multivariado: Aprende técnicas de análisis multivariado, como análisis de componentes principales, análisis factorial, análisis discriminante y análisis de conglomerados.

8. Métodos estadísticos avanzados: Explora métodos estadísticos más avanzados, como análisis de supervivencia, modelos lineales generalizados, modelos mixtos, análisis de datos longitudinales y métodos de muestreo complejo.

9. Programación y herramientas estadísticas: Adquiere habilidades en programación, especialmente en Python o R, para realizar análisis estadísticos, visualización de datos y modelado. Familiarízate con herramientas estadísticas como NumPy, pandas, SciPy, scikit-learn (en Python) o tidyverse (en R).

10. Investigación y metodología: En un nivel de doctorado, es importante desarrollar habilidades de investigación y comprender los aspectos metodológicos de la estadística. Aprende a diseñar estudios, recopilar datos, analizarlos y presentar resultados de manera clara y efectiva.

Recuerda que el aprendizaje de la estadística es un proceso continuo y gradual. Es recomendable combinar estudios teóricos con ejercicios prácticos y proyectos para fortalecer tu comprensión y habilidades.

Además, te recomendaría consultar los planes de estudio de programas académicos en estadística o ciencias de datos de universidades reconocidas, ya que suelen ofrecer una secuencia de cursos que abarcan desde los fundamentos hasta los niveles más avanzados.

---------------------------


## Estadistica descriptiva 
La estadística descriptiva es una rama de la estadística que se centra en la descripción y resumen de datos mediante medidas y técnicas adecuadas. Su objetivo principal es proporcionar una comprensión básica de los datos y extraer información relevante de ellos sin hacer inferencias más allá de la muestra analizada. A continuación, se presentan los detalles clave de la estadística descriptiva:

Población y muestra: En estadística, una población se refiere al conjunto completo de elementos o individuos que se desea estudiar, mientras que una muestra es un subconjunto seleccionado de la población. La estadística descriptiva se aplica tanto a poblaciones como a muestras.

1. **Datos**: Los datos son la información recopilada y utilizada en un estudio estadístico. Pueden ser numéricos (variables cuantitativas) o no numéricos (variables cualitativas). Los datos pueden presentarse en diferentes formatos, como tablas, gráficos, listas, entre otros.

2. **Medidas de tendencia central**: Las medidas de tendencia central son utilizadas para describir la ubicación o valor central de un conjunto de datos. Las medidas más comunes son la media, la mediana y la moda. La media aritmética es la suma de todos los valores dividida por el número de valores. La mediana es el valor que separa el conjunto de datos en dos partes iguales, mientras que la moda es el valor que ocurre con mayor frecuencia.

3. **Medidas de dispersión**: Las medidas de dispersión miden la variabilidad o dispersión de los datos alrededor de una medida de tendencia central. Las medidas más utilizadas son el rango, la desviación estándar y la varianza. El rango es la diferencia entre el valor máximo y mínimo. La desviación estándar mide la dispersión promedio de los datos con respecto a la media. La varianza es el cuadrado de la desviación estándar.

4. **Gráficos estadísticos**: Los gráficos estadísticos son representaciones visuales de los datos que ayudan a comprender su distribución y características. Algunos gráficos comunes incluyen histogramas, diagramas de barras, diagramas de dispersión, diagramas de caja y bigotes, y gráficos de sectores.

5. **Medidas de posición**: Las medidas de posición proporcionan información sobre la ubicación relativa de un valor dentro de un conjunto de datos. Los percentiles son medidas de posición comunes que indican el porcentaje de datos que se encuentra por debajo de un valor dado. Por ejemplo, el percentil 75 (P75) es el valor que divide el conjunto de datos en el 75% inferior y el 25% superior.

6. **Tablas de frecuencia**: Las tablas de frecuencia son utilizadas para organizar y resumir datos discretos o categorizados. Muestran la frecuencia o conteo de observaciones en cada categoría. Además, se pueden calcular frecuencias relativas y porcentajes para tener una visión más completa de los datos.

7. **Medidas de asimetría y apuntamiento**: Estas medidas cuantifican la forma de la distribución de los datos. La asimetría mide si la distribución es simétrica (asimetría cercana a cero) o sesgada hacia un lado (asimetría positiva)

Si sabes hacer bien esta parte tanto en Python, R o Excel entonces podrias tener la capacidad de ser un análista Junior pues estas simplemes herramientas son de gran valor para las empresas ya que apartir de ella pueden tomar decisones rumbo a un mejor modelo de negocios.

## Visualización de datos

La visualización de datos es una parte fundamental del análisis estadístico de datos, ya que permite explorar, resumir y comunicar de manera efectiva los patrones, tendencias y relaciones presentes en los datos. Aquí hay algunos aspectos importantes sobre la visualización de datos en el análisis estadístico:

1. **Exploración de datos**: La visualización de datos proporciona una forma intuitiva de explorar los datos y obtener una comprensión inicial de su distribución, variabilidad y estructura. Los gráficos permiten identificar patrones, valores atípicos, relaciones entre variables y cualquier otra característica relevante.

2. **Identificación de patrones y tendencias**: Los gráficos ayudan a identificar patrones y tendencias en los datos. Por ejemplo, un gráfico de líneas puede mostrar cambios a lo largo del tiempo, un gráfico de dispersión puede revelar relaciones entre variables y un histograma puede mostrar la forma de la distribución de una variable.

3. **Resumen y comparación de datos**: Los gráficos resumen los datos de manera visual y concisa. Por ejemplo, un gráfico de barras puede comparar la frecuencia o proporción de diferentes categorías, y un gráfico de caja y bigotes puede mostrar la distribución y resaltar posibles valores atípicos.

4. **Comunicación efectiva**: La visualización de datos es una forma poderosa de comunicar resultados y hallazgos estadísticos de manera clara y efectiva. Los gráficos permiten transmitir información de manera más impactante y comprensible que solo mediante texto o números.

5. **Selección adecuada de gráficos**: Es importante elegir el tipo de gráfico adecuado para los datos y el objetivo del análisis. Existen diversos tipos de gráficos, como histogramas, gráficos de barras, gráficos circulares, gráficos de dispersión, gráficos de líneas, gráficos de caja y bigotes, entre otros. Cada tipo de gráfico tiene sus propias fortalezas y limitaciones, y es esencial seleccionar el que mejor se ajuste a los datos y a la historia que se quiere contar.

6. **Herramientas de visualización**: Existen varias herramientas y bibliotecas de visualización de datos disponibles en lenguajes de programación como Python (Matplotlib, Seaborn) y R (ggplot2). Estas herramientas facilitan la creación de gráficos personalizados y permiten el ajuste de aspectos como el color, el estilo y la etiquetación de los gráficos.

7. **Visualización interactiva**: Las visualizaciones interactivas, como gráficos interactivos en línea o dashboards interactivos, permiten explorar los datos de manera dinámica, cambiar parámetros y obtener información detallada al interactuar con los gráficos.

8. **Visualización multidimensional**: Para datos multidimensionales, técnicas como los gráficos de dispersión en 3D, los mapas de calor y los gráficos de burbujas pueden ayudar a visualizar relaciones complejas entre múltiples variables.

En resumen, la visualización de datos desempeña un papel crucial en el análisis estadístico, ya que permite explorar, resumir y comunicar los patrones y relaciones presentes en los datos. Utilizar gráficos adecuados y herramientas de visualización eficientes ayuda a mejorar la comprens

---------------

## Inferencia estadística 

La inferencia estadística es una rama de la estadística que se ocupa de hacer inferencias o generalizaciones sobre una población a partir de una muestra de datos. Ayuda a tomar decisiones basadas en la evidencia proporcionada por los datos recopilados. A continuación, se presentan detalles sobre la inferencia estadística, ejemplos de la vida real y cómo se puede aplicar con ejemplos en Python:

Población y muestra: En inferencia estadística, una población se refiere al conjunto completo de elementos o individuos que se desea estudiar, mientras que una muestra es un subconjunto seleccionado de la población. La inferencia estadística se basa en la idea de que una muestra representativa puede proporcionar información sobre la población en su conjunto.

Estimación puntual: La estimación puntual es una técnica utilizada en inferencia estadística para estimar un parámetro desconocido de la población basándose en los datos de la muestra. Por ejemplo, si se desea estimar la media de edad de los estudiantes universitarios, se puede calcular la media de edad en una muestra de estudiantes y utilizarla como una estimación puntual de la media de la población.

Intervalos de confianza: Los intervalos de confianza son utilizados para estimar un rango plausible de valores para un parámetro desconocido de la población. Proporcionan información sobre la precisión de la estimación y su nivel de confianza. Por ejemplo, se puede calcular un intervalo de confianza del 95% para la media de edad de los estudiantes universitarios, lo que indica que existe un 95% de confianza de que la verdadera media de edad de la población caiga dentro de ese intervalo.

Pruebas de hipótesis: Las pruebas de hipótesis son utilizadas para tomar decisiones sobre afirmaciones o hipótesis basadas en los datos de la muestra. Se plantea una hipótesis nula (H0) y una hipótesis alternativa (H1) y se evalúa la evidencia en contra de la hipótesis nula. Por ejemplo, se puede realizar una prueba de hipótesis para determinar si el nuevo tratamiento médico es efectivo comparado con el tratamiento existente.

Ejemplo de la vida real: Supongamos que una empresa desea determinar si un nuevo diseño de empaque tiene un impacto significativo en las ventas de un producto en comparación con el diseño anterior. Para realizar inferencia estadística, se puede seleccionar una muestra de tiendas y registrar las ventas del producto durante un período de tiempo utilizando ambos diseños de empaque. Luego, se pueden aplicar técnicas de inferencia estadística para determinar si hay una diferencia significativa en las ventas entre los dos diseños.

Ejemplo en Python:

Supongamos que tenemos una muestra de alturas de estudiantes universitarios y queremos estimar la media de altura de la población y construir un intervalo de confianza del 95% utilizando Python:

```PYTHON
import numpy as np
import scipy.stats as stats

# Datos de muestra (altura en centímetros)
altura = [165, 170, 175, 168, 172, 180, 185, 178, 169, 172]

# Estimación puntual de la media
media_estimada = np.mean(altura)
print("Media estimada:", media_estimada)
```

-------

## Estadística bayesiana

La estadística bayesiana es una rama de la estadística que se basa en el teorema de Bayes para hacer inferencias y actualizar la creencia sobre los parámetros desconocidos de un modelo estadístico. A diferencia de la estadística clásica, que utiliza estimaciones puntuales y pruebas de hipótesis, la estadística bayesiana utiliza distribuciones de probabilidad para representar la incertidumbre y actualizar las creencias a medida que se obtienen nuevos datos. A continuación, se presentan detalles sobre la estadística bayesiana, ejemplos de la vida real y cómo se puede aplicar con ejemplos en Python:

1. Teorema de Bayes: El teorema de Bayes establece que la probabilidad de una hipótesis o evento condicionado a un conjunto de datos puede ser calculada mediante la combinación de información previa y nueva evidencia. Matemáticamente, el teorema de Bayes se expresa de la siguiente manera:

P(H|D) = (P(D|H) * P(H)) / P(D)

donde P(H|D) es la probabilidad posterior de la hipótesis H dado el conjunto de datos D, P(D|H) es la probabilidad de los datos D condicionados a la hipótesis H, P(H) es la probabilidad previa de la hipótesis y P(D) es la probabilidad marginal de los datos.

2. Distribución posterior: En la estadística bayesiana, se utiliza una distribución posterior para representar la probabilidad de los parámetros del modelo dados los datos observados. La distribución posterior se calcula mediante la combinación de la distribución previa y la verosimilitud de los datos.

3. Distribución previa: La distribución previa representa la creencia o conocimiento previo sobre los parámetros antes de observar los datos. Puede ser una distribución subjetiva o basada en información previa.

4. Verosimilitud: La verosimilitud es la probabilidad de los datos condicionados a los parámetros del modelo. Proporciona información sobre cómo los datos respaldan diferentes valores de los parámetros.

5. Actualización de creencias: A medida que se obtienen nuevos datos, la distribución posterior se actualiza utilizando el teorema de Bayes. Esto permite incorporar la nueva información y actualizar las creencias sobre los parámetros del modelo.

- Ejemplo de la vida real: 

Supongamos que queremos determinar la efectividad de un nuevo medicamento para reducir la presión arterial. Utilizando la estadística bayesiana, podemos utilizar información previa, como estudios previos sobre medicamentos similares, para construir una distribución previa sobre la efectividad del medicamento. Luego, a medida que se realizan ensayos clínicos y se obtienen nuevos datos, podemos actualizar nuestra distribución posterior y obtener estimaciones más precisas de la efectividad del medicamento.

- Un ejemplo de la vida real:

La detección de enfermedades en pruebas médicas. Supongamos que queremos determinar si una persona tiene una enfermedad rara. Tenemos una prueba que es 95% precisa, lo que significa que si una persona tiene la enfermedad, la prueba dará positivo el 95% de las veces, y si una persona no tiene la enfermedad, la prueba dará negativo el 95% de las veces. Sin embargo, solo el 0,1% de la población tiene la enfermedad. Entonces, si una persona da positivo en la prueba, ¿cuál es la probabilidad de que realmente tenga la enfermedad?

Utilizando la estadística bayesiana, podemos actualizar nuestra creencia sobre la probabilidad de que una persona tenga la enfermedad después de conocer el resultado de la prueba. En este ejemplo, podemos utilizar el teorema de Bayes para calcular la probabilidad posterior:

P(enfermedad | prueba positiva) = P(prueba positiva | enfermedad) * P(enfermedad) / P(prueba positiva)

donde P(enfermedad | prueba positiva) es la probabilidad posterior de que una persona tenga la enfermedad dada una prueba positiva, P(prueba positiva | enfermedad) es la probabilidad de una prueba positiva dada la enfermedad, P(enfermedad) es la probabilidad previa de que una persona tenga la enfermedad, y P(prueba positiva) es la probabilidad de una prueba positiva en general.

En Python, podemos utilizar la librería PyMC3 para implementar modelos bayesianos. A continuación, se presenta un ejemplo de código que utiliza PyMC3 para estimar la probabilidad posterior de una moneda justa:

```PYTHON
import pymc3 as pm
import numpy as np

# Generamos datos de una moneda justa
data = np.random.binomial(n=1, p=0.5, size=100)

# Definimos el modelo bayesiano
with pm.Model() as model:
    # Definimos la distribución a priori
    theta = pm.Beta('theta', alpha=1, beta=1)
    
    # Definimos la verosimilitud
    y = pm.Bernoulli('y', p=theta, observed=data)
    
    # Estimamos la probabilidad posterior
    trace = pm.sample(1000)

# Imprimimos las estadísticas resumen de la probabilidad posterior
pm.summary(trace)
```

En este ejemplo, generamos datos de una moneda justa utilizando la función np.random.binomial. Luego, definimos un modelo bayesiano en el que la distribución a priori es una distribución Beta y la verosimilitud es una distribución Bernoulli. Finalmente, utilizamos la función pm.sample para estimar la probabilidad posterior del parámetro theta. La función pm.summary nos proporciona estadísticas resumen de la probabilidad posterior, como la media, la mediana, el intervalo de credibilidad y otros.

----------------

## Análisis de supervivencia 

El análisis de supervivencia es una técnica estadística utilizada para analizar el tiempo hasta que ocurre un evento, como la muerte, el fracaso de un componente o la aparición de una enfermedad. El objetivo es modelar y comprender las tasas de supervivencia a lo largo del tiempo y examinar cómo diferentes variables influyen en la probabilidad de supervivencia.

Un ejemplo de la vida real del análisis de supervivencia podría ser el estudio de supervivencia de pacientes con cáncer de pulmón después de recibir un determinado tratamiento. En este estudio, se recopilarían datos sobre el tiempo de supervivencia de los pacientes (desde el diagnóstico hasta la muerte o final del estudio) y se analizarían para identificar los factores que pueden influir en la supervivencia, como la edad, el sexo, el estadio del cáncer, el tipo de tratamiento, entre otros.

En Python, se puede utilizar la biblioteca lifelines para realizar análisis de supervivencia. A continuación se muestra un ejemplo de código que utiliza lifelines para ajustar un modelo de riesgos proporcionales de Cox a un conjunto de datos de supervivencia:

```PYTHON
import pandas as pd
from lifelines import CoxPHFitter

# Cargar los datos de supervivencia
data = pd.read_csv('datos_supervivencia.csv')

# Crear el objeto de ajuste del modelo de Cox
cph = CoxPHFitter()

# Ajustar el modelo a los datos de supervivencia
cph.fit(data, duration_col='tiempo', event_col='evento', formula='variables')

# Imprimir el resumen del modelo
print(cph.summary)
```
En este ejemplo, se asume que los datos de supervivencia están en un archivo CSV llamado 'datos_supervivencia.csv' y que contiene columnas para el tiempo de supervivencia (tiempo), el indicador de evento (1 si ocurre el evento, 0 si no ocurre) (evento), y otras variables relevantes (variables) que pueden influir en la supervivencia. El modelo de riesgos proporcionales de Cox se ajusta a los datos utilizando la función fit de lifelines, y luego se puede imprimir un resumen del modelo utilizando la propiedad summary.

El análisis de supervivencia proporciona información valiosa sobre las tasas de supervivencia y los factores que pueden influir en la supervivencia en diferentes contextos, como estudios médicos, estudios de fiabilidad de equipos, estudios de tiempo hasta el fracaso de componentes, entre otros.
