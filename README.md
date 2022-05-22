# iotcrashcourse
Tutorial rápido para desplegar un entorno IoT

## Arquitectura
![alt text](https://github.com/ManoloCourses/iotcrashcourse/blob/main/images/arquitectura.png)


## Problemas conocidos
Este repositorio recoge el despliegue realizado en un tutorial de inicio rápido, para el que se han pasado por alto diferentes recomendaciones de seguridad y buenas práticas. El objetivo principal es familiarizarse con las tecnologías y los conceptos básicos de una arquitectura IoT. En el estado actual no debe ser utilizado más allá de fines didácticos, y bajo ningún concepto se aconseja su uso en entornos productivos.

Está orientado a desplegar un entorno IoT básico que permita recoger los datos de diferentes sensores allmacenarlos, analizarlos y generar alertas simples. 

## Despliegue

```
docker-compose up
```

## Enlaces de utilidad

* https://docs.docker.com/engine/install/ubuntu/
* https://docs.docker.com/compose/gettingstarted/
* https://hub.docker.com/_/emqx
* https://hub.docker.com/_/influxdb?tab=description
* https://hub.docker.com/_/telegraf
* https://hub.docker.com/r/grafana/grafana
* https://docs.influxdata.com/influxdb/v2.2/reference/key-concepts/data-elements/
* https://www.emqx.io/docs/en/v4.4/configuration/configuration.html