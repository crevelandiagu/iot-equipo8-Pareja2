# entrega semana 5 prueba de bases de datos

En la carpeta **postgres_iot** y **timescale_iot** se encuntran los códigos modificados con la nueva consulta
en la cual se incluye en el ORM de Django el **value** de la medición de la temperatura.
En el documento se colocan los pantallazos.

## Código modificado de Postgres

la ruta del código modificado es 

```shell
cd /postgres_iot/Realtime-Monitoring-webApp/realtimeMonitoring/realtimeGraph/urls.py
cd /postgres_iot/Realtime-Monitoring-webApp/realtimeMonitoring/realtimeGraph/views.py
```

se modifica las urls para ingresar al nuevo endpoint y se agrega una nueva función en el views para ser accedida por la url 
y mostar los resultados de la consulta.

## Código modificado de timescale

la ruta del código modificado es 

```shell
cd /timescale_iot/Realtime-Monitoring-webApp/realtimeMonitoring/realtimeGraph/urls.py
cd /timescale_iot/Realtime-Monitoring-webApp/realtimeMonitoring/realtimeGraph/views.py
```

se modifica las urls para ingresar al nuevo endpoint y se agrega una nueva función en el views para ser accedida por la url 
y mostar los resultados de la consulta.

## Prueba de JMeter

el archivo **pruebas_carga_capa_datos.jmx** contiene las pruebas realizadas en JMeter
