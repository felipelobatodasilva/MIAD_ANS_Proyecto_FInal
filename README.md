# Análisis de Características Musicales en Spotify

## Contenido

●  [Descripción del Proyecto](#descripcion_proyecto)<br/>
●  [Estructura del Repositorio](#estructura_del_repo)<br/>

## 📌Descripción del Proyecto <a name="descripcion_proyecto"></a>

En la era digital, la música es una parte esencial de nuestra vida diaria, y plataformas como Spotify han revolucionado la forma en que descubrimos y disfrutamos canciones. Este proyecto utiliza una base de datos que abarca desde 1998 hasta 2020, recopilando información detallada sobre canciones, incluyendo atributos como género, bailabilidad, energía, popularidad y emociones transmitidas.

Se obtuvieron grupos con características diferentes, tanto económicas como musicales, que pueden generar impacto en la industria musical al servir como insumo para conocer preferencias de la población de acuerdo con el contexto económico.

Este proyecto está dirigido a productores musicales, plataformas de streaming y analistas de datos que buscan entender las tendencias musicales."


*¿Por que algunos generos musicales se vuelven más populas en diferentes contextos económicos en EEUA?*
 

### Motivación

La motivación para resolver esta pregunta radica en la posibilidad de aplicar técnicas de aprendizaje no supervisado, específicamente el clustering, para revelar estructuras ocultas en los datos musicales que permitan caracterizaciones relacionadas con la realidad económica de la audiencia
 

### Tecnologías y Métodos

Este proyecto emplea técnicas de aprendizaje no supervisado, tales como:

- *Reducción de Dimensionalidad:* Para simplificar la visualización y el análisis de datos complejos.
- *Clustering:* Para identificar grupos de canciones con características similares.
    

## 📌Estructura del Repositorio <a name="estructura_del_repo"></a>

Este repositorio contiene la estructura y los archivos necesarios para el proyecto de análisis de datos musicales utilizando técnicas de aprendizaje automático no supervisado. A continuación, se muestra el árbol acompañado de la descripción detallada de las carpetas y archivos presentes en el repositorio.
     
    .
    ├── cicloeeuu.png
    ├── Clusters aplicado al análisis de la música y su relación con variaciones macroeconómicas.pdf
    ├── Documentos_Academicos
    │   ├── A Study on Music Genre Classification using Machine Learning.pdf
    │   ├── Clustering Music by Genres Using Supervised and Unsupervised Algorithm.pdf
    │   ├── Music Genre Classification using Machine Learning A Comparative Study.pdf
    │   ├── ProQuestDocuments-2024-09-25.pdf
    │   ├── Supervised learning and unsupervised learning on music data with different genres.pdf
    │   └── Unsupervised Learning for Music Genre Classification of Song Lyrics.pdf
    ├── Insumos
    │   ├── Crecimiento Renta nacional neta.csv
    │   ├── Final consumption expenditure.csv
    │   ├── gdp-per-capita-worldbank.csv
    │   ├── Gross savings.csv
    │   ├── Inflation_USA_worldbank.csv
    │   ├── songs_normalize.csv
    │   └── unemployment_worldbank.csv
    ├── Presentacion usada en el video.pdf
    ├── README.md
    └── Transform_df_songs.Ajuste.ipynb

**cicloeeuu.png**

Imagen del ciclo económico que se usó para la creación de la variable que permitió separar la base en data asociada de la recesion economia y data de la no recesion economia en los EEUA


**Clusters aplicado al análisis de la música y su relación con variaciones macroeconómicas.pdf**

Informe final de la metodologia implementada


**_Documentos_Academicos_**

Esta carpeta contiene todos los artículos utilizados para la Revisión preliminar de antecedentes.


**Insumos**

Carpeta que contiene los insumos de datos económicos y de música necesarios para el análisis.El insumo base es songs_normalize.csv y los demas insumos están asociados a información macroeconomica

**Presentacion usada en el video.pdf**

Archivo que contiene toda los slides usados en la creación del video (Link del video: https://www.youtube.com/watch?v=xHJUuwU6Vqw)

**README.md**

Archivo que contiene las instrucciones generales y descripción del proyecto.


**Transform_df_songs.Ajuste.ipynb**

Notebook de Jupyter utilizado para transformar y ajustar los datos de canciones como parte del proceso de análisis de datos.