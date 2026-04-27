# auto_link
aplicacion de terminal, en phyton, para poder comprovar si un html, tiene URS validas, es decir que funcioen y te lleven a una web real. Antes de nada dar permiso de ejecucion con chmod +x auto_link.py
si quieres ejecutarlo como aplicacion y con python3 auto_link.py debes de moverlo hantes a la ruta: /usr/local/bin/

# Requisitos
pip install requests beautifulsoup4

## Funciones
- Detecta enlaces rotos (HTTP 4xx/5xx)
- Filtra enlaces internos y javascript
- Elimina enlaces rotos si el usuario lo desea
- Genera HTML limpio

## comando
bash
python3 auto_link.py archivo.html
o
auto_link archivo.html
