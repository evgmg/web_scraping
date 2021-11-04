# Práctica 1: Web_scraping

Este proyecto es una práctica realizada por:<br>

EVGENY MUZAREV GEVORGIAN<br>
PABLO CHILLERÓN BEVIÁ<br>

para la asignatura M2.851 Tipología y ciclo de vida de los datos, dentro del Máster Oficial en Ciencia de Datos en la Universitat Oberta de Catalunya.<br>

## Descripción

Se trata de un proyecto en Python para recolectar datos de establecimientos hoteleros en la zona de costa de la geografía española, con el fin de probar las aplicaciones del web-scrapping en este sector, haciendo después un análisis de una supuesta competencia y otras aplicaciones interesantes.<br>

## Archivos
Existen dos carpetas con ficheros:<br>
<br>
1) csv<br>
Guarda dataframes en formato csv<br>


dataframe.csv: Dataframe con los datos de un día (como prueba)<br>
dataframe_13943.csv: Dataframe con datos de 14 días publicado en Zenodo<br>

DOI Link: 10.5281/zenodo.5639715<br>
Target URL: https://doi.org/10.5281/zenodo.5639715<br>

2) intermediate_files<br>
Guarda elementos como listas y diccionarios en formato pkl para cargarlos a lo largo de la práctica y reducir el impacto en los servidores de booking.com<br>


dic_d.pkl: Diccionario con los elementos fecha<br>
dic_p.pkl: Diccionario con los elementos precios<br>
dic_u.pkl: Diccionario con los elementos URLs<br>
dic_serv.pkl: Diccionario con los elementos servicios<br>
res.pkl: Lista con los datos identificativos del establecimiento en una noche determinada<br>

## Librerías necesarias<br>
pip install requests<br>
pip install beautifulsoup4<br>
pip install datetime<br>
pip install random<br>
pip install matplotlib.pyplot<br>
pip install pickle<br>
pip install warnings<br>
pip install pandas<br>
pip install numpy<br>
pip install lxml<br>
pip install threading<br>
pip install apriori<br>
pip install association_rules<br>
