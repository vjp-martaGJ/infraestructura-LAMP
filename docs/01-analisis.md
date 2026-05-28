# 01. Análisis de Requisitos del Cliente

## 1.1. Perfil del Cliente y Necesidades
El cliente es una pequeña y mediana empresa (PYME) que requiere iniciar su transformación digital mediante el despliegue de su presencia web corporativa y un sistema de gestión interna (ERP/CRM). 

## 1.2. Requisitos Funcionales
* **Presencia Web:** El sistema debe servir páginas web dinámicas utilizando el lenguaje PHP.
* **Gestión de Datos:** Se requieren dos entornos de base de datos relacionales completamente independientes y aislados:
  1. Base de datos para la producción del sitio web.
  2. Base de datos para el sistema de gestión interna.

## 1.3. Requisitos No Funcionales y Seguridad
* **Disponibilidad:** El sistema debe contar con monitorización continua para alertar sobre caídas del servicio o falta de recursos.
* **Seguridad (Hardening):** Acceso administrativo restringido mediante protocolos seguros y blindaje del servidor con cortafuegos.
* **Integridad:** Copias de seguridad automáticas diarias para evitar la pérdida de datos de clientes y de gestión.