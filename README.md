# 04-Data_Visualization

Mi vida antes de convertirme en data analyst⬇️

![sonic](https://github.com/charlieciordia/04-Data_Visualization/blob/main/img/sonic.gif)


## Objetivo 🎯

El objetivo es contar una historia a través de un proyecto de visulización en Tableau. Se ha elegido un dataset que recoge la venta de videojuegos desde 1980 hasta 2016, y se procederá a un estudio de mercado según regiones, géneros, plataformas e histórico de ventas.


## Estructura 📂

El repositorio se divide en las siguientes carpetas y archivos:

- **Folder data:**
   - Contiene el dataset, tanto en crudo como limpio.

- **Folder notebook:**
   - **main**: Contiene el procedicimiento de exploración, análisis y limpieza del dataset.

- **Folder img:**
   - Para guardar memes e imágenes.


## El especulador de videojuegos 👾

**1. Intro**

Como jugador y coleccionista, he decidido empezar una colección de videojuegos retro. Para tener una colección digna de mención, además de los mejores juegos y populares, quiero averiguar los más raros del catálogo, para poder especular y revender juegos en el momento que por falta de espacio mi pareja me quiera echar de casa.

**2. Desarrollo**

Primero realizo un estudio de los géneros con más ventas según los años. Además, puedo obtener las preferencias según región (Europa, Norteamérica y Japón).

![sales_genres](https://github.com/charlieciordia/04-Data_Visualization/blob/main/img/sales_genres.png)

Observo que el mercado japonés se comporta de manera diferente que los mercados europeo y norteamericano, que guardan una alta correlación. De este modo, decido que mis objetivos en cuanto a títulos serán distintos según mercado, ya que los géneros más populares difieren.

Por otro lado, distingo entre diferentes plataformas la cantidad de videojuegos que salieron al mercado, y discretizo por los géneros más populares observados anteriormente para poder tener una mayor variedad catálogo. De este modo, me marco objetivos según consola y género para averiguar los títulos más raros.

Como criterio de especulador experto, considero que los videojuegos que tuvieron una baja repercusión en ventas, pero que cuentan con una alta valoración por parte de los usuarios, son aquellos que me interesa conseguir. Escasez de producto + calidad = 💸💸💸

![games_obj](https://github.com/charlieciordia/04-Data_Visualization/blob/main/img/games_obj.png)


**3. Conclusión**

Con las condiciones comentadas, filtro y obtengo listas de videojuegos por género y plaforma. Consulto por internet el mercado de segunda mano y compruebo que en efecto, muchos videojuegos obtenidos se encuentran en reventa por un alto precio. Por otro lado, aquellos que no cuenten con un sobreprecio son candidatos a revalorizarse en un futuro, lo cual sería un objetivo interesante para acumular stock a largo plazo.

Como ejemplo, en los siguientes enlaces se puede consultar el precio de venta actual de videojuegos como resultado del estudio:

[Shin Megami Tensei: strange journey de DS](https://www.ebay.es/sch/i.html?_from=R40&_trksid=p2334524.m570.l1313&_nkw=shin+megami+tensei+strange+journey+ds&_sacat=0&LH_TitleDesc=0&_odkw=shin+megami+tensei+strange+journeyds&_osacat=0)

[Bully de PS2](https://www.ebay.es/sch/i.html?_from=R40&_trksid=p2334524.m570.l1313&_nkw=bully+ps2&_sacat=0&LH_TitleDesc=0&_odkw=shin+megami+tensei+strange+journey+ds&_osacat=0)

Se puede consultar el **Dashboard** en el primer enlace del siguiente apartado.


## Libraries and resources📚
 
[Dashboard](https://public.tableau.com/app/profile/carlos.ciordia/viz/Videogamessales_16997268251410/Dashboard12) 🎮

[Tableau](https://www.tableau.com/) 📊

[Pandas](https://pandas.pydata.org/docs/) 🐼

[Kaggle](https://www.kaggle.com/datasets/gregorut/videogamesales) 🪘

