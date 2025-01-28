Análisis de la pobreza en el Perú en 2022: ingresos e informalidad

Descripción del proyecto

Este proyecto evalúa la pobreza en los hogares peruanos durante 2022 utilizando datos de la Encuesta Nacional de Hogares (ENAHO) del Instituto Nacional de Estadística e Informática (INEI). Se analiza cómo los ingresos y la informalidad laboral influyen en la probabilidad de pobreza en diferentes regiones del país, con un enfoque en las diferencias entre áreas rurales y urbanas.

Se procesaron más de 87,000 registros utilizando Python para limpiar, analizar y visualizar los datos, generando insights clave para orientar políticas públicas.

Objetivo

Evaluar la relación entre los ingresos, la informalidad laboral y la probabilidad de pobreza en los hogares peruanos, identificando disparidades económicas regionales y proponiendo estrategias para su mitigación.

Hipótesis

Un aumento en los ingresos y la formalidad laboral disminuye significativamente la probabilidad de pobreza.

Datos utilizados

Origen:

Encuesta Nacional de Hogares (ENAHO) del Instituto Nacional de Estadística e Informática (INEI) de Perú.

Descargar datos oficiales

Módulos empleados:

Módulo de ingresos y empleo (Enaho01a-2022-500)

Módulo de educación

Módulo de salud

El archivo principal analizado está disponible en este repositorio: dataPobrezaPeru2022.csv.

Metodología

Limpieza de datos

Estandarización:

Renombrado de columnas para facilitar su interpretación.

Creación de diccionarios para mapear variables categóricas (dominio, estrato, tipo de contrato, etc.).

Manejo de valores nulos:

Imputación de variables numéricas usando la mediana por conglomerado (nconglome).

Imputación de variables categóricas usando la moda.

Tratamiento de valores atípicos:

Eliminación de outliers utilizando el rango intercuartil (IQR).

Eliminación de duplicados:

Remoción de registros duplicados.

Exploración de datos (EDA)

Distribución de ingresos:

Asimetría positiva con concentración de ingresos bajos.

Densidad de ingresos significativamente más alta en áreas rurales.

Relación entre variables:

Correlación negativa fuerte entre ingresos y pobreza (-0.56).

La formalidad laboral presenta una correlación moderada con menores probabilidades de pobreza (-0.39).

Visualizaciones:

Histogramas y boxplots para analizar la distribución de ingresos por dominio geográfico.

Gráficos de barras para examinar las tasas de pobreza en zonas urbanas y rurales.

Métodos estadísticos avanzados

Regresión Logística:

Relación entre ingreso_total, es_formal y es_pobre.

Resultados:

Aumentar ingresos reduce la probabilidad de pobreza (-0.027).

La formalidad laboral tiene un efecto protector significativo (-1.083).

Índice de Gini:

Valor: 0.45 (desigualdad moderada-alta).

Análisis de varianza (ANOVA):

Diferencias significativas entre ingresos en zonas urbanas y rurales (p-value = 0.0).

Resultados clave

Impacto de los ingresos:

Los ingresos tienen un efecto directo en la reducción de la pobreza.

38% de los hogares rurales y 17% de los urbanos son pobres.

Formalidad laboral:

Trabajos formales están asociados con menores probabilidades de pobreza.

Desigualdad económica:

El índice de Gini (0.45) refleja una concentración alta de ingresos.

Diferencias regionales:

Las zonas rurales muestran ingresos significativamente más bajos que las urbanas.

Recomendaciones

Promover la formalización laboral:

Simplificar el registro en la seguridad social.

Incentivar la formalización en sectores rurales clave.

Reducir la desigualdad:

Diseñar programas redistributivos como transferencias condicionadas.

Incrementar la inversión en educación y capacitación laboral.

Fomentar el desarrollo rural:

Invertir en infraestructura y conectividad para mejorar el acceso al mercado.

Estimular la inversión privada en zonas rurales.

Ampliar el acceso a créditos:

Fomentar programas de microcréditos para pequeños emprendedores.

Mejorar la educación:

Implementar capacitaciones laborales enfocadas en habilidades técnicas.

Tecnologías utilizadas

Python: Limpieza, análisis y visualización de datos (Pandas, NumPy, Matplotlib, Seaborn).

GitHub: Documentación y publicación del proyecto.

Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar este proyecto, abre un pull request o contacta al autor.

Autor

Wilmer Gastón Lozano Huamán

Correo: wglozanoh@gmail.com
