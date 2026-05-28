# Instalación del Servidor Web Apache
Para el servidor de la PYME se instala Apache2 junto con los módulos necesarios para PHP:
```bash
sudo apt update && sudo apt install apache2 php libapache2-mod-php -y
sudo systemctl enable apache2 --now
* **Archivo `docs/04-instalacion/base-de-datos.md`**:
```markdown
# Instalación de Base de Datos MySQL
Se instala el motor relacional y se ejecuta el script de seguridad:
```bash
sudo apt install mysql-server -y
sudo mysql_secure_installation