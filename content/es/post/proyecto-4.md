---
date: 2023-06-23T10:58:08-04:00
featured_image: "/images/futbol.jpg"
title: "Proyecto 4: Análisis estadístico de las cinco grandes ligas de fútbol europeas"
---

Se trata del proyecto llevado a cabo para mi trabajo de final de grado (TFG) para la titulación de Matemáticas Computacionales en la Universidad Jaime I.

El proyecto se basa en el empleo de diferentes técnicas de minería de datos. El análisis de las componentes principales, para reducir la dimensión de un conjunto de datos. Los contrastes de hipótesis para evaluar los datos. La regresión logística, para predecir la ocurrencia de un evento binario. Y, la regresión ordinal, para predecir variables categóricas. El empleo de estas técnicas tiene como propósito realizar el estudio de datos sobre las diferentes ligas europeas de fútbol. A parte de la implementación y descripción de las técnicas empleadas, en el documento se encuentran explicados los fundamentos teóricos en los que se sustentan dichos procedimientos. Además, se exponen los resultados obtenidos en la implementación de dichos procedimientos. El desarrollo del proyecto se divide en tres fases. 

En la primera, se comienza comprobando si existen diferencias entre los equipos en función de su posición en la clasificación. Para ello, en primer lugar se evaluará mediante el Test de Kruskal-Wallis, si es posible encontrar diferencias tanto entre los equipos de una misma liga como entre las diferentes ligas. Y, en caso de encontrar diferencias, mediante el Test Post Hoc de Tukey se tratará de reagrupar estos grupos. Además, en esta fase, mediante el uso de mapas de correlaciones y el uso de la técnica del PCA se ha tratado de identificar los patrones ocultos en los datos y, además, poder graficar los equipos gracias a la reducción de la dimensionalidad.

En la segunda, lo que se ha pretendido es averiguar aquellos indicadores cuantificables del juego en la temporada de un equipo de cualquiera de las cinco ligas que están relacionados con el estilo de juego y resultan determinantes en que dicho equipo acabe la temporada clasificándose para jugar competiciones europeas. Como parte del desarrollo de esta fase, se ha empezado generando un mapa de correlaciones y el gráfico bidimensional resultante de aplicar el algoritmo de PCA con las variables de esta sección. Para completar el análisis se han realizado diferentes implementaciones de un algoritmo de regresión logística para así poder analizar los gráficos de odds ratios resultantes.

Por último, en la tercera fase, se ha implementado un modelo de regresión ordinal. Para este caso, la variable objetivo es una variable categórica con tres posibles valores: Europa, Permanencia y Descenso. En función de que al final de cada temporada registrada el equipo acabó clasificándose para una de las dos competiciones europeas (Champions League y Europa League), acabó en la zona de media tabla, o acabó en la zona de descenso de su correspondiente liga.

[Enlace al repositorio de GitHub](https://github.com/nicolascamanesantolin/TFG.git)

