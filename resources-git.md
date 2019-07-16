<h1 style="text-align: center; color: lightgreen;">Recursos para el Taller</h1>



- **Runtime online de python3:** https://repl.it/languages/python3

- **Descarcar Visual Studio Code:** https://code.visualstudio.com/download
- **Descargar Live Share:** https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare

- **Descargar interprete python 3.7.2:** https://www.python.org/downloads/

- **snake-game:** https://github.com/XTEALER/snake-py

Entrar al repositorio **snake-py** y copiar el contenido del archivo **snake.py**, ir al **runtime online de python3** borrar el codigo por defecto y pegar el codigo copiado en **main.py** despues hacer click en **run**. Lo que sucede a continuacion es que se genera un error de tipos, esto se da porque los calculos realizados en la linea 29 retornan valores flotantes mientras que la funcion espera valores de tipo entero. Para solucionar esto hacemos casting del resultado de estas operaciones con la funcion **int()** para cada una de las operaciones. Estas correciones se encuentran aplicadas en la rama [fix-int](https://github.com/XTEALER/snake-py/tree/fix-int).

A continuacion vamos al repositorio [fix-int](https://github.com/XTEALER/snake-py/tree/fix-int) y copiamos el contenido del archivo **snake.py**, vamos a **repl** borramos el codigo que ya teniamos y pegamos el del archivo con las correciones. En esta ocasion vemos que si corre. 
