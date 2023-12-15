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

Primero realizo un estudio de las ventas totales, discretizando por regiones (Europa, Norteamérica y Japón) y géneros.

![sales_01](https://github.com/charlieciordia/04-Data_Visualization/blob/main/img/01.png)
![sales_02](https://github.com/charlieciordia/04-Data_Visualization/blob/main/img/02.png)

También compruebo el top 10 de videojuegos más vendidos de la historia y las 5 publicadoras que más videojuegos han sacado al mercado.

![top](https://github.com/charlieciordia/04-Data_Visualization/blob/main/img/03.png)

Se observa que el mercado japonés se comporta de manera diferente que los mercados europeo y norteamericano. 

Una vez estudiado el mercado, puedo adentrarme en la aventura de la especulación. Considero que los videojuegos que tuvieron una baja repercusión en ventas, pero que cuentan con una alta valoración por parte de los usuarios, son aquellos que me interesa conseguir. Escasez de producto + calidad = 💸💸💸

![games_obj](https://github.com/charlieciordia/04-Data_Visualization/blob/main/img/04.png)


**3. Conclusión**

Con las condiciones comentadas, filtro y obtengo listas de videojuegos por género y plaforma. Consulto por internet el mercado de segunda mano y compruebo que en efecto, muchos videojuegos obtenidos se encuentran en reventa por un alto precio. Por otro lado, aquellos que no cuenten con un sobreprecio son candidatos a revalorizarse en un futuro, lo cual sería un objetivo interesante para acumular stock a largo plazo.

Como ejemplo, en los siguientes enlaces se puede consultar el precio de venta actual de videojuegos como resultado del estudio:

[Shin Megami Tensei: devil summoner de PS2](https://www.ebay.es/sch/i.html?_from=R40&_trksid=p2334524.m570.l1313&_nkw=shin+megami+tensei+devil+summoner+ps2&_sacat=0&LH_TitleDesc=0&_odkw=shin+megami+tensei+strange+journey+ds&_osacat=0)


Se puede consultar el **Dashboard** en el primer enlace del siguiente apartado.


## Libraries and resources📚
 
[Dashboard](https://public.tableau.com/views/Videogamessales_16997268251410/Story1?:language=es-ES&publish=yes&:display_count=n&:origin=viz_share_link) 🎮

[Tableau](https://www.tableau.com/) 📊

[Pandas](https://pandas.pydata.org/docs/) 🐼

[Kaggle](https://www.kaggle.com/datasets/gregorut/videogamesales) 🪘

