# Playas-de-Espana-2017

PLAYAS DE ESPAÑA 2017

Visualización y análisis de las Playas de España 2017 (fuente de datos : esri España)


A) Características del dataset
================================================================================

Las características de los datos son las siguientes :

   * FUENTE DE DATOS : http://opendata.esri.es/datasets/84ddbc8cf4104a579d579f6441fcaa8a_0   (Open Data)
   * FECHA           : año 2017
   * NUM. REGISTROS  : 3.511
   * NUM. ATRIBUTOS  : 80
      
B) Visualización del dataset
================================================================================
   
Se ha elaborado una visualización del dataset con la herramienta TABLEAU PUBLIC (https://public.tableau.com/profile/mercedes.parrado#!) donde se muestran las playas y algunas de sus características. Por ejemplo :

   * Playas nudistas
   * Playas con bandera azul
   * Nombre de cada playa
   * Kilómetros de playa

agrupadas (cuando proceda) por Comunidad Autónoma y por provincia.

La visualización pone de manifiesto algunos insights, tales como :
   1) Sorprende que sea Galicia la que más playas tiene con diferencia, teniendo como tiene un clima no demasiado cálido (pestaña BARRAS_H).
   2) Las playas nudistas de Galicia no se  distribuyen a lo largo de toda su costa, sino que se concentran en torno a 2 grandes núcleos de población (pestaña MAPA_3) :
         - La Coruña
         - Pontevedra/Vigo.
   3) Se observa (pestaña MAPA_3) un trozo en la costa norte de la provincia de La Coruña donde no hay playas (=> ¿ es quizá una zona de acantilados ?).

y otros datos esperados como que en Ceuta y Melilla no haya playas nudistas.

C) Análisis del dataset
================================================================================

Llevamos a cabo un análisis del dataset respondiendo a las siguientes preguntas :

   * QUERY_1 : Las 10 playas más largas (incluído el nombre de la provincia) 
   * QUERY_2 : Las 10 playas más largas de una cierta provincia (incluído el nombre de la provincia)
   * QUERY_3 : Las playas de una comunidad autónoma concreta (ordenadas por longitud) 
   * QUERY_4 : Las 10 provincias que más metros de playa tienen 
   * QUERY_5 : Metros de playa de una cierta Comunidad Autónoma agrupados por provincia 
   * QUERY_6 : ¿ Qué Comunidad tiene más metros de playa ?
   * QUERY_7 : ¿ Qué provincia tiene más playas ... ?
   
               - QUERY_7.1 : ¿ Qué provincia tiene más playas ... en número ?
               - QUERY_7.2 : ¿ Qué provincia tiene más playas ... con nombres diferentes ?
               - QUERY_7.3 : ¿ Qué provincia tiene más playas ... nudistas ?
               - QUERY_7.4 : ¿ Qué provincia tiene más playas ... con bandera azul ?

Respondemos a estas preguntas cargando los datos en la correspondiente BD y, a continuación, ejecutando la QUERY en el lenguaje particular de la BD. Las BD que hemos utilizado son :
   * BD SQL :
        - PostgreSQL
   * BD NoSQL :
        - Riak
        - Cassandra
        - MongoDB
        - Neo4j
