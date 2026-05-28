# 02. Diseño de la Infraestructura

## 2.1. Arquitectura lógia (Stack LAMP)
La solución se basará en una arquitectura monolítica clásica de tres capas sobre un único sistema operativo:

| Componente | Tecnología | Rol en la Infraestructura |
| :--- | :--- | :--- |
| **Sujeto S.O.** | Ubuntu Server 22.04 LTS | Sistema operativo base de nivel empresarial |
| **Servidor Web** | Apache 2.4 | Servidor HTTP encargado de procesar peticiones || Servidor Web | Apache 2.4.58 (Versión Estable) | Servidor HTTP encargado de procesar peticiones |  
| **Base de Datos** | MySQL 8.0 / MariaDB | Motor relacional para el almacenamiento seguro |
| **Procesamiento** | PHP 8.1 | Intérprete para la lógica de la web y gestión |

## 2.2. Diseño de Red y Seguridad Básica
* **Puerto 22 (TCP):** Acceso SSH para administración remota (restringido por Firewall).
* **Puerto 80 (TCP):** Tráfico HTTP para la consulta web ordinaria.
* **Puerto 443 (TCP):** Tráfico HTTPS blindado para la pasarela de gestión interna.