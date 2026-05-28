# Politica de Copias de Seguridad
## 4.1. Estrategia de Copias
Se implementará una estrategia de respaldo local y remoto automatizada basada en utilidades nativas de Linux.

## 4.2. Componentes del Backup
1. **Bases de Datos:** Volcado lógico de las dos bases de datos de forma aislada utilizando la herramienta `mysqldump`.
2. **Archivos Web y Configuración:** Sincronización de directorios (`/var/www/html` y `/etc/`) mediante el comando `rsync`.

## 4.3. Frecuencia y Rotación
* **Periodicidad:** Ejecución diaria automatizada de madrugada (02:00 AM) mediante tareas programadas en el sistema (`cron`).
* **Política de Retención:** Rotación de copias de seguridad manteniendo un histórico de los últimos 7 días en el servidor para optimizar el almacenamiento.
