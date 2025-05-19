Resumen
Este proyecto recopil� informaci�n diversa sobre el juego de mesa Pradera a trav�s de m�ltiples fuentes. El objetivo fue construir un conjunto de datos completo que incluyera opiniones de jugadores, detalles t�cnicos y conexiones relevantes entre distintos aspectos del juego, trabajando con contenido en varios idiomas.

Para la recolecci�n de datos se utilizaron:
* T�cnicas automatizadas para extraer texto.
* Procesamiento de documentos oficiales y gu�as.
* Transcripci�n de contenido audiovisual.

Introducci�n

Objetivo
Este trabajo tiene como objetivo extraer, procesar y analizar datos multiling�es relacionados con Pradera. Los datos obtenidos abarcan informaci�n textual (reviews, tutoriales, manuales), estad�sticas del juego y relaciones entre entidades (desarrolladores, personajes, sagas), con el fin de generar un conjunto de datos estructurados.

Metodolog�a
Para cumplir con los requerimientos, se utilizaron las siguientes t�cnicas:
* Extracci�n de texto:
	* Documentos: Procesamiento de archivos PDF.
	* Videos: Transcripci�n autom�tica de reviews y tutoriales mediante 		  herramientas como ffmpeg , pydub y speech Recognition.
	* Foros: Web scraping de hilos de discusi�n (ej: Reddit, foros oficiales) con 	  BeautifulSoup o Selenium.

* Organizaci�n de datos:
	* Almacenamiento en formatos tabulares (CSV, Excel) para estad�sticas y 	relaciones.

Idiomas cubiertos
Los datos fueron recolectados en al menos dos idiomas: espa�ol e ingl�s.

Datos obtenidos
Los datos extra�dos fueron almacenados en un repositorio (Drive) cuya estructura es la siguiente:
 

	+++++++ c�digo		+++++++	estadisticas
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

En la carpeta Pradera/datos/inforrmacion se guardaron los archivos surgidos de la extracci�n de texto proveniente de distintas fuentes, como ser descripciones del juego, foros, rese�as, videos, etc.

En la carpeta Pradera/datos/estadisticas se guardaron en formato tabular (archivo .csv), estad�sticas que fueron extra�das de la p�gina del juego.

En la carpeta Pradera/datos/relaciones se guardaron en formato tabular (archivo .csv), relaciones establecidas entre el juego como nodo central y sujetos que mantienen distinto tipo de relaci�n con el mismo (creador, ilustrador, editorial, etc).

En la carpeta Pradera/codigo se guardaron los archivos que contienen el c�digo a trav�s del cual se procedi� a extraer la informaci�n detallada m�s arriba. Son 3 notebook Jupyter, a saber:

	* Web_Scraping_dinamico_Pradera.ipynb: con este archivo se realizo el web scraping a la pagina del Sitio 1 y se extrajo texto correspondiente a descripciones, rese�as, comentarios de foros, estad�sticas, relaciones, etc. Adem�s, contiene c�digo para extraer como texto las reglamentaciones del juego desde archivos en formato PDF.

	* Pradera_Misutmeeple.ipynb: con este archivo se realiz� el web scraping a la p�gina del Sitio 2 y se extrajeron tambi�n descripciones, rese�as, comentarios de foro, etc. 

	* Extraccion_texto_videosypdf.ipynb: con este archivo se realiz� la extracci�n de texto desde v�deo tutoriales del Sitio 1 as� como tambi�n de archivos PDF.

En la carpeta Pradera/informe se almaceno un archivo PDF que contiene un informe mas detallado acerca de las distintas tareas que se llevaron a cabo para la realizaci�n del Trabajo Practico correspondiente al juego Pradera y que como resultado de las mismas se obtuvo la estructura del repositorio y los datos que fueron detallados anteriormente.

