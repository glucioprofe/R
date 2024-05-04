# Curso de Estadísticas 
**Especialización en Analítica de Datos**  
**CUN: Corporación Unificada Nacional de Educación Superior**

**Estudiantes:**
- Claudia Ximena Perez.  
  Email: claus_ximena@hotmail.com
  
- Gonzalo Andrés Lucio.  
  Email: gonzaloandreslucio@gmail.com


En GitHub, puedes usar el Markdown estándar para crear títulos y subtitulares en tu archivo README. Si deseas crear un título que pueda ser contraído y expandido en GitHub, puedes usar Markdown extendido con la sintaxis de encabezado y detalles. Por ejemplo:


<details>
    <summary>
        ## Variables
    </summary>
    <details>
        <summary>
        ### Cualitativas 
        </summary>
        Son variables que describen características o cualidades de un individuo u objeto, sin asignarles un valor numérico específico.
    </details>
</details>

#### Nominal
Las variables nominales son aquellas que representan categorías que no tienen un orden inherente. Los datos son simplemente etiquetas sin ningún tipo de jerarquía.

**Ejemplo:** Género (masculino, femenino), Estado Civil (soltero, casado, divorciado).

#### Ordinal
Las variables ordinales representan categorías que tienen un orden inherente. Los datos pueden ser ordenados o clasificados.

**Ejemplo:** Nivel de educación (primaria, secundaria, universitaria), Clasificación socioeconómica (bajo, medio, alto).

### Cuantitativas 
Son variables que representan cantidades numéricas medibles.

#### Discreto
Las variables discretas toman valores numéricos finitos o contables. Estos valores son distintos y separados, no pueden tomar valores intermedios.

**Ejemplo:** Número de hijos (1, 2, 3, ...), Cantidad de estudiantes en una clase (20, 30, 40).

#### Continuo
Las variables continuas pueden tomar un número infinito de valores dentro de un rango específico. Pueden ser medidas con cualquier grado de precisión.

**Ejemplo:** Altura (1.65 m, 1.70 m, 1.75 m, ...), Peso (65 kg, 66 kg, 67 kg, ...).


## Medidas de la Estadística Exploratoria

Dentro de este apartado se presentan diversas medidas estadísticas que son útiles para explorar y comprender conjuntos de datos.

### Medida de Ocurrencia

La medida de ocurrencia indica la frecuencia con la que aparece un determinado valor en un conjunto de datos. Es útil para identificar la prevalencia o frecuencia de eventos específicos.

**Ejemplo:** En una encuesta sobre preferencias de color, se registraron las siguientes ocurrencias: rojo: 15 veces, azul: 20 veces, verde: 10 veces.

#### Frecuencia Absoluta

La frecuencia absoluta es el número de veces que aparece un valor específico en un conjunto de datos.

**Ejemplo:** En un conjunto de datos de edades de estudiantes, la frecuencia absoluta de la edad 20 años es 5, lo que significa que hay 5 estudiantes de 20 años en el conjunto de datos.

#### Frecuencia Relativa

La frecuencia relativa es el cociente entre la frecuencia absoluta de un valor y el tamaño total del conjunto de datos. Se expresa como un porcentaje y representa la proporción que representa un valor específico en el conjunto de datos.

**Ejemplo:** Siguiendo el ejemplo anterior, si el tamaño total del conjunto de datos es 100, la frecuencia relativa de la edad 20 años sería del 5%, lo que significa que el 5% de los estudiantes tienen 20 años.

#### Frecuencia Acumulada

La frecuencia acumulada es la suma acumulativa de las frecuencias absolutas de todos los valores anteriores en un conjunto de datos ordenados. Es útil para determinar el número total de observaciones hasta cierto punto en la distribución de los datos.

**Ejemplo:** En un conjunto de datos de edades de estudiantes ordenado de menor a mayor, si las frecuencias absolutas de las edades son 5, 8, 12, 6, respectivamente, entonces la frecuencia acumulada sería 5 para la primera edad, 5 + 8 = 13 para la segunda edad, 5 + 8 + 12 = 25 para la tercera edad, y así sucesivamente.


#### Frecuencia Acumulada Relativa

La frecuencia acumulada relativa es la suma acumulativa de las frecuencias relativas de todos los valores anteriores en un conjunto de datos ordenados. Es útil para determinar la proporción acumulativa de observaciones hasta cierto punto en la distribución de los datos.

**Ejemplo:** En un conjunto de datos de edades de estudiantes ordenado de menor a mayor, si las frecuencias relativas de las edades son 0.1, 0.2, 0.3, 0.4, respectivamente, entonces la frecuencia acumulada relativa sería 0.1 para la primera edad, 0.1 + 0.2 = 0.3 para la segunda edad, 0.1 + 0.2 + 0.3 = 0.6 para la tercera edad, y así sucesivamente.


### Medida de Tendencia Central

Las medidas de tendencia central, como la media, la mediana y la moda, proporcionan información sobre el valor típico o central de un conjunto de datos. Ayudan a entender dónde se concentran la mayoría de los datos.

**Ejemplo:** En un conjunto de datos de edades de estudiantes, la media es 25 años, la mediana es 24 años y la moda es 22 años.

### Medida de Variabilidad

La medida de variabilidad, como la desviación estándar o el rango intercuartílico, indica cuánto se dispersan los datos alrededor de la medida de tendencia central. Es útil para comprender la heterogeneidad o dispersión de los datos.

**Ejemplo:** En un conjunto de datos de alturas de árboles, la desviación estándar es 10 cm, lo que indica que las alturas varían en promedio alrededor de 10 cm de la media.

### Medida de Localización

Las medidas de localización, como los percentiles, proporcionan información sobre la posición relativa de un valor dentro de un conjunto de datos ordenados. Son útiles para entender la distribución de los datos y para realizar comparaciones entre diferentes conjuntos de datos.

**Ejemplo:** En un conjunto de datos de puntuaciones en un examen, el percentil 75 indica que el 75% de los estudiantes obtuvieron una puntuación igual o menor que este valor.

### Medida de Simetría y Forma

La medida de simetría y forma describe la forma de la distribución de los datos y si hay algún sesgo o asimetría en ella. Algunas medidas comunes incluyen el coeficiente de simetría y la curtosis.

**Ejemplo:** En un conjunto de datos de ingresos familiares, una distribución sesgada positivamente podría indicar que hay más familias con ingresos bajos y pocos con ingresos muy altos.

### Medida de Atipicidad

La medida de atipicidad identifica valores atípicos o extremos en un conjunto de datos. Estos valores pueden afectar significativamente los resultados del análisis estadístico y deben ser examinados cuidadosamente.

**Ejemplo:** En un conjunto de datos de temperaturas diarias, una temperatura extremadamente alta en invierno podría considerarse un valor atípico.
