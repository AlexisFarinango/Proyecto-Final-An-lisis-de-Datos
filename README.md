# Proyecto Final Analisis de Datos Creación de DataLake
Integrantes: Bedoya Dilan, Cardenas Alex, Castillo Steven, Farinango Alexis, Gomez Lenin

## DataLake Proyecto

Este repositorio contiene un proyecto de datalake que combina datos de 6 bases de datos diferentes. El objetivo es extraer, limpiar y almacenar datos en un concentrador central. Antes de este proceso, se recopilaron 15 conjuntos de datos de diversas fuentes y temas.

**Contenido**

* Descripción
* Requisitos previos
* Instalación
* Ejecución
  

**Descripción**

El proyecto se centra en la creación de un datalake que almacena datos de diferentes bases de datos. Los datos se extraen, se limpian y se almacenan en un concentrador central para su posterior análisis.

**Requisitos previos**

Antes de comenzar, asegúrate de tener instalado lo siguiente:
* Python 3.7 o superior
* Jupyter Notebook o Visual Studio Code
	Librerias necesarias para instalar y ejecutar Jupyter Notebook
	- pip install notebook
	- pip install jupyterlab
	 

**Instalación**

Clona este repositorio en tu máquina local.
Descarga todos los archivos necesarios.
Instala las dependencias: 
	* requests 
	* BeautifulSoup 
	* pymongo 
	* sqlite3
	* myqsl.connector 
	* sqlalchemy 
	* pymysql
	* boto3 
	* pyodbc
	* pandas


**Ejecución**

Se necesita haber cargado los diferentes archivos en las bases de datos respectivas

Ejecuta los diferentes scripts principales: 
	* conciertos.ipynb
	* deportes.ipynb
	* juegos.ipynb
	* noticias.ipynb
	* peliculas.ipynb

Como resultado de la ejecución de cada apartado de codigo los datos se extraerán de los gestores de bases de datos y finalmente se almacenarán en el datalake.

