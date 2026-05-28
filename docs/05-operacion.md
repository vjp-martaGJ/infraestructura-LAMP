## 5.2. Mantenimiento del Balanceador
Comandos esenciales para asegurar el tráfico:
* Comprobar sintaxis de configuración: `haproxy -c -f /etc/haproxy/haproxy.cfg`
* Reiniciar tras cambios: `sudo systemctl restart haproxy`