# Análisis de Características Musicales en Spotify

## Contenido

●  [Descripción del Proyecto](#descripcion_proyecto)<br/>
●  [Estructura del Repositorio](#estructura_del_repo)<br/>

## 📌Descripción del Proyecto <a name="descripcion_proyecto"></a>

En la era digital, la música es una parte esencial de nuestra vida diaria, y plataformas como Spotify han revolucionado la forma en que descubrimos y disfrutamos canciones. Este proyecto utiliza una base de datos que abarca desde 1998 hasta 2020, recopilando información detallada sobre canciones, incluyendo atributos como género, bailabilidad, energía, popularidad y emociones transmitidas.

El objetivo de este proyecto es analizar esta base de datos para descubrir patrones y grupos de canciones que comparten características similares. A través del análisis de características musicales, buscamos responder a la pregunta:

*¿Existen grupos de canciones con características similares que podrían ayudar a predecir su éxito?*

### Motivación

La motivación detrás de este proyecto es utilizar técnicas de aprendizaje no supervisado para revelar estructuras ocultas en los datos musicales. Identificar patrones y agrupaciones en canciones puede ofrecer valiosas perspectivas tanto para artistas como para plataformas de streaming como Spotify:

- *Para los artistas:* Comprender qué características musicales tienden a ser más exitosas puede guiar la creación de nuevas canciones y álbumes.
- *Para las plataformas de streaming:* Mejorar las recomendaciones personalizadas, optimizar listas de reproducción y diseñar estrategias de marketing más efectivas.

Además, este análisis puede proporcionar una ventaja competitiva en el mercado musical, permitiendo predecir el éxito de nuevas canciones y adaptarse mejor a las tendencias emergentes.

### Tecnologías y Métodos

Este proyecto emplea técnicas de aprendizaje no supervisado, tales como:

- *Reducción de Dimensionalidad:* Para simplificar la visualización y el análisis de datos complejos.
- *Clustering:* Para identificar grupos de canciones con características similares.
    

## 📌Estructura del Repositorio <a name="estructura_del_repo"></a>

Este repositorio contiene la estructura y los archivos necesarios para el proyecto de análisis de datos musicales utilizando técnicas de aprendizaje automático no supervisado. A continuación, se muestra el árbol acompañado de la descripción detallada de las carpetas y archivos presentes en el repositorio.


    ├── Documentos_Academicos
    │   ├── A Study on Music Genre Classification using Machine Learning.pdf
    │   ├── Clustering Music by Genres Using Supervised and Unsupervised Algorithm.pdf
    │   ├── Music Genre Classification using Machine Learning A Comparative Study.pdf
    │   ├── Supervised learning and unsupervised learning on music data with different genres.pdf
    │   └── Unsupervised Learning for Music Genre Classification of Song Lyrics.pdf
    ├── estrategia de trabajo.docx
    ├── Notebook y datos proyecto
    │   ├── Proyecto_ANS_songs_(1).ipynb
    │   └── spotify.xlsx
    └── Tranformación de data
        ├── Documentación del modelado para el Trabajo final de Visualización y Storytelling.docx
        ├── songs_normalize.csv
        └── songs_transformed.csv

**_Documentos_Academicos_**

Esta carpeta contiene todos los artículos utilizados para la Revisión preliminar de antecedentes.


**_estrategia de trabajo.docx_**

Documento que proporciona la estrategia general para el proyecto, incluyendo objetivos, plan de trabajo, metodologías a emplear y una revisión preliminar de los antecedentes relacionados con el análisis de datos musicales de Spotify, cubriendo el período de 1998 a 2020. También describe la base de datos que se utilizará y propone una metodología para segmentar canciones en función de sus características, con el fin de prever su éxito.

**_Notebook y datos proyecto_**

*Proyecto_ANS_songs_(1).ipynb*: Notebook Jupyter utilizado para el análisis de datos, la aplicación de técnicas de aprendizaje automático y la visualización de los resultados. Es la herramienta principal para realizar experimentos y análisis dentro del proyecto.

*spotify.xlsx*: Archivo Excel que contiene datos de canciones extraídos de Spotify. Incluye varias características de las canciones, como género, popularidad, energía, entre otras, que se utilizarán para los análisis en el notebook.

**_Tranformación de data_**

Documentación del modelado para el Trabajo final de Visualización y Storytelling.docx: Documento que detalla el proceso de modelado y transformación de los datos para el trabajo final, centrado en la visualización y storytelling. Describe cómo se transformaron las variables originales y cómo se prepararon los datos para su uso en visualizaciones y análisis.

*songs_normalize.csv*: Archivo CSV que contiene datos de canciones que han sido normalizados, facilitando su análisis posterior.
    
*songs_transformed.csv*: Archivo CSV que contiene datos transformados de canciones, posiblemente después de haber sido limpiados y preparados para análisis finales y visualizaciones.

