# Virtualenv-Python-Course
### Crash Course: Viertualenv Windows &amp; Linux

#### Basic Commands to Start & Activate Pipevnv...

cd project

pip install pipenv

or 

pip3 install pipenv

pipenv shell

pipenv install discord.py

#### Basic Commands to Start & Activate my Project...

cd project

python -m venv venv

\venv\Scripts>activate/deactivate

python -m venv venv or virtualenv <"nombre del projecto">

venv\Scripts>activate

\venv\Scripts>pipenv shell  or  (>exit) to exit


#### Basic Commands to Activate my Project...

cd project

\venv\Scripts>activate

(venv) C:\venv\Scripts>pipenv shell
Launching subshell in virtual environment…
Microsoft Windows [Versión 10.0.00000.000]
(c) 2019 Microsoft Corporation. Todos los derechos reservados.

(Scripts-uFinIKPs) (venv) C:\venv\Scripts>_____________


#### Other Commands...

pip install virtualenv

virtualenv "nombre del projecto" or python -m venv venv 

venv\Scripts>activate

pip -h   or    pip --help

pipenv -h   or    pipenv --help

pip freeze > ../../src/requirements.txt

pip install flask or flask==2.0

pip install gunicorn

pip install python3.6.7 https://www.python.org/downloads/release/python-376/


#### start Django or Flask Project...

 > Cd Project...
 
 - Instalar...
 
 > pip install virtualenv
 
 - En caso de ya tenerlo instalado de modo global en todo la computadora, ejecutamos...
 
 > virualenv venv
 
 > project> .\venv/scripts/activate.bat
 
 - Comenzar a instalar modulos y dependencias dentro de nuestro projecto Flask o Django...
 
 > pip install flask pymongo or pip install flask-pymongo
 
 



### Source:

https://pipenv-es.readthedocs.io/es/latest/basics.html
