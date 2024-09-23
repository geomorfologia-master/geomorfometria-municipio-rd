Práctica de desarrollo 2. PD02. Geomorfometría, reproducibilidad,
redacción, estilos de formato, figuras, tablas, citas y
referencias<small><br>Geomorfología (GEO-114)<br>Universidad Autónoma de
Santo Domingo (UASD)<br>Semestre 2024-02</small>
================
El Tali
2024-09-23

<!-- README.md se genera a partir de README.Rmd. Por favor, edita ese archivo. -->

Versión HTML (quizá más legible),
[aquí](https://geomorfologia-master.github.io/geomorfometria-municipio-rd/README.html)

# Fecha/hora de entrega

**30 de septiembre de 2024, 11:59 pm.**

# Objetivos

Vamos a “calentar motores”. El objetivo de esta práctica de desarrollo
es que demuestres o mejores … a) tus capacidades de realizar análisis
geomorfométricos; b) tus capacidades de usar software de procesamiento
de texto; c) tus capacidades de redacción. Esto te preparará, a futuro,
para el manuscrito.

Esta práctica tratará **sobre geomorfometría de un área de República
Dominicana**, intentando que sea una investigación reproducible y bien
redactada (nada de alto nivel, sólo estamos ensayando). Lo ideal es que
presentes un un documento que cumpla con estilos de formato, uso
apropiado de figuras, tablas, citas y referencias.

# Mandato

1.  Usando el DEM del Shuttle Radar Topography Mission (SRTM) recortado
    para un municipio, aplica una técnica geomorfométrica que elegirás
    (en el siguiente punto te explico más). Los archivos se encuentran
    en la carpeta [data/](data/). Debes elegir un municipio por su
    número y anunciarlo en el foro.

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

2.  Elige una técnica geomorfométrica de Hengl et al. (2009) y
    aplícasela a tu DEM. Al hacerlo, obtendrás una característica,
    variable o parámetro del relieve; por ejemplo, si aplicas la técnica
    “Geomórfonos” obtendrás una clasificación del relieve. Usa todos los
    apoyos que necesites, desde el software SIG que mejor conozcas
    (recomiendo QGIS y GRASS GIS), hasta inteligencia artificial (IA).
    Si usas IA, no le pidas que te resuelva el ejercicio pasándole el
    mandato tal cual y luego copiando pegando. Más bien, pídele que te
    explique cómo resolverlo y hazlo por tu cuenta (modo tutor).

Revisa demostraciones y aplicaciones de geomorfometría en Hengl et al.
(2009). Estos son los grupos de técnicas que se encuentran en el libro,
pero debes leer en el interior del libro para enterarte mejor (puedes
elegir otras que no se encuentren en esta lista y que conozcas mejor;
sólo consúltalo conmigo antes de tomar la decisión):

- Parámetros básicos de la superficie del terreno (locales y
  regionales). Capítulo 6 de Hengl et al. (2009). Por ejemplo,
  pendiente, curvatura, índice de rugosidad topográficas, etc.

- Parámetros de la superficie del terreno y objetos hidrológicos.
  Capítulo 7 de Hengl et al. (2009). Por ejemplo, acumulación de flujo,
  dirección de drenaje.

- Parámetros de la superficie del terreno para topoclimas. Capítulo 8 de
  Hengl et al. (2009). Por ejemplo, orientación de vertiente, distancia
  a la costa.

- Formas y formas elementales. Capítulo 9 de Hengl et al. (2009). Por
  ejemplo, clasificación del relieve por geomórfonos, extracción de
  depresiones, extracción de piedemontes.

3.  Redacta un miniensayo, basándote en la plantilla
    `manuscrito-geomorfometria-municipio-rd.Rmd` que se encuentra en
    este mismo repositorio. Para hacerlo, deberás clonar este
    repositorio, muy parecido a como hiciste con la PD01. Deberás usar
    estilos de formato (los títulos debidamente escritos, el texto
    normal también, siguiendo lo aprendido en la PD01), referencias
    bibliográficas, referencias cruzadas a figuras y tablas (es decir,
    necesitarás que las figuras y tablas tengan título o “*caption*”).
    No podrás desarrollar tu redacción usando listas de viñetas ni
    listas numeradas. Recuerda usar la plantilla mencionada. Distribuye
    tu texto en las siguientes secciones:

