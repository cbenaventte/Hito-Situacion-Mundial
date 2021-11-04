# Hito-Situacion-Mundial

Descripción
En este hito se comenzará a crear el sitio web acerca del Covid-19, se debe construir un
pequeño MVP que permita a los visitantes conocer la situación actual del Covid-19 en los
diferentes países del mundo. El usuario que visite el sitio web debe poder ver un gráfico con
los países con más casos activos y una tabla que detalle cada uno de los países afectados
por la pandemia. 

Requerimientos
1. Crear una estructura básica con HTML para el proyecto y cargar la librería de
bootstrap o similar, además de jQuery.
2. Consumir la API http://localhost:3000/api/total con JavaScript o jQuery.
3. Desplegar la información de la API en un gráfico de barra que debe mostrar sólo los
países con más de 10000 casos activos.
4. Desplegar toda la información de la API en una tabla. 
5. Cada fila de la tabla debe incluir un link que diga "ver detalle", al hacer click levante
un modal y muestre los casos activos, muertos, recuperados y confirmados en un
gráfico, para obtener esta información debes llamar a la API
http://localhost:3000/api/countries/{country} al momento de levantar el modal.

