# Análisis de la pobreza en el Perú en 2022: ingresos e informalidad

## Descripción del proyecto

Este proyecto evalúa la pobreza en los hogares peruanos durante 2022 utilizando datos de la Encuesta Nacional de Hogares (ENAHO) del Instituto Nacional de Estadística e Informática (INEI). Se analiza cómo los ingresos y la informalidad laboral influyen en la probabilidad de pobreza en diferentes regiones del país, con un enfoque en las diferencias entre áreas rurales y urbanas.

Se procesaron más de 87,000 registros utilizando Python para limpiar, analizar y visualizar los datos, generando insights clave para orientar políticas públicas.

## Objetivo

Evaluar la relación entre los ingresos, la informalidad laboral y la probabilidad de pobreza en los hogares peruanos, identificando disparidades económicas regionales y proponiendo estrategias para su mitigación.

## Hipótesis

Un aumento en los ingresos y la formalidad laboral disminuye significativamente la probabilidad de pobreza.

## Datos utilizados

### Origen:

* Encuesta Nacional de Hogares (ENAHO) del Instituto Nacional de Estadística e Informática (INEI) de Perú.

* Descargar datos oficiales: https://www.datosabiertos.gob.pe/dataset/encuesta-nacional-de-hogares-enaho-2022-instituto-nacional-de-estad%C3%ADstica-e-inform%C3%A1tica-%E2%80%93

## Módulos empleados:

* Módulo de ingresos y empleo (Enaho01a-2022-500)

El archivo principal analizado está disponible en este repositorio: 'dataPobrezaPeru2022.csv'.

## Metodología

### Limpieza de datos

1. Estandarización:

* Renombrado de columnas para facilitar su interpretación.

* Creación de diccionarios para mapear variables categóricas (dominio, estrato, tipo de contrato, etc.).

2. Manejo de valores nulos:

* Imputación de variables numéricas usando la mediana por conglomerado (nconglome).

* Imputación de variables categóricas usando la moda.

3. Tratamiento de valores atípicos:

* Eliminación de outliers utilizando el rango intercuartil (IQR).

4. Eliminación de duplicados:

* Remoción de registros duplicados.

## Exploración de datos (EDA)

1. Distribución de ingresos:

* Asimetría positiva con concentración de ingresos bajos.

* Densidad de ingresos significativamente más alta en áreas rurales.

2. Relación entre variables:

* Correlación negativa fuerte entre ingresos y pobreza (-0.56).

* La formalidad laboral presenta una correlación moderada con menores probabilidades de pobreza (-0.39).

3. Visualizaciones:

* Histogramas y boxplots para analizar la distribución de ingresos por dominio geográfico.

* Gráficos de barras para examinar las tasas de pobreza en zonas urbanas y rurales.

## Métodos estadísticos avanzados

1. Regresión Logística:

*  Relación entre ingreso_total, es_formal y es_pobre.

#### Resultados:

  * Aumentar ingresos reduce la probabilidad de pobreza (-0.027).

  * La formalidad laboral tiene un efecto protector significativo (-1.083).

2. Índice de Gini:

* Valor: 0.45 (desigualdad moderada-alta).

3. Análisis de varianza (ANOVA):

Diferencias significativas entre ingresos en zonas urbanas y rurales (p-value = 0.0).

## Resultados clave

1. Impacto de los ingresos:

* Los ingresos tienen un efecto directo en la reducción de la pobreza.

* 38% de los hogares rurales y 17% de los urbanos son pobres.

2. Formalidad laboral:

* Trabajos formales están asociados con menores probabilidades de pobreza.

3. Desigualdad económica:

* El índice de Gini (0.45) refleja una concentración alta de ingresos.

4. Diferencias regionales:

* Las zonas rurales muestran ingresos significativamente más bajos que las urbanas.

## Recomendaciones

1. Promover la formalización laboral:

* Simplificar el registro en la seguridad social.

* Incentivar la formalización en sectores rurales clave.

2. Reducir la desigualdad:

* Diseñar programas redistributivos como transferencias condicionadas.

* Incrementar la inversión en educación y capacitación laboral.

3. Fomentar el desarrollo rural:

* Invertir en infraestructura y conectividad para mejorar el acceso al mercado.

* Estimular la inversión privada en zonas rurales.

4. Ampliar el acceso a créditos:

* Fomentar programas de microcréditos para pequeños emprendedores.

5. Mejorar la educación:

* Implementar capacitaciones laborales enfocadas en habilidades técnicas.

## Tecnologías utilizadas

* Python: Limpieza, análisis y visualización de datos (Pandas, NumPy, Matplotlib, Seaborn).

* GitHub: Documentación y publicación del proyecto.

### Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar este proyecto, abre un pull request o contacta al autor.

### Autor

Wilmer Gastón Lozano Huamán

Correo: wglozanoh@gmail.com