- **Introducción** (tamaño recomendado: 3 párrafos). Desde lo amplio,
  comienza escribiendo sobre geomorfometría (qué es). A continuación,
  explica en qué consiste el parámetro que has elegido, su importancia,
  por qué es necesario calcularlo, para qué se usa. Plantea tu o tus
  objetivos, que en este caso son bastante sencillos. Cierra con la
  importancia que reviste obtener el parámetro o rasgo geomorfométrico
  que has elegido respecto del conjunto de la ciencia.

  - Dentro de esta sección, debes incluir al menos tres citas. Los
    conceptos y afirmaciones ajenas, deben citarse bibliográficamente, y
    nunca deberás usar cita literal, pues se considera plagio. Las citas
    bibliográficas que incluyas, deberán estar respaldadas por sus
    correspondientes cuyas referencias, que deberán aparecer en la
    sección final (Referencias). Las citas y la lista de referencias,
    deberán seguir el estándar APA 7ma edición (APA7), que es el que la
    propia plantilla tiene configurado por defecto; en principio, no
    tendrás que ocuparte de todos los detalles de sintaxis del formato
    APA7, pero no debes confiar ciegamente en lo que hace RMarkdwon.

- **Materiales y métodos** (tamaño recomendado: 2 párrafos). Explica
  cómo obtuviste los datos que usaste, y documenta en qué consiste la
  fuente. Arriba te especifiqué que se trata del DEM SRTM, pero debes
  describirlo y citar fuentes. Debes igualmente citar el software y
  hardware usado, y las referencias sobre la técnica o algoritmo
  empleados. Dentro de la redacción, debes incluir al menos dos citas.
  Si incluyes un diagrama de flujo metodológico (“metodología gráfica”),
  te resultará más fácil explicar tu metodología. **No adelantes
  resultados, sólo escribe que fuentes y herramientas usaste
  (materiales) y qué técnicas concretas o algoritmos utilizaste
  (métodos)**. Toda figura y tabla que insertes debe citarse con
  referencia cruzada, que básicamente se construyen con (más
  instrucciones en el aula, por vídeos o por el foro). Usa un sistema de
  referencia cruzada asistido por el procesador de texto que uses
  (pregunta a tu tutor de inteligencia artificial de preferencia cómo
  insertar títulos a tablas y figuras, y cómo referirlos en el texto;
  también pregúntale cómo insertar y referir fórmulas).

- **Resultados** (tamaño recomendado: 1 párrafo). El parámetro o
  variable morfométrica que obtuviste, presentándolo en sus respectivas
  componentes. No hagas valoraciones en esta sección, simplemente
  incluye el resultado obtenido.

- **Discusión** (tamaño recomendado: 2 párrafos). Abre la discusión
  indicando si alcanzaste tus objetivos. Describe por qué era importante
  alcanzarlos. Comenta sobre las limitaciones, de cualquier tipo, ya sea
  las limitaciones de los datos, de la técnicas, de los objetivos de
  aprendizaje. Cierra indicando qué desafíos futuros quedan abiertos
  tras este trabajo.

- **Referencias**. Las referencias que hayas citado en el texto, se
  incluirán automáticamente en la sección “Referencias”. No obstante,
  debes verificar la integridad de las mismas.

