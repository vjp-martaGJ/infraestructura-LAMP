# Diseño de la Red
# Análisis de Requisitos del Cliente

## Requisitos del Sistema
* **Sistema Operativo:** Ubuntu Server 22.04 LTS.
* **Arquitectura:** LAMP (Linux, Apache, MySQL, PHP).

## Necesidades de la PYME
* Despliegue de presencia web corporativa.
* Entorno de base de datos para la gestión interna.
## 2.4. Balanceador de Carga HAProxy
Se incorpora HAProxy como punto de entrada único (Puerto TCP 80/443). Este redirigirá el tráfico hacia el servidor web Apache interno de manera transparente.