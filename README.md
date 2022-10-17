Integrantes:
Gustavo Faúndez Garay
Esteban Holtheuer Rojas

Estructura de archivos y carpetas:
Carpeta raw: Datos sin procesar, archivos: calendar.7z y listings.csv
Carpeta output: Datos procesados, Archivos: data_procesada.csv y 3_reporte.html


Descripción general del proyecto:

Información de Airbnb en Santiago en un año y en cuanto valorizar el precio alojamiento. Al explorar la información realizamos cambios en la selección de variables.

Información de Airbnb en la ciudad de Santiago, son tres archivos con la siguiente información:

Calendar.csv: Información de precios por tipo de alojamiento en fechas en un año en Santiago de Chile.
Listings.csv: informción de tipo de propiedad, tipo de habitaciones, cantidad de camas, cantidad de habitaciones, puntaje entregado por los que se han hospedado, lista de amenidades, comuna, etc.


Ejecución del código:

Primero se debe descomprimir el archivo calendar.7z dentro de la carpeta raw 
Luego se debe ejecutar el jupyter notebook 1_limpieza.ipynb para generar el archivo data_procesada.csv en la carpeta processed
Finalmente en el jupyter notebook 3_reporte.ipynb se encuentra el resumen de lo realizado en el código anterior, con ayuda de gráficos e indicadores y sus repectivas explicaciones.