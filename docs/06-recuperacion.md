# 06. Plan de Recuperación ante Desastres
En caso de caída total del servidor, se provisionará una nueva instancia y se restaurará el último backup con:
```bash
mysql -u root -p < backup_pyme.sql


* **Archivo `CHANGELOG.md`** (En la raíz del proyecto):
```markdown
# Changelog (Historial de Cambios)

## [v1.0.0] - Sesión 3
- Añadidos manuales de instalación de Apache y MySQL.
- Desarrollada la guía de operaciones diarias y el plan de desastres.
- Configuradas las reglas del Firewall UFW.