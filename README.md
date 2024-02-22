# Introducción

Para obtener datos meteorológicos utilizaremos el lenguaje de programación Python (ver https://www.python.org/). En este documento se describen brevemente los pasos a seguir para instalar las herramientas para trabajar con él en vuestro ordenador.

Seguid este proceso y en caso de problemas o duda consultad con el profesor Rafael Vidal.
Instalación de Python
Descargar la versión de Python para el sistema operativo de tu ordenador
- Enlace: https://www.python.org/downloads/

Instalar Python utilizando las opciones por defecto. Para conocer su significado, no hace falta, podéis consultar estos enlaces:
- Windows: https://docs.python.org/3/using/windows.html#the-full-installer
- MacOS: https://docs.python.org/3/using/mac.html

# Test de la instalación

Para comprobar que la instalación anterior es operativa necesitaremos abrir una consola/terminal. En Windows podéis abrirla escribiendo “cmd” en “ejecutar”.

En la consola escribid “py –-version” debería aparecer:

```
C:\Users\Rafael>py --version`
Python 3.11.2
```
Si utilizas MacOS o Linux consulta este enlace para encontrar las instrucciones equivalentes: https://packaging.python.org/en/latest/tutorials/installing-packages/ 

# Herramientas adicionales
Para completar la instalación de Python instalaremos un par de herramientas que nos facilitarán su uso.  

## Pip
Pip es un gestor de paquetes de software o módulos, también denominados librerías. En nuestro caso, utilizaremos pip para facilitar la instalación de librerías. Una librería es un código que implementa funciones más o menos complejas. Utilizando en nuestro código una librería podemos utilizar cada una de estas funciones con una única línea de código. Por tanto, la existencia de librerías y su uso facilita y simplifica el desarrollo de código.
Una de las grandes ventajas que ofrece Python es el gran número de librerías existentes. Podéis consultarlas en los siguientes enlaces:
- The Python Standard Library: https://docs.python.org/3/library/index.html 
- Python Package Index (PyPI): https://pypi.org/ 

Para instalar pip y testear su funcionamiento, necesitaremos otra vez una consola.

Primero comprobaremos que no se haya instalado ya en la instalación inicial de Python. Para ello preguntaremos por la versión de pip que se encuentre instalada

```
C:\Users\Rafael>py -m pip --version
```
Si no se ha instalado ninguna versión, instalaremos pip de la siguiente forma. Primero descargaremos el programa get-pip.py desde el siguiente enlace 

https://bootstrap.pypa.io/get-pip.py. 

Después ejecutaremos este programa. Asumiendo que se ha guardado en la misma carpeta, sería

```
C:\Users\Rafael>py get-pip.py
````

Seguidamente, actualizaremos la herramienta para tener su última versión

```
C:\Users\Rafael>py -m pip install --upgrade pip
````

Si utilizas MacOS o Linux consulta este enlace para encontrar las instrucciones equivalentes: https://pip.pypa.io/en/stable/installation/. 

## Editor de código
Existen entornos de programación que integran y facilitan el desarrollo de código. Son los denominados IDEs, Integrated Development environment, y su uso se considera indispensable para un desarrollador de código. 

Sin embargo, los IDEs pueden llegar a ser muy complejos por lo que, para hacer más sencilla esta primera toma de contacto con Python, utilizaremos un editor de texto que puede funcionar como IDE denominado Notepad++.

Podéis descargar este software desde el siguiente enlace e instalarlo con las opciones que vienen por defecto:
- https://notepad-plus-plus.org/downloads/

Algunas alternativas a Notepad++ para MacOS (os pueden servir cualquier editor tipo “Bloc de notas”):
- https://code.visualstudio.com/
- https://www.sublimetext.com/ 
- https://macromates.com/

