# entrega semana 5 prueba de bases de datos

En la carpeta **postgres_iot** y **timescale_iot** se encuntran los codigos modificados con la nueva consulta
en la cual se incluye en el ORM de Django el **value** de la medicion de la temperatura.
En el documento se colocan los pantallazos.

## Codigo modificado de postgres

la ruta del codigo modificado es 

```shell
cd /postgres_iot/Realtime-Monitoring-webApp/realtimeMonitoring/realtimeGraph/urls.py
cd /postgres_iot/Realtime-Monitoring-webApp/realtimeMonitoring/realtimeGraph/views.py
```

se modifica las urls para ingresar al nuevo endpoint y se agrega una nueva funcion en el views para ser accedida por la url 
y mostar los resultados de la consulta.

## Codigo modificado de timescale

la ruta del codigo modificado es 

```shell
cd /timrescale_iot/Realtime-Monitoring-webApp/realtimeMonitoring/realtimeGraph/urls.py
cd /timrescale_iot/Realtime-Monitoring-webApp/realtimeMonitoring/realtimeGraph/views.py
```

se modifica las urls para ingresar al nuevo endpoint y se agrega una nueva funcion en el views para ser accedida por la url 
y mostar los resultados de la consulta.

## Prueba de JMeter

el archivo **pruebas_carga_capa_datos.jmx** contiene las pruebas realizadas en JMeter