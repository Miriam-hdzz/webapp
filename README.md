# Demo de una Webapp con Python3, Web.py y Sqlite3

## 1.Crear un Ambiente Virtual (Virtual Environment)

Crear un virtual enviroment para instalar las librerias necesarias de Python.

````shell
python3 -m venv .venv
````

## 2. Iniciar el Virtual Enviroment

Iniciar el virtual enviroment para instalar las librerias necesarias para el proyecto.

````shell
source .venv/bin/activate
````

## 3. Actualizar **PIP**

Actualizar el instalador de paquetes de Python **pip**.

````shell
pip install --upgrade pip
````

## 4. Instalar el micro-framework **web.py**

Instalar el *micro-framework* **web.py** para la creacion de aplicaciones web utilizando Python.

````shell
pip install web.py
````

## 5. Crear el archivo **requirements.txt**

Crear el archivo **requirements.txt** con las listas de las librerias y versiones de cada una, necesarias para el proyecto.

````shell
pip freeze > requirements.txt
````

## 6. Crear el archivo **runtime.txt**

Crear el archivo **runtime.txt** con la version Python3 utilizada.

````shell
python3 -V > runtime.txt
````

## 7. Crear el archivo **.gitignore**

Crear el archivo **.gitignore** para indicar las carpetas y archivos que no se van a sincronizar con el repositorio.

````shell
*.pyc
__pycache__/
.venv/
````

## 8. Indexar las carpetas y archivos 

Indexar las carpetas y archivos creados o modificados.

````shell
git add .
````

## 9. Crear el punto de control **comit**

Crear e punto de control con los cambios realizados al proyecto.

````shell
git commit -m "CREATED configuracion del virtual environment"
````

## 10. Sincronizar los cambios al repositorio 

Sincronizar los datos realizados al proyecto repositorio.

````shell
git push -u origin