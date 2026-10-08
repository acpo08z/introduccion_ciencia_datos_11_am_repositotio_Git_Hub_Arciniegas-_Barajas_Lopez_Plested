###### introduccion_ciencia_datos_11_am_repositotio_Git_Hub_Arciniegas_Barajas_Lopez_Plested
------
## Algoritmos de análisis del usuario y contenido de los medios informativos 
##### 1. Introducción
En la actualidad, los medios informativos constituyen uno de los pilares de la economía colombiana, en la que empresas nacionales e internacionales buscan fortalecer su reputación y visibilidad en una audiencia constituida por 52 millones de personas (Gali C, 2026). La constante digitalización, en conjunto con el auge de las plataformas virtuales y medios informáticos, ha ejercido influencia directa en la manera en que lo colombianos consumen y procesan la información de su entorno. Según el Digital News Report 2026, el 54% de las personas encuestadas a nivel global manifiesta emplear redes sociales para obtener información, en contraste con el 51% que acude a casa editoriales oficiales. Aquellas cifras, trasladadas al contexto nacional, reflejan la transformación de los hábitos de consumo dado el contexto y las problemáticas que atraviesa el país: Una brecha entre desinformación masiva y el desplome de la confianza. Víctor García-Perdomo, investigador de la Universidad de la Sabana, revela que la confianza general de las noticias se ha desplomado al 25%, estando 12 puntos porcentuales por debajo del promedio global, mientras que el 60% de las personas expresa abiertamente sentir preocupación por la desinformación, lo que demuestra que existen múltiples variables asociadas que pueden llegar a incidir en los porcentajes de inconformismo.

Por ende, la data presente en el campo de los medios informativos se vuelve crucial para poder comprender con mayor exactitud la diversidad de factores que determinan el consumo de noticias y la percepción de la audiencia. Como referencia, el proyecto toma inspiración en la labor desarrollada por el científico de datos Chris Wiggins, quien se empeña como Chief Data Scientist en el New York Times. Dentro de sus principales funciones, se encuentra la realización de modelos asociativos realizados con Machine Learning acerca del contenido generado por los periódicos y la data de los usuarios del periódico y del canal digital The New York Times.  (Gutierrez S, s/f). 

En este contexto, el presento proyecto propone la implementación de algoritmos basados en la implementación del aprendizaje automático (machine learning), característicos a la Ciencia e ingeniería de Datos, en los medios informativos Colombianos. Lo anterior permitae analizar y comprender con mayor rigurosidad los fenómenos de consumo, los patrones de lectura, interpretación e interacción con el contenido presentado por los noticieros y similares más representativos de la región.

------
##### 2. Proyecto
PREGUNTA DE NEGOCIO: ¿Cómo podrían los diarios y medios de información colombianos conocer más a profundidad el comportamiento de los lectores mediante la ciencia de datos para ofrecer contenido que sea más relevante?

NUESTRA PROPUESTA: En la actualidad, la mayoría de contenido que los periódicos en línea suelen sugerir se basa en lo que esté en tendencia, y se tiende a estandarizar para la mayoría de usuarios (y usuarios no suscritos al medio en sí). Por ello, sería muy útil construir un sistema con un algoritmo más preciso, que con ayuda de la ciencia de datos brinde recomendaciones de artículos y noticias más consistentes con el comportamiento del lector.

FASES: 
1. Conocer los datos y analizar los patrones de comportamiento de los lectores: Analizando categorías de noticias consultadas, tiempo que permanecen en cada artículo, horarios de búsqueda, frecuencia.
2. Segmentar a los usuarios: Según sus intereses. Esto con el fin de perfilar a cada uno de los lectores que interactuaron con el medio y que son posibles o habituales consumidores.
3. Modelo de sistema de recomendación: ¿Qué contenido se le recomendará ahora a cada usuario según su perfil?
4. Evaluar el impacto: En la experiencia del usuario, evaluar lo que generará el nuevo sistema de recomendación. Se vería en el análisis de factores relacionadas a la experiencia del usuario tras hacer parte del sistema (si el tiempo de lectura aumentó/disminuyó, si cambió de alguna forma las interacciones de los usuarios con en contenido, entre otros factores).
------

##### 3. Metodologia y Datos

3.1.Datos y variables a utilizar

* Datos de comportamiento e interacción:
  
  * **tiempo_lectura**: Tiempo exacto (en segundos) que el usuario dura leyendo un artículo.
  * **porcentaje_scroll**: Qué tanto baja el usuario en la página para saber si leyó la noticia completa.
  * **frecuencia_visitas**: Cuántas veces a la semana o al mes entra el lector al periódico.
  * **horario_acceso**: Horas y días en los que el usuario suele leer noticias.

* Datos del contenido (Metadatos):
  * **categoria_noticia**: Sección del periódico (Deportes, Política, Economía, Opinión, etc.).
  * **palabras_clave**: Temas principales y etiquetas asociadas a cada artículo.
  * **tipo_formato**: Si es una noticia corta, una columna de opinión o un reportaje largo.

* Datos técnicos:
  * **dispositivo**: Si lee desde un celular, computador o tablet.
  * **fuente_origen**: Si llegó desde redes sociales, Google o entrando directo a la página.

3.2. Metodología
El desarrollo del proyecto se hará en los siguientes pasos:

1. Limpieza de datos: Filtrar la información recolectada para eliminar datos incompletos o visitas automáticas de bots.
2. Análisis de patrones: Revisar los datos para entender qué secciones se leen más según la hora y el tipo de dispositivo.
3. Creación del sistema de recomendación:
   * Recomendación por Contenido: Sugerir artículos parecidos en tema a los que el usuario ya leyó anteriormente.
   * Recomendación colaborativa: Recomendar noticias que hayan leído otros usuarios con gustos similares.
4. Evaluación del sistema: Medir el éxito del proyecto analizando si aumentó el tiempo que la gente pasa en la página y la cantidad de clics en las recomendaciones.

   ------
### Bibliografía y referencias

1. Libreta de Apuntes. (2026, 16 de junio). La «plataformización» de las noticias en 2026: Una radiografía global y la revolución informativa en Colombia. https://libretadeapuntes.com/digital-news-report-2026-colombia/

2. (Periódicos diarios de Colombia - Colombianos, s/f)
Periódicos diarios de Colombia - Colombianos. (s/f). Prensaescrita.com. Recuperado el 8 de octubre de 2026, de https://www.prensaescrita.com/america/colombia.php

3. Wiggins, C. (2014). Chris Wiggins: The New York Times. En S. Gutierrez, Data scientists at work (pp. xx-xx). Apress. https://doi.org/10.1007/978-1-4302-6599-8