> **RECUADRO: recomendaciones básicas de redacción**
>
> Usa una voz (activa o pasiva) de forma consistente, pero sólo ten
> presente que la redacción de manuscritos científicos a menudo se
> utilizan ambas voces, dependiendo del contexto y el mensaje que el/la
> autor/a quiera transmitir. Veamos algunos ejemplos:
>
> **Voz activa en manuscrito científicos:**
>
> - **Analicé** los datos utilizando el software R.
>
> - El experimento **mostró** que la temperatura afecta directamente la
>   tasa de reacción.
>
> - Los investigadores **encontraron** una correlación significativa
>   entre las dos variables.
>
> La voz activa puede hacer que la redacción parezca más directa y
> clara, y es especialmente útil cuando el/la autor/a quiere enfatizar
> quién llevó a cabo una acción o cuándo se desea hacer una afirmación
> fuerte.
>
> **Voz pasiva en artículos científicos:**
>
> - Los datos **fueron analizados** utilizando el software R.
>
> - **Se observó** que la temperatura afecta directamente la tasa de
>   reacción.
>
> - Una correlación significativa **fue encontrada** entre las dos
>   variables.
>
> La voz pasiva es común en la redacción científica porque a menudo se
> prefiere un tono más impersonal, enfocando la atención en los
> resultados y procedimientos en lugar de en quienes llevaron a cabo la
> investigación. También puede ser útil cuando no se quiere o no es
> relevante especificar quién realizó la acción.
>
> **En todas mis prácticas, está completamente permitido usar IA
> (e.g. chatGPT), pero te recomiendo que la uses más como tutor que como
> redactor**. Tal como te sugerí arriba, no le pidas que te resuelva los
> problemas del mandato. Pídele que te dé ideas, y que luego tú las
> mejores o las descartes. No abuses tampoco del texto, pues mucha
> redacción no siempre es mejor; en redacción de ensayos “menos es más”.
> Cruza las redacciones que te ofrezca con tu conocimiento, y revisa si
> los términos o conceptos usados son descabellados (toda IA se inventa
> cosas, cuidate de no caer en esa trampa). Nunca le pidas referencias
> bibliográficas, porque se va equivocar.

## Criterios de evaluación y escala de valoración

| Criterio                          | Nivel 1 (En Desarrollo)                                                  | Nivel 2 (Aceptable)                                                | Nivel 3 (Bueno)                                                                                  | Nivel 4 (Excelente)                                                                                  |
|-----------------------------------|--------------------------------------------------------------------------|--------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------|
| **Análisis Geomorfométricos**     | Análisis incompleto o incorrecto de los datos geomorfométricos.          | Análisis básico y correcto de los datos geomorfométricos.          | Análisis detallado y correcto de los datos geomorfométricos.                                     | Análisis exhaustivo y avanzado de los datos geomorfométricos.                                        |
| **Uso de Software**               | Uso limitado y con errores del software de procesamiento de texto y SIG. | Uso adecuado del software de procesamiento de texto y SIG.         | Buen manejo del software de procesamiento de texto y SIG, con algunas características avanzadas. | Excelente manejo del software de procesamiento de texto y SIG, incluyendo características avanzadas. |
| **Redacción y Estilo**            | Redacción pobre con numerosos errores gramaticales y de estilo.          | Redacción clara con algunos errores gramaticales y de estilo.      | Redacción fluida y coherente con pocos errores gramaticales.                                     | Redacción impecable y elegante sin errores gramaticales.                                             |
| **Formato y Estructura**          | Formato y estructura incorrectos o ausentes.                             | Formato y estructura básicos y mayormente correctos.               | Buen formato y estructura, con adecuada organización del documento.                              | Excelente formato y estructura, con organización perfecta del documento.                             |
| **Uso de Figuras y Tablas**       | Uso inadecuado o ausente de figuras y tablas.                            | Uso básico y correcto de figuras y tablas.                         | Uso adecuado de figuras y tablas, con buena integración en el texto.                             | Uso excelente de figuras y tablas, perfectamente integradas en el texto.                             |
| **Citas y Referencias**           | Citas y referencias inadecuadas o incorrectamente formateadas.           | Citas y referencias adecuadas con algunos errores de formato.      | Citas y referencias bien utilizadas y mayormente en el formato correcto.                         | Uso ejemplar de citas y referencias, perfectamente formateadas según APA 7ma edición.                |
| **Reproducibilidad del Análisis** | Análisis no reproducible o con instrucciones poco claras.                | Análisis mayormente reproducible con algunas instrucciones claras. | Análisis bien documentado y reproducible con instrucciones detalladas.                           | Análisis perfectamente documentado y totalmente reproducible con instrucciones claras y completas.   |

## Referencias

<div id="refs" class="references csl-bib-body hanging-indent"
entry-spacing="0" line-spacing="2">

<div id="ref-hengl2009geomorphometry" class="csl-entry">

Hengl, T., Reuter, H. I. y Institute for Environment and Sustainability
(European Commission. Joint Research Centre) (Eds.). (2009).
*Geomorphometry: concepts, software, applications* (1st ed). Elsevier.

</div>

</div>
