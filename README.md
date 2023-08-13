# PROYECTO: *Análisis de la Efectividad de Programas de Educación Continua y Permanente (ECP) en la Facultad de Ciencias de la Universidad Nacional de Colombia*
---
## AUTORES: ##

Kelly Johana Castillo Beltran\\
Andres Felipe Guerrero Guio\\
Maryi Martinez Paredes\\

## ASESOR PRINCIPAL: Prof. Camilo Torres
---

## INTRODUCCIÓN ##

La Facultad de Ciencias ofrece a la comunidad en general proyectos de Extensión diseñados para atender las necesidades académicas de sectores específicos, las cuales no solo responden a requerimientos puntuales, fruto de una cuidadosa planificación tanto a nivel académico como administrativo. Las mismas requieren del compromiso y la inversión de recursos por parte de diversos actores dentro de la Universidad. 

A pesar de su importancia, la evaluación del éxito de estos cursos y diplomados (en términos de apertura) ha sido una cuestión poco estudiada en la Facultad. Esta falta de análisis representa un desafío significativo, ya que la cancelación de un proyecto no solo implica la pérdida de recursos económicos, como otros factores que pueden ser intangibles, como la inversión de tiempo que requiere la planificación de la actividad, así como la oportunidad de generar un impacto positivo en la comunidad. 

Por ello, con el ejercicio desarrollado a lo largo de este trabajo se buscará establecer los factores determinantes que influyen para que una actividad sea exitosa desde su promoción hasta su apertura administrativa y académica.

## DESCRIPCIÓN DEL PROBLEMA ##

Las actividades de educación continua y permanente que se plantean y aprueban ante el Consejo de Facultad, determina un punto de equilibrio con el fin de poder desarrollar o no dicha actividad; por lo tanto el alto número de actividades derogadas por no cumplir este punto de equilibrio, conlleva además de una pérdida de tiempo y de trámites administrativos, pérdidas económicas y de credibilidad.

## FUENTES DE DATOS ##

Bases datos detalladas de los programas de educación continua, incluyendo información sobre los participantes, cursos tomados, duración de los programas, calificaciones, encuestas de satisfacción, entre otros

## PROCESAMIENTO ETL ##

Las bases de datos que se trabajarán son las de “pre inscritos e inscritos”, las cuales se encuentran en formato *XLSX* separadas para cada curso ofertado, estas serán descargadas en formato csv para leerlas a través de pandas y realizar la unificación de las bases de datos. En este proceso se hará un procedimiento de transformación de los datos en el que se incluyen nuevas variables que dan cuenta del curso y si se ejecutó o no. Posteriormente se realiza un análisis exploratorio de los datos identificando el tipo de variable para variable e identificando datos faltantes y unificando criterios.

Finalmente se realizará el proceso “merge” para unir las dos bases de datos y agregar una nueva variable que indique la inscripción o no de un participante. De igual forma,  se usará la función “merge” con una base de datos que contiene información del estado de ejecución de las actividades para etiquetar los cursos efectivamente ejecutados. 

## EXPLORACIÓN DE DATOS ##

1	Limpieza de datos

2	Identificación de outliers

3	Análisis de correlación

4	Segmentación y agrupación

5	Exploración geoespacial

## TÉCNICAS DE MODELACIÓN PROPUESTAS  ##
No se tiene definida en este momento.

## CONOCIMIENTOS REQUERIDOS PARA EL DESARROLLO DEL PROYECTO  ##
Python, SQL, modelos supervisados y/o no supervisados.

## RESULTADOS ESPERADOS  ##

Este proyecto permitirá no solo aplicar técnicas de ciencias de datos hacia el campo administrativo, sino también contribuir a la mejora de la Educación Continua en la Facultad de Ciencias de la UNAL, en pro de disminuir la tasa porcentual de las actividades derogadas de ECP, evitando reprocesos contractuales, y generen y/o conserven el buen nombre de la institución hacia los usuarios tanto internos como externos.

