Resumen
Este proyecto recopiló información diversa sobre el juego de mesa Pradera a través de múltiples fuentes. El objetivo fue construir un conjunto de datos completo que incluyera opiniones de jugadores, detalles técnicos y conexiones relevantes entre distintos aspectos del juego, trabajando con contenido en varios idiomas.

Para la recolección de datos se utilizaron:
* Técnicas automatizadas para extraer texto.
* Procesamiento de documentos oficiales y guías.
* Transcripción de contenido audiovisual.

Introducción

Objetivo
Este trabajo tiene como objetivo extraer, procesar y analizar datos multilingües relacionados con Pradera. Los datos obtenidos abarcan información textual (reviews, tutoriales, manuales), estadísticas del juego y relaciones entre entidades (desarrolladores, personajes, sagas), con el fin de generar un conjunto de datos estructurados.

Metodología
Para cumplir con los requerimientos, se utilizaron las siguientes técnicas:
* Extracción de texto:
	* Documentos: Procesamiento de archivos PDF.
	* Videos: Transcripción automática de reviews y tutoriales mediante 		  herramientas como ffmpeg , pydub y speech Recognition.
	* Foros: Web scraping de hilos de discusión (ej: Reddit, foros oficiales) con 	  BeautifulSoup o Selenium.

* Organización de datos:
	* Almacenamiento en formatos tabulares (CSV, Excel) para estadísticas y 	relaciones.

Idiomas cubiertos
Los datos fueron recolectados en al menos dos idiomas: español e inglés.

Datos obtenidos
Los datos extraídos fueron almacenados en un repositorio (Drive) cuya estructura es la siguiente:
 

	+++++++ código		+++++++	estadisticas
	+			+
	+			+
	+			+
Pradera	+++++++ datos +++++++++++++++++	informacion
	+			+	
	+			+
	+			+
	+++++++ informe		+++++++ relaciones


Principalmente los datos se obtuvieron de los siguientes sitios:
* Sitio 1: https://boardgamegeek.com/boardgame/314491/meadow
* Sitio 2: https://misutmeeple.com/2021/05/resena-pradera/

En la carpeta Pradera/datos/inforrmacion se guardaron los archivos surgidos de la extracción de texto proveniente de distintas fuentes, como ser descripciones del juego, foros, reseñas, videos, etc.

En la carpeta Pradera/datos/estadisticas se guardaron en formato tabular (archivo .csv), estadísticas que fueron extraídas de la página del juego.

En la carpeta Pradera/datos/relaciones se guardaron en formato tabular (archivo .csv), relaciones establecidas entre el juego como nodo central y sujetos que mantienen distinto tipo de relación con el mismo (creador, ilustrador, editorial, etc).

En la carpeta Pradera/codigo se guardaron los archivos que contienen el código a través del cual se procedió a extraer la información detallada más arriba. Son 3 notebook Jupyter, a saber:

	* Web_Scraping_dinamico_Pradera.ipynb: con este archivo se realizo el web scraping a la pagina del Sitio 1 y se extrajo texto correspondiente a descripciones, reseñas, comentarios de foros, estadísticas, relaciones, etc. Además, contiene código para extraer como texto las reglamentaciones del juego desde archivos en formato PDF.

	* Pradera_Misutmeeple.ipynb: con este archivo se realizó el web scraping a la página del Sitio 2 y se extrajeron también descripciones, reseñas, comentarios de foro, etc. 

	* Extraccion_texto_videosypdf.ipynb: con este archivo se realizó la extracción de texto desde vídeo tutoriales del Sitio 1 así como también de archivos PDF.

En la carpeta Pradera/informe se almaceno un archivo PDF que contiene un informe mas detallado acerca de las distintas tareas que se llevaron a cabo para la realización del Trabajo Practico correspondiente al juego Pradera y que como resultado de las mismas se obtuvo la estructura del repositorio y los datos que fueron detallados anteriormente.

