[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)


# Prueba testing en Django
## 1 Descargar repositorio 
Abrir una carpeta de su eleccion en su Sistema operativo y ejecutar:
```sh
git clone https://github.com/Epalaciol/testPruebaDjango.git
```

## 2 Configurar entorno virtual

[Instalar pyenv](https://github.com/pyenv/pyenv-installer)


&nbsp;
Despuesde haberlo instalado Ejecutar: 
```sh
pyenv install 3.8.4 
pyenv virtualenv 3.8.4 test
pyenv virtualenv test local 
```
## 3 Descargar django
Verificamos que el pyenv este con el entorno test y ejecutamos lo siguente:
```python
python -m pip install Django==3.1.5
```
## 4 Ejecutar pruebas 

Vamos a la carpeta  mysite dentro de ella debe de aparecer lo siguiente:
mysite:
-- mysite
-- polls
-- manage.py 

&nbsp;
Estando parados aqui podemos ejecutar:
```python
python manage.py runserver
```
Si no hay problemas debe de desplegar la aplicacion de forma local 


&nbsp;
*Para correr pruebas*
Ejecutamos: 
```py
python manage.py test polls 
```

