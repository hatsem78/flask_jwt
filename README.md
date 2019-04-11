

# Proyecto crear un Api-Rest con tecnología Python3, Flask-framework con Json Web Token

Es un simple API-REST de seguridad con token para resguardar los recursos que se exponen para ser consumidos por distintas aplicaciones

Versión.

- [V1.0.0](https://github.com/hatsem78/flask_jwt.git): Puede ejecutar el servidor directamente después de clonar esta versión. Creará una API RESTful simple a través de HTTP.


## Requirements
[Flask-RESTful-Documentación](https://flask-restful.readthedocs.io/en/latest/index.html)\
[Flask-JWT-Documentación](https://flask-jwt-extended.readthedocs.io/en/latest/) \
[Flask-SQLAlchemy-Documentación](http://flask-sqlalchemy.pocoo.org/2.3/)\







## Getting Started

Se debe crear un Entornos Virtuales 
[Entornos-Virtuales-Turorial](http://docs.python.org.ar/tutorial/3/venv.html)\

simples paso para crear un virtualenv Python3
```
virtualenv -p python3 virtual_pru
```

Activar el virtual creado virtual_pru
```
source virtual_pru/bin/activate
```

Desactivar el virtual 
```
deactivate 
```
## Clone el repositorio

```
git clone https://github.com/hatsem78/flask_jwt.git
```

Instalar las dependencias

```
pip install -r requirements.txt
```

## Start the server


```
FLASK_APP=run.py FLASK_DEBUG=1 flask run
```



