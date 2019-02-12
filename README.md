# alta_pagina_web
Script creación hosting:

- usuario
- directorio
- virtualhost
- configuracion ftp


Usando Ansible como herramienta de conexion con los host.

Variables en el archivo:

- myvarsfile.yml

Ademas de las variables, debes escribir manualmente en /files/etc/httpd/sites-available la ruta del directorio.

Start with:

ansible-playbook escenario.yaml
