PA02 · Geomorfometría, reproducibilidad, redacción, estilos de formato,
figuras, tablas, citas y referencias<small><br>Geomorfología
(GEO-114)<br>Universidad Autónoma de Santo Domingo (UASD)
================
El Tali
2026-03-09

<!-- README.md se genera a partir de README.Rmd. Por favor, edita ese archivo. -->

# Fecha/hora de entrega

[**VER PORTAL DE LA
ASIGNATURA**](https://github.com/geomorfologia-202601)

## Objetivos

El objetivo de esta práctica es que demuestres o mejores:

- tus capacidades de **realizar análisis geomorfométricos**;
- tus capacidades de **usar RMarkdown para producir documentos
  científicos reproducibles**;
- tus capacidades de **redacción científica**;
- tus capacidades de **comunicar resultados de investigación mediante
  una presentación oral breve**.

Esta práctica tratará sobre **geomorfometría aplicada a un área de la
República Dominicana**, intentando que el resultado final sea una
**investigación reproducible y bien redactada**.

El resultado esperado es un trabajo que cumpla con estándares básicos de
comunicación científica: uso apropiado de **figuras, tablas, citas,
referencias y estructura de manuscrito**, acompañado de una
**presentación oral clara y sintética**.

------------------------------------------------------------------------

# Entregables

Debes producir **tres productos obligatorios**:

## 1. Manuscrito reproducible (PDF)

### Requisitos de formato

Un manuscrito breve en formato académico generado a partir de
**RMarkdown**.

La entrega se realiza mediante **commit + push al repositorio personal**
asignado.

Puedes utilizar …

- la plantilla `plantilla.Rmd` del repositorio, o
- otra plantilla RMarkdown (por ejemplo de `rticles`),

… siempre que el resultado sea un **PDF generado desde RMarkdown** y que
mantenga la estructura típica de un manuscrito científico.

### Estructura mínima

El manuscrito debe incluir:

- Título
- Autor/a
- Resumen y palabras clave
- Introducción (contexto conceptual, problemas, justificación,
  preguntas, hipótesis, objetivos)
- Materiales y métodos (procedimientos, técnicas, herramientas, datos
  utilizados)
- Resultados (tablas, figuras)
- Discusión (cumplimiento de objetivos rechazo o no de hipótesis,
  interpretación, limitaciones, perspectivas de futuro)
- Conclusiones
- Referencias
- Opcional: información suplementaria.

Las **figuras y tablas deben tener título y referencia cruzada dentro
del texto**.

**Extensión sugerida:** 4–8 páginas (sin contar referencias).

------------------------------------------------------------------------

## 2. Diapositivas

Debes preparar una presentación breve para explicar tu trabajo.

Formato recomendado:

- 8–10 diapositivas
- claridad visual
- poco texto

Las diapositivas pueden seguir la estructura IMRaD, pero no es
obligatorio. Este es un esquema tradicional:

- Título y autor/a
- Introducción
- Materiales y métodos
- Resultados
- Discusión
- Conclusiones

------------------------------------------------------------------------

## 3. Defensa oral

Cada estudiante realizará una **exposición oral de 17 minutos**.

La defensa debe explicar al menos lo siguiente:

- problema de investigación
- metodología
- evidencia principal
- interpretación de resultados
- limitaciones
- conclusiones

El objetivo no es repetir el manuscrito completo, sino **explicar el
argumento central del trabajo**. Reitero: no es obligatorio seguir la
estructrua IMRaD, pero si te da confianza, puedes usarla.

------------------------------------------------------------------------

# Mandato de la práctica

## Selección del área de estudio

Usando el **DEM del Shuttle Radar Topography Mission (SRTM)** recortado
para un municipio, aplica una técnica geomorfométrica.

Los archivos se encuentran en la carpeta `data/`.

Debes elegir **un municipio por su número** y anunciarlo en el foro.

| estudiante | nombre_archivo              |
|-----------:|:----------------------------|
|          1 | sabana_yegua.tif            |
|          2 | arenoso.tif                 |
|          3 | neyba.tif                   |
|          4 | castanuela.tif              |
|          5 | luperon.tif                 |
|          6 | ramon_santana.tif           |
|          7 | bayaguana.tif               |
|          8 | imbert.tif                  |
|          9 | constanza.tif               |
|         10 | santa_barbara_de_samana.tif |
|         11 | monte_plata.tif             |
|         12 | las_salinas.tif             |
|         13 | sabana_grande_de_boya.tif   |
|         14 | peralta.tif                 |
|         15 | jamao_al_norte.tif          |
|         16 | yamasa.tif                  |
|         17 | tenares.tif                 |
|         18 | jaquimeyes.tif              |
|         19 | san_jose_de_ocoa.tif        |
|         20 | fantino.tif                 |

------------------------------------------------------------------------

## Selección de técnica geomorfométrica

Debes elegir **una técnica geomorfométrica** basada en Hengl et al.
(2009).

Ejemplos de grupos de técnicas:

### Parámetros básicos del terreno

Capítulo 6.

Ejemplos:

- pendiente
- curvatura
- índice de rugosidad topográfica

### Parámetros hidrológicos

Capítulo 7.

Ejemplos:

- acumulación de flujo
- dirección de drenaje

### Parámetros topoclimáticos

Capítulo 8.

Ejemplos:

- orientación de vertiente
- distancia a la costa

### Formas del relieve

Capítulo 9.

Ejemplos:

- geomórfonos
- detección de depresiones
- extracción de piedemontes

Puedes usar:

- software SIG (QGIS, GRASS GIS),
- R,
- Python,
- o cualquier herramienta que domines.

Puedes usar **inteligencia artificial como apoyo**, pero no como
sustituto del análisis.

------------------------------------------------------------------------

# Estructura del manuscrito

## Introducción

Extensión sugerida: **3 párrafos**.

Debes:

- explicar qué es la geomorfometría;
- explicar el parámetro o técnica seleccionada;
- justificar su importancia;
- plantear los objetivos del trabajo.

La introducción debe incluir **al menos tres citas bibliográficas**.

------------------------------------------------------------------------

## Materiales y métodos

Extensión sugerida: **2 párrafos**.

Debes describir:

- el DEM SRTM utilizado;
- las herramientas empleadas (software y hardware);
- el algoritmo o técnica geomorfométrica aplicada.

No adelantes resultados en esta sección.

Si incluyes:

- diagramas metodológicos,
- esquemas,
- tablas,

deben referirse mediante **referencias cruzadas**.

------------------------------------------------------------------------

## Resultados

Extensión sugerida: **1 párrafo**.

Debes presentar el **resultado geomorfométrico obtenido**.

No incluyas interpretaciones extensas; eso corresponde a la discusión.

------------------------------------------------------------------------

## Discusión

Extensión sugerida: **2 párrafos**.

Debes:

- indicar si alcanzaste los objetivos;
- interpretar el resultado;
- discutir limitaciones;
- plantear posibles extensiones futuras.

------------------------------------------------------------------------

## Referencias

Todas las referencias citadas deben aparecer en la sección final.

Debes utilizar **formato APA 7** mediante **BibTeX**.

------------------------------------------------------------------------

# Recomendaciones de redacción

Usa una voz (activa o pasiva) de forma consistente.

Ejemplos:

**Voz activa**

- Analicé los datos utilizando R.
- Los resultados muestran una relación clara.

**Voz pasiva**

- Los datos fueron analizados utilizando R.
- Se observó una relación significativa.

Ambas formas son aceptables en redacción científica.

------------------------------------------------------------------------

## Uso de inteligencia artificial

Está permitido utilizar herramientas de IA.

Sin embargo:

- úsala como **tutor**, no como redactor;
- verifica todos los conceptos;
- no copies texto sin revisarlo;
- nunca confíes ciegamente en referencias generadas por IA.

------------------------------------------------------------------------

# Organización del trabajo (3 días)

## Día 1 — Selección y análisis

- elegir el municipio
- elegir la técnica geomorfométrica
- generar el producto principal (mapa o variable)

Avanzar:

- figuras
- tablas
- materiales y métodos

------------------------------------------------------------------------

## Día 2 — Redacción del manuscrito

Redactar:

- introducción
- materiales y métodos
- resultados
- discusión
- conclusiones

Preparar:

- figuras finales
- tablas finales

------------------------------------------------------------------------

## Día 3 — Presentación

Completar:

- manuscrito final
- diapositivas

Realizar:

- defensa oral en clase.

------------------------------------------------------------------------

# Criterios de evaluación del manuscrito

| Criterio                  | Nivel 1                | Nivel 2                   | Nivel 3              | Nivel 4                 |
|---------------------------|------------------------|---------------------------|----------------------|-------------------------|
| Análisis geomorfométrico  | Análisis incorrecto    | Análisis básico           | Análisis correcto    | Análisis exhaustivo     |
| Uso de software           | Uso limitado           | Uso adecuado              | Buen manejo          | Manejo avanzado         |
| Redacción científica      | Redacción deficiente   | Redacción clara           | Redacción fluida     | Redacción excelente     |
| Estructura del manuscrito | Estructura incorrecta  | Estructura básica         | Buena organización   | Organización impecable  |
| Figuras y tablas          | Ausentes o incorrectas | Uso básico                | Buena integración    | Integración excelente   |
| Citas y referencias       | Incorrectas            | Algunas correctas         | Mayormente correctas | Uso perfecto de APA     |
| Reproducibilidad          | No reproducible        | Parcialmente reproducible | Bien documentado     | Totalmente reproducible |

------------------------------------------------------------------------

# Criterios de evaluación de la presentación oral

| Criterio                     | Nivel 1               | Nivel 2              | Nivel 3                | Nivel 4                       |
|------------------------------|-----------------------|----------------------|------------------------|-------------------------------|
| Claridad de la exposición    | Difícil de seguir     | Comprensible         | Clara                  | Muy clara y bien estructurada |
| Uso de diapositivas          | Diapositivas confusas | Uso básico           | Buen apoyo visual      | Excelente diseño visual       |
| Explicación del método       | Poco clara            | Parcial              | Correcta               | Muy bien explicada            |
| Interpretación de resultados | Ausente               | Básica               | Adecuada               | Profunda                      |
| Manejo del tiempo            | Fuera del tiempo      | Ligeramente fuera    | Ajustado               | Perfectamente ajustado        |
| Capacidad de defensa         | No responde           | Respuestas limitadas | Responde correctamente | Argumenta con claridad        |

<!-- # Objetivos -->
<!-- El objetivo de esta práctica de desarrollo es que demuestres o mejores ... a) tus capacidades de realizar análisis geomorfométricos; b) tus capacidades de usar software de procesamiento de texto en RStudio; c) tus capacidades de redacción. Esto te preparará, a futuro, para el manuscrito.  -->
<!-- Esta práctica tratará **sobre geomorfometría de un área de República Dominicana**, intentando que sea una investigación reproducible y bien redactada. Lo ideal es que presentes un un documento que cumpla con estilos de formato, uso apropiado de figuras, tablas, citas y referencias. -->
<!-- # Mandato -->
<!-- 1. Usando el DEM del Shuttle Radar Topography Mission (SRTM) recortado para un municipio, aplica una técnica geomorfométrica que elegirás (en el siguiente punto te explico más). Los archivos se encuentran en la carpeta [data/](data/). Debes elegir un municipio por su número y anunciarlo en el foro. -->
<!-- ```{r, eval=T, echo=F, warning=F, message=F} -->
<!-- library(tidyverse) -->
<!-- library(kableExtra) -->
<!-- archivos <- list.files(path = 'data', pattern = '*.tif') -->
<!-- set.seed(99); m <- archivos[sample(1:length(archivos), 20)] -->
<!-- estudiante <- 1:20 -->
<!-- df <- data.frame(estudiante, nombre_archivo = m, check.names = F) -->
<!-- df %>% kableExtra::kable() -->
<!-- ``` -->
<!-- 2. Elige una técnica geomorfométrica de @hengl2009geomorphometry y aplícasela a tu DEM. Al hacerlo, obtendrás una característica, variable o parámetro del relieve; por ejemplo, si aplicas la técnica "Geomórfonos" obtendrás una clasificación del relieve. Usa todos los apoyos que necesites, desde el software SIG que mejor conozcas (recomiendo QGIS y GRASS GIS), hasta inteligencia artificial (IA). Si usas IA, no le pidas que te resuelva el ejercicio pasándole el mandato tal cual y luego copiando pegando. Más bien, pídele que te explique cómo resolverlo y hazlo por tu cuenta (modo tutor). -->
<!-- Revisa demostraciones y aplicaciones de geomorfometría en @hengl2009geomorphometry. Estos son los grupos de  técnicas que se encuentran en el libro, pero debes leer en el interior del libro para enterarte mejor (puedes elegir otras que no se encuentren en esta lista y que conozcas mejor; sólo consúltalo conmigo antes de tomar la decisión): -->
<!-- - Parámetros básicos de la superficie del terreno (locales y regionales). Capítulo 6 de @hengl2009geomorphometry. Por ejemplo, pendiente, curvatura, índice de rugosidad topográficas, etc. -->
<!-- - Parámetros de la superficie del terreno y objetos hidrológicos. Capítulo 7 de @hengl2009geomorphometry. Por ejemplo, acumulación de flujo, dirección de drenaje. -->
<!-- - Parámetros de la superficie del terreno para topoclimas. Capítulo 8 de @hengl2009geomorphometry. Por ejemplo, orientación de vertiente, distancia a la costa. -->
<!-- - Formas y formas elementales. Capítulo 9 de @hengl2009geomorphometry. Por ejemplo, clasificación del relieve por geomórfonos, extracción de depresiones, extracción de piedemontes. -->
<!-- 3. Redacta un miniensayo, basándote en la plantilla `plantilla.Rmd` que se encuentra en este mismo repositorio. Para hacerlo, deberás aceptar la práctica desde el portal de la asignatura (ve al [portal de la asignatura](https://github.com/geomorfologia-202601)), haz clic en el enlace de la práctica, acepta la asignación y luego clona tu repo en RStudio. Deberás usar estilos de formato (los títulos debidamente escritos), referencias bibliográficas, referencias cruzadas a figuras y tablas (es decir, necesitarás que las figuras y tablas tengan título o "*caption*"). No podrás desarrollar tu redacción usando listas de viñetas ni listas numeradas. Recuerda usar la plantilla mencionada. Distribuye tu texto en las siguientes secciones: -->
<!-- - **Introducción** (tamaño recomendado: 3 párrafos). Desde lo amplio, comienza escribiendo sobre geomorfometría (qué es). A continuación, explica en qué consiste el parámetro que has elegido, su importancia, por qué es necesario calcularlo, para qué se usa. Plantea tu o tus objetivos, que en este caso son bastante sencillos. Cierra con la importancia que reviste obtener el parámetro o rasgo geomorfométrico que has elegido respecto del conjunto de la ciencia. -->
<!--     - Dentro de esta sección, debes incluir al menos tres citas. Los conceptos y afirmaciones ajenas, deben citarse bibliográficamente, y nunca deberás usar cita literal, pues se considera plagio. Las citas bibliográficas que incluyas, deberán respaldarse por sus correspondientes cuyas referencias, que deberán aparecer en la sección final (Referencias). Las citas y la lista de referencias, deberán seguir el estándar APA 7ma edición (APA7), que es el que la propia plantilla tiene configurado por defecto; en principio, no tendrás que ocuparte de todos los detalles de sintaxis del formato APA7, pero no debes confiar ciegamente en lo que hace RMarkdwon. -->
<!-- - **Materiales y métodos** (tamaño recomendado: 2 párrafos). Explica cómo obtuviste los datos que usaste, y documenta en qué consiste la fuente. Arriba te especifiqué que se trata del DEM SRTM, pero debes describirlo y citar fuentes. Debes igualmente citar el software y hardware usado, y las referencias sobre la técnica o algoritmo empleados. Dentro de la redacción, debes incluir al menos dos citas. Si incluyes un diagrama de flujo metodológico ("metodología gráfica"), te resultará más fácil explicar tu metodología. **No adelantes resultados, sólo escribe que fuentes y herramientas usaste (materiales) y qué técnicas concretas o algoritmos utilizaste (métodos)**. Toda figura y tabla que insertes debe citarse con referencia cruzada, que básicamente se construyen con (más instrucciones en el aula, por vídeos o por el foro). Usa un sistema de referencia cruzada asistido por el procesador de texto que uses (pregunta a tu tutor de inteligencia artificial de preferencia cómo insertar títulos a tablas y figuras, y cómo referirlos en el texto; también pregúntale cómo insertar y referir fórmulas). -->
<!-- - **Resultados** (tamaño recomendado: 1 párrafo). El parámetro o variable morfométrica que obtuviste, presentándolo en sus respectivas componentes. No hagas valoraciones en esta sección, simplemente incluye el resultado obtenido. -->
<!-- - **Discusión** (tamaño recomendado: 2 párrafos). Abre la discusión indicando si alcanzaste tus objetivos. Describe por qué era importante alcanzarlos. Comenta sobre las limitaciones, de cualquier tipo, ya sea las limitaciones de los datos, de la técnicas, de los objetivos de aprendizaje. Cierra indicando qué desafíos futuros quedan abiertos tras este trabajo. -->
<!-- - **Referencias**. Las referencias que hayas citado en el texto, se incluirán automáticamente en la sección "Referencias". No obstante, debes verificar la integridad de las mismas. -->
<!-- > **RECUADRO: recomendaciones básicas de redacción** -->
<!-- >  -->
<!-- > Usa una voz (activa o pasiva) de forma consistente, pero sólo ten presente que la redacción de manuscritos científicos a menudo se utilizan ambas voces, dependiendo del contexto y el mensaje que el/la autor/a quiera transmitir. Veamos algunos ejemplos: -->
<!-- >  -->
<!-- > **Voz activa en manuscrito científicos:** -->
<!-- >  -->
<!-- > - **Analicé** los datos utilizando el software R. -->
<!-- >  -->
<!-- > - El experimento **mostró** que la temperatura afecta directamente la tasa de reacción. -->
<!-- >  -->
<!-- > - Los investigadores **encontraron** una correlación significativa entre las dos variables. -->
<!-- >  -->
<!-- > La voz activa puede hacer que la redacción parezca más directa y clara, y es especialmente útil cuando el/la autor/a quiere enfatizar quién llevó a cabo una acción o cuándo se desea hacer una afirmación fuerte. -->
<!-- >  -->
<!-- > **Voz pasiva en artículos científicos:** -->
<!-- >  -->
<!-- > - Los datos **fueron analizados** utilizando el software R. -->
<!-- >  -->
<!-- > - **Se observó** que la temperatura afecta directamente la tasa de reacción. -->
<!-- >  -->
<!-- > - Una correlación significativa **fue encontrada** entre las dos variables. -->
<!-- >  -->
<!-- > La voz pasiva es común en la redacción científica porque a menudo se prefiere un tono más impersonal, enfocando la atención en los resultados y procedimientos en lugar de en quienes llevaron a cabo la investigación. También puede ser útil cuando no se quiere o no es relevante especificar quién realizó la acción. -->
<!-- >  -->
<!-- > **En todas mis prácticas, está completamente permitido usar IA (e.g. chatGPT), pero te recomiendo que la uses más como tutor que como redactor**. Tal como te sugerí arriba, no le pidas que te resuelva los problemas del mandato. Pídele que te dé ideas, y que luego tú las mejores o las descartes. No abuses tampoco del texto, pues mucha redacción no siempre es mejor; en redacción de ensayos "menos es más". Cruza las redacciones que te ofrezca con tu conocimiento, y revisa si los términos o conceptos usados son descabellados (toda IA se inventa cosas, cuidate de no caer en esa trampa). Nunca le pidas referencias bibliográficas, porque se va equivocar. -->
<!-- ## Criterios de evaluación y escala de valoración -->
<!-- | Criterio                          | Nivel 1 (En Desarrollo) | Nivel 2 (Aceptable) | Nivel 3 (Bueno) | Nivel 4 (Excelente) | -->
<!-- |-----------------------------------|-------------------------|---------------------|-----------------|---------------------| -->
<!-- | **Análisis Geomorfométricos**     | Análisis incompleto o incorrecto de los datos geomorfométricos. | Análisis básico y correcto de los datos geomorfométricos. | Análisis detallado y correcto de los datos geomorfométricos. | Análisis exhaustivo y avanzado de los datos geomorfométricos. | -->
<!-- | **Uso de Software**               | Uso limitado y con errores del software de procesamiento de texto y SIG. | Uso adecuado del software de procesamiento de texto y SIG. | Buen manejo del software de procesamiento de texto y SIG, con algunas características avanzadas. | Excelente manejo del software de procesamiento de texto y SIG, incluyendo características avanzadas. | -->
<!-- | **Redacción y Estilo**            | Redacción pobre con numerosos errores gramaticales y de estilo. | Redacción clara con algunos errores gramaticales y de estilo. | Redacción fluida y coherente con pocos errores gramaticales. | Redacción impecable y elegante sin errores gramaticales. | -->
<!-- | **Formato y Estructura**          | Formato y estructura incorrectos o ausentes. | Formato y estructura básicos y mayormente correctos. | Buen formato y estructura, con adecuada organización del documento. | Excelente formato y estructura, con organización perfecta del documento. | -->
<!-- | **Uso de Figuras y Tablas**       | Uso inadecuado o ausente de figuras y tablas. | Uso básico y correcto de figuras y tablas. | Uso adecuado de figuras y tablas, con buena integración en el texto. | Uso excelente de figuras y tablas, perfectamente integradas en el texto. | -->
<!-- | **Citas y Referencias**           | Citas y referencias inadecuadas o incorrectamente formateadas. | Citas y referencias adecuadas con algunos errores de formato. | Citas y referencias bien utilizadas y mayormente en el formato correcto. | Uso ejemplar de citas y referencias, perfectamente formateadas según APA 7ma edición. | -->
<!-- | **Reproducibilidad del Análisis** | Análisis no reproducible o con instrucciones poco claras. | Análisis mayormente reproducible con algunas instrucciones claras. | Análisis bien documentado y reproducible con instrucciones detalladas. | Análisis perfectamente documentado y totalmente reproducible con instrucciones claras y completas. | -->
<!-- ¿Qué entregar? -->
<!-- * **Manuscrito**. La entrega del manuscrito se realiza en PDF generado a partir de RMarkdown, y por medio del repositorio personal haciendo (commit + push), siguiendo el flujo usual de la asignatura. Dispones de una plantilla RMarkdown (archivo `plantilla.Rmd`) en el repo, con el cual podrás crear tu PDF, pero puedes usar otras plantillas, siempre que generes tu PDF a partir de un RMarkdown, y siempre que tenga estructura típica de manuscrito (Título, Autor/a + Matrícula, Resumen, Introducción, Materiales y Métodos, Resultados, Discusión, Conclusiones, Referencias, Información Suplementaria). Muchas revistas científicas tienen plantillas RMarkdown a través del paquete rticles; puedes usar alguna de esas plantillas si lo deseas yendo al menú `File > New File > R Markdown... > From Template`. -->
<!-- * **Diapositivas**. -->
<!-- * **Defensa oral (en clase)**. -->
<!-- # Introducción -->
<!-- Esta práctica inaugura la asignatura y está diseñada para que el estudiantado construya una base sólida en los **fundamentos conceptuales**, las **bases geológicas/estructurales**, y la noción de **tiempo en geomorfología**, tal como se plantea en la **Unidad 1**. -->
<!-- A diferencia de una práctica de “ejercicios sueltos”, aquí trabajaremos bajo un esquema de **práctica integradora (taller + defensa)**. Tu tarea será: -->
<!-- 1. **Elegir un (1) ejercicio** de los propuestos (de un conjunto de ocho), y -->
<!-- 2. Convertirlo en un **problema geomorfológico bien formulado** que culmine en dos productos: -->
<!-- * Un **manuscrito científico reproducible**, y -->
<!-- * Una **presentación oral breve** (diapositivas + defensa). -->
<!-- El punto clave es que, aunque solo desarrolles **un ejercicio**, tu manuscrito debe evidenciar un recorrido por la teoría de la Unidad 1: **conceptos, supuestos, decisiones, evidencia, limitaciones y conclusiones**. -->
<!-- # Qué debes producir (entregables) -->
<!-- ## Entregable 1: Manuscrito reproducible (obligatorio) -->
<!-- Un manuscrito breve en formato académico, construido a partir de la **plantilla del repositorio** o de una plantilla alternativa, con las siguientes secciones mínimas: -->
<!-- * **Título**. -->
<!-- * **Autor/a + Matrícula**. -->
<!-- * **Resumen**. -->
<!-- * **Introducción**. -->
<!-- * **Marco teórico**. -->
<!-- * **Metodología** (documental / conceptual). -->
<!-- * **Resultados** (tablas, figuras, esquemas, mapas conceptuales, o producto cartográfico si aplica). Las figuras y tablas deben referirse en el texto, es decir, deben contar con "referencia cruzada". -->
<!-- * **Discusión**. -->
<!-- * **Conclusiones**. -->
<!-- * **Referencias**. Las referencias deben insertarse automáticamente mediante la bibliografía del repositorio, usando formato BibTeX y colocando las entradas en un archivo .bib. -->
<!-- * **Información suplementaria (si aplica)**. -->
<!-- > Reiterando información anterior. La entrega del manuscrito se realiza en PDF generado a partir de RMarkdown, y por medio del repositorio personal haciendo (commit + push), siguiendo el flujo usual de la asignatura. Dispones de una plantilla RMarkdown (archivo `plantilla.Rmd`) en el repo, con la cual podrás crear tu PDF, pero puedes usar otras plantillas, siempre que generes tu PDF a partir de un RMarkdown, y siempre que tenga estructura típica de manuscrito (Título, Autor/a + Matrícula, Resumen, Introducción, Materiales y Métodos, Resultados, Discusión, Conclusiones, Referencias, Información Suplementaria). Muchas revistas científicas tienen plantillas RMarkdown a través del paquete rticles; puedes usar alguna de esas plantillas si lo deseas yendo al menú File > New File > R Markdown... > From Template. -->
<!-- **Extensión sugerida**: 4–8 páginas (sin contar referencias). -->
<!-- **Evita las listas de "viñetas" y las listas numeradas en la redacción.** -->
<!-- ## Entregable 2: Presentación oral (obligatorio) -->
<!-- Una exposición breve: -->
<!-- * **17 minutos** por estudiante -->
<!-- * Recomendado: 10 diapositivas -->
<!-- * Debe explicar: problema, enfoque, evidencia principal (tabla/figura/mapas), conclusiones y limitaciones. -->
<!-- # Cómo se organiza la práctica (ciclo estándar + entregas parciales) -->
<!-- > Las entregas parciales son cortas y sirven para evitar "hacer todo el último día". -->
<!-- ## Día 1 — Elección + delimitación del problema (entrega parcial 1) -->
<!-- * Elige **un ejercicio** que no haya sido elegido por otra persona. -->
<!-- * Redacta una **pregunta principal** y 2–3 subpreguntas. -->
<!-- * Define el **corpus** (manuales, artículos, mapas, etc.), es decir, las fuentes que usarás. -->
<!-- * Esboza las **tablas/figuras** que usarás. Si aplica, qué variables o elementos incluirás en tu manuscrito. -->
<!-- **Entrega parcial 1 (1 página o menos):** -->
<!-- * Título provisional. -->
<!-- * Pregunta(s). -->
<!-- * Corpus (lista de fuentes). -->
<!-- * Boceto de tablas/figuras/mapas. -->
<!-- ## Día 2 — Lectura + estructura del manuscrito (entrega parcial 2) -->
<!-- * Lee el corpus seleccionado. -->
<!-- * Escribe un **esquema** del manuscrito (bullets por sección). -->
<!-- * Redacta el **marco teórico** en borrador. -->
<!-- * Avanza las tablas/figuras/mapas. Deben referirse en el texto; figuras y tablas deben contar con "referencia cruzada". -->
<!-- **Entrega parcial 2:** -->
<!-- * Esquema (con subtítulos). -->
<!-- * Primer borrador del marco teórico (mínimo 500–800 palabras). -->
<!-- * Tablas/figuras/mapas en borrador. Deben referirse en el texto; figuras y tablas deben contar con "referencia cruzada". -->
<!-- ## Día 3 — Resultados + discusión (entrega parcial 3) -->
<!-- * Completa el producto central (tablas/figuras/mapas). -->
<!-- * Redacta resultados y discusión. -->
<!-- * Añade conclusiones y limitaciones. -->
<!-- **Entrega parcial 3:** -->
<!-- * Tablas/figuras finales (o mapas, si aplica). Deben referirse en el texto; figuras y tablas deben contar con "referencia cruzada". -->
<!-- * Resultados + Discusión (borrador avanzado). -->
<!-- ## Día 4 — Entrega final + defensa -->
<!-- * Manuscrito final (PDF exportado desde RMarkdown). -->
<!-- * Diapositivas. -->
<!-- * Defensa oral. -->
<!-- # Qué debes elegir (ejercicio) -->
<!-- * Cada estudiante debe elegir **un solo ejercicio**. -->
<!-- * No se permiten ejercicios repetidos entre personas. -->
<!-- # Cómo usar los ejercicios (reglas del juego) -->
<!-- 1. **No es un resumen de clase.** Es un manuscrito: plantea un problema, muestra evidencia (tablas/figuras, resultados), discute y concluye. -->
<!-- 2. **Debes usar fuentes académicas.** Como mínimo: -->
<!--    * 2 manuales / capítulos, y -->
<!--    * 3 artículos científicos (o equivalentes) para sostener tu discusión. -->
<!-- 3. **Tablas/figuras obligatorias** en todos los ejercicios. Éstas deben referirse en el texto; figuras y tablas deben contar con "referencia cruzada". -->
<!-- 4. **No inventes contenido.** Toda afirmación importante debe estar sustentada. -->
<!-- 5. **Usa IA, pero supervisa/controla lo que te dé.** No copies y pegues sin revisar. Verifica todo. -->
<!-- 6. **Evita lo puramente opinativo.** Argumenta con base en el corpus y en conceptos geomorfológicos. -->

## Referencias

<div id="refs" class="references csl-bib-body hanging-indent"
entry-spacing="0" line-spacing="2">

<div id="ref-hengl2009geomorphometry" class="csl-entry">

Hengl, T., Reuter, H. I. y Institute for Environment and Sustainability
(Eds.). (2009). *Geomorphometry: concepts, software, applications* (1st
ed). Elsevier.

</div>

</div>
