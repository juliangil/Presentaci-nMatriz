### Pasos para visualizar las presentaciones


1) Se debe instalar Python y Jupyter. 


http://jupyter.org/


https://www.python.org/


NOTA: Existe una plataforma, llamada Anaconda, que viene con todo esto: https://www.continuum.io/downloads 


2) OPCIONAL - Instalar Node js (para que jupyter corra javascript). 


3) OPCIONAL - Instalar el kernel, para este caso, de javascript. Se llama ijavascript, y se instala globalmente con npm.
	```
	$ npm install -g ijavascript
    ```

4) Instalar el plugin para slides. Para esto se clona el repositorio y se ejecuta con Python. 
	```
 	$ git clone https://github.com/damianavila/RISE
    $ cd RISE
    $ python setup.py install
	```


5) Ejecutar el comando ```$ ipython notebook``` dentro del directorio raíz de este repositorio. Una vez iniciada la aplicación web, desde el explorador, abrir los archivos *.ipynb (Matriz de Flexibilidad es matriz-merged.ipynb)
