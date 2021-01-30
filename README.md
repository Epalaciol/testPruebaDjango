# Prueba testing en Django
## 1 Descargar repositorio 
Abrir una carpeta de su eleccion y ejecutar 
git clone https://github.com/Epalaciol/testPruebaDjango.git

## 2 Configurar entorno virtual

Instalar pyenv [https://github.com/pyenv/pyenv-installer]
Ejecutar: 
pyenv install 3.8.4 
pyenv virtualenv 3.8.4 test
pyenv virtualenv test local 

## 3 descargar django
Verificamos que el pyenv este con el entorno test y ejecutamos lo siguente:

python -m pip install Django==3.1.5

## 4 Ejecutar pruebas 

vamos a la carpeta  mysite dentro de ella debe de aparecer lo siguiente:
mysite:
-- mysite
-- polls
-- manage.py 
Estando parados aqui podemos ejecutar:

python manage.py runserver

Si no hay problemas debe de desplegar la aplicacion de forma local 

*Para correr pruebas*
Ejecutamoss: 
python manage.py test polls 


