# Plan de Monotorizacion 
## 3.1. Herramienta Seleccionada
Para mantener una observabilidad en tiempo real sin sobrecargar los recursos de la PYME, se opta por **Netdata**, complementado con scripts analíticos locales.

## 3.2. Métricas Críticas a Supervisar
El sistema debe vigilar constantemente los siguientes umbrales de rendimiento:

* **Uso de CPU:** Alertas si la carga sostenida supera el 85% durante más de 10 minutos.
* **Memoria RAM:** Monitorización del consumo del proceso de Apache y MySQL para evitar eventos *Out of Memory (OOM)*.
* **Espacio en Disco (Almacenamiento):** Alerta crítica si el espacio disponible en la partición raíz `/` decae por debajo del 15%.
* **Estado de los Servicios:** Verificación de que los daemons `apache2` y `mysql` están en estado *active (running)*
