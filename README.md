# Flask App

Este proyecto es una aplicación simple hecha en Flask.
Correspondiente al primer ejercicio de la lección API development and Documentation del curso FSND.

## Getting Starting

Se crea el directorio del proyecto.
Luego creamos el entorno virtual.

```bash
mkdir flask_setup_example
cd flask_setup_example
python3 -m venv env
# Opción
virtualenv nombre_del_entorno
```

Activamos el entorno virtual.

```bash
source env/bin/activate
```

Instalamos Flask.

```bash
pip3 install Flask
```

Creamos el directorio flaskr y el archivo __init__.py.

```bash
mkdir flaskr
touch flaskr/__init__.py
```

En el archivo __init__.py escribimos el siguiente código.

Para ejecutar en la consola:

```bash
export FLASK_APP=flaskr
export FLASK_ENV=development
export FLASK_DEBUG=true
flask run
```

**¿Por qué hacemos esto?**
Porque Flask busca la variable FLASK_APP para saber dónde está la aplicación y FLASK_ENV para saber en qué entorno está corriendo la aplicación.

```python
